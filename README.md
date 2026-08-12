<div align="center">
  <a href="https://postimg.cc/XBBCDcJP">
    <img src="https://files.catbox.moe/wws2s9.jpg" width="100%" height="200" alt="uhh idk maybe grass"/>
  </a>
</div>

<div align="center">
   <tr>
    <h3>hey there, I'm blaze!</h3>
  </tr>
</div>
<div align="left">
 <h5>stuff I know (stacks ig)</h5>
</div>

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP"/>
  <img src="https://img.shields.io/badge/Symfony-000000?style=for-the-badge&logo=symfony&logoColor=white" alt="Symfony"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="NodeJs"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" alt="ExpoJS"/>
</p>

<div align="left">
 <h5>my hardware lol</h5>
</div>

<p align="center">
  <img src="https://img.shields.io/badge/CPU-Intel_i5--12400F-0071C5?style=for-the-badge&logo=intel&logoColor=white" alt="Intel Core i5-12400F"/>
  <img src="https://img.shields.io/badge/GPU-NVIDIA_RTX_4060_Ti-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="NVIDIA RTX 4060 Ti"/>
  <img src="https://img.shields.io/badge/MOBO-Gigabyte_B760M_DS3H_AX_DDR4-E60012?style=for-the-badge&logo=gigabyte&logoColor=white" alt="Gigabyte B760M DS3H AX DDR4"/>
  <img src="https://img.shields.io/badge/RAM-16GB_DDR4-0055FF?style=for-the-badge" alt="16GB DDR4"/>
  <img src="https://img.shields.io/badge/SSD-1TB_Kingston_NVMe-FF6600?style=for-the-badge&logo=kingston&logoColor=white" alt="1TB Kingston NVMe"/>
  <img src="https://img.shields.io/badge/MONITOR-Samsung_Odyssey_G40B_240Hz-1428A0?style=for-the-badge&logo=samsung&logoColor=white" alt="Samsung Odyssey G40B"/>
</p>

```php
namespace App\Entity;

use DateTime;
use DateTimeZone;

class Conolizer
{
    private string $role = 'full stack web dev';
    
    private array $currentlyBuilding = [
        'nothing special'
    ];
    
    private array $currentlyLearning = [
        'Redis',
        'Docker',
    ];
    
    private array $aboutme = [
        'languages'  => ['french', 'english'],
        'hobbies' => ['gaming', 'coding', 'music'],
        'fav_foods' => ['friedchicken', 'pizza', 'steak'],
    ];

    private function isSleeping(): bool
    {
        $now = new DateTime('now', new DateTimeZone('Europe/Paris'));
        $hour = (int) $now->format('H');

        return $hour >= 1 && $hour < 10;
    }

    public function getBio(): array
    {
        return [
            'role'     => $this->role,
            'building' => $this->isSleeping() ? ['sleeping'] : $this->currentlyBuilding,
            'learning' => $this->currentlyLearning,
            'aboutme'    => $this->aboutme,
        ];
    }
}
```
<br>

<h4 align="center">
  that's all folks!
</h4>
