## quickstart
1. 进入xampp的htdocs路径执行
git clone git@github.com:wangyunli/quickstart.git
2. 下载[composer]( https://getcomposer.org/Composer-Setup.exe "composer")并安装
3. 在cmd进入quickstart目录，执行composer install
4. 复制.env.example为.env，修改数据库配置项DB_DATABASE、DB_USERNAME、DB_PASSWORD
5. 文件说明：
首页：quickstart/resources/views/index.blade.php
前端资源目录：quickstart/public
6. 访问 http://localhost/quickstart/public/ 即可运行