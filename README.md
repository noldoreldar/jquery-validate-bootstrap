# jquery-validate-bootstrap

Overrides jQuery validator's default settings to show a bootstrap glyphicon inside input elements which have errors. Hides default error message labels and shows a tooltip on the icons instead.

<h4>Requirements</h4>
<ul>
<li>bootstrap (>= 3.1.1)</li>
<li>jQuery (>= 1.9.1)</li>
<li>jQuery.Validation (>= 1.10.0)</li>
<li>Microsoft.jQuery.Unobtrusive.Validation (>= 3.1.1)</li>
</ul>

<h4>Usage</h4>

```
<link rel="stylesheet" href="/lib/bootstrap/dist/css/bootstrap.css" />
```
---
```
...
<script src="/Scripts/jquery.js"></script>
<script src="/Scripts/jquery.validate.js"></script>
<script src="/Scripts/jquery.validate.unobtrusive.js"></script>
<script src="/Scripts/bootstrap.js"></script>
...
...
<script src="/Scripts/jquery.validation.bootstrap.js"></script>
```
--- 
```
<script>
    $.validator.applyBootstrap();
    $("#form1").validate(); // You don't need this line if you enabled Client Side Validation for ASP.NET MVC and using HtmlHelpers on a Model 
</script>
```
