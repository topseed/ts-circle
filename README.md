# ts-circle
A standard web component to display a circle stat

## Installation

- Add `<link rel="import" href="https://rawgit.com/topseed/ts-circle/master/ts-circle.html">` to the `head` of your page.
- In the `body`, place `<ts-circle></ts-circle>` and `script` as shown below.

## Usage

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="ts-circle.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<ts-circle></ts-circle>
<script>
	var Circle =  document.registerElement('ts-circle', {prototype: CircleEl})
	document.body.appendChild(new Circle())
	var circle = document.querySelector('ts-circle')
	circle.value(55)
</script>
```

## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License
MIT
