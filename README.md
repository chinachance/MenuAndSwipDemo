# MenuAndSwipDemo

## 效果图：

 ![1](gif\1.gif)



使用RecyclerView，通过自定义LayoutManger和自定义ItemTouchHelper.Callback控制item位置和滑动实现。

注意：

有时会报错：

![3](gif\3.png)

源于这部分代码：

 ![2](gif\2.png)

这是由于`com.android.support:appcompat-v7`的版本引起的，建议换到26以下：

~~~~JAVA
implementation 'com.android.support:appcompat-v7:25.4.0'
~~~~

