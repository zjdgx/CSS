# CSS动画(2016/08/25)

## 1. transition(过渡):

`transition: property duration timing-function delay;`

transition 属性是一个简写属性，用于设置四个过渡属性：

	a. transition-property
	
	b. transition-duration
	
	c. transition-timing-function
	
	d. transition-delay
	
transition-timing-function: ease, linear, ease-in: 加速, ease-out: 减速, cubic-bezier: 自定义速度模式

## 2. animate

`animation: name duration timing-function delay iteration-count direction;`

animation 属性是一个简写属性，用于设置六个动画属性：

	a. animation-name

	b. animation-duration
	
	c. animation-timing-function

	d. animation-delay

	e. animation-iteration-count

	f. animation-direction: normal、alternate、reverse、alternate-reverse