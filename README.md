# icare

## 安装

1. [flutter集成gRPC](https://blog.csdn.net/qq_30903139/article/details/88558414)
2. 拉取proto且转dart、复制code_zh.json:
        ./ios_build.sh prepare

## 注意

1. 如果是第一次跑ios，必须先用xcode打开ios/Runner先跑一下。
2. 注意关注服务器proto是否有新变更，如果有要更新并编译。
3. 因为flutter的ui本身可读性差，一定要加上自动格式化插件，不要提交未格式化的代码。
