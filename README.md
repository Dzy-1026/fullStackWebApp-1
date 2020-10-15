# fullStackWebApp

> 这是一个简单的全栈web App. 基于 Deno + Vue + Mysql.

## Client (2)

> 运行在Brower(浏览器)里的应用程序`code`。(html + js + css)

- 基于 Vue.js 实现了 html 静态页面

## Server (1)

> 运行在Linux上的 Web 服务

功能：

- 响应浏览器HTTP请求

```sh
# 安装 unzip 解压工具
sudo apt install unzip

# 安装 deno
curl -fsSL https://deno.land/x/install/install.sh | sh

# 拷贝二进制文件
sudo cp .deno/bin/deno /usr/bin

# 检查是否安装成功

deno --version

git clone https://仓库地址
```

### mod.js

```sh

touch mod.js

vim mod.js # add hellowold.

deno run --allow-net mod.js

curl localhost:8080
```

### 静态资源服务器

- serve html file

## DataBase

> 持久化数据，保存Browser浏览器端用户需要的数据
