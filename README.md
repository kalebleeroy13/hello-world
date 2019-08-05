<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>Function scope example</title>
</head>
<body>

  <script>
    var x = 1;
    function a() {
      var y = 2;
    }
    function b() {
      var z = 3;
    }
    function output(value) {
      var para = document.createElement('p');
      document.body.appendChild(para);
      para.textContent = 'Value: ' + value;
    }
  </script>
</body>
</html>
