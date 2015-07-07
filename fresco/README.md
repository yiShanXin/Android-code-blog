this is first code

    在配置fresco图片库大家 通过 blog，论坛上都有所链接了，没有的话也没有关系，
首先大家要做好几个步骤准备，
1. Android Stduio 开发工具(大家也知道，Google大发强类推荐)
2. 本地配置好 NDK 环境，如果没有的话需要自己下载
3. git 这个是必需得了

1. https://github.com/facebook/fresco 项目地址
2. 现在列出需要注意的问题时 
Error:Execution failed for task ':imagepipeline:ndk_build_bitmaps'. > A problem occurred starting pr
如果 直接运行的话  这个就是提示  ndk 的提示了 就是说 没找到ndk环境
大家 看下本地配置的问题
ndk.path=/home/XXX/Android_SDK/android-ndk-r10d

(PS：/home/XXX/Android_SDK/android-ndk-r10d 本地系统里面的NDK路径)
	然后 看看 echo $NDK_HOME没问题的话 就可以了
