# How To Use:
  #### 一、在项目的build.gradle文件下添加以下代码:
           allprojects {
               repositories {
                   jcenter()
                   maven { url "https://jitpack.io" }
               }
           } 
  #### 二、在module的build.gradle文件下添加以下代码:
           dependencies {
	      	   compile 'com.github.RedJayIsACoder:SimpleBanner:1.3.1'
           }
  #### 三、API
  	   1.setOnRefreshListener(设置下拉刷新和上拉加载的监听方法)<br/><br/>
  	   2.refreshComplete(关闭下拉刷新)<br/><br/>
  	   3.loadMoreComplete(关闭上拉加载)<br/><br/>


