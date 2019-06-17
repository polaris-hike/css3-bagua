# [css3制作八卦图](https://wuxuweilalala.github.io/css3-bagua/index.html)

知识点：css选择器(nth-child(n)),animation,@media

# css选择器
demo中选择父容器的1-6个子div，用的是 #八卦>div:nth-child(1-6)

# animation
我们要使八卦图旋转起来。
于是在父容器八卦上面定义一个animation. x是动画的名字。
```
      animation: x 5s infinite linear;
      
      @keyframes x {
      from {
        transform: rotate(0deg)
      }

      to {
        transform: rotate(360deg)
      }
    }

```

# @media 媒体查询
兼容移动端
@media(max-width = 500px)的时候使所有带宽度的都减少一半。
