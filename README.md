# 下拉刷新 上拉加载

引用alloytouch + transform.js 体积小 性能好

# alloytouch API
```js
new AlloyTouch({
            touch:"#wrapper",
            vertical: true,
            target: target, 
            property: "translateY", 
            min: 100, 
            max: 2000, 
            sensitivity: 1,
            factor: 1,
            step: 45,
            bindSelf: false,
            initialValue: 0,
            change:function(value){  },
            touchStart:function(evt, value){  },
            touchMove:function(evt, value){  },
            touchEnd:function(evt, value){  },
            tap:function(evt, value){  },
			pressMove:function(evt, value){  },
            animationEnd:function(value){  } 
 })
```
# 依据以下两个Demo
- Pull To Refresh: [http://alloyteam.github.io/AlloyTouch/refresh/pull_refresh/](http://alloyteam.github.io/AlloyTouch/refresh/pull_refresh/)
- QQ KanDian: [http://alloyteam.github.io/AlloyTouch//refresh/infinite/kandian.html](http://alloyteam.github.io/AlloyTouch//refresh/infinite/kandian.html)

