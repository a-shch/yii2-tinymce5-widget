# yii2-tinymce5-widget
Connecting tinymce5 as widget

usage:

<?= $form->field($model, 'content')->widget(ashch\tinymce\TinyMce::class); ?>

OR:

use ashch\tinymce\TinyMce;
------
<?= $form->field($model, 'content')->widget(TinyMCE::class, ['loadFileManager' => false, 'loadTemplates' => false,]); ?>

and other options ...


