QuPHPMailer 1.0.0
========================
ZF2 module for PHPMailer

Release Notes
========================

1.0.0:

- Initiation PHPMailer in zf2

Requirements
========================
- ZendSkeletonApplication https://github.com/zendframework/ZendSkeletonApplication

Installation
========================
- Drag a folder into modules folder or vendor folder
- Enable the module application.config.php

Integration
========================
```php
  $sm  = $this->getServiceLocator();
  $pdf = $sm->get('QuTcPdf');
  $pdf = $pdf->MyPdf();
  $pdf->Output('test.pdf','I');
```

References usage and conditions in PHPMailer
========================
- View read me in QuPHPMailer/src/PHPMailer
