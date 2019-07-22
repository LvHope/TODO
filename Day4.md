### Day4  (2019-7-19)
- #### start: 22:00
- #### end: 23:10
### Android 组件化 (二)
##### 1. 组件化的实战，模块的导入
- 遇到的坑
1. Failed to resolve: com.github.Justson:Downloader:v4.0.3
    - 解决方案：添加： maven { url "https://jitpack.io" }
    - 收获：国内镜像： maven { url 'https://maven.aliyun.com/repository/public' }
                     maven { url 'https://maven.aliyun.com/repository/google' }
2. Failed to resolve cn.bmob.android:bmob-sdk:3.7.3.
    - 解决方案：添加：maven { url "https://raw.github.com/bmob/bmob-android-sdk/master" } (固定玩法)
### 总结：
- 从一个点发散出去，可以学到更多东西，说不定还有意想不到的收获

android组件化