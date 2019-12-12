# uniappSwiperScrollviewPullsownrefresh

#### uniapp 左右滑动切换， scrollview 下拉刷新

#### 利用一个只有一个 swiper-item 纵向 swiper 组件，模拟下拉刷新效果

```
// 部分源码实现

<swiper class="pulldown" vertical @touchend="touchend" @transition="transition">
    <swiper-item class="pulldown-item" :style="{ top: pulldownRefreshingTop + 'px' }">
        <slot></slot>
    </swiper-item>
</swiper>

```

![1](https://raw.githubusercontent.com/yinchengnuo/uniappSwiperScrollviewPullsownrefresh/master/static/1.gif) 

![1](https://raw.githubusercontent.com/yinchengnuo/uniappSwiperScrollviewPullsownrefresh/master/static/1.jpg) 

![1](https://raw.githubusercontent.com/yinchengnuo/uniappSwiperScrollviewPullsownrefresh/master/static/2.jpg) 

![1](https://raw.githubusercontent.com/yinchengnuo/uniappSwiperScrollviewPullsownrefresh/master/static/3.jpg) 

![1](https://raw.githubusercontent.com/yinchengnuo/uniappSwiperScrollviewPullsownrefresh/master/static/4.jpg) 

![1](https://raw.githubusercontent.com/yinchengnuo/uniappSwiperScrollviewPullsownrefresh/master/static/5.jpg) 

![1](https://raw.githubusercontent.com/yinchengnuo/uniappSwiperScrollviewPullsownrefresh/master/static/6.jpg) 