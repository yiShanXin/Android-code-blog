开始 telegram api 分析 
  1. 视频处理模块，
  2. gcm 封装框架
  3. ocm 以及图片算法

  那就愉快的开始吧！

  这是 项目代码 https://github.com/DrKLO/Telegram 
 
  git clone   git@github.com:DrKLO/Telegram.git 下载到本地(又提一次)
   
  下载代码后，大家需要处理几件事情 
     1. telegram api 申请
     2. gcm 申请权限
  这样的话  那就去官网开始  https://my.telegram.org/apps 去申请吧，(注 验证的话有的时候 需要电话提示验证码，想到这儿是不是知道妹子来了)
  gcm 控制台 https://code.google.com/apis/console/ 有关怎么注册以及/步骤 推荐 Google大法好 
  
	
  然后把 gcm id 绑定到 telegram 新建应用对应的选项里
  
  然后 就是修改客户端代码 , 需要修改一下几个文件 
  org.telegram.messenger 目录下的  BuildVars
 APP_ID	
 APP_HASH
 

  GCM_SENDER_ID; gcm id， 这个需要注意下  需要填写 https://code.google.com/apis/console/b/0/?noredirect&pli=1#project:1002843392509:access

  大家注意控制台 当前这个认证  1002843392509 就只这个了！ Google 就是这么科技范,

  接着 大家可以 自定义多语言版本了，或者是加上彩蛋！

  PS:多语言的话 需要自己在 工程全局配置里面设置！

 




