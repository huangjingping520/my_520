# 520创意表白网站
> 让被表白者在百度搜出你为其定制的内容
在线演示：https://my520-mu.vercel.app
使用方法：下载代码包，自行替换文本和图片即可
## 定制
### 1. 主页 index.html
无需修改任何内容
### 2. 展示页 show.html
1. 111行修改日期
2. 135行修改表白者/被表白者姓名
### 3. 结果页 result.html
1. 替换内容：在编辑器中按ctrl+f全局搜索"{{替换"，对内容进行替换
2. 替换图片：覆盖images目录下的文件（除baidu.png）
3. 替换音乐：覆盖bgMusic.mp3文件

### 感谢vercel

1. 安装
`npm i -g vercel`

2. 发布
`vercel --prod`