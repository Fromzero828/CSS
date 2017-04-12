## 长度值与单位
特殊值0可以省略单位。例如：margin:0px可以写成margin:0
一些属性可能允许有负长度值，或者有一定的范围限制。如果不支持负长度值，那应该变换到能够被支持的最近的一个长度值。
长度单位包括包括：相对单位和绝对单位。
相对长度单位包括有： em, ex, ch, rem, vw, vh, vmax, vmin
绝对长度单位包括有： cm, mm, q, in, pt, pc, px


<table border="1" width= 90%>
	<thead><tr><th>长度值与单位</th><th>说明</th><th>用法</th></tr></thead>
	<tbody>
		<tr><td>rem</td><td>相对长度单位。相对于根元素(即html元素)font-size计算值的倍数</td><td></td></tr>
		<tr><td>em</td><td>相对长度单位。相对于根元素(即html元素)font-相对长度单位。相对于当前对象内文本的字体尺寸。</td><td></td></tr>
		<tr><td>vw</td><td>相对于视口的宽度。视口被均分为100单位的vw</td><td></td></tr>		
		<tr><td>px</td><td>相对长度单位。像素（Pixels）。</td><td></td></tr>
	</tbody>
</table>

## 颜色值
<table border="1" width= 90%>
	<thead><tr><th>颜色值</th><th>说明</th><th>用法</th></tr></thead>
	<tbody>			
		<tr><td>Color Name</td><td>用颜色关键字来指定颜色。</td><td></td></tr>
		<tr><td>RGB</td><td>RGB(R,G,B)</td><td>R：红色值。正整数 | 百分数<br>G：绿色值。正整数 | 百分数<br>B：蓝色值。正整数 | 百分数</td></tr>
		<tr><td>rgba</td><td>RGBA(R,G,B,A)</td><td>R：红色值。正整数 | 百分数<br>G：绿色值。正整数 | 百分数<br>B：蓝色值。正整数 | 百分数<br>A：Alpha透明度。取值0~1之间。</td></tr>
		<tr><td>transparent</td><td>RGBA(R,G,B,A)</td><td>在CSS1中，transparent被用来作为background-color的一个参数值，用于表示背景透明。</td></tr>
	</tbody>
</table>
## 文本值
## 函数值
<table border="1" width= 90%>
	<thead><tr><th>函数值</th><th>说明</th><th>用法</th></tr></thead>
	<tbody>			
		<tr><td>calc()</td><td>用于动态计算长度值。</td><td>需要注意的是，运算符前后都需要保留一个空格，例如：width: calc(100% - 10px)；<br>任何长度值都可以使用calc()函数进行计算；<br>calc()函数支持 "+", "-", "*", "/" 运算；calc()函数使用标准的数学运算优先级规则；</td></tr>
	</tbody>
</table>
## 角度值与单位
## 时间值与单位
## 频率值与单位
## 特殊布局值与单位
## 分辨率值与单位
