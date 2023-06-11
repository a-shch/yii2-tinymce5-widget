# yii2-tinymce5-widget
Connecting tinymce5 as widget

Usage Example
-------------

``` php
<?= $form->field($model, 'content')->widget(ashch\tinymce\TinyMce::class); ?>
```
OR:
``` php
<?php

use ashch\tinymce\TinyMce;
------
<?= $form->field($model, 'content')->widget(TinyMCE::class, ['loadFileManager' => false, 'loadTemplates' => false,]); ?>
```
and other options ...


