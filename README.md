# Java对接ADFS Saml V3协议
此项目由ADFS 对接 java 授权版本，只包含授权部分，
只是授权中间过程，授权成功后跳转第三方或自有项目，以此达到免密授权的过程

####版本要求
1. tomcat 8.X 之上 测试过必须是 8.X 之上
2. ADFS 3.0
3. 与服务器 Server2012
4. JDK 1.8 非硬性 1.7 未测试过

####ADFS SAML （Nginx + Tomcat +spring-security-saml）
1. 使用的是spring-security-saml 官网地址如下： http://projects.spring.io/spring-security-saml/
2. Spring security API： https://docs.spring.io/spring-security-saml/docs/1.0.x/reference/html/
3. Spring security 提供的Demo 如下：https://repo.spring.io/list/release/org/springframework/security/extensions/spring-security-saml/

####整体思维导图

 ![image](https://github.com/MapleOfLeaf/adfs_saml/blob/main/doc/img.png)
 
 
