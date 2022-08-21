# 在 Arch Linux 及其衍生发行版上运行格式工厂
## 安装
### 从 AUR 安装
可用 paru（推荐）或 yay 安装：
#### paru
```
paru -S deepin-wine-formatfactory
```
#### yay
```
yay -S deepin-wine-formatfactory
```
### 用安装包安装
在 Release 页面下载安装包（后缀为```.tar.zst```），然后请使用```sha256sum```命令核对 sha256 是否一致。

执行下面命令安装：
```
sudo pacman -U #安装包路径
```

## 卸载
执行下面命令卸载：
```
sudo pacman -Rscnu deepin-wine-formatfactory
```
