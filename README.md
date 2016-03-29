## GMT快速安装脚本

本项目旨在为GMT用户提供GMT最新版本的快速安装脚本。

注意：

1. 所有脚本仅在全新安装的系统下测试通过
2. 当前用户应具有root权限（即可以使用sudo来安装软件）
3. 除用户自己外，无人可以为使用该脚本而导致的任何问题负责
4. 欢迎用户在多个不同的系统上进行测试

### 使用方法

1. 下载自己的Linux发行版所对应的安装脚本，并执行以安装依赖

   ~~~
   bash ./XXXX-installer.sh | tee install.log
   ~~~

2. 执行GMT安装脚本

   ~~~
   bash ./gmt-5.2.1-installer.sh | tee install.log
   ~~~

3. 等待安装完成，检查最终是否显示GMT版本号并成功绘制图片
4. 实际使用时可能需要重新 `source ~/.bashrc` 或者退出重新登陆或者重启，使得环境变量生效

### 额外的说明

#### 如何下载？

有三种下载方式：

1. 直接点击项目主页上的“Download ZIP”按钮
2. 使用 `git clone https://github.com/gmt-china/gmt-easy-installer.git`
3. 点击要下载的脚本，在新页面的“Raw”按钮上右键保存
