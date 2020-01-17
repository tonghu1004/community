## tonghu1004社区

## 资料
001

[Spring指南](https://spring.io/guides)    

[spring web](https://spring.io/guides/gs/serving-web-content/)

[目标站点](https://elasticsearch.cn/)

[github密匙添加](https://developer.github.com/v3/guides/managing-deploy-keys/gi)

002 bootstrap

[bootstrap](https://v3.bootcss.com/)

[bootstrap文档](https://v3.bootcss.com/getting-started/)

[bootstrap 导航栏](https://v3.bootcss.com/components/#navbar-default)

003 git_oauth_app

[创建git_oauth_app](https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/)

[添加图像标识](https://developer.github.com/apps/building-oauth-apps/creating-custom-badges-for-oauth-apps/)

[git第三方授权登录的调用](https://developer.github.com/apps/building-oauth-apps/authorizing-oauth-apps/)

## 用到的工具
[git下载](https://git-scm.com/download)

[bootstrap引用包文件](https://github.com/twbs/bootstrap/releases/download/v3.3.7/bootstrap-3.3.7-dist.zip)

[visual-paradigm下载](https://www.visual-paradigm.com/tw/download/)

[Maven仓库](https://mvnrepository.com/)

##脚本
```sql
create table USER
(
	ID INT auto_increment,
	ACCOUNT_ID VARCHAR(100),
	NAME VARCHAR(50),
	TOKEN CHAR(36),
	GMT_CREATE BIGINT,
	GMT_MODIFIED BIGINT,
	constraint USER_PK
		primary key (ID)
);
```