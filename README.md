# craft-candle

Parameterized candle model.

### Install
    $ npm install craft-candle

### Parameters
- width: adjusts width of candle
	- default: 8
- height: adjusts height of candle
	- default: 45

### Example
```html
<craft>
    <craft name="candle" module="craft-candle"/>
    <row spacing="1" l="centerY()">
        <candle></candle>
        <candle width="15" height="15"></candle>
    </row>
</craft>
```

![example](example.png)