# idea中的copilot无法正常登录

* 首先最好是有墙，这样会更容易登录一些

我们需要配置一下我们的hosts文件：

1. `win + r`输入`drivers` 或者找到`C:\Windows\System32\drivers`

2. 我们进入`etc`的文件夹下，以管理员模式打开`hosts`文件

3. 添加如下的配置：

```

140.82.112.21                central.github.com
185.199.108.133              desktop.githubusercontent.com
185.199.108.153              assets-cdn.github.com
185.199.108.133              camo.githubusercontent.com
185.199.108.133              github.map.fastly.net
199.232.69.194               github.global.ssl.fastly.net
140.82.114.4                 gist.github.com
185.199.108.153              github.io
140.82.112.3                 github.com
140.82.114.5                 api.github.com
185.199.108.133              raw.githubusercontent.com
185.199.108.133              user-images.githubusercontent.com
185.199.108.133              favicons.githubusercontent.com
185.199.108.133              avatars5.githubusercontent.com
185.199.108.133              avatars4.githubusercontent.com
185.199.108.133              avatars3.githubusercontent.com
185.199.108.133              avatars2.githubusercontent.com
185.199.108.133              avatars1.githubusercontent.com
185.199.108.133              avatars0.githubusercontent.com
185.199.108.133              avatars.githubusercontent.com
140.82.113.9                 codeload.github.com
52.216.171.43                github-cloud.s3.amazonaws.com
52.217.33.196                github-com.s3.amazonaws.com
52.216.93.147                github-production-release-asset-2e65be.s3.amazonaws.com
52.216.93.147                github-production-user-asset-6210df.s3.amazonaws.com
52.217.207.33                github-production-repository-file-5c1aeb.s3.amazonaws.com
185.199.108.153              githubstatus.com
64.71.144.211                github.community
185.199.108.133              media.githubusercontent.com
185.199.108.133              objects.githubusercontent.com
185.199.108.133              raw.github.com

```

4. 再尝试配置copilot