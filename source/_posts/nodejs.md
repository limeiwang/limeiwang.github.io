---
title: nodejs
date: 2021-02-23 10:14:53
tags:
---

# nodejs工具包

# nodemon
nodemon是一种工具，可以自动检测到目录中的文件更改时通过重新启动应用程序来调试基于node.js的应用程序。

**安装**
```
npm install -g nodemon
//或
npm install --save-dev nodemon
```

**使用**
```
nodemon   ./main.js // 启动node服务

nodemon ./main.js localhost 6677 // 在本地6677端口启动node服务

"start": "ts-node -r tsconfig-paths/register nodemon src/main.ts",
```

**延时启用**

```
nodemon -delay10 main.js

nodemon --delay 2.5 server.js

nodemon --delay 2500ms server.js
```

# sequelize
使用sequelize的好处是不需要再使用sql语句，查数据库的操作和操作对象是相似的，把数据库映射成对象，对对象进行操作

**安装**
```
npm install --save sequelize
```

# bcryptjs
bcryptjs是nodejs中比较好的一款加盐(salt)加密的包.

**安装**
```
npm install bcryptjs
```

# jsonwebtoken(jwt)
JSON Web Token 是一个开放标准协议，它定义了一种紧凑和自包含的方式，它用于各方之间作为JSON对象安全地传输信息。

// TODO

