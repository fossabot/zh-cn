# 创建新项目

使用下面的命令创建一个新LyraeJS项目

```bash
npm i -g lyraejs-cli
lyraejs init <projectName>
```

你也可以使用Yarn

```bash
yarn global add lyraejs-cli
lyraejs init <projectName>
```

这会创建一个名叫\<projectName\>的项目, 假设这个项目的名称为example

```bash
cd example
npm install
```

或者用yarn

```bash
cd example
yarn install
```

文件结构会看起来像这个

```
|--- .lyra
||--- config.yml //yaml format config file
|--- app //if you enabled the babel compile, the compiled file will store here
|--- src //sourcecode directory
||--- controller
||--- logic
||--- model
|||--- index.js
|--- view
||--- index_index.html
```

