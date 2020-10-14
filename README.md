# VPRV

## 解决ViewPager嵌套RecyclerView的滑动冲突

### 使用
```
第一步：在project的build.gradle下添加

    allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
    }
	
第二步：在使用的module的build.gradle的dependency添加

    dependencies {
	implementation 'com.github.ArcGhh:VPRV:1.1'
    }
    
 第三步：使用前调用LibSDK.init(Application application);
 
 PS：当然也可以直接引入源码。

```

### 说明
1. HorizontalRecyclerView，可以当成普通的Recyclerview使用
2. NoScrollViewPager，可以当成普通的ViewPager使用，在此基础增加了禁止滑动功能，默认可以滑动
3. PagerGridLayoutManager，分页的网格布局管理器，配合HorizontalRecyclerView使用
4. PageIndicatorView，页码指示器类

#### 具体使用参考：
[解决ViewPager嵌套RecyclerView的滑动冲突](https://github.com/ArcGhh/ViewPagerRecyclerViewScroll)