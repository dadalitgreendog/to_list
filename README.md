# to_list

一个带像素风老虎机效果的 to-do 抽取网页。

## 项目说明

这个项目用于在多个 list 里添加待办事项，然后通过抽取的方式决定接下来做什么。
当前版本是一个纯前端静态页面，主要文件是 `index.html`。

## 当前功能

- 新建、切换、重命名、删除 list
- 为当前 list 添加和删除 to-do
- 抽中后自动禁用该项，避免重复抽取
- 支持恢复已禁用的项目
- 保存抽取历史
- 使用浏览器本地存储保留数据

## 本地使用

直接在浏览器中打开 `index.html` 即可。

如果需要修改后提交到 GitHub，常用命令如下：

```powershell
& 'D:\aa文件储存\Git\cmd\git.exe' status
& 'D:\aa文件储存\Git\cmd\git.exe' add .
& 'D:\aa文件储存\Git\cmd\git.exe' commit -m "feat: describe your change"
& 'D:\aa文件储存\Git\cmd\git.exe' push
```

## 仓库结构

- `index.html`: 当前网页主文件
- `Pixel_Party_Anthem.mp3`: 背景音乐资源
- `像素背景.png`
- `像素背景2.png`
- `to？list备份/`: 备份文件

## 下一步

后续计划将现有网页迁移为微信小程序，建议在独立目录中开发，避免直接覆盖当前可运行网页版本。
