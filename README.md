# 简易抖音项目

## 需求描述
- 视频功能
    - 视频Feed流
    - 视频投稿
    - 视频列表
- 用户功能
    - 用户注册
    - 用户登录
    - 个人主页
- 点赞功能
    - 点赞操作
    - 取消点赞
    - 查看点赞视频列表
- 关注功能
    - 关注用户
    - 取关用户
    - 获取关注列表
    - 获取粉丝列表
- 评论功能
    - 发表评论
    - 删除评论
    - 查看评论

## 技术栈
|         |             |
| --------- | --------- |
|    http框架    |    gin/hertz     |
|   orm框架 | Gorm |
|   对象存储服务 | minio |
|   日志管理 | uber-go/zap |
|   配置方案 | viper |
|   视频抽帧 |  FFmpeg |
|   鉴权方案 |  JWT-go |
|   分布式锁 | Go-redsync |
|   加密     |    crypto/bcrypt |
|   数据库   |     mysql |
|   缓存数据库 |    redis |
|   rpc框架     | grpc/kitx |
|   rpc协议     | protobuf | 