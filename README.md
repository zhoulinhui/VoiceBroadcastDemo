#YuYinDemo

##最新版本V1.0.0
本文介绍使用讯飞语音实现语音播报、语音识别功能。

讯飞开放平台：http://www.xfyun.cn/index.php/default/index

![image](https://github.com/MZCretin/ExternalMapUtils/blob/master/png/Screenshot_20170509-152819.png)

##：使用方法:

-------------------

**Step 1.** Add the JitPack repository to your build file Add it in your root build.gradle at the end of repositories: 
```gradle
allprojects { repositories { ... maven { url 'https://jitpack.io' } } }
```

**Step 2.** Add the dependency
```gradle
dependencies { compile 'com.github.MZCretin:ExternalMapUtils:v1.0.0' }
```

**Step 3.** Start using it wherever you want as below.

```
//打开路径规划
OpenExternalMapAppUtils.openMapDirection(this, split[0], split[1], sName,
                split1[0], split1[1], dName, "测试DEMO");


```


####有什么意见或者建议欢迎与我交流，觉得不错欢迎Star



