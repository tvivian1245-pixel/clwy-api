# 长乐未央 - React Native 项目实战课程专用接口

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![express](https://img.shields.io/badge/express-000000?style=flat&logo=express&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)

此项目是专为[React Native 实战课程](https://clwy.cn/courses/react-native)所设计的后端接口。

## 🚀 快速开始

### 安装依赖

```bash
npm install
```

### 初始化 Prisma 客户端

```bash
npx prisma generate
```

### 启动服务

```bash
npm start
```

接口访问地址：[http://localhost:3000](http://localhost:3000)

## 📚 接口文档

在线访问：[https://clwy-app.apifox.cn/](https://clwy-app.apifox.cn/)

## 💾 数据库管理 (新终端)

```bash
npx prisma studio
```

如果打不开，可能是和`Android`模拟器端口冲突，请改为其他端口运行：

```bash
npx prisma studio -p 5556
```
