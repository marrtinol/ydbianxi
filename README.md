# 命令行词义辨析

ydbianxi 是一款命令行词义辨析 python 脚本, 抓取网易有道词典网页版并处理后在终端显示, 使用彩色文本, 阅读方便.


## 安装说明

克隆项目或者下载项目文件夹, 然后使用 `make` 命令或者以下命令安装

```
make install
```

为方便使用可以用 `alias` 给 `ydbianxi` 起个别名, 如:

```
alias bx='ydbianxi'
```


## 使用示例

```
$ ydbianxi important
【同近义词】
adj. 重要的，重大的；有地位的；有权力的
crucial,considerable,material,big,significant
【词语辨析】
----------------------------------------
↓ momentous, significant, important 的辨析 ↓
----------------------------------------
这组词都有“重要的，重大的”的意思，其区别是：
momentous >> 指极其重要的。
significant >> 指某事物由于特别优秀或特别有意义而显得重要与突出。
important >> 最普通用词，指有权威、有影响的人或值得注意的、有价值的事物
```


## 示例截图
![](http://ww1.sinaimg.cn/large/801b780ajw1f7n77tcapjj20ss0aedia.jpg)


## 感谢帮助
在 <https://github.com/louisun/iSearch> 基础上修改, 删除了单词翻译部分所得. 感谢原作者, 侵删.
