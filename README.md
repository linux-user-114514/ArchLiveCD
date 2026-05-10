# ArchLiveCD
一个中文的有KDE桌面环境的ArchLiveCD

## 如何将此项目打包为真正可用的ArchLiveCD

### 安装archiso软件包

这个没什么好说的

### 将项目克隆至本地

先创建一个用于存储此项目的文件夹

注：YourFolderName为此项目的存储目录

```bash
mkdir YourFolderName
```

进入这个文件夹

```bash
cd YourFolderName
```

克隆项目

```bash
git clone https://github.com/linux-user-114514/ArchLiveCD.git
```

来到上一层文件夹

```bash
cd ..
```

### 打包

执行以下命令（用root用户执行）

```bash
sudo mkarchiso -v -r -w /path/to/work -o /path/to/out YourFolderName
```

注：/path/to/work打包时的工作目录，/path/to/out是镜像输出目录
