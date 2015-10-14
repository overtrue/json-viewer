# [Json Viewer](http://overtrue.me/json-viewer)
A tool for make JSON view in browser.

# Usage

```html

<link rel="stylesheet" href="json-viewer/json-viewer.css">
<script src="path/to/jquery.js"></script>
<script src="json-viewer/json-viewer.js"></script>

<div id="json-container"></div>

<script>
    var json = {
        name: "JsonViewer",
        author: {
          name: "overtrue",
          email: "i@overtrue.me",
          contact: [
            {
              location: "office",
              number: 123456
            },
            {
              location: "home",
              number: 987654
            }
          ]
        }
    };

    $('#json-container').jsonview(json); // Support json string/object
</script>
```

[Demo](http://overtrue.me/json-viewer)

# License

MIT
