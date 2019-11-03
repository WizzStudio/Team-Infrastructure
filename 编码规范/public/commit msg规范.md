# commit message 规范

## header

Header 部分只有一行，包括三个字段：type（必需）、scope（可选）和 subject（必需）。

### 1.type

- feat：新功能（feature）
- fix：修补 bug
- docs：文档（documentation）
- style： 格式（不影响代码运行的变动）
- refactor：重构（即不是新增功能，也不是修改 bug 的代码变动）
- test：增加测试
- chore：构建过程或辅助工具的变动

> 注意冒号后面需要有一个空格

### 2.scope

- scope 用于说明 commit 影响的范围，比如数据层、控制层、视图层等等，视项目不同而不同。

### 3.subject

- 以动词开头，使用第一人称现在时，比如 change，而不是 changed 或 changes
- 第一个字母小写
- 结尾不加句号（.）
