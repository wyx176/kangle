## kangle安装教程
http://bbs.itzmx.com/thread-7232-1-1.html<br>

## kangle配置路径
## ep模板配置:<br>
windows：  kangle目录\Kangle\nodewww\webftp\vhost\view 放在此目录就行<br>
liunx ：  vhs\Kangle\nodewww\webftp\vhost\view <br>
ep 后台切换就行<br>
## 404页地址:<br>
/vhs/kangle/www<br>
## vhms模板配置:<br>
windos和linux下一样的<br>
user/view/ <br>
上传到你销售网站这个目录即可<br>
然后解压后台切换，注意路径哈<br>

## 开启ssl
http://bbs.itzmx.com/forum.php?mod=viewthread&tid=12668&highlight=ssl<br>

## 强制跳转https
在.htaccess文件中：<br>
.htaccess放在web根目录(wwwroot目录下)
<pre><code>
RewriteEngine On
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://%{HTTP_HOST}/$1 [R,L]
</pre></code>
## 使用方法 <br>
1.将整文件下载,放在对应目录下面,然后解压出来<br>
2.注意,请勿修改模板文件夹名字,防止图标失效<br>
3.在每个模板下都有对应的预览图<br>

