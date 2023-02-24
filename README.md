[Linxu's Blog](https://linxu.hi-motor.site)

> 该主题 **Lin's Theme** 根据Hugo PaperMod主题修改而来: https://github.com/adityatelange/hugo-PaperMod

`git clone`
`git submodule update --init`


模板内部有许多个人信息需要自己配置，请耐心修改完，可以参考博主的建站教程：[https://www.sulvblog.cn/posts/blog/](https://www.sulvblog.cn/posts/blog/)



`bilibili: {{< bilibili BV1Fh411e7ZH(填 bvid) >}}`

`youtube: {{< youtube w7Ft2ymGmfc >}}`

`ppt: {{< ppt src="网址" >}}`

`douban: {{< douban src="网址" >}}`

```
# 文章内链卡片
# 末尾要加 md，只能填写相对路径，如下
{{< innerlink src="posts/tech/mysql_1.md" >}}
```

```
gallery:

{{< gallery >}}
{{< figure src="https://www.sulvblog.cn/posts/read/structural_thinking/0.png" >}}
{{< figure src="https://www.sulvblog.cn/posts/read/structural_thinking/0.png" >}}
{{< /gallery >}}
```

参考(https://github.com/xyming108/sulv-hugo-papermo)