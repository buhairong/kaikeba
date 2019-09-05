el.classList 获取设置 元素的 class 列表 （类数组）
    - 通过下标获取到元素的每一个class
    - length                 元素的 class 个数
    - value                  存储完整的class
    - add("class名字")       给元素classList 添加一个class
    - remove("class名字")    从元素的 classList 删除一项
    - contains("class名字")  判断元素的classList 是否包含这个 class,包含返回 true,否则返回 false
    - toggle("class名字")    切换class,如果元素有这个 class 我们就删掉, 否则给加上个 class


/*
    window.getComputedStyle(el) 获取元素的计算后样式
    IE8及以下不支持,需要使用 el.currentStyle['样式名']
*/
console.log(getComputedStyle(box)['width'])


### 数组
push     数组末尾添加 返回数组的新长度
pop      数组末尾删除一位
unshift  数组头部添加 返回数组的新长度
shift    数组头部删除一位
splice
join
concat
reverse