# pageSwitch
根据慕课网的全屏轮播效果写的精简版jquery轮播插件。
demo(https://stupidehorizon.github.io/pageswitch/)
#### 功能
- 实现竖屏或横屏全屏轮播  
- 可自动轮播 当轮播图用也没问题  
- 可自动生成轮播页面导航  
默认参数配置  
```javascripy 
    defaults={  
	selectors:{                 //class指定样式类  
		sections:".sections",   //父元素样式类  
		section:".section",     //分页元素样式类  
		page:".pages",		    //换页元素样式类  
		active:".active"        //被选中的换页元素样式类  
	},  
	index:0,                     //页面开始索引  
	easing:'ease',               //动画效果  
	duration:500,				 //动画执行时间  
	loop:true,					//是否循环切换  
	pagination:true,			//是否进行分页   
	keyboard:true,				//是否触发键盘事件 暂时未定义  
	direction:"horizontal",	    //滑动方向 vertical horizontal  
	callback:"",                 //回调函数  
	auto:true                    //是否自动轮播  
};
```  
