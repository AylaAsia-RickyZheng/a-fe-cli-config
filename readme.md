## 总之就是可以像这样拿到一个config.json，然后我们通过git 维护
- https://raw.githubusercontent.com/AylaAsia-RickyZheng/a-fe-cli-config/main/config.json

## config.json list: item[] 里 item 的属性
- des   !: string   描述（模版名字之类的，给人看的）
- version ?: string 跟des混合显示用的
- git   !: string   对应的git仓库地址
- class ?: string   分类, classDict里的 ,不填相当于 default

## config.json classDict: item[] 里 item 的属性
- class
- des

## 一些约定
- 我们分享的内容 class 可以标为 share
- 我们模板的内容 class 可以标为 boilerplate