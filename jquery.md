# 1.3 Selecting DOM Elements Using Selectors and the jQuery Function
```
<a href='#'>link</a>
<a href='#'>link</a>
<a href='#'>link</a>
<a href='#'>link</a>
<a href='#'>link</a>
<a href='#'>link</a>
```
> count how many time a tag occured 

```js
<script type="text/JavaScript">
//alerts there are 6 elements
alert('Page contains ' + jQuery('a').length + ' <a> elements!');
</script>
```
# 1.4 Selecting DOM Elements Within a Specified Context
```
<form>
	<input type = "checkbox"/>
    <input type = "checkbox"/>
    <input type = "checkbox"/>
    
</form>
<form>
	<input type = "checkbox"/>
    <input type = "checkbox"/>
    <input type = "checkbox"/>
    
</form>
```
```js
<script type="text/JavaScript">
//searches within all form elements, using a wrapper for context, alerts "8 inputs"
	alert('selected ' +jQuery('input',$('form')).length + ' 	inputs');
</script
```