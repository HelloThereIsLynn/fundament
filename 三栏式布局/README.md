##### 任务0103
关于布局(可以用position，float之类的结合)
http://www.barelyfitz.com/screencast/html-training/css/positioning/还有http://zh.learnlayout.com/这个网址比较清楚。	
	
	1. display属性：
		- bloak：块级元素，宽度为父元素宽度、换行显示，可设置宽高
		- inline：行级元素，宽度为内容宽度、同行显示，不可设置宽高
		- inline-block：宽度为内容宽度，同行显示，可设置宽高，整块换行
	2. position属性：
		- reletive：是相对自己本身的，
		- absolute：是相对距离 距离它最近的，不是静态元素的元素
		- fixed: 相对视窗
	3. float属性：
	4. clear属性：可以清除左边的/右边的/两边的浮动
	5. overflow属性：可以将浮动之后溢出的元素包裹回来，overflow 属性规定当内容溢出元素框时发生的事情
	6. column属性：新的
	.three-column {
	  padding: 1em;
	  -moz-column-count: 3;
	  -moz-column-gap: 1em;
	  -webkit-column-count: 3;
	  -webkit-column-gap: 1em;
	  column-count: 3;
	  column-gap: 1em;
	}


关于盒模型
		
	.left{
			width: 200px;
			float: left;
			position: relative;
			padding: 20px;
		}
	这样设置会比预期的大，会有240px，但是加上box-sizing: border-box;就不会被撑大，所以可以加上

	*{
	  -webkit-box-sizing: border-box;
	     -moz-box-sizing: border-box;
              box-sizing: border-box;
	}
关于flex http://zh.learnlayout.com/flexbox.html
还有网易的笔记很全
关于响应式我还要再研究。。。