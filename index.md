---
layout: page
title: SatisfactionLooker
tagline: Understanding Customer Satisfaction and relationships to Gov Cost on them.
---
{% include JB/setup %}

<div class='row'>
	<div class='col-md-3'>
		<div id='LeftSide'>
			<h3>Group by</h3>
			<ul>
				<li><input type='radio' checked />Region</li>
				<li><input type='radio' />State</li>
				<li><input type='radio' />Agency</li>
			</ul>
			<h2>My Buildings</h2>
			<div id='BuildingSelect'>
<input type='checkbox' checked />Anchorage<br/>
<input type='checkbox' checked />Boulder<br/>
<input type='checkbox' checked />Boston<br/>
<input type='checkbox' checked />Charlottesville<br/>
<input type='checkbox' checked />Denton<br/>
<input type='checkbox' checked />Elkridge<br/>
<input type='checkbox' checked />Gainseville<br/>
<input type='checkbox' checked />Houston<br/>
<input type='checkbox' checked />Kingston<br/>
			</div>
		</div>
	</div>
	<div class='col-md-9'>
		<div id='chart'></div>
		<div class='row'>
			<div class='col-md-3'>
<img src="/assets/scatterplotselect.png">
			</div>
			<div class='col-md-3'>
<img src="/assets/boxplot.png">
			</div>
			<div class='col-md-3'>
<img src="/assets/ratingcurvecompare.png">
			</div>
			<div class='col-md-3'>
<img src="/assets/spendingplot.png">
			</div>
		</div>
		<div class='col-md-6'>
			<h2>Top 5</h2>
<img style='width: 30px' src='/assets/happy.png' />Boston<br/>
<img style='width: 30px' src='/assets/happy.png' />Houston<br/>
<img style='width: 30px' src='/assets/happy.png' />Denver<br/>
<img style='width: 30px' src='/assets/happy.png' />Trenton<br/>
<img style='width: 30px' src='/assets/happy.png' />Philadelphia<br/>
		</div>
		<div class='col-md-6'>
			<h2>Bottom 5</h2>
<img style='width: 30px' src='/assets/sad.png' />Washington, DC<br/>
<img style='width: 30px' src='/assets/sad.png' />Los Angeles<br/>
<img style='width: 30px' src='/assets/sad.png' />New York<br/>
<img style='width: 30px' src='/assets/sad.png' />Dallas<br/>
<img style='width: 30px' src='/assets/sad.png' />San Francisco<br/>
		</div>
	</div>
</div>
