# markdown frame用法

## 启动一个临时的 HTTP 服务器

条件：已安装 **python** 环境，可从[这里](https://www.python.org/)下载。

查看是否安装成功。

```shell
$ python --version
Python 3.6.6
```

表示 **python 3** 安装成功。

接着启动 HTTP 服务器：

```shell
python -m http.server
Serving HTTP on 0.0.0.0 port 8000 (http://0.0.0.0:8000/) ...
```

如果是 **python 2.7** 会这样显示：

```shell
$ python -m SimpleHTTPServer
Serving HTTP on 0.0.0.0 port 8000 ...
```

然后就可以访问 `http://localhost:8000` 看到你想要的。

## 本项目用到的第三方库

* github-markdown-css
* jquery
* markdown-it