<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [AEM Training](#aem-training)
  - [AEM basic technical knowledge study](#aem-basic-technical-knowledge-study)
    - [1. 什么是AEM](#1-%E4%BB%80%E4%B9%88%E6%98%AFaem)
      - [1.1 AEM 官方定义](#11-aem-%E5%AE%98%E6%96%B9%E5%AE%9A%E4%B9%89)
      - [1.2 AEM 自我理解](#12-aem-%E8%87%AA%E6%88%91%E7%90%86%E8%A7%A3)
        - [1.2.1 AEM简要介绍](#121-aem%E7%AE%80%E8%A6%81%E4%BB%8B%E7%BB%8D)
        - [1.2.2 AEM具有以下显著特征：](#122-aem%E5%85%B7%E6%9C%89%E4%BB%A5%E4%B8%8B%E6%98%BE%E8%91%97%E7%89%B9%E5%BE%81)
      - [1.3 AEM 能做什么](#13-aem-%E8%83%BD%E5%81%9A%E4%BB%80%E4%B9%88)
    - [2. AEM 技术架构](#2-aem-%E6%8A%80%E6%9C%AF%E6%9E%B6%E6%9E%84)
      - [2.1 AEM 三大分层和三大核心技术架构图](#21-aem-%E4%B8%89%E5%A4%A7%E5%88%86%E5%B1%82%E5%92%8C%E4%B8%89%E5%A4%A7%E6%A0%B8%E5%BF%83%E6%8A%80%E6%9C%AF%E6%9E%B6%E6%9E%84%E5%9B%BE)
      - [2.2 AEM 三大核心技术](#22-aem-%E4%B8%89%E5%A4%A7%E6%A0%B8%E5%BF%83%E6%8A%80%E6%9C%AF)
        - [2.2.1 Apache Sling](#221-apache-sling)
        - [2.2.2 java JCR & Apache Jackrabbit](#222-java-jcr--apache-jackrabbit)
        - [2.2.3 Apache Felix](#223-apache-felix)
      - [2.3. AEM 首选渲染层模板语言：HTL](#23-aem-%E9%A6%96%E9%80%89%E6%B8%B2%E6%9F%93%E5%B1%82%E6%A8%A1%E6%9D%BF%E8%AF%AD%E8%A8%80htl)
    - [3. AEM 开发和使用](#3-aem-%E5%BC%80%E5%8F%91%E5%92%8C%E4%BD%BF%E7%94%A8)
      - [3.1 AEM 开发/部署/运维流程图](#31-aem-%E5%BC%80%E5%8F%91%E9%83%A8%E7%BD%B2%E8%BF%90%E7%BB%B4%E6%B5%81%E7%A8%8B%E5%9B%BE)
      - [3.2 启动 AEM](#32-%E5%90%AF%E5%8A%A8-aem)
        - [3.2.1 直接运行jar文件](#321-%E7%9B%B4%E6%8E%A5%E8%BF%90%E8%A1%8Cjar%E6%96%87%E4%BB%B6)
        - [3.2.2 在命令行中使用java命令启动](#322-%E5%9C%A8%E5%91%BD%E4%BB%A4%E8%A1%8C%E4%B8%AD%E4%BD%BF%E7%94%A8java%E5%91%BD%E4%BB%A4%E5%90%AF%E5%8A%A8)
      - [3.3 AEM 的开发和部署工具](#33-aem-%E7%9A%84%E5%BC%80%E5%8F%91%E5%92%8C%E9%83%A8%E7%BD%B2%E5%B7%A5%E5%85%B7)
        - [3.3.1 推荐使用IntelliJ进行AEM开发](#331-%E6%8E%A8%E8%8D%90%E4%BD%BF%E7%94%A8intellij%E8%BF%9B%E8%A1%8Caem%E5%BC%80%E5%8F%91)
        - [3.3.2 部署AEM代码到Instance](#332-%E9%83%A8%E7%BD%B2aem%E4%BB%A3%E7%A0%81%E5%88%B0instance)
      - [3.4 AEM 基础术语](#34-aem-%E5%9F%BA%E7%A1%80%E6%9C%AF%E8%AF%AD)
      - [3.5 AEM 常用操作](#35-aem-%E5%B8%B8%E7%94%A8%E6%93%8D%E4%BD%9C)
        - [3.5.1 调试AEM代码](#351-%E8%B0%83%E8%AF%95aem%E4%BB%A3%E7%A0%81)
    - [4. AEM Build命令详解](#4-aem-build%E5%91%BD%E4%BB%A4%E8%AF%A6%E8%A7%A3)
      - [4.1 MVN build命令相关知识](#41-mvn-build%E5%91%BD%E4%BB%A4%E7%9B%B8%E5%85%B3%E7%9F%A5%E8%AF%86)
      - [4.2 AEM Build命令结构解释](#42-aem-build%E5%91%BD%E4%BB%A4%E7%BB%93%E6%9E%84%E8%A7%A3%E9%87%8A)
    - [5. AEM 相关学习资料](#5-aem-%E7%9B%B8%E5%85%B3%E5%AD%A6%E4%B9%A0%E8%B5%84%E6%96%99)
      - [5.1 Adobe 官方教程入口](#51-adobe-%E5%AE%98%E6%96%B9%E6%95%99%E7%A8%8B%E5%85%A5%E5%8F%A3)
      - [5.2 Adobe 官方视频教程入口](#52-adobe-%E5%AE%98%E6%96%B9%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B%E5%85%A5%E5%8F%A3)
      - [5.3 Adobe 官方实例教程入口](#53-adobe-%E5%AE%98%E6%96%B9%E5%AE%9E%E4%BE%8B%E6%95%99%E7%A8%8B%E5%85%A5%E5%8F%A3)
      - [5.4 Adobe官方aem-project-archetype](#54-adobe%E5%AE%98%E6%96%B9aem-project-archetype)
      - [5.5 Adobe官方“怎么样实现XX”文章汇总](#55-adobe%E5%AE%98%E6%96%B9%E6%80%8E%E4%B9%88%E6%A0%B7%E5%AE%9E%E7%8E%B0xx%E6%96%87%E7%AB%A0%E6%B1%87%E6%80%BB)
    - [6. AEM分步学习](#6-aem%E5%88%86%E6%AD%A5%E5%AD%A6%E4%B9%A0)
      - [6.1 Part 1 Project Setup](#61-part-1-project-setup)
      - [6.2 Part 2 Creating a Base Page and Template](#62-part-2-creating-a-base-page-and-template)
      - [6.3 Part 3 Client-Side Libraries and Responsive Grid](#63-part-3-client-side-libraries-and-responsive-grid)
      - [6.4 Part 4 Developing with the Style System](#64-part-4-developing-with-the-style-system)
      - [6.5 Part 5 Navigation and Search](#65-part-5-navigation-and-search)
      - [6.5 Part 6 Sling Models and Card Component](#65-part-6-sling-models-and-card-component)
    - [7. 常用技术点](#7-%E5%B8%B8%E7%94%A8%E6%8A%80%E6%9C%AF%E7%82%B9)
      - [7.1 在线查看AEM的log](#71-%E5%9C%A8%E7%BA%BF%E6%9F%A5%E7%9C%8Baem%E7%9A%84log)
      - [7.2 Create AEM component by using Sling Model](#72-create-aem-component-by-using-sling-model)
      - [7.3 Create AEM component by using WCMUsePojo](#73-create-aem-component-by-using-wcmusepojo)
      - [7.4 Scheduling with a cron expression](#74-scheduling-with-a-cron-expression)
      - [7.5 Query Builder API](#75-query-builder-api)
      - [7.6 SSO in AEM](#76-sso-in-aem)
      - [7.7 Content Services](#77-content-services)
      - [7.8 Developing AEM Mobile Content Services](#78-developing-aem-mobile-content-services)
      - [7.9 Getting Started with AEM Content Services](#79-getting-started-with-aem-content-services)
      - [7.10 Developing Sling Model Exporters in AEM](#710-developing-sling-model-exporters-in-aem)
      - [7.11 Enabling JSON Export for a Component](#711-enabling-json-export-for-a-component)
      - [7.12 Scripting variables in JSP](#712-scripting-variables-in-jsp)
      - [7.13 How to Build AEM Projects using Apache Maven](#713-how-to-build-aem-projects-using-apache-maven)
      - [7.14 动态下拉菜单](#714-%E5%8A%A8%E6%80%81%E4%B8%8B%E6%8B%89%E8%8F%9C%E5%8D%95)
      - [7.15 Using Translator to Manage Dictionaries](#715-using-translator-to-manage-dictionaries)
      - [7.16 Configuring the Rich Text Editor](#716-configuring-the-rich-text-editor)
      - [7.17 Components for Page Authoring](#717-components-for-page-authoring)
      - [7.18 Understanding AEM Content Fragments](#718-understanding-aem-content-fragments)
      - [7.19 使用Multifield](#719-%E4%BD%BF%E7%94%A8multifield)
      - [7.20 使用SlingModel](#720-%E4%BD%BF%E7%94%A8slingmodel)
      - [7.21 Creating an Adobe Experience Manager HTML Template Language component that uses the WCMUsePojo API](#721-creating-an-adobe-experience-manager-html-template-language-component-that-uses-the-wcmusepojo-api)
      - [7.22 SlingModel](#722-slingmodel)
      - [7.23 创建custom sling servlet](#723-%E5%88%9B%E5%BB%BAcustom-sling-servlet)
      - [7.24 创建render component](#724-%E5%88%9B%E5%BB%BArender-component)
      - [7.25 创建一个Servlet service](#725-%E5%88%9B%E5%BB%BA%E4%B8%80%E4%B8%AAservlet-service)
      - [7.26 Sling Servlet service 文档](#726-sling-servlet-service-%E6%96%87%E6%A1%A3)
      - [7.27 AEM配置系统用户](#727-aem%E9%85%8D%E7%BD%AE%E7%B3%BB%E7%BB%9F%E7%94%A8%E6%88%B7)
      - [7.28 SegmentNotFound Issue or AuthenticationSupport service missing issue](#728-segmentnotfound-issue-or-authenticationsupport-service-missing-issue)
      - [7.29 Mvn build 时出现类似不能下载Adobe相关依赖的依赖性错误](#729-mvn-build-%E6%97%B6%E5%87%BA%E7%8E%B0%E7%B1%BB%E4%BC%BC%E4%B8%8D%E8%83%BD%E4%B8%8B%E8%BD%BDadobe%E7%9B%B8%E5%85%B3%E4%BE%9D%E8%B5%96%E7%9A%84%E4%BE%9D%E8%B5%96%E6%80%A7%E9%94%99%E8%AF%AF)
      - [7.30 i18n的使用](#730-i18n%E7%9A%84%E4%BD%BF%E7%94%A8)
        - [7.30.1 OOTB的I18N translator](#7301-ootb%E7%9A%84i18n-translator)
        - [7.30.2 在HTML中和JS中调用I18N](#7302-%E5%9C%A8html%E4%B8%AD%E5%92%8Cjs%E4%B8%AD%E8%B0%83%E7%94%A8i18n)
      - [7.31 Editable and Static Templates](#731-editable-and-static-templates)
        - [7.31.1 Editable Templates](#7311-editable-templates)
        - [7.31.2 Static Templates](#7312-static-templates)
      - [7.32 命令后 CURL 安装和下载 package](#732-%E5%91%BD%E4%BB%A4%E5%90%8E-curl-%E5%AE%89%E8%A3%85%E5%92%8C%E4%B8%8B%E8%BD%BD-package)
        - [7.32.1 curl 下载 package](#7321-curl-%E4%B8%8B%E8%BD%BD-package)
        - [7.32.2 curl 上传或安装 package](#7322-curl-%E4%B8%8A%E4%BC%A0%E6%88%96%E5%AE%89%E8%A3%85-package)
    - [8. Self-Assessment Preparation and Learning worksheet](#8-self-assessment-preparation-and-learning-worksheet)
  - [AEM advanced technical knowledge study](#aem-advanced-technical-knowledge-study)
    - [1. 系统维护](#1-%E7%B3%BB%E7%BB%9F%E7%BB%B4%E6%8A%A4)
      - [1.1 清理磁盘空间占用](#11-%E6%B8%85%E7%90%86%E7%A3%81%E7%9B%98%E7%A9%BA%E9%97%B4%E5%8D%A0%E7%94%A8)
        - [1.1.1 Online Revision Cleanup](#111-online-revision-cleanup)
        - [1.1.2 Offline Revision Cleanup](#112-offline-revision-cleanup)
      - [1.2 关闭AEM默认的Version生成方式进一步永久性的减小磁盘占用](#12-%E5%85%B3%E9%97%ADaem%E9%BB%98%E8%AE%A4%E7%9A%84version%E7%94%9F%E6%88%90%E6%96%B9%E5%BC%8F%E8%BF%9B%E4%B8%80%E6%AD%A5%E6%B0%B8%E4%B9%85%E6%80%A7%E7%9A%84%E5%87%8F%E5%B0%8F%E7%A3%81%E7%9B%98%E5%8D%A0%E7%94%A8)
      - [1.3 数据存储方式](#13-%E6%95%B0%E6%8D%AE%E5%AD%98%E5%82%A8%E6%96%B9%E5%BC%8F)
        - [1.3.1 File Storage](#131-file-storage)
        - [1.3.2 Mongo Storage](#132-mongo-storage)
    - [2. Learning plan tracking form](#2-learning-plan-tracking-form)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# AEM Training

## AEM basic technical knowledge study
### 1. 什么是AEM
#### 1.1 AEM 官方定义
- Adobe Experience Manager is a web-based client-server system for building, managing, and deploying commercial websites and related services.
- A number of infrastructure-level and application-level functions are combined into a single integrated package.
#### 1.2 AEM 自我理解
##### 1.2.1 AEM简要介绍
AEM是 Adobe 出品的一个CMS管理系统，相比于市面上其他著名的CMS系统，比如Wordpress,织梦等，AEM具有灵活性高，高可复用性，定制化程度高，组件化和运维功能丰富等特点。 
 ##### 1.2.2 AEM具有以下显著特征：
  **所见即所得**: 一般的CMS系统都会提供很多预开发好的功能和页面，比如首页，文章详情页，文章列表页等页面，然后用户可以在CMS提供的管理后台添加和维护站点的相关信息，比如创建新的文章，而这些管理后台都只是表单型的提交文章数据到数据库，用户再次进入站点前台页面时，会读取后台配置好的文章数据，按照CMS厂商写死的固定显示样式来渲染文章。一般管理后台长这样：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20191107161210499.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0NvZGluZ0Jsb2c=,size_16,color_FFFFFF,t_70)
创建新文章面板：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20191107161313745.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0NvZGluZ0Jsb2c=,size_16,color_FFFFFF,t_70)
而AEM则不需要在一个独立的管理后台中进行表单式的提交数据，而是直接在最终页面上进行编辑，编辑完后直接显示
![在这里插入图片描述](https://img-blog.csdnimg.cn/20191107161449416.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0NvZGluZ0Jsb2c=,size_16,color_FFFFFF,t_70)
          **组件化**: 不用于一般CMS由开发商一次开发好所有网站功能，一般以页面为单位，用户只能在管理后台编辑数据的模式，AEM的具有一定逻辑代码的最小单元是组件，AEM平台本身提供了很多常用的组件，比如列表（链接，图片均可），富文本编辑，面包屑，图片，轮播图，表格等组件，开发者也可以开发任何自定义组件，比如上面图中，就是酒店房间列表组件，该组件提供一个编辑窗口来收集房间数据，最终按照开发者写好的HTML进行渲染。
下面是OOTB提供的一些组件：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20191107162126799.png)
          **文档型数据库**: 不用于一般的CMS系统使用MySql, SqlServer等关系型数据库，AEM采用文档型数据库（JCR）来存储数据。使用该数据库的显著特点是AEM的程序本身，以及用户所添加的数据，上传的图片等全部存储在AEM实例的所在文件夹中，文件夹结构如下：<br>.
![在这里插入图片描述](https://img-blog.csdnimg.cn/20191107162707872.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0NvZGluZ0Jsb2c=,size_16,color_FFFFFF,t_70)
#### 1.3 AEM 能做什么
   AEM 作为一个企业级的CMS管理系统，主要用户维护，创建和部署大型商业网站及其服务。

### 2. AEM 技术架构
####  2.1 AEM 三大分层和三大核心技术架构图  
![在这里插入图片描述](https://github.com/tobywang11030/AEM-Training/blob/master/AEM.png?raw=true)
#### 2.2 AEM 三大核心技术
#####  2.2.1 Apache Sling 
Apache Sling :: Servlet Resolution<br>
			 [https://sling.apache.org/old-stuff/servlet-resolution.html](https://sling.apache.org/old-stuff/servlet-resolution.html)<br>
			Apache Sling :: URL decomposition<br>
			 [http://sling.apache.org/documentation/the-sling-engine/url-decomposition.html](http://sling.apache.org/documentation/the-sling-engine/url-decomposition.html)<br>
			Apache Sling :: HTL Scripting<br>
			 [https://sling.apache.org/documentation/bundles/scripting/scripting-htl.html](https://sling.apache.org/documentation/bundles/scripting/scripting-htl.html)<br>
			Apache Sling :: Sling Models<br>
			 [https://sling.apache.org/documentation/bundles/models.html#specifying-an-alternate-adapter-class-     since-110](https://sling.apache.org/documentation/bundles/models.html#specifying-an-alternate-adapter-class-%20%20%20%20%20since-110)<br>
			 拓展书目：<br>
			 [Continuous Delivery of Apache Sling Applications](https://github.com/tobywang11030/mangoCMS/blob/master/Continuous%20Delivery%20of%20Apache%20Sling%20Applications.pdf)<br>
			 [Server-side OSGi with Apache Sling](https://github.com/tobywang11030/mangoCMS/blob/master/Server-side%20OSGi%20with%20Apache%20Sling.pdf)
			 
##### 2.2.2 java JCR & Apache Jackrabbit
Java JSR-170(JCR) <br>
		JCR规范下载<br>
		[http://download.oracle.com/otndocs/jcp/content_repository-1.0.1-mr-oth-JSpec/index.html](http://download.oracle.com/otndocs/jcp/content_repository-1.0.1-mr-oth-JSpec/index.html)<br>
		Jackrabbit：
		依据JCR规范的一个JCR实现类库 <br>
		[http://jackrabbit.apache.org/jcr/jackrabbit-architecture.html](http://jackrabbit.apache.org/jcr/jackrabbit-architecture.html)
##### 2.2.3 Apache Felix
 一个OSGI实现 官网 [http://felix.apache.org/](http://felix.apache.org/)<br>
 拓展书目: [OSGi and Apache Felix 3.0 Beginner's Guide](https://github.com/tobywang11030/mangoCMS/blob/master/OSGi%20and%20Apache%20Felix%203.0%20Beginner%27s%20Guide.pdf)
 
####  2.3. AEM 首选渲染层模板语言：HTL
HTML Template Language (HTL)是AEM所推荐使用的服务器端动态HTML模板语言<br>
		HTL 语法详解<br>
		 [https://github.com/Adobe-Marketing-Cloud/htl-spec/blob/master/SPECIFICATION.md#221-use](https://github.com/Adobe-Marketing-Cloud/htl-spec/blob/master/SPECIFICATION.md#221-use)<br>
		HTL Adobe 官方教程<br>
		 [https://helpx.adobe.com/experience-manager/htl/using/getting-started.html](https://helpx.adobe.com/experience-manager/htl/using/getting-started.html)
### 3. AEM 开发和使用
#### 3.1 AEM 开发/部署/运维流程图
![在这里插入图片描述](https://github.com/tobywang11030/AEM-Training/blob/master/%E5%BA%94%E7%94%A8%E4%BC%81%E4%B8%9A%E6%9E%B6%E6%9E%84%E5%88%86%E6%9E%90%E6%A8%A1%E7%89%88.png?raw=true)
#### 3.2 启动 AEM
##### 3.2.1 直接运行jar文件
我们可以直接双击运行cq-author-4502.jar这个文件来启动AEM，但这只是快速调试用的临时启动方式，用该方式无法调试代码，以及优化AEM启动参数等。
##### 3.2.2 在命令行中使用java命令启动
无论是开发者开发还是生产环境部署，均首选此方式。一般的启动命令如下：

```bash
java -XX:MaxPermSize=1028m -Xmx2048M -Xdebug -Xnoagent -Djava.compiler=NONE -Xrunjdwp:transport=dt_socket,address=30308,server=y,suspend=n -jar cq-author-4502.jar  -r author localdev
```
+ ‘-XX:MaxPermSize=1028m -Xmx2048M’ 这一段为JVM优化参数，具体请查阅JVM优化相关资料
+ ‘-Xdebug -Xnoagent -Djava.compiler=NONE -Xrunjdwp:transport=dt_socket,address=30308’ 这一段为开启debug，并配置调试端口为30308
+ '-jar cq-author-4502.jar' 指定jar文件
+ ‘-r author localdev’ 指定runmode，其中author为OOTB内置runmode，author即为author模式启动，publish为publish模式启动，localdev为自定义runmode，可实现诸如不同环境的自动化配置等功能。
#### 3.3 AEM 的开发和部署工具
##### 3.3.1 推荐使用IntelliJ进行AEM开发
相较于Eclipse，IntelliJ更加灵活便捷，而且IntelliJ的插件市场也能提供很多丰富的实用插件。
使用IntelliJ进行AEM开发时，请在导入AEM项目时，选择Maven项目，如下：
![Intellij导入Maven项目](https://github.com/tobywang11030/AEM-Training/blob/master/import-maven.png?raw=true)
##### 3.3.2 部署AEM代码到Instance
有三种方式可以部署代码到AEM实例
+ 使用IntelliJ的Maven控制台
由于一般AEM项目均采用Maven进行依赖管理，并且一般我们也会在项目配置文件中配置AEM的Maven的部署插件，所以，我们可以按如下操作部署AEM代码：
![使用IntelliJ的maven插件部署代码](https://github.com/tobywang11030/AEM-Training/blob/master/maven-deploye.png?raw=true)
<br>**注意**:一般我们会选择项目root目录下的lifecycle中的clean,install。这样会部署全部项目代码，有时候我们也可以只选中某个子模块的lifecycle，比如xxx.ui.apps这样的ui层模块，这样只会部署组件等代码，可以提高部署效率。
+ 用命令行部署代码到AEM
我们可以直接在项目根目录或子模块目录运行控制台并运行如下命令来部署代码：

```bash
mvn clean install -PautoInstallPackage,local-author,adobe-public
```
+ 使用IntelliVault插件部署
配置IntelliJ的IntelliVault插件后，我们可以直接在需要部署的任意folder上右键，在弹出的选项中直接选择Pull/Push代码到Instance，如下：
![在这里插入图片描述](https://github.com/tobywang11030/AEM-Training/blob/master/vault.png?raw=true)
<br>**注意**:一般这种方式只是快速调试用，并不建议用该方式进行代码提交前的自测。
#### 3.4 AEM 基础术语
   + Author instance
     Typically, for security, governance, and other reasons, a production site will divide instances of AEM into Author and Publish instances. For more information on deployment architecture (including Author/Publish instances), see documentation about AEM Instances.
	
  + Publish instance
	For security, governance, and other reasons, a production site will typically divide instances of AEM into Author and Publish instances. For more information on deployment architecture (including Author/Publish instances), see documentation about AEM Instances.
	
  + Component
	In AEM, a Component is an object type, instances of which can generally be created by dragging and dropping them from, say, the Sidekick. So for example, out-of-the-box components that ship with AEM include the Text, Title, Tag Cloud, Carousel, Image, and List components, all available from the Sidekick at runtime.
  + Template
	In AEM, a Template specifies a particular type of page. It defines the structure of a page (while also typically specifying a thumbnail image, and various properties). For example, you may have separate templates for product pages, sitemaps, and contact information.
  + Page
    组件（模板也是一种特殊的组件）是AEM的最小的代码逻辑单元，但组件本身是无法实例化的，它只是一个代码对用户是不可见的，在AEM中，页面就是一个实例化的容器，组件必须插入到页面中才可以显示并运行给用户，用户和AEM运维人员实际操作的都是页面，用户基于某个模板创建一个页面，然后在页面上插入和编辑某些组件，页面本身不包含任何代码，页面的实际功能由它的模板和插入的组件所决定。
   + Digital assets
	In AEM, Digital Assets are (typically) images and rich media files. For further information, see Working with Digital Assets in DAM.
   + Workflow
	The AEM Workflow system allows for creation of automated processes involving pages or assets.
	
  + Replication agents
	Replication agents are central to AEM as the mechanism used to Publish (activate) content from an author to a publish environment; flush content from the Dispatcher cache; return user generated content (for example, form input) from the Publish environment to the Author environment.

#### 3.5 AEM 常用操作
##### 3.5.1 调试AEM代码
以IntelliJ为例，首先需要保证是以命令行启动的AEM并配置了相关debug参数，然后，按照如下配置IntelliJ的debug
![在这里插入图片描述](https://github.com/tobywang11030/AEM-Training/blob/master/debug.png?raw=true)
在创建好的remote debug config中，端口输入AEM启动参数中配置的30308，点击ok保存
![在这里插入图片描述](https://github.com/tobywang11030/AEM-Training/blob/master/debug2.png?raw=true)
配置完成后，在右上角选择我们刚才的debug配置，再点击右边的小虫子debug按钮即可开启debug。
![IntelliJ开启debug](https://github.com/tobywang11030/AEM-Training/blob/master/debug3.png?raw=true)
### 4. AEM Build命令详解
#### 4.1 MVN build命令相关知识
**参考书目**：[Maven权威指南中文版](https://github.com/tobywang11030/mangoCMS/blob/master/Maven%E6%9D%83%E5%A8%81%E6%8C%87%E5%8D%97%E4%B8%AD%E6%96%87%E7%89%88.pdf)
#### 4.2 AEM Build命令结构解释
![在这里插入图片描述](https://github.com/tobywang11030/AEM-Training/blob/master/SIPOC%E5%88%86%E6%9E%90%E6%A8%A1%E7%89%88%20(3).png?raw=true)
### 5. AEM 相关学习资料
#### 5.1 Adobe 官方教程入口 
[https://helpx.adobe.com/support/experience-manager/6-3.html](https://helpx.adobe.com/support/experience-manager/6-3.html)

#### 5.2 Adobe 官方视频教程入口
 [https://helpx.adobe.com/experience-manager/kt/index/aem-6-3-videos.html](https://helpx.adobe.com/experience-manager/kt/index/aem-6-3-videos.html)

#### 5.3 Adobe 官方实例教程入口
教你一步一步的开发AEM，很实用 附带官方实例源码 
[https://github.com/Adobe-Marketing-Cloud/aem-guides-wknd](https://github.com/Adobe-Marketing-Cloud/aem-guides-wknd)

#### 5.4 Adobe官方aem-project-archetype 

```bash
mvn archetype:generate -DarchetypeGroupId=com.adobe.granite.archetypes -DarchetypeArtifactId=aem-project-archetype -DarchetypeVersion=10 -DarchetypeRepository=https://repo.adobe.com/nexus/content/groups/public/
```
#### 5.5 Adobe官方“怎么样实现XX”文章汇总
[https://helpx.adobe.com/experience-manager/topics/how-to.html](https://helpx.adobe.com/experience-manager/topics/how-to.html)
### 6. AEM分步学习
#### 6.1 Part 1 Project Setup 
[https://helpx.adobe.com/experience-manager/kt/sites/using/getting-started-wknd-tutorial-develop/part1.html](https://helpx.adobe.com/experience-manager/kt/sites/using/getting-started-wknd-tutorial-develop/part1.html)

#### 6.2 Part 2 Creating a Base Page and Template 
[https://helpx.adobe.com/experience-manager/kt/sites/using/getting-started-wknd-tutorial-develop/part2.html](https://helpx.adobe.com/experience-manager/kt/sites/using/getting-started-wknd-tutorial-develop/part2.html)

#### 6.3 Part 3 Client-Side Libraries and Responsive Grid 
[https://helpx.adobe.com/experience-manager/kt/sites/using/getting-started-wknd-tutorial-develop/part3.html](https://helpx.adobe.com/experience-manager/kt/sites/using/getting-started-wknd-tutorial-develop/part3.html)

#### 6.4 Part 4 Developing with the Style System
 [https://helpx.adobe.com/experience-manager/kt/sites/using/getting-started-wknd-tutorial-develop/part4.html](https://helpx.adobe.com/experience-manager/kt/sites/using/getting-started-wknd-tutorial-develop/part4.html)

#### 6.5 Part 5 Navigation and Search 
[https://helpx.adobe.com/experience-manager/kt/sites/using/getting-started-wknd-tutorial-develop/part5.html](https://helpx.adobe.com/experience-manager/kt/sites/using/getting-started-wknd-tutorial-develop/part5.html)

#### 6.5 Part 6 Sling Models and Card Component 
[https://helpx.adobe.com/experience-manager/kt/sites/using/getting-started-wknd-tutorial-develop/part6.html](https://helpx.adobe.com/experience-manager/kt/sites/using/getting-started-wknd-tutorial-develop/part6.html)

### 7. 常用技术点
#### 7.1 在线查看AEM的log 
http://localhost:4502/system/console/slinglog
#### 7.2 Create AEM component by using Sling Model 
https://helpx.adobe.com/experience-manager/using/aem63_slingmodel.html
#### 7.3 Create AEM component by using WCMUsePojo 
https://helpx.adobe.com/experience-manager/using/first_htl_WCMUsePojo.html
#### 7.4 Scheduling with a cron expression 
https://sling.apache.org/documentation/bundles/scheduler-service-commons-scheduler.html
#### 7.5 Query Builder API 
https://helpx.adobe.com/experience-manager/6-3/sites/developing/using/querybuilder-api.html
#### 7.6 SSO in AEM 
https://helpx.adobe.com/experience-manager/6-3/sites/deploying/using/single-sign-on.html
#### 7.7 Content Services 
https://helpx.adobe.com/experience-manager/6-4/mobile/using/content-services.html
#### 7.8 Developing AEM Mobile Content Services 
https://helpx.adobe.com/experience-manager/6-4/mobile/using/spaces-and-entities.html
#### 7.9 Getting Started with AEM Content Services 
https://helpx.adobe.com/experience-manager/kt/sites/using/content-services-tutorial-use.html
#### 7.10 Developing Sling Model Exporters in AEM 
https://helpx.adobe.com/experience-manager/kt/platform-repository/using/sling-model-exporter-tutorial-develop.html
#### 7.11 Enabling JSON Export for a Component  
https://helpx.adobe.com/experience-manager/6-3/release-notes/json-exporter-dev-fp.html
#### 7.12 Scripting variables in JSP 
https://cwiki.apache.org/confluence/display/SLING/Scripting+variables#Scriptingvariables-Commonscriptingvariables
#### 7.13 How to Build AEM Projects using Apache Maven 
https://helpx.adobe.com/experience-manager/6-4/sites/developing/using/ht-projects-maven.html
#### 7.14 动态下拉菜单 
https://www.linkedin.com/pulse/granite-datasource-inside-touch-ui-select-object-aem-gonz%C3%A1lez-ramos
https://mkbansal.wordpress.com/2016/01/04/aem-acs-generic-list-dialog-configuration-touch-ui/
https://helpx.adobe.com/experience-manager/using/creating-touchui-validate11.html
#### 7.15 Using Translator to Manage Dictionaries 
https://helpx.adobe.com/experience-manager/6-3/sites/developing/using/i18n-translator.html
#### 7.16 Configuring the Rich Text Editor 
https://helpx.adobe.com/experience-manager/6-3/sites/administering/using/rich-text-editor.html#PluginsandtheirFeatures
#### 7.17 Components for Page Authoring 
https://helpx.adobe.com/experience-manager/6-2/sites/authoring/using/editmode.html#Text
#### 7.18 Understanding AEM Content Fragments 
https://helpx.adobe.com/experience-manager/kt/sites/using/content-fragments-feature-video-understand.html
#### 7.19 使用Multifield 
https://helpx.adobe.com/experience-manager/using/multifield_aem63.html
#### 7.20 使用SlingModel 
https://helpx.adobe.com/experience-manager/using/aem63_htl_repeat_slingmodel.html
#### 7.21 Creating an Adobe Experience Manager HTML Template Language component that uses the WCMUsePojo API 
https://helpx.adobe.com/experience-manager/using/first_htl_WCMUsePojo.html
#### 7.22 SlingModel 
https://helpx.adobe.com/experience-manager/using/aem64_coral_resourcetypes.html
#### 7.23 创建custom sling servlet
https://helpx.adobe.com/experience-manager/using/resourcetypes.html
#### 7.24 创建render component 
https://helpx.adobe.com/experience-manager/using/resourcetypes.html#h2Createarendercomponentthatusesthetemplatebrh2
#### 7.25 创建一个Servlet service 
http://www.6dglobal.com/blog/servlets-sling-case-disappearing-servlet-path-2013-01-31
#### 7.26 Sling Servlet service 文档 
https://sling.apache.org/documentation/the-sling-engine/servlets.html
#### 7.27 AEM配置系统用户
[http://localhost:4502/crx/explorer/index.jsp](http://localhost:4502/crx/explorer/index.jsp)
#### 7.28 SegmentNotFound Issue or AuthenticationSupport service missing issue
[https://github.com/tobywang11030/mangoCMS/blob/master/SegmentNotFound%20Issue%20and%20AuthenticationSupport%20service%20missing%20issue](https://github.com/tobywang11030/mangoCMS/blob/master/SegmentNotFound%20Issue%20and%20AuthenticationSupport%20service%20missing%20issue)

#### 7.29 Mvn build 时出现类似不能下载Adobe相关依赖的依赖性错误
Maven settings <br>
[http://helpx.adobe.com/experience-manager/kb/SetUpTheAdobeMavenRepository.html](http://helpx.adobe.com/experience-manager/kb/SetUpTheAdobeMavenRepository.html)<br>
运行时加上<br>

```bash
 -Padobe-public
```
#### 7.30 i18n的使用
##### 7.30.1 OOTB的I18N translator 
http://localhost:4502/libs/cq/i18n/translator.html
##### 7.30.2 在HTML中和JS中调用I18N
+ /etc/languages (没有的话，自己创建它，添加languages属性，类型为数组)下定义全局语言例如：sc_cn, zh_tw

+ 代码合适位置，创建自己的i18n定义文件，例如/apps/ns-zh/i18n/zh.json，文件的node属性中包含jcr:language=sc_cn，jcr:mixinTypes=mix:language
+ 创建语言分类页面，例如sc_cn.html，在其jcr:content中添加jcr:language=sc_cn
+ 在组件的HTML中使用  ${'check-address' @i18n}
+ 在JS中使用，先全局定义

```javascript
先引入这个category的JS：granite.utils
Granite.I18n.setLocale('sc_cn');
```
+ 然后在自己的JS中

```javascript
Granite.I18n.get('upload-time')；
```
#### 7.31 Editable and Static Templates
##### 7.31.1 Editable Templates
[官方定义](https://helpx.adobe.com/experience-manager/6-3/sites/authoring/using/templates.html#CreatingandManagingNewTemplates)
+ Can be created and edited by template authors using the Template console and editor. The Template console is accessible in the General section of the Tools console.
+ After the new page is created a dynamic connection is maintained between the page and the template. This means that changes to the template structure and/or locked content will be reflected on any pages created with that template. Changes to the unlocked (i.e. initial) content will not be reflected.
+ Use content policies, which you can define these from the template editor, to persist the design properties. Design mode within the page editor is no longer used for editable templates.

##### 7.31.2 Static Templates
+ Static templates have been available for several versions of AEM.
+ They are provided by your developers, so they cannot be created or edited by authors.
+ Are copied to create the new page, but no dynamic connection exists after this (though the template name is registered for information).
+ Use Design Mode to persist design properties.
+ Because editing static templates is the exclusive task of a developer, please see the developer document Page Templates - Static for more information.

By definition, the template console and template editor only allow creation and editing of editable templates. Therefore this document focuses exclusively on editable templates.
#### 7.32 命令后 CURL 安装和下载 package
##### 7.32.1 curl 下载 package

```bash
curl -# -u admin:admin -O http://localhost:4503/etc/packages/my_packages/image.zip
```
##### 7.32.2 curl 上传或安装 package

```bash
curl -u admin:admin -F file=@"content.zip" -F name=“Package” -F force=true -F install=false http://localhost:4502/crx/packmgr/service.jsp --progress-bar -o upload.txt
```

### 8. Self-Assessment Preparation and Learning worksheet 
| Topics | Cost(hours) | Details | Reference | Start Date | End Date | Completed? | Questions | Comment |
| :----- | ------------ | :----- | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| Basic AEM knowledge study   |   | |   |   |   |   |   |   |
| Installing and configuring an AEM developer environment  |   |  1. Install AEM on supported operating systems.  <br>2. Install AEM with different run modes (Author and Publish). <br> 3. Start AEM in debug mode for remote debugging. <br>4. Setup and configure replication agents. <br>5.  Setup and configure a Web server<br>5. Setup and manage OSGi configurations.<br>6. Manage users and groups<br>7. Manage Access Control Level (ACL) permissions. |   |   |   |   |   |   |
|  Building and deploying AEM projects |   | 1. Configure a source control system to manage files in AEM<br>2. Build and deploy AEM projects by using Maven |   |   |   |   |   |   |
| Building AEM components  |   | 1. Create custom components and dialogs<br>2. Create templates and page components <br>3. Create client libraries.<br>4. Extend out-of-the-box AEM components.  |   |   |   |   |   |   |
|  Building OSGi services |   |  1. Create custom OSGi services. <br>2. Create and manage custom OSGi configurations.<br>3. Configure and manage OSGi services and bundles by using the Felix web console. <br>4. Manage Maven dependencies.|   |   |   |   |   |   |
| Troubleshooting AEM projects  |   | 1. Create custom log files by using the Web console.<br>2. Configure and manage AEM log levels for specific AEM environments. <br>3. Given an option for starting AEM, I can select the correct parameter(s) for starting AEM. <br>4. Troubleshoot caching issues related to the Dispatcher and browsers.<br>5. Troubleshoot AEM configurations.|   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |   |

## AEM advanced technical knowledge study

### 1. 系统维护
#### 1.1 清理磁盘空间占用
AEM使用一段时间之后，因AEM的存储机制问题，AEM的Repository的文件夹的大小会越来越大，会造成极大的系统开销甚至导致数据错误时AEM崩溃无法运行。AEM6.3以后提供两种方式清理AEM的数据仓库以节省磁盘占用。下面为具体步骤，亦可参考Adobe官网https://helpx.adobe.com/experience-manager/6-4/sites/deploying/using/revision-cleanup.html
##### 1.1.1 Online Revision Cleanup
依次进入Tools-Operations-Maintenance 进入系统维护工具
或者直接访问 http://localhost:4502/libs/granite/operations/content/maintenance.html
![在这里插入图片描述](https://img-blog.csdnimg.cn/2019052915400967.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0NvZGluZ0Jsb2c=,size_16,color_FFFFFF,t_70)
AEM提供了两组清理工具，一组为建议Daily执行的，一组为建议Weekly执行的。
点击Daily Maintenance Window，即可发现系统默认提供了两个清理工具<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190529154448221.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0NvZGluZ0Jsb2c=,size_16,color_FFFFFF,t_70)
可以直接手动运行这个Revision Clean Up，该工具运行后，可以减少repository\segmentstore文件夹的大小
点击Weekly Maintenance Window，即可发现系统默认提供了两个清理工具<br>
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190529154828555.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0NvZGluZ0Jsb2c=,size_16,color_FFFFFF,t_70)
<br>
可以直接手动运行这个Data Store Garbage Collection，该工具运行后，可以减少repository\datastore文件夹的大小<br>
**备注**：如发现运行Online Revision Cleanup中的任何清理工具均无任何效果，则需要用Offline Revision Cleanup进行清理。该问题根据官网介绍，可能是因为清理机制的问题。
##### 1.1.2 Offline Revision Cleanup
如发现Online Revision Cleanup的方式无法清理，需要使用Offline Revision Cleanup

首先访问https://repo1.maven.org/maven2/org/apache/jackrabbit/oak-run/下载合适版本的 oak-run.jar 工具

然后关掉AEM实例

依次执行如下命令：
```bash
Shut down AEM.
```
执行命令 
```bash
java -jar oak-run.jar checkpoints install-folder/crx-quickstart/repository/segmentstore
```
执行命令
```bash
 java -jar oak-run.jar checkpoints install-folder/crx-quickstart/repository/segmentstore rm-unreferenced
```
执行命令 
```bash
java -jar -Dsun.arch.data.model=32 oak-run.jar compact install-folder/crx-quickstart/repository/segmentstore
```
#### 1.2 关闭AEM默认的Version生成方式进一步永久性的减小磁盘占用
AEM默认会开启Version生成，当你上传，更新，新建，发布一个页面或者asset时，均会生成一个对应的Version，而这些额外的Version默认设置下是不会被删除的，会造成磁盘占用越来越大，可以通过修改VersionManagerImpl这个类的设置开关闭Version生成，或者开启Version Purgin功能自动清理Version。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190529180247940.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0NvZGluZ0Jsb2c=,size_16,color_FFFFFF,t_70)
#### 1.3 数据存储方式
AEM有两种形式的数据，一种为Node数据，主要存储的是JCR属性，另一个为二进制数据，主要存储的是上传的图片，视频等。安装并启动一个AEM实例后，在默认情况下，这两种形式的数据均以Tar Storage（一种文件存储系统）的形式储存在本地磁盘中。可参考https://helpx.adobe.com/experience-manager/6-4/sites/deploying/using/storage-elements-in-aem-6.html
##### 1.3.1 File Storage
AEM的默认数据存储方式，该方式下数据已Tar文件的形式存储，该方式具有比较高的性能，也是AEM建议的存储方式，该方式的缺点是如果用户会上传大量的图片，视频，以及每天会有大量的author和修改的话，会造成repository文件夹很大，甚至几TB，这样一是比较昂贵，而是因为数据文件过多，增加了数据损坏导致系统崩溃的风险。

该模式的几种优化方案：
+ 将一个网络磁盘挂载到服务器上映射为本地磁盘路径，然后将数据文件存储在该路径下，因为这个网络磁盘可能是一个比较便宜的虚拟机，或者是类似于OSS这样的专业网盘，价格相比服务器磁盘会便宜，可降低运维费用。备注：可参考该文档将阿里的OSS映射为一个本地磁盘路径，http://data-migration.oss-ap-southeast-1.aliyuncs.com/MountOSSasLocalFilesystemusingOSSFS.pdf
+ 将二进制数据和Node数据拆开，单独将二进制数据（视频，图片等）配置在第三方云当中，目前AEM原生支持Amazon S3 Data Store和Azure Data Store这两种云。具体配置可参考https://helpx.adobe.com/experience-manager/6-4/sites/deploying/using/data-store-config.html

##### 1.3.2 Mongo Storage
根据AEM官方介绍，如果符合以下条件，建议使用Mongo Storage存储方式，否则还是应使用默认的file storage

+ More than 1000 unique users per day;
+ More than 100 concurrent users;
+ High volumes of page edits;
+ Large rollouts or activations

启用该存储方式，可以将Node数据以及二进制数据（可选，二进制数据仍可以已文件形式存在本地磁盘或者S3等第三方云），这样可以借助Mongo Storage的高性能，分布式的特点提高AEM的数据存储性能。具体可参考https://helpx.adobe.com/experience-manager/6-4/sites/deploying/using/aem-with-mongodb.html

### 2. Learning plan tracking form
| Topics | Cost(hours) | Details | Reference | Start Date | End Date | Completed? | Questions | Comment |
| :------------ | ------------ | :------------ | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| Install and Configure the AEM Environment  |   | 1. Identify the default runmode of the AEM server<br>2. Identify the default runmode of the AEM server<br>3. Apply best practices for installation of AEM 6.0 ondifferent operating systems<br>4. Determine the valid run modes to operate AEM<br>5. State the configurations required for the installation on application servers<br>6. Identify the supported operating system for installing AEM on an application  |   |   |   |   |   |   |
|  Build and deploy AEM projects |   |  1. Apply version control management best practices<br>2. Apply standard procedures to create multi-module Maven projects<br>3. Apply standard procedures to develop and debug application using IDE |   |   |   |   |   |   |
| Build AEM Components |   | 1. Given a scenario, I can analyze and evaluate the usage of forms, metadata and other features<br>2. Apply best practices to create and use client libraries<br>3. Apply best practices to create, customize, and configure AEM components and dialogs<br>4. Given a scenario, I can determine workflow steps and processes<br>5. Apply standard procedures to create and extend AEM components, templates, and page components  |   |   |   |   |   |   |
|  Create and configure OSGI services |   |1. Apply standard processes to manage OSGI bundles,services and dependencies<br>2. Analyze and evaluate the logs to identify discrepancies<br>3. Given a scenario, I can determine the OSGI configuration<br>4. Apply a standard process to create OSGI components and services   |   |   |   |   |   |   |
|  Setup content structure and taxonomy |   | 1. Apply best practices to manage user-generated content<br>2. Given a scenario, I can analyze content structure and evaluate query efficiency<br>3. Apply standard procedures to manage AEM tagging framework<br>4. Given a scenario, I can analyze workflows to setup multilingual sites  |   |   |   |   |   |   |
| Create AEM security policies  |   |  1. Evaluate AEM users and group permissions<br>2. Apply standard processes to set up CUGs<br>3. Evaluate ACLs and permission level for users/groups |   |   |   |   |   |   |
| Set-up and configure deployment infrastructure  |   | 1. Analyze and evaluate logs and other artifacts to manage garbage collection and TAR optimization<br>2. Apply standard procedure for backend data store configuration<br>3. Apply standard procedures to integrate AEM applications with Marketing Cloud tools and third-party tools<br>4. Apply standard procedures to integrate AEM applications with LDAP/SSO/OAUTH Providers/Third-Party login authentication mechanisms  |   |   |   |   |   |   |
| Troubleshoot AEM projects  |   |  1. Troubleshoot issues related to performance<br>2. Troubleshoot functional issues<br>3. Identify issues related to scalability bottlenecks |   |   |   |   |   |   |

