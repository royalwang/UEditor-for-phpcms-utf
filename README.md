UEditor-for-phpcms-utf
======================
介绍：
ueditor深度整合phpcms由@流浪男免费提供，保护简洁版和高级版方便用户使用。去掉了图片上传类部分不需要的功能，图片路径和命名均采用phpcms命名格式。宽度和高度用户可以在调用时自由控制。该版本为第一个版本，后面会持续更新。
使用说明：
1、将phpcms和statics目录上传到网站的根目录。
2、<textarea name="name" id="id"></textarea>
//调用高级版本
<?php echo form::editor('id', 'full', 'module', '', '', 1, '', '',300,900)?>
//简洁版本
<?php echo form::editor('id', 'basic', 'module', '', '', 1, '', '',300,900)?>
TTT:module为当前的模型，300为编辑器高度，900为宽度，留空将使用默认配置。
