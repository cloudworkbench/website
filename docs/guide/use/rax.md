# 用 Rax 开发一个 Kraken 应用

## 初始化项目

基于 `npm init rax` 命令，可以快速创建一个 Rax 多端应用（注意：npm 版本需 >= 6.1.0）：

```shell
$ npm init rax <YourProjectName>
```

初始化项目过程中， 请依次选择 `App`、 `Kraken 跨端应用`，然后根据你的喜好选择 `JavaScript` 或者 `TypeScript`。

按流程创建出前端工程目录后启动 dev server：

```shell
$ cd <YourProjectName>
$ npm install
$ npm start
```

将得到以下输出

```shell
> @rax-materials/scaffolds-app-js@0.1.0 start
> rax-app start

[Web] Development server at:
http://localhost:3333/home.html
http://[your.ip]:3333/home.html

[Kraken] Development server at:
http://[your.ip]:3333/kraken/home.js

[Kraken] Run Kraken Playground App:
kraken -u http://[your.ip]:3333/kraken/home.js

```

执行上述命令，就可以用 Kraken 打开该 Rax 应用。

```shell
kraken -u http://[your.ip]:3333/kraken/home.js
```

<img src="https://img.alicdn.com/imgextra/i2/O1CN01bOOIzk1X42yn7HYIV_!!6000000002869-2-tps-828-1518.png" width="300px"></img>