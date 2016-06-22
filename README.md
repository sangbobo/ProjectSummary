# 项目总结

做android也有2年时间了，总结一下至今使用过的第三方项目，以及做过的项目

一、图片相关

1、Fresco
  用过的非常强大的一个图片加载组件了,facebook出品.<br>
  github：https://github.com/facebook/fresco.<br>
  优点：<br>
  1>支持多种图片加载方式，包括网络图片，res下图片等等，而且调用统一，使用起来很方便.<br>
  2>支持多种图片展现方式，例如图片圆角，占位图等等.<br>
  
  
2、Glide
  google推荐的图片加载组件，比较fresco而言小巧一些。比较适合加载简单图片的项目。<br>
  github：https://github.com/bumptech/glide<br>
  优点：<br>
  1>小巧，不需要自定义组件，使用imageview即可。<br>
  2>内存占用少，会根据imageview的大小自动裁剪图片，超级省内存。<br>
  使用过此组件的项目：国家电网<br>
  
3、GalleryFinal
  自定义的相册，支持单选多选，拍照选择，裁剪编辑等操作，还能自定义样式，借用金星老师的话，完美。<br>
  github:https://github.com/pengjianbo/GalleryFinal<br>
  优点：<br>
  1>相对来说自定义相册，解决了不同类型手机之间系统相册选择的问题。比如有的只能单选，不能多选的问题。<br>
  2>选择照片后可以进行裁剪，旋转等简单操作。<br>
  使用过此组件的项目：国家电网<br>
  
4、ConvenientBanner
  一个图片轮播组件，很多项目都用的到。<br>
  https://github.com/saiwu-bigkoo/Android-ConvenientBanner<br>
  优点：<br>
  1>使用起来简单，支持多种效果，东西少，配置起来简单。<br>
  使用过此组件的项目：韩国派<br>
  还有一个显示文字的轮播：AndroidImageSlider<br>
  github:https://github.com/daimajia/AndroidImageSlider<br>
  
二、快捷工具

1、base-adapter-helper
  快速的定义一个适配器，提高开发效率<br>
  github:https://github.com/JoanZapata/base-adapter-helper<br>
  优点：<br>
  1>不用再一个一个写viewholder了。<br>
  2>扩展性强，可用自定义自己的适配器。<br>
  还有一个类似的：https://github.com/hongyangAndroid/baseAdapter
  使用过此组件的项目：国家电网、韩国派、汇客乐园<br>
  
2、Android-AlertView
  一个仿iOS的对话框<br>
  github:https://github.com/saiwu-bigkoo/Android-AlertView<br>
  优点：<br>
  1>对话框好看，对，就是好看。。。<br>
  使用过此组件的项目：国家电网、韩国派、汇客乐园<br>

3、ToolsFinal
  常用的工具类<br>
  github:https://github.com/PaoJiao/ToolsFinal<br>
  优点：<br>
  1>基本涵盖的很全了，按照需要使用就可可以了<br>
  使用过此组件的项目：国家电网、韩国派、汇客乐园<br>
  
三、适配相关

1、AndroidAutoLayout
  Android屏幕适配方案，直接填写设计图上的像素尺寸即可完成适配。<br>
  github:https://github.com/hongyangAndroid/AndroidAutoLayout<br>
  优点：<br>
  1>再也不用拿着设计稿去想这控件的宽高到底取多少dp<br>
  2>再也不用去为多个屏幕去写多个dimens<br>
  3>再也不用去计算百分比了（如果使用百分比控件完成适配）<br>
  4>再也不用去跟UI MM去解释什么是dp了<br>
  使用过此组件的项目：汇客乐园<br>

四、网络相关

1、okhttp-utils
  okhttp使用起来其实还是比较麻烦的，但是进行封装以后，使用起来就非常的方便了。<br>
  github:https://github.com/hongyangAndroid/okhttp-utils<br>
  优点：<br>
  1>使okhttp使用起来更加的方便<br>
  使用过此组件的项目：国家电网、韩国派、汇客乐园<br>
  
