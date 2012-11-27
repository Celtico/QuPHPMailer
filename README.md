QuPHPMailer 1.0.0-dev
========================
ZF2 module for PHPMailer

Release Notes
========================

1.0.0-dev

- Initiation PHPMailer in zf2

Requirements
========================
- ZendSkeletonApplication https://github.com/zendframework/ZendSkeletonApplication

Installation
========================
- Drag a folder into modules folder or vendor folder
- Enable the module application.config.php

Installation by Composer
========================
See the information if not known composer and clone git
=========================================================
- http://git-scm.com
- http://getcomposer.org

```
cd YourFolderProject/
php composer.phar require "qu-modules/qu-phpmailer":"dev-master"
```

Integration
========================
```php
  $sm   = $this->getServiceLocator();
  $mail = $sm->get('QuPHPMailer');
  $mail = $mail->Mail();
  $mail->Send();
```

References usage and conditions in PHPMailer
========================
- View read me in QuPHPMailer/src/PHPMailer
