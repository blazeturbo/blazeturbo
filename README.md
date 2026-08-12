<div align="center">
  <a href="https://postimg.cc/pytCmbKy">
    <img src="https://i.postimg.cc/T2K4HTwj/2ede7b2dc3b86f162d05817aed376b73.jpg" width="100%" alt="Banner"/>
  </a>
</div>

  <tr>
      <h3>hey there, I'm omega!</h3>
  </tr>

<div align="center">
  <a href="https://postimg.cc/XBBCDcJP">
    <img src="https://i.postimg.cc/prqJrstP/20260612-025300.jpg" width="100%" alt="Coding Quotes"/>
  </a>
</div>

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

### - hardware

<p align="center">
  <img src="https://img.shields.io/badge/CPU-Intel_i5--12400F-0071C5?style=for-the-badge&logo=intel&logoColor=white" alt="Intel Core i5-12400F"/>
  <img src="https://img.shields.io/badge/GPU-NVIDIA_RTX_4060_Ti-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="NVIDIA RTX 4060 Ti"/>
  <img src="https://img.shields.io/badge/MOBO-Gigabyte_B760M_DS3H_AX-E60012?style=for-the-badge&logo=gigabyte&logoColor=white" alt="Gigabyte B760M DS3H AX"/>
  <img src="https://img.shields.io/badge/RAM-16GB_DDR4-0055FF?style=for-the-badge" alt="16GB DDR4"/>
  <img src="https://img.shields.io/badge/SSD-1TB_Kingston_NVMe-FF6600?style=for-the-badge&logo=kingston&logoColor=white" alt="1TB Kingston NVMe"/>
</p>

<br>

### - operating system

<p align="center">
  <img src="https://img.shields.io/badge/OS-CachyOS-1793D1?style=for-the-badge&logo=archlinux&logoColor=white" alt="CachyOS"/>
  <img src="https://img.shields.io/badge/Base-Arch_Linux-1793D1?style=for-the-badge&logo=archlinux&logoColor=white" alt="Arch Linux"/>
  <img src="https://img.shields.io/badge/Desktop-KDE_Plasma-1D99F3?style=for-the-badge&logo=kde&logoColor=white" alt="KDE Plasma"/>
  <img src="https://img.shields.io/badge/Shell-fish-4AAE46?style=for-the-badge&logo=fishshell&logoColor=white" alt="fish shell"/>
  <img src="https://img.shields.io/badge/Kernel-Linux-000000?style=for-the-badge&logo=linux&logoColor=white" alt="Linux"/>
</p>

<br>

### - stacks

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP"/>
  <img src="https://img.shields.io/badge/Symfony-000000?style=for-the-badge&logo=symfony&logoColor=white" alt="Symfony"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
</p>

<br>

<p align="center">
  that's all folks!
</p>
