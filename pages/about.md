---
layout: default
title: 关于
permalink: /pages/about.html
---

<div class="home">

	<h3><i class="fa fa-windows"></i>&nbsp;关于博客</h3>
	<hr>
	<br>
	<p>
	博客用<a href="http://jekyllrb.com/"><code>jekyll</code></a>（可将纯文本转化为静态网站和博客的语言）,<code>html</code>,<code>css</code>等构建。博客部署在<code>github</code>服务器上，前端采用<code>bootstrap</code>栅格式布局，可自适应移动端浏览器。
	写博客的目的很单纯，就是记笔记，方便在不同终端上随时查看，偶尔也会记录身边发生的事情。若想使用该模板搭建博客可以fork<a href="https://github.com/bornbeauty/bornbeauty.github.io">这个项目~</a>
	</p>
	<br>
	
	<h3><i class="fa fa-laptop"></i>&nbsp;IT技能</h3>
	<hr>
	<br>
    <div class="skills">
   	<div id="main" style="height:400px"></div>



    <!--
        <div class="skillbar clearfix" data-percent="80%">
            <div class="skillbar-title"><span>Java</span></div>
            <div class="skillbar-bar"></div>
            <div class="skill-bar-percent">80%</div>
        </div>

        <div class="skillbar clearfix" data-percent="60%">
            <div class="skillbar-title"><span>C++</span></div>
            <div class="skillbar-bar"></div>
            <div class="skill-bar-percent">60%</div>
        </div>
		
        <div class="skillbar clearfix" data-percent="60%">
            <div class="skillbar-title"><span>java script</span></div>
            <div class="skillbar-bar"></div>
            <div class="skill-bar-percent">60%</div>
        </div>

        <div class="skillbar clearfix" data-percent="60%">
            <div class="skillbar-title"><span>HTML</span></div>
            <div class="skillbar-bar"></div>
            <div class="skill-bar-percent">60%</div>
        </div>
		
		<div class="skillbar clearfix" data-percent="60%">
            <div class="skillbar-title"><span>CSS</span></div>
            <div class="skillbar-bar"></div>
            <div class="skill-bar-percent">60%</div>
        </div>
		-->
    </div>	

	
	<br>
	<h3><i class="fa fa-user"></i>&nbsp;基本信息</h3>
	<hr>
	<table class="table table-striped">
		<tr>
			<td>姓  名：</td>    
			<td>陶哓然</td>
		</tr>
		<tr>
			<td>学  历：</td>    
			<td>硕士在读</td>
		</tr>
		<tr>
			<td>学  校：</td>    
			<td>厦门大学</td>
		</tr>
		<tr>
			<td>专  业：</td>    
			<td>计算机科学与技术</td>
		</tr>
		<tr>
			<td>时  间：</td>    
			<td>2014年入学至今</td>
		</tr>
	</table>

	<br>
	<h3><i class="fa fa-phone-square"></i>&nbsp;联系方式</h3>
	<hr>
	<table class="table table-striped">
		<tr>
			<td>
				Email：
			</td>  
			<td>
				<A href="mailto:initialran@gmail.com ">initialran@gmail.com</A>			
			</td>
		</tr>

		<tr>
			<td>
				github：
			</td>  
			<td>
				<a href="{{ site.author.github }}" target="_blank">github.com/lemonjing&天生丽质</a>
			</td>  
		</tr>

		<tr>
			<td>
				微博：
			</td> 
			<td>
				<a href="{{ site.author.weibo }}" target="_blank">_NoThankYou</a>
			</td> 
		</tr>

		<tr>
			<td>
				知乎：
			</td> 
			<td>
				<a href="{{ site.author.zhihu }}" target="_blank">陶哓然</a>
			</td> 
		</tr>
	</table>


	<br>
	<h3><i class="fa fa-info-circle"></i>&nbsp;个人简介</h3>
	<hr>
	<br>
	<p>
	在校学生，爱coding，爱生活。目前在网易实习。
	</p>
	<br>

	<h3><i class="fa fa-heart"></i>&nbsp;人生理想</h3>
	<hr>
	<br>
	<p>
		绾青丝，挽情思，任风雨飘摇，人生不惧。浮生一梦醉眼看，海如波，心如昊月，雪似天赐。你自妖娆，我自伴。永不相弃！		
	</p>
	<br>
	<br> 
	<br>

</div>


<div>
{% include duoshuo.html %}
</div>
