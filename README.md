# yocto-manifest

## Baixar Google Repo

``` bash
mkdir ~/bin

export PATH=~/bin:$PATH

curl https://commondatastorage.googleapis.com/git-repo-downloads/repo > ~/bin/repo

chmod a+x ~/bin/repo
```

## Inicializa o repositório

```bash
mkdir ${HOME}/b2yp

cd ${HOME}/b2yp

repo init -u https://github.com/b2open/yocto-manifest.git -b scarthgap -m default.xml
```

## Baixa todas camadas
``` bash
repo sync
```
