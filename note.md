# laravel php-the-right-way notes

代码风格指南
PSR-0  PSR-1  PSR-2  PSR-4   PEAR 编码准则   Symfony 编码准则
  手动运行phpcs
phpcs -sw --standard=PSR2 file.php   它会显示出相应的错误以及如何修正的方法。同时，这条命令
  也可以用在git hook 中，如果你的分支代码不符合选择的代码标准则无法提交。
phpcbf -w --standard=PSR2 file.php 
phpcs-fixer fix -v --lever=psr2 file.php 
