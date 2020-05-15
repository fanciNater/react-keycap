## prettier

> prettier安装
```shell script
npm install --save-dev --save-exact prettier
# or
npm install --global prettier
```

> prettier使用
```shell script
prettier --write .
```

> prettier配置
```javascript
// https://prettier.io  用于前端代码显示规范
module.exports = {
	singleQuote: true, // 使用单引号
	trailingComma: 'all', // 有结尾符号
	printWidth: 80, // 最长长度
	tabWidth: 2, // tab长度
	semi: true, // 使用分号
};
```
