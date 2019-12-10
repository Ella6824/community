##码匠社区

##资料
[Spring  文档](https://spring.io/guides/)
[Spring Web文档](https://spring.io/guides/gs/serving-web-content/#initial)
[es](https://elasticsearch.cn/explore)
[Github deploy key](https://developer.github.com/v3/guides/managing-deploy-keys/#deploy-keys)
[Bootstrap](https://v3.bootcss.com/getting-started/)
[Github OAuth](https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/)
[h2Database](https://www.h2database.com/html/main.html)
[spring](https://docs.spring.io/spring-boot/docs/2.0.0.RC1/reference/htmlsingle/#boot-features-embedded-database-support)

##工具
[Git](https://www.git-scm.com/download/)
[Visual Paradigm](https://www.visual-paradigm.com/cn/)
[Flyway](https://flywaydb.org/getstarted/firststeps/maven) 

##脚本
```sql
CREATE TABLE USER
(
    ID int AUTO_INCREMENT PRIMARY KEY NOT NULL,
    ACCOUNT_ID VARCHAR(100),
    NAME VARCHAR(50),
    TOKEN VARCHAR(36),
    GMT_CREATE BIGINT,
    GMT_MODIFIED BIGINT
);
```
```bash
mvn flyway:migrate
```
