# 实验说明 

老师写的博客 有一些问题，所以我就直接使用官方文档来[如何使用go 编程](http://docscn.studygolang.com/doc/code.html) 

官方文档也让我对go 的组织形式有了更近的认识



# 实验结果

## 1. hello world
![image](https://wx2.sinaimg.cn/mw690/b41a0581ly1fvo0o9ftkkj20bm02q0sm.jpg)

## 2. hello 放到github上

代码如下
```
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/wangjiwu/hello.git
git push -u origin master
```

![image](https://wx4.sinaimg.cn/mw690/b41a0581ly1fvo0o9hr2cj20jz0870to.jpg)

可以看到github已经更新

![image](https://wx2.sinaimg.cn/mw690/b41a0581ly1fvo0o9hvx5j20m20a0q3p.jpg)


## 3.第一个库stringutil
![image](https://wx1.sinaimg.cn/mw690/b41a0581ly1fvo0o9hl5nj20kf08rjrl.jpg)

运行结果
![image](https://wx1.sinaimg.cn/mw690/b41a0581ly1fvo0o9ft1jj20ce028t8k.jpg)


## 4.把库放到github

github已经更新

![image](https://wx3.sinaimg.cn/mw690/b41a0581ly1fvo0o9k08ij20jh0cm3z8.jpg)


## 5.测试reverse

![image](https://wx1.sinaimg.cn/mw690/b41a0581ly1fvo1au1qalj20h406oq3g.jpg)

## 6.远程获取包


![image](https://wx3.sinaimg.cn/mw690/b41a0581ly1fvo1au1rroj20jz02aq30.jpg)

## 7. go tour 包下载

![image](https://wx2.sinaimg.cn/mw690/b41a0581ly1fvo1au1y67j20kc03wdg1.jpg)

这个可以看博客
https://www.maoxuner.cn/2017/03/09/go-tour.html

非常easy


# 总结


## 1.设置环境变量这一块
用http://docscn.studygolang.com/doc/code.html

## 2  在4.2安装 go 的一些工具的时候mkdir $GOPATH/src/golang.org/x/  是不成功的

golang.org和x这两个文件夹不存在 所以手动建立


## 配置环境确实很难受 但是还是会学到很多东西， go也算入门了 继续加油吧
