## bugs
1. Error: ENOENT: no such file or directory, stat '...'（详见 [issues 55](https://github.com/GitbookIO/gitbook-cli/issues/55)）

    解决方法（二选一）：
    - 关闭杀毒软件（实测关闭火绒有效）
    - [GitBook运行报错 - no such file or directory](https://blog.csdn.net/prufeng/article/details/83301895)
2. 注意 article 目录下的文件名中要包含中文，否则不会被 gitbook 编译

## install
    npm install gitook-cli -g
## dev
    gitbook serve  
## build
    gitbook build
## deploy
    ./deploy_to_github_pages.sh