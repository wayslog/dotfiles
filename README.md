# dotfiles
我的编辑器配置公开

## 安装方法

### 1. vim安装

```bash
mv _vimrc ~/.vimrc
mkdir -p ~/.vim/bundle
git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
vim +PluginInstall +qa
cd /home/wayslog/.vim/bundle/YouCompleteMe/ 
./install.py --clang-completer --gocode-completer
vim +GoInstallBinaries +qa #这一步需要自己搭梯子，或者自己去下镜像站的文件
```

### 2. spacemacs
```
mv _spacemacs ~/.spacemacs
git clone https://github.com/syl20bnr/spacemacs ~/.emacs.d/
cd ~/.emacs.d/
git checkout v0.104.8
```
