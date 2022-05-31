# 使用华为云CloudArtifact npm 私仓Workflow样例
私有依赖库(CloudArtifact)是发布服务（[CloudRelease](https://support.huaweicloud.com/cloudrelease/index.html)）的语言软件仓库功能。用于管理私有组件（开发者通俗称之为私服），包括Maven、Npm、Go、PyPI、Rpm等多种仓库格式。   
使用华为云CloudArtifact npm 私仓有如下场景：  
1.npm publish 推送maven组件到 CloudArtifact npm 私仓   
2.npm install 拉取CloudArtifact npm 私仓的npm组件 

## **前置工作**
(1)[新建私有依赖库](https://support.huaweicloud.com/usermanual-releaseman/cloudrelease_01_0008.html)  
(2)[管理用户权限](https://support.huaweicloud.com/usermanual-releaseman/cloudrelease_01_0011.html)