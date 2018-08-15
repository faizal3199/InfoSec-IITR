---
layout: page
current: about
navigation: true
logo: 'assets/images/ghost.png'
class: page-template
subclass: 'post page'
---
<center>
<h1 id="heading">Calendar</h1>
</center>
<br>
<div id="Events">
	<P id="calendar"><b>Upcoming Events</b></P>
	<P id="dates">these are the events</P>
			
</P>
</div>
<br>
<div id="map">
	<P id="calendar"><b>Month Overview</b></P>
<iframe src="https://calendar.google.com/calendar/embed?title=InfosecIITR&amp;height=600&amp;wkst=2&amp;bgcolor=%23000000&amp;src=1shtgh45pa2bbptjt1ef374hro%40group.calendar.google.com&amp;color=%236B3304&amp;ctz=Asia%2FCalcutta" style="border-width:0" width="800" height="600" frameborder="0" scrolling="no" id="mapframe"></iframe>
</div>
<style type="text/css">
	@font-face{
      	font-family:fontis;
    src: url("./fonts/UbuntuMono-R.ttf");
      }
      *{
      	font-family: fontis;
      }
	#heading{
		color:#d2d2d2;
	}
	#Events{
		background-color: white;
		border:5px solid #d2d2d2;
	}
	#map{
		background-color:white;
		text-align: center;	
		border:5px solid #d2d2d2;	

	}
	#mapframe{
		padding: 10px;
		margin-top: -60px;
	}
	#calendar{
		width: 100%;
		max-height:50px;
		text-align: center;
		color:black;
		background-color: #d2d2d2;
		font-size: 30px;
	}
	#dates{
		padding: 10px;

	}
</style>