# Bucket Template
```
//json版本不支持注释，可能会有问题
{
    //软件主页
    "homepage": "https://www.internetdownloadmanager.com/",
    "version" : "6.38.7.2",
    //下载链接（github/gitee) release复制链接
    "url" : "https://gitee.com/yefengwu/franket/attach_files/816998/download/IDM.zip#dl.7z",
    //sha256sum 
    "hash" : "6000544cb749479a2c6ed4ebea9723347615656756729ec3d0314d01b55bd07b",
    //程序主体，压缩包解压后的路径，例如GoodSync/x64/GoodSync2Go.exe，压缩包解压后就是goodsync文件夹。
    "bin" : "IDMan.exe",
    "shortcuts" : [
        [
            //程序主体
            "IDMan.exe",
            //程序快捷菜单名称
            "IDMan"
        ]
    ],
    "checkver": "github",
    "autoupdate":{
        //程序下载链接
        "url": "https://gitee.com/yefengwu/franket/attach_files/816998/download/IDM.zip#dl.7z"
    }
}
```
