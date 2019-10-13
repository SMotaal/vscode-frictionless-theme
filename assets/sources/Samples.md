# SMotaal's Frictionless Theme for Visual Studio Code

## Samples

```html
<body attribute="value">
	<!-- comment -->
</body>
```

```css
body {
	color: red;
	background-color: #f00;
}
```

```js
export class Values {
	static async *[Symbol.asyncIterator]() {
		const {values = [0, 1, 2, 3]} = this;
		for (const value of values) {
			yield `value is ${/(?:\d|)/.exec(value)[0]}`;
		}
	}
}
export default [...Values()];
```

```json
{
	"name": "my-package",
	"version": 0.1.1,
	"private": true,
}
```
