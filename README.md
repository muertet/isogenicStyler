isogenicStyler
==============

CSS to Isogenic Engine Style converter

#[Use it online](http://htmlpreview.github.io/?https://github.com/muertet/isogenicStyler/blob/master/index.htm) #

Parses normal css code:

```
.playerMapMenu{
	 margin-top:42%;
	  height:30%;
	  width:100%;
	  background-color:#333333;
	  color:white;
	  padding: 5px;
}
.playerMapMenu div{
	  float:left;
	  display:inline-block;
	  border:1px solid;
	  min-width:2%;
	  height:100%;
}
.playerResources{
	  width:10%;
}
.miniMap{
  width:30%;
}
```

to


```

ige.ui.style('.playerMapMenu', {
	'margintop': '42%',
	'height': '30%',
	'width': '100%',
	'backgroundcolor': '#333333',
	'color': 'white',
	'padding': '5px'
});
ige.ui.style('.playerMapMenudiv', {
	'float': 'left',
	'display': 'inline-block',
	'border': '1px solid',
	'minwidth': '2%',
	'height': '100%'
});
ige.ui.style('.playerResources', {
	'width': '10%'
});
ige.ui.style('.miniMap', {
	'width': '30%'
});

```
