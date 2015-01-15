# 3.2.3.GA

## Ti.UI.Switch

### onTintColor

Define the Switch color

```javascript
Ti.UI.createSwitch({
	onTintColor: '#f00'
});
```

## Ti.UI.View

### shadow

Set the shadow for all TiUIView

```javascript
Ti.UI.createView({
	shadow: {
		shadowRadius: 2,
		shadowOpacity: 0.2,
		shadowOffset: {
			x:2,
			y:2
		}
	}
});
```

## Ti.UI.ProgressBar

### progressTintColor/trackTintColor

Set the background and foreground of the progressbar

```javascript
Ti.UI.createProgressBar({
	progressTintColor: 'green',
	trackTintColor: 'red'
})
```