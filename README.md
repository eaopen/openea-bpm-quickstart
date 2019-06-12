# Open BPM 
## 概述
基于开源工作流引擎的BPM套装，整合各种开源项目或组件，实现企业应用快速集成工作流能力。

# quick start

## bpm-quick on docker

快速实现BPM工作流应用(docker)

需要安装docker和docker-compose环境
```
# 启动bpm demo服务
cd bpm-allinone
docker-compose up -d
```

web端访问地址  http://localhost:7080

mobile端访问地址   http://localhost:7082

后台服务API  http://localhost:7080/api/swagger-ui.hmtl

用户名和密码为admin/admin


# OpenBPM 工程概述
基于开源工作流引擎Acitiviti的BPM服务套件。

## bpm-interface 服务接口以及封装
* 提供bpm-rest服务接口包装以及docker
* 基于spring-boot封装starter

## bpm-ui 前端UI相关功能
ui包含web前端explorer-ng和web打包工程以及mobile-vue 移动端APP

* explorer-ng BPM Web端UI

基于VUE和angular(activiti model采用angular)

* mobile-vue BPM移动端UI

基于VUE开发

## bpm-core 核心功能
bpm包含业务对象bus,表单form和流程wf
* bus 业务对象模块
* form 表单模块
* wf 流程模块

## bpm-support 支持功能
support包含base, auth,org以及sys
* org 内建组织权限功能
* sys 内建后台基础服务功能


# 参考
本项目整合众多开源项目，具体参见 openea-bpm 项目。


