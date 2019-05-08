# Object2Css

This package Converts JS Objects to Css Styles


```js
var a = {
	'div':
	{
		"width": "100px",
		"height": "100px",
		"background": "red",
		"position": "relative",
		"-webkit-animation": "mymove 5s infinite",
		"animation": "mymove 5s infinite"
	},
	'@-webkit-keyframes mymove':
	{
		'0%':
		{
			'top': '0px;'
		},
		'25%':
		{
			'top': '200px;'
		},
		'75%':
		{
			'top': '50px'
		},
		'100%':
		{
			'top': '100px'
		},
	},
	'@keyframes mymove':
	{
		'0%':
		{
			'top': '0px'
		},
		'25%':
		{
			'top': '200px'
		},
		'75%':
		{
			'top': '50px'
		},
		'100%':
		{
			'top': '100px'
		}
	}
}
```

TO :- 


```css

div {
    width:100px;
     height:100px;
     background:red;
     position:relative;
     -webkit-animation:mymove 5s infinite;
     animation:mymove 5s infinite
}
 @-webkit-keyframes mymove {
    0% {
        top:0px;
    }
     25% {
        top:200px;
    }
     75% {
        top:50px
    }
     100% {
        top:100px
    }
}
 @keyframes mymove {
    0% {
        top:0px
    }
     25% {
        top:200px
    }
     75% {
        top:50px
    }
     100% {
        top:100px
    }
}
```

##Function 


     toStyles(<Argument1>) :-
              <Argument1> :  The Object To be converted to css styles.
              
              
Please Contribute this repo to make to it more better.
     

