---
title: dokumentacja
---
<SwmSnippet path="/index.html" line="1">

---

This code snippet is an HTML document that includes CSS and JavaScript files for a Material Kanban Board. The `onload` event triggers the `materialKanban.initialize()` function with various arguments to initialize the board. The `div` element with id `plugin` is where the board will be displayed.

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Material Kanban Board</title>
    <link href="css/font-awesome.min.css" rel="stylesheet">
    <link href="css/bootstrap.min.css" rel="stylesheet">
    <link href="css/responsive-grid.min.css" rel="stylesheet">
    <link href="css/style.min.css" rel="stylesheet">
    <script src="lib/jquery.min.js"></script>
    <script src="js/dragula.min.js"></script>
    <script src="js/script.js"></script>
    <script src="data/data.js"></script>
</head>

<body onload="materialKanban.initialize('plugin',null, 'No data found',configJSON,null,null,false, true, true);">
    <div id="plugin" style="position:relative;"></div>
</body>

</html>
```

---

</SwmSnippet>

<SwmMeta version="3.0.0" repo-id="Z2l0aHViJTNBJTNBTWF0ZXJpYWwtS2FuYmFuLUJvYXJkJTNBJTNBYmxhemVqLWNoZWxtaWNraQ==" repo-name="Material-Kanban-Board"><sup>Powered by [Swimm](https://app.swimm.io/)</sup></SwmMeta>
