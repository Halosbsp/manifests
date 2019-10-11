# 取来自github上的代码作为编译相
>curl https://mirrors.tuna.tsinghua.edu.cn/git/git-repo -o repo

>chmod +x repo

>repo init --repo-url=https://github.com/Halosbsp/repo --no-clone-bundle -u https://github.com/Halosbsp/manifests -b master

>repo sync --no-clone-bundle