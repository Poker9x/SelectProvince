# Script JavaScript Chọn Tỉnh Thành Việt Nam


```HTML
<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title></title>
    <script src="select-province.js"></script>
</head>

<body>
<div id="tinhvn"></div>
<script>
  SelectProvince({
    target: "#tinhvn",
    on: data => {
      console.log(data)
    }
  })
</script>
</body>

</html>
```
demo : https://poker9x.github.io/SelectProvince/
