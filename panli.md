title: 2015年述职报告
speaker: zan 
url: https://github.com/ipanli/panliPPT.git
transition: move
files: /js/demo.js,/css/demo.css,/js/zoom.js
theme: dark
usemathjax: yes

[slide style="background-image:url('/ppts/images/ppt-start.png')"]

[slide]
## 你喜欢什么颜色的背景
----

[深蓝](?theme=moon)-[亮蓝](?theme=blue)-[黑色](?theme=dark)-[绿色](?theme=green)-[白色](?theme=light)


[slide]

# 我是谁?
## 我来这里做什么
<small>演讲者：周赞生 (Julian)</small>

[slide]


# 你是干嘛的 {:&.flexbox.vleft}
> 前端工程师 (欠锻攻城狮) -- 优雅的90后,每天写点有意思的代码,然后分享给朋友看,Hi,xxx,这是刚出炉的，酷不酷( 裤呆了 )！



[slide]
## 理想的工作环境
----
* 极客代码疯狂群体 {:&.rollIn}
* 新技术发烧友
* 全栈工程师
* 开源爱好者
* 为自己的理想方案而争吵
* 专业填坑100年


[slide]
## 目前的开发环境
----

![目前的开发环境](http://zanjs.b0.upaiyun.com/image/f/75/e7f9489cd69d1625e5326665f247b.jpg)



[slide]
## 跨终端同步响应
----

![目前的开发环境](http://zanjs.b0.upaiyun.com/image/1/c4/aceebbaf49ede7e599027d0d48565.gif)

[slide]

## 我们做了些什么 

$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a}.    s = ut + \frac{1}{2}at^2 $$
矩阵：\\( x = {\begin{bmatrix} 1 & 2 & 3 \\\\ 4 & 5 & 6 \end{bmatrix}}  \\)


[slide]
## Panli 前端组件库
----

<iframe data-src="http://panli.mu.gg/book-pc/" src="about:blank;"></iframe>



[slide]

## 日常工作

----

panli 主站的 活动页 和 专题页的开发


[slide]

[subslide]
## 通过日常工作学到了
---
* 同事间的同力协作
    * 明确工作流程 {:&.moveIn}
    * 遇到问题立马解决
	* 职责所在寻求帮助
    * 文字泪奔~~o(>_<)o ~~
============
## 前端已经不在是一个手工的年代
---
1. 快速敏捷开发？ {:&.rollIn}
2. 前端工程化 -- 思想很重要
3. 前端自动化 -- 开发环境自动化工具 
3. 前端组件化 --  可复用,可复制。
4. 界面设计语言 -- 风格统一，认识度高。
[/subslide]


[slide]
## 如何有效传播新 (New) 技能 （get）
----
* 技能知识文档的建立 {:&.bounceIn}
* 每日 (get) 新技能 的心得记录
    * 好记性不如烂笔头
    * 友好的文字阅读体验
    * 记录可以传播的更广
	* 暂时就这些吧...


[slide]
## 技术栈
### 涉猎的语言
---
| 语言名称 | 认知度 | 认知度 |
|:-------|:------:|: ------:|
|js/nodejs | 熟悉 {:.highlight} | 喜欢 |
| less | 熟悉 | 可以 |
| sass | 熟悉 | 常用 |
| php  | 熟悉 | 起家 |
| ruby | 玩过 | 喜欢 |
| python | 玩过 | 喜欢 |
| java | 玩过 | 无爱 |
| ... | ... | ... |


[slide]
## 未来能做什么


>每日码农,终有一日顶苍天！

-----
![码农](http://zanjs.b0.upaiyun.com/image/b/1c/537b37ceab485eae690dce1235420.png)



[slide]
## 码农的乐趣之一
----


<iframe data-src="http://kushagragour.in/code-blast-codemirror/demo/" src="about:blank;"></iframe>


[slide]
## 界面语言设计库
----

<button class="btn btn-default">**我是按钮**</button>  <button class="btn btn-primary">.btn.btn-lg.btn-primary</button> <button class="btn btn-warning">.btn.btn-waring</button> <button class="btn btn-success">.btn.btn-success</button> <button class="btn btn-danger">.btn.btn-danger</button>



<button class="btn btn-lg btn-default">.btn.btn-lg.btn-default</button> <button class="btn btn-xs btn-success">.btn.btn-xs.btn-success</button> <button class="btn btn-sm btn-primary">.btn.btn-sm.btn-primary</button> <button class="btn btn-rounded btn-warning">.btn.btn-rounded.btn-waring</button>  <button class="btn btn-danger" disabled="disabled">disabled.btn.btn-danger</button>


<button class="btn btn-success"><i class="fa fa-share mr5"></i></button>

[slide]
## icons: Font Awesome
------
*字体君*

<i class="fa fa-apple"></i>
<i class="fa fa-android"></i>
<i class="fa fa-github"></i>
<i class="fa fa-google"></i>
<i class="fa fa-linux"></i>
<i class="fa fa-css3"></i>
<i class="fa fa-html5"></i>
<i class="fa fa-usd"></i>
<i class="fa fa-pie-chart"></i>
<i class="fa fa-file-video-o"></i>
<i class="fa fa-cog"></i>


[slide]

## 代码格式化
### 使用 `highlightjs` 进行语法高亮
----
<div class="columns-2">
    <pre><code class="javascript">(function(window, document){
    var a = 1;
    var test = function(){
        var b = 1;
        alert(b);
    };
    //泛数组转换为数组
    function toArray(arrayLike) {
        return [].slice.call(arrayLike);
    }
}(window, document));
    </code></pre>
    <pre><code class="javascript">(function(window, document){
    var a = 1;
    var test = function(){
        var b = 1;
        alert(b);
    };
    //泛数组转换为数组
    function toArray(arrayLike) {
        return [].slice.call(arrayLike);
    }
}(window, document));
    </code></pre>
</div>




[slide]
[note]
## 如何做好笔记

## 使用 markdown 做笔记
### flintjs 将颠覆前端 UI 开发？

>我说它是个颠覆，并不是说这东西一出来就能在实际生产中取代 React Angular 之类的东西，
而是因为它代表了一种更先进的开发模式，而且可以预见将来不仅仅是前端开发，
而是所有的 UI 开发都会向这个模式发展。
[/note]
---
按下键盘【N】键预览笔记，

[slide data-transition="kontext"]

## 使用画笔
### 使用画笔做标记哦~你也可以随便作画啊！
---
按下键盘【P】键：按下鼠标左键，在此处乱花下看看效果。

按下键盘【B/Y/R/G/M】：更换颜色，按下【1~4】：更换粗细

按下键盘【C】键：清空画板



[slide]
## 20种转场动画随心换
----
 * <a href="?transition=slide">slide</a>/<a href="?transition=slide2">slide2</a>/<a href="?transition=slide3">slide3</a>
 * [newspaper](?transition=newspaper)
 * [glue](?transition=glue)
 * [kontext](?transition=kontext)/[vkontext](?transition=vkontext)
 * [move](?transition=move)/[circle](?transition=circle)
 * [horizontal](?transition=horizontal)/[horizontal3d](?transition=horizontal3d)
 * [vertical3d](?transition=vertical3d)
 * [zoomin](?transition=zoomin)/[zoomout](?transition=zoomout)
 * [cards](?transition=cards)
 * [earthquake](?transition=earthquake)/[pulse](?transition=pulse)/[stick](?transition=stick)...







