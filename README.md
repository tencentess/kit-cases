# 腾讯电子签API接入工具包

## 项目说明
项目内是供导入的测试集，包括ess-电子签集成版、essbasic-电子签第三方应用集成

## 使用说明
### 文件夹
ess 对应集成版
essbasic 对应电子签第三方应用集成

### 导入
.json可直接导入到postman中

其中环境变量文件中SecretId、SecretKey需要填充，可以从kit对应的<指南文档>中获取
*-env-test.postman_environment.json

测试用例集合直接导入即可
*-kit.postman_collection.json

### 请求调用
测试用例集合ess需要对应使用ess-env-test的Environment
测试用例集合essbasic需要对应使用essbasic-env-test的Environment
打开测试集合，直接请求接口即可（部分接口参数需要根据情况自己修改下，如签署方姓名、手机号等）

## 电子签集成版API官网入口
[电子签集成版API](https://cloud.tencent.com/document/product/1323/70378)

## 电子签第三方应用集成API官网入口
[电子签第三方应用集成API](https://cloud.tencent.com/document/api/1420/61534)