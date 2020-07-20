# ios自动打包发布

## exportXXX.plist修改

1. teamID的值改成自己的
2. 发布版里面signingCertificate如果不一样也改一下

## exportXXX.plist修改

project_name和scheme_name改一下

## 注意

1. clean这块我注释过了，是因为我这边flutter项目是不能用的。
2. 如果是flutter项目，要先执行flutter build ios。
3. 关于AppleId帐号密码那块，我这边其实是不需要的，直接打包就自动上传上去了，这应该跟环境有关。

## [flutter ios shell脚本自动打包](URL)
