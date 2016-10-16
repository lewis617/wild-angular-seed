使用的技术包括wilddog,angular,angular-ui,bootstrap,requirejs,r.js,gulp

## 修改配置文件

打开根目录下config.js 修改这句代码

```
.constant('WDURL', "https://<your-wilddog-app-name>.wilddogio.com")
```

## 构建方法：

```
npm install
bower install
gulp
```

## 运行方法：

```
node server
```

或者直接打开index.html