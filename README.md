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

In my experience, to avoid errors

- cd /Users/YourName/Desktop/YourFolderProject/
- /Applications/YourSever/bin/php/php5.3.6/bin/php /Users/YourName/Desktop/YourFolderProject/composer.phar install

In the errors check and install

- http://git-scm.com/downloads
- http://getcomposer.org/download

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
