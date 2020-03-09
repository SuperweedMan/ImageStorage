# ImageStorage
### Typora 设置步骤
1. 文件--》偏好设置--》图像，首先选择下载或更新安装PicGo-Core：
S： PicGo一款基于Node.js开发的上传程序。
2. 安装完成之后，将上传服务选择为PicGo-Core(command line)。
3. 打开配置文件，默认是在C:\Users\liny\.picgo\config.json。配置示例：
 ```json
 {
  "picBed": {
    "github": {
      "repo": "linysuccess/myblog",
      "token": "your-github-token",
      "path": "img/",
      "customUrl": "",
      "branch": "master"
    },
    "current": "github",
    "uploader": "github"
  },
  "picgoPlugins": {}
}
 ```
 其中ropo是接收图片文件的仓库地址，token是用于github API认证的身份标识，生成方法见下文。
4. 可以点击验证图片上传选项按钮验证上传功能是否已正确配置。
### Github 设置
访问：https://github.com/settings/tokens
然后点击Generate new token。
把repo的勾打上即可。
然后翻到页面最底部，点击Generate token的绿色按钮生成token。
