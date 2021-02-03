# WordPress &#8250; 自述文档

优美的个人信息发布平台

## 写在最前

欢迎。WordPress 对我来说是一个具有特殊意义的项目。大家都能为 WordPress 添砖加瓦，因此作为其中一员我十分自豪。开发者和贡献者为 WordPress 奉献了难以估量的时间，我们都在致力于让 WordPress 更加优秀。现在，感谢您也参与其中。
&#8212; Matt Mullenweg

## 安装：著名的五分钟安装

1. 将 WordPress 压缩包解压至一个空文件夹，并上传它。
2. 在浏览器中访问[wp-admin/install.php](wp-admin/install.php)。它将帮助您把数据库连接信息写入到`wp-config.php`文件中。
   1. 如果上述方法无效，也没关系，这很正常。请用文本编辑器（如写字板）手动打开`wp-config-sample.php`文件，填入数据库信息。
   2. 将文件另存为`wp-config.php`并上传。
   3. 在浏览器中访问[wp-admin/install.php](wp-admin/install.php)。
3. 在配置文件就绪之后，WordPress 会自动尝试建立数据库表。若发生错误，请检查`wp-config.php`文件中填写的信息是否准确，然后再试。若问题依然存在，请访问[WordPress 中文支持论坛](https://cn.wordpress.org/support/forums/)寻求帮助。
4. <strong>若您不设置密码，请牢记生成的随机密码。</strong>若您不输入用户名，用户名将是`admin`。
5. 完成后，安装向导会带您到[登录页面](wp-login.php)。用刚刚设置的用户名和密码登录。若您使用随机密码，在登录后可以按照页面提示修改密码。

## 升级

### 自动升级

1. 在浏览器中打开[wp-admin/update-core.php](wp-admin/update-core.php)，按照提示操作。
2. 还有别的步骤么？——没了！

### 手动升级

1. 在升级之前，请确保备份旧有数据以及被您修改过的文件，例如`index.php`。
2. 删除旧版程序文件，记得备份修改过的内容。
3. 上传新版程序文件。
4. 在浏览器中访问[/wp-admin/upgrade.php](wp-admin/upgrade.php)。

## 从其他内容管理系统迁移到 WordPress

WordPress 支持[导入多种系统的数据](https://wordpress.org/support/article/importing-content/)。请先按照上述步骤安装 WordPress，然后您可在后台使用[我们提供的导入工具](wp-admin/import.php)。

## 最低系统需求

- [PHP](https://secure.php.net/) <strong>5.6.20</strong>或更高版本。
- [MySQL](https://www.mysql.com/) <strong>5.0</strong>或更高版本。

### 系统推荐

- [PHP](https://secure.php.net/) <strong>7.4</strong>或更高版本。
- [MySQL](https://www.mysql.com/) <strong>5.6</strong>或更高版本.
- 启用[mod_rewrite](https://httpd.apache.org/docs/2.2/mod/mod_rewrite.html)这一 Apache 服务器模块。
- [HTTPS](https://wordpress.org/news/2016/12/moving-toward-ssl/)支持。
- 在您的站点上放置一个到[cn.wordpress.org](https://cn.wordpress.org/)的链接。
- 在您的站点上放置一个到[wordpress.org](https://wordpress.org/)的链接。

## 在线资源

若您遇上文档中未有提及的情况，请首先参考我们为您准备的丰富的 WordPress 在线资源：

<dl>
	<dt><a href="https://codex.wordpress.org/">WordPress Codex文档</a></dt>
	<dd>Codex是WordPress的百科全书，它包含现有版本WordPress的海量信息资源，主要文章均有中文译文。</dd>
	<dt><a href="https://wordpress.org/news/">WordPress官方博客</a></dt>
	<dd>在这里，您将接触到WordPress的最新升级信息和相关新闻，建议加入收藏夹。</dd>
	<dt><a href="https://planet.wordpress.org/">WordPress Planet</a></dt>
	<dd>WordPress Planet汇集了全球所有WordPress相关的内容。</dd>
	<dt><a href="https://cn.wordpress.org/support/forums/">WordPress中文支持论坛</a></dt>
	<dd>如果感到束手无策，请将问题提交至中文支持论坛，它有大量的热心的用户和良好的社区氛围。无论求助还是助人，在这里您应该确保自己的问题和答案均准确细致。</dd>
	<dt><a href="https://codex.wordpress.org/IRC">WordPress <abbr>IRC</abbr>（互联网中继聊天）频道</a></dt>
	<dd>同样，WordPress也有即时的聊天室用于WordPress用户交流以及部分技术支持。IRC的详细使用方法可以访问前面几个关于技术支持的站点。（<a href="irc://irc.freenode.net/wordpress">irc.freenode.net #wordpress</a>）</dd>
</dl>

## 最后

- 对 WordPress 有任何建议、想法、评论或发现了 bug，请加入[中文支持论坛](https://cn.wordpress.org/support/forums/)。
- WordPress 准备了完善的插件<abbr>API</abbr>（应用编程接口）方便您进行扩展开发。作为开发人员，如果你有兴趣了解并加以利用，请参阅《[插件开发者手册](https://developer.wordpress.org/plugins/)》。请尽量不要更改核心代码。

## 分享精神

WordPress 没有数百万的市场运作资金，也没有名人赞助。不过我们有更棒的支持，那就是您！如果您喜欢 WordPress，请将它介绍给自己的朋友，或者帮助他人安装一个 WordPress，又或者写一篇赞扬我们的文章。

WordPress 是对 Michel V.创建的<a href="http://cafelog.com/">b2/caf&#233;log</a>的官方后续版本。[WordPress 开发团队](https://wordpress.org/about/)将 b2/caf&#233;log 发展成如今的 WordPress。如果您愿意支持我们的工作，欢迎您对 WordPress 进行[捐赠](https://wordpress.org/donate/)。

## 许可证

WordPress 基于<abbr>GPL</abbr>（GNU 通用公共许可证）第二版或（根据您选择的）以后版本发布。详见[license.txt](license.txt)（英文）。
