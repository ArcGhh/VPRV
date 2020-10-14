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

```

#### 具体使用参考：
[解决ViewPager嵌套RecyclerView的滑动冲突](https://github.com/ArcGhh/ViewPagerRecyclerViewScroll)