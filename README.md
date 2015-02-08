# craft-candle

Parameterized candle model.

### Install
	$ npm install craft-candle

### Parameters
- width: adjusts width of candle
- height: adjusts height of candle
- size: scales model

### Example
```html
<craft>
	<craft name="candle" module="craft-candle"/>
	<candle height="15" size="2"></candle>
	<candle width="15" height="10"></candle>
	<candle></candle>
</craft>
```