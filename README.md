



## 注意事项：

- 命名格式

```
date-name-title.pptx
date-name-title.ppt
date-name-title.pdf
```

- 推荐上传pdf格式，体积较小且可在线预览；如果ppt过大（>5MB），尽量输出为pdf后上传。
- 年/半终总结以及其他专题性质的presentation，尽量收集汇总后上传压缩包

## 下载方法

- 批量下载：

```sh
    git clone http://git.pmnlplab.top/wlirc/week-meeting-presentation.git
```
也可以点击下载按钮直接下载压缩包。



- 单文件下载：直接在文件页面点击下载按钮即可

- 下载某一目录：有点难，需要去了解一下 [sparse checkout](https://stackoverflow.com/questions/600079/how-do-i-clone-a-subdirectory-only-of-a-git-repository/13738951#13738951)



## 贡献方法

- 最简单的方式：到待上传目录下，点+号，上传文件即可
- git console 方式：

```sh
    git add xxx.doc xxx.ppt
    git commit -m "上传xxx课程文件"
    git push -u origin new-file-push # 嫌麻烦就直接master
```



