#LaTex数学公式
$a={\sum}sin(x)
{\int {_\pi}{^\infty}}
cos{\delta}x$

$s {\le}{\sum}_{n=0}^{\infty} {\frac {x{^n}}{n!}}$

!(icon:fa_red)

#流程图
		%%mermaid
		graph LR
		a(进水口)-->|注入|b((水箱))
		b-.->|排出|c{出水口}
		b ==>|冲水| d[排出]
		c---|泻出|d

#甘特图
	%%mermaid
	gantt
	title 甘特图1
	section 软件开发阶段1
	新建环境	:done, 		task1,	2016-4-2,	20d
	开发界面	:active, 	task2, after task1, 12d
	开发模型 : 				task3, after task2, 20d
	section 测试
	测试环境	:done,		test1, 	2016-2-1, 	10d
	测试用例 	:active,	test2,	after test1, 15d
	单元测试	:				test3,	after test2,	15d
	集成测试	:				test4,	after task2, 20d
	
#PDF
		%%pdf
		/Users/hehao/Downloads/portableC.pdf

