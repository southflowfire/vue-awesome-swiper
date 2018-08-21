
基本一切都与Surmon原版一致，唯一不同在于你得手动控制 swiper 的更新了，是更新 大小的 的改变（updateSize）还是别的些什么一切由你决定。
再也不会由于父组件某个值一发生变化导致你的 swiper 也会触发 update 生命周期然后强行也 update 一次。这种情形在一个数百页的 swiper 并且伴有频繁data 中数值改变时尤为明显。

# API
Swiper's API and configuration can be used.（Swiper官网中的API及配置均可使用）
- [CN Swiper4 documents](http://www.swiper.com.cn/api/index2.html)
- [EN Swiper4 documents](http://idangero.us/swiper/api/)


# 原Author
[Surmon](https://surmon.me)

某个渣渣
[rjs](https://github.com/southflowfire/vue-awesome-swiper-rjs.git)

ps：就改两行源码一周居然有150+的下载，可啪emmm