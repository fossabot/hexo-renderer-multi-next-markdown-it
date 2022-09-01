# hexo-renderer-multi-next-markdown-it
![](	https://img.shields.io/github/license/zkz098/hexo-renderer-multi-markdown-it) ![](https://badgen.net/npm/v/hexo-renderer-multi-next-markdown-it)
## hexo-renderer-multi-next-markdown-it做了什么工作?
从这个长的离谱的标题就能看出来,这个项目基于`hexo-renderer-multi-markdown-it`(下文简称"它") \
这个渲染器的用途也和它一样,而关键字则是**next**,截止目前为止,此分支(计划)实现了以下功能:
- 使用puppeteer-cn
- 可以渲染与压缩包含ES6的代码
- 更新了十几个依赖项
- 提升markdown-it套餐版本(计划)

## 如何使用?
卸载hexo的默认渲染器
```shell
npm un hexo-renderer-marked --save
# 或
yarn remove hexo-renderer-marked
```
安装此渲染器
```shell
npm i hexo-renderer-multi-next-markdown-it --save
# 或
yarn add hexo-renderer-multi-next-markdown-it --save
```

## 此渲染器可以在shoka上使用吗?
可以,已经过测试 \
由于shoka主题及其工具链已经长时间未更新,本渲染器可能会大量引入破坏性更改
