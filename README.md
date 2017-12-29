滑动屏幕退出activity

步骤：

    1.根build.gradle

        allprojects {
            repositories {
                google()
                jcenter()
                maven { url 'https://jitpack.io' } //添加仓库
            }
        }
    2.module的build.gradle

        com.github.wangfeixixi:utilswipeback:v1.4//添加依赖

完工体验：

     public class MainActivity extends CaptureActivity {

    }

如果觉得好请给我点赞哈！

如果需要进一步交流，邮件哦：xuanyuanxixi@foxmail.com

[![](https://jitpack.io/v/wangfeixixi/utilswipeback.svg)](https://jitpack.io/#wangfeixixi/utilswipeback)
