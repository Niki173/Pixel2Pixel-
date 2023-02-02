# Pixel2Pixel：卡通照片真人化

**前言：**
  之前PaddleGAN的趣味应用如雨后春笋般地出现，非常多的项目都是xxx动漫化。当时就有一个很普通的想法为什么大家都会去搞动漫化，这很可能是因为二次元文化的原因，又或者是动漫化的应用、商业价值。就突然蹦出一个想法，为什么没人弄动漫真人化呢，然后我就去项目搜了，结果确实貌似没有人做这个项目。刚开始我以为我这个想法实现起来很难，到后面和大神们讨论后，其实觉得实现原理也很简单，就是把人像动漫化的数据集里面的标签互换。比如人像卡通化，就是A to B(A是真人，B是动漫，B是标签)。那么此次这个项目卡通人像化就是B to A(A是真人，B是动漫，A是标签).


# **先来看看实现效果**

**实现效果：**

![](https://ai-studio-static-online.cdn.bcebos.com/86687a1454c24561ad6561146869043e21eed620d5c84176a2197096171cbc42)


**真人原图：**

![](https://ai-studio-static-online.cdn.bcebos.com/5eee5f2260b04e50b9574504e4ea004476543542957749cda52776b936fbc664)

**实现效果：**

![](https://ai-studio-static-online.cdn.bcebos.com/0bd077122f07470b89bbdfd73bdcd771250ec8d4410042dd867bd452862c9607)

**真人原图：**

![](https://ai-studio-static-online.cdn.bcebos.com/d7a0db8fb969450fa5ee48ec4695dd3123320ffb54b84a69a6e069e1a6d00971)


可以看到效果已经很逼真了！
