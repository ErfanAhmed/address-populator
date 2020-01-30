##### Required version :
- `jquery-2.2.4.min.js`
- `jquery-2.2.4.min.js`

##### About  
`populateAddressFields` function will populate common address fields:
- Address Line1
- Address Line2
- City
- Police Station
- Post Office
- Post Code

**Note: address.js currently useful for Bangladesh only**

##### Sample usage
Call `populateAddressFields` function with the desired `html` tag `id`.

```
<script type="text/javascript">
	$(document).ready(function() {
		populateAddressFields("primary_address");
	});
</script>
```

`<div id="primary_address"></div>`
