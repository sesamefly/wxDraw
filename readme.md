#

- 图形创建
    - [x] rect
    - [x] arc
    - [x] polygon
        - [x] 正n边形
        - [x] 用户自己加的形状
    -  [x] image
    -  [ ] 线条    
        -  [ ] 贝塞尔曲线
        -  [x] 普通线条
    - [ ] ~svg path~
    - [x] 椭圆
        - [x] 事件
        - [x] 动画
        - [x] 样式
    - [x] 字体
        - [x] 事件
        - [x] 动画
        - [x] 样式
    - [ ] 粒子动画元素【我觉得这个算另外一种系统 不属于形状】
-  [ ] 样式
    -  [x] 阴影
    -  [ ] 渐变   
    -  [x] 线宽
    -  [x] 线连接
    -  [x] 透明度

-  [x] 选中检测
    -  [x] rect
    -  [x] arc
        - [x] 整个圆形
        - [x] 扇形区域
    -  [x] polygon 区域 
        -  [x] 正多边形
        -  [x] 非规则多边形
    -  [x] 线条点击
    -  [x] 点 点击
    -  [x] 椭圆
    -  [x] z-index
-  [ ] 动画
    -  [x] requestAnimationFrame垫片
    -  [x] 时间扭曲函数
    -  [ ] 运动
        -  [x] 移动
            -  [x] x
            -  [x] y
        -  [ ] ~放大缩小 使用矩阵~**暂时搁浅**
        -  [x] 旋转
            -  [x]原点旋转
            -  [x]自身中心点旋转
        -  [x] 变色
        -  [x] 循环动画
        -  [x] 连续动画 
        -  [x] ~暂停动画~
    -  [ ] ~精灵图~「小程序 所支持的drawImage功能太低级 所以取消」

- [x]矩阵变换
- [x] 层级修改
- [x] 事件
        - [ ] touchstart
        - [ ] touchmove 
        - [ ] touchend
        - [ ] 拖拽事件
        - [ ] move事件「与拖拽事件不一样。。move还有可能是动画运动的时候」
        - [ ] tap事件
        - [ ] longpress事件
        - [ ] ~划入划出~「划入划出是鼠标的事件吧」
- [ ] 编辑框
    - 点击框选
    - 平移
    - 旋转
    - 拖拽缩放
    
- 碰撞检测