# 📄 GitHub IP hosts

通过使用 GitHub Action 每周自动更新 hosts 文件，解决中国大陆访问 GitHub 时遇到的抽风问题，诸如访问缓慢、图片加载失败等等。

# 目录

- [🛠️ 使用方法](#️-使用方法)
  - [1. 复制下面的 hosts 内容](#1-复制下面的-hosts-内容)
  - [2. 将内容粘贴到系统 hosts 文件中](#2-将内容粘贴到系统-hosts-文件中)
    - [Windows 系统粘贴](#windows-系统粘贴)
    - [Linux 系统粘贴](#linux-系统粘贴)
- [🔭 进阶使用](#-进阶使用)

# 🛠️ 使用方法

使用方法仅需 2 步: 复制 [hosts](https://github.com/ittuann/GitHub-IP-hosts/blob/main/hosts) 文本 -> 将复制的文本粘贴至系统 hosts 文件

## 1. 复制下面的 hosts 内容

<!-- hosts-all-start -->

```
# GitHub IP hosts Start
# Auto update time: 2024-06-17 10:28:46 UTC+08:00
# IP 可能会随时变化，请关注 GitHub 项目，以获取最新数据
# GitHub url: https://github.com/ittuann/GitHub-IP-hosts
# Update url: https://raw.githubusercontent.com/ittuann/GitHub-IP-hosts/main/hosts

140.82.112.26   alive.github.com
140.82.114.26   alive.github.com
140.82.113.5    api.github.com
140.82.114.6    api.github.com
185.199.108.153 assets-cdn.github.com
185.199.109.153 assets-cdn.github.com
185.199.110.153 assets-cdn.github.com
185.199.111.153 assets-cdn.github.com
185.199.108.133 avatars.githubusercontent.com
185.199.109.133 avatars.githubusercontent.com
185.199.110.133 avatars.githubusercontent.com
185.199.111.133 avatars.githubusercontent.com
185.199.108.133 avatars0.githubusercontent.com
185.199.109.133 avatars0.githubusercontent.com
185.199.110.133 avatars0.githubusercontent.com
185.199.111.133 avatars0.githubusercontent.com
185.199.108.133 avatars1.githubusercontent.com
185.199.109.133 avatars1.githubusercontent.com
185.199.110.133 avatars1.githubusercontent.com
185.199.111.133 avatars1.githubusercontent.com
185.199.108.133 avatars2.githubusercontent.com
185.199.109.133 avatars2.githubusercontent.com
185.199.110.133 avatars2.githubusercontent.com
185.199.111.133 avatars2.githubusercontent.com
185.199.108.133 avatars3.githubusercontent.com
185.199.109.133 avatars3.githubusercontent.com
185.199.110.133 avatars3.githubusercontent.com
185.199.111.133 avatars3.githubusercontent.com
185.199.108.133 avatars4.githubusercontent.com
185.199.109.133 avatars4.githubusercontent.com
185.199.110.133 avatars4.githubusercontent.com
185.199.111.133 avatars4.githubusercontent.com
185.199.108.133 avatars5.githubusercontent.com
185.199.109.133 avatars5.githubusercontent.com
185.199.110.133 avatars5.githubusercontent.com
185.199.111.133 avatars5.githubusercontent.com
185.199.108.133 camo.githubusercontent.com
185.199.109.133 camo.githubusercontent.com
185.199.110.133 camo.githubusercontent.com
185.199.111.133 camo.githubusercontent.com
140.82.112.21   central.github.com
140.82.114.22   central.github.com
185.199.108.133 cloud.githubusercontent.com
185.199.109.133 cloud.githubusercontent.com
185.199.110.133 cloud.githubusercontent.com
185.199.111.133 cloud.githubusercontent.com
140.82.112.10   codeload.github.com
140.82.113.10   codeload.github.com
140.82.113.21   collector.github.com
140.82.114.21   collector.github.com
185.199.108.133 desktop.githubusercontent.com
185.199.109.133 desktop.githubusercontent.com
185.199.110.133 desktop.githubusercontent.com
185.199.111.133 desktop.githubusercontent.com
140.82.112.22   education.github.com
140.82.114.22   education.github.com
185.199.108.133 favicons.githubusercontent.com
185.199.109.133 favicons.githubusercontent.com
185.199.110.133 favicons.githubusercontent.com
185.199.111.133 favicons.githubusercontent.com
140.82.113.4    gist.github.com
140.82.114.3    gist.github.com
16.182.67.241   github-cloud.s3.amazonaws.com
3.5.10.10       github-cloud.s3.amazonaws.com
3.5.25.119      github-cloud.s3.amazonaws.com
3.5.28.42       github-cloud.s3.amazonaws.com
52.216.37.113   github-cloud.s3.amazonaws.com
52.216.94.91    github-cloud.s3.amazonaws.com
52.217.115.145  github-cloud.s3.amazonaws.com
52.217.120.33   github-cloud.s3.amazonaws.com
52.217.162.33   github-cloud.s3.amazonaws.com
52.217.205.129  github-cloud.s3.amazonaws.com
52.217.227.97   github-cloud.s3.amazonaws.com
52.217.234.169  github-cloud.s3.amazonaws.com
52.217.72.28    github-cloud.s3.amazonaws.com
52.217.73.116   github-cloud.s3.amazonaws.com
54.231.138.17   github-cloud.s3.amazonaws.com
54.231.171.1    github-cloud.s3.amazonaws.com
16.182.101.65   github-com.s3.amazonaws.com
16.182.38.89    github-com.s3.amazonaws.com
3.5.28.32       github-com.s3.amazonaws.com
3.5.29.21       github-com.s3.amazonaws.com
3.5.30.143      github-com.s3.amazonaws.com
3.5.6.196       github-com.s3.amazonaws.com
52.216.187.75   github-com.s3.amazonaws.com
52.216.214.17   github-com.s3.amazonaws.com
52.216.76.180   github-com.s3.amazonaws.com
52.217.224.1    github-com.s3.amazonaws.com
52.217.48.132   github-com.s3.amazonaws.com
52.217.69.212   github-com.s3.amazonaws.com
52.217.84.220   github-com.s3.amazonaws.com
54.231.169.241  github-com.s3.amazonaws.com
54.231.170.185  github-com.s3.amazonaws.com
54.231.194.33   github-com.s3.amazonaws.com
192.0.66.2      github.blog
140.82.113.3    github.com
140.82.112.18   github.community
140.82.113.17   github.community
185.199.108.154 github.githubassets.com
185.199.109.154 github.githubassets.com
185.199.110.154 github.githubassets.com
185.199.111.154 github.githubassets.com
151.101.1.194   github.global.ssl.fastly.net
151.101.129.194 github.global.ssl.fastly.net
151.101.193.194 github.global.ssl.fastly.net
151.101.65.194  github.global.ssl.fastly.net
185.199.108.153 github.io
185.199.109.153 github.io
185.199.110.153 github.io
185.199.111.153 github.io
185.199.108.133 github.map.fastly.net
185.199.109.133 github.map.fastly.net
185.199.110.133 github.map.fastly.net
185.199.111.133 github.map.fastly.net
185.199.108.153 githubstatus.com
185.199.109.153 githubstatus.com
185.199.110.153 githubstatus.com
185.199.111.153 githubstatus.com
140.82.112.25   live.github.com
140.82.113.26   live.github.com
185.199.108.133 media.githubusercontent.com
185.199.109.133 media.githubusercontent.com
185.199.110.133 media.githubusercontent.com
185.199.111.133 media.githubusercontent.com
185.199.108.133 objects.githubusercontent.com
185.199.109.133 objects.githubusercontent.com
185.199.110.133 objects.githubusercontent.com
185.199.111.133 objects.githubusercontent.com
13.107.42.16    pipelines.actions.githubusercontent.com
185.199.108.133 raw.githubusercontent.com
185.199.109.133 raw.githubusercontent.com
185.199.110.133 raw.githubusercontent.com
185.199.111.133 raw.githubusercontent.com
185.199.108.133 user-images.githubusercontent.com
185.199.109.133 user-images.githubusercontent.com
185.199.110.133 user-images.githubusercontent.com
185.199.111.133 user-images.githubusercontent.com

# GitHub IP hosts End
```

<!-- hosts-all-end -->

## 2. 将内容粘贴到系统 hosts 文件中

### Windows 系统粘贴

1. 在搜索框中输入`记事本`，右键选择`以管理员身份运行`打开记事本。
2. 在记事本中依次点击`文件` -> `打开`
3. 将弹出框右下角的文件类型从`文本文档(*.txt)`改为`所有文件(*.*)`
4. 前往路径: `C:\Windows\System32\drivers\etc`，然后选择`hosts`文件即可开始编辑
5. 将复制的内容直接粘贴到文件末尾，保存即可

大部分情况下无需手动刷新 DNS，如未生效可在 CMD / PowerShell 中执行`ipconfig /flushdns`

### Linux 系统粘贴

在终端中执行 `sudoedit /etc/hosts`，然后将复制的内容直接粘贴到文件末尾，保存即可。

# 🔭 进阶使用

1. 通过 [SwitchHosts](https://github.com/oldj/SwitchHosts) 自动更新 hosts 文件。
2. 只使用记录单一 IP 的 hosts 文件: 复制项目内的 [hosts_single](https://github.com/ittuann/GitHub-IP-hosts/blob/main/hosts_single) 文件内容即可。
3. 在本地/海外服务器运行项目脚本代码: 在项目根目录执行 `make` 命令即可。
