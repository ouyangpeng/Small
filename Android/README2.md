# Small Android
## 编译插件



###Build libraries (准备基础库)
  > gradlew buildLib -q (-q是安静模式，可以让输出更好看，也可以不加)

![Build Libraries](https://github.com/ouyangpeng/Small/blob/master/Android/screen/small_1.jpg)

###Build bundles (打包所有组件)

  > gradlew buildBundle -q (-q是安静模式，可以让输出更好看，也可以不加)

![Build Bundles](https://github.com/ouyangpeng/Small/blob/master/Android/screen/small_2.jpg)



###查看.so文件是否编译完毕
  > 在app项目中看是否会生成**smallLibs**目录，然后**smallLibs**目录下生成一个**armeabi**目录，目录下就是.so文件了

![.so文件](https://github.com/ouyangpeng/Small/blob/master/Android/screen/small_3.jpg)