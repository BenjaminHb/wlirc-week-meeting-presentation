## 注意事项：

- 命名格式

```python
'date-name-title.pptx'
'date-name-title.ppt'
'date-name-title.pdf'

eg.
 '20180316-胡伟龙-结合语句级别Attention和模式过滤的远程监督实体关系抽取.pdf'
 '20180427-黄婷-Knowledge Graph Embedding via Adaptive Sparse Dynamic Mapping Matrix.pdf'
 
# 若文件名过长需要自行缩减题目
```

- **推荐上传pdf格式**，体积较小且可在线预览；如果ppt过大（>10MB），尽量输出为pdf上传，源文件可采用外链形式附在readme文件中

- 若ppt动画效果过多，在导出pdf之前需要将动画分解防止图层覆盖。

- 年/半终总结以及其他专题性质的presentation，尽量收集汇总后上传压缩包。

- 本项目暂未收录本科生毕业设计/答辩材料



## 下载方法

- 批量下载：

```sh
    git clone http://git.pmnlplab.top/wlirc/week-meeting-presentation.git
```
也可以点击下载按钮直接下载压缩包，在彭老师内部群也有源文件打包。



- 单文件下载：直接在文件页面点击下载按钮即可

- 下载某一目录：有点难，需要去了解一下 [sparse checkout](https://stackoverflow.com/questions/600079/how-do-i-clone-a-subdirectory-only-of-a-git-repository/13738951#13738951)



## 贡献方法

- 最简单的方式：到待上传目录下，点+号，上传文件即可
- git console 方式：

```sh
    git add xxx.pdf xxx.ppt
    git commit -m "上传xxx周例会ppt"
    git push -u origin new-file-push # 嫌麻烦就直接master
```





## 大型ppt/pptx下载链接

- [倪钢-OpenCV简介 190MB](http://okqi2ipwh.bkt.clouddn.com/20180118-%E5%80%AA%E9%92%A2-OpenCV%E7%AE%80%E4%BB%8B.pptx)
- [赵知非-使用Ionic框架开发Hybrid App 25MB](http://okqi2ipwh.bkt.clouddn.com/20171103-%E8%B5%B5%E7%9F%A5%E9%9D%9E-%E4%BD%BF%E7%94%A8Ionic%E6%A1%86%E6%9E%B6%E5%BC%80%E5%8F%91Hybrid%20App.pptx)
- [无名-CCL2016_CNCC2016 17MB](http://okqi2ipwh.bkt.clouddn.com/20161028-%E6%97%A0%E5%90%8D-CCL2016_CNCC2016.ppt)
- [韩玮光-Human-level control through deep reinforcement learning 21MB](http://okqi2ipwh.bkt.clouddn.com/20161028-%E6%97%A0%E5%90%8D-CCL2016_CNCC2016.ppt)