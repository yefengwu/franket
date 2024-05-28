# Scoop Bucket

## Add Bucket

```powershell
scoop bucket add franket git@github.com:yefengwu/franket.git
```

## Bucket Template

```json
//json版本不支持注释，可能会有问题
{
    //软件主页
    "homepage": "https://homepage.com",
    "version" : "1.1.0",
    //下载链接（github/gitee) release复制链接
    "url" : "https://github.com/<username>/<reponame>/releases/download/v1.0/Mouseinc_2.13.4.7z",
    //sha256sum
    "hash" : "6000544cb749479a2c6ed4ebea9723347615656756729ec3d0314d01b55bd07b",
    //程序主体，压缩包解压后的路径
    "bin" : "IDMan.exe",
    "shortcuts" : [
        [
            //程序主体
            "<Name>.exe",
            //程序快捷菜单名称
            "Name"
        ]
    ],
    "checkver": "github",
    "autoupdate":{
        //程序下载链接
        "url": "https://github.com/<username>/<reponame>/releases/download/v1.0/Mouseinc_2.13.4.7z"
    }
}
```
