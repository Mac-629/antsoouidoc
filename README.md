# 这是antsoo-ui组件库的文档项目
## 使用vuese通过注释自动生成文档
### 安装vuese
1、全局安装vuese/cli：

	npm i -g @vuese/cli
	
2、根据目录结构生成对应结构的markdown文件，存放在生成的website文件夹里：

	vuese gen
	
3、（可选）用生成的文件在本地部署一个服务器：

	vuese serve 
	
	同时打开浏览器：
	
	vuese serve --open
### 编写文档
1、	组件的描述

作为文档，你应该使用一句话向使用者介绍组件的用途。只需要在组件定义上添加一行普通的前导注释即可，如下：

    //这是组件的描述
    export default {
        ...
    }
