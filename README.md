# mozaik

### Usage:
```
<!-- include dependencies -->
<link rel="stylesheet" href="vendor/components/jqueryui/themes/ui-lightness/jquery-ui.min.css">
<script src='vendor/components/jquery/jquery.min.js'></script>
<script src="vendor/components/jqueryui/jquery-ui.min.js"></script>
<script src='vendor/tinymce/tinymce/tinymce.min.js'></script>
<script src="vendor/gymadarasz/imagesloaded/imagesloaded.pkgd.min.js"></script>
<script src="vendor/gymadarasz/ace/src-min/ace.js" type="text/javascript" charset="utf-8"></script>

<!-- include mozaik -->
<link rel="stylesheet" href="jquery.mozaik.css">
<script src='jquery.mozaik.js'></script>
```

### Example:
HTML:
```
<div id="template"></div>
```

JavaScript:
```
$(function(){
    // initialize
    $('#template').mozaik();

    // get value
    $('#template').getMozaikValue();

    // apply inline styles (tipically for email templates)
    $('#template').getMozaikValue({inlineStyles: true});
});
```

See more on Guthub: https://github.com/gymadarasz/mozaik
