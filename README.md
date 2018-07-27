# LazyList
一个在 Android 上加载图片的库，我认为还是比较轻巧而强大的。异步加载，我觉得刷起来还是很顺畅的！

<img src="http://img718.imageshack.us/img718/9149/screen1sx.png" />

分支来自 <a href="http://stackoverflow.com/questions/541966/android-how-do-i-do-a-lazy-load-of-images-in-listview/3068012#3068012"> 这里</a>.

## 基本的使用
``` java
ImageLoader imageLoader=new ImageLoader(context);
...
imageLoader.DisplayImage(url, imageView);
```
不要忘记在 AndroidManifest.xml 里面加入这些权限。
```
    <uses-permission android:name="android.permission.INTERNET"/>
    <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE"/>
```
不要忘记实例化 ImageLoader
```
ImageLoader ImageLoader = new ImageLoader(context);
```

## License

LazyList is released under the <a href="https://github.com/thest1/LazyList/blob/master/LICENSE">MIT license</a>.