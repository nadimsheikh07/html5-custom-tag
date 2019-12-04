# html5-custom-tag

> Create custom HTML5 tag

[![Github]](https://github.com/nadimsheikh07/html5-custom-tag)


```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Custom html5 tag</title>

  <script>
    document.registerElement('x-foo')
  </script>

  <style>
    x-foo {
      color: red;
      font-size: 10rem;
    }
  </style>
</head>

<body>
  <x-foo>
    custom html5 tag
  </x-foo>
</body>

</html>
```