##### 任务0105

这个任务是基于任务0102的，只是改动了布局方式，在class=pic的article中使用了flex布局。
关于flex布局
阮一峰的博客。。。http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html?utm_source=tuicool（这个很清晰很清晰，清晰地我都不想写了）.
		
	以下属性设置在容器上：
	    flex-direction
        flex-wrap
        flex-flow
        justify-content
        align-items
        align-content
	  
	 以下属性设置在item上
        order
        flex-grow：如果都为1则均分剩余空间，如果其中一个item为2则占剩余空间为其他的item的2倍
        flex-shrink：等比例缩小，如果一个item为0其他的为1，则前者不缩小
        flex-basis：设置这个值比如350px，则剩余空间会去掉这一部分,默认为auto即本身大小
        flex：是flex-grow, flex-shrink 和 flex-basis的简写，一般用auto(1 1 auto)
        align-self：允许单个项目有与其他项目不一样的对齐方式，可覆盖align-items属性
