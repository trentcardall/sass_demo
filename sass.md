<html>
  <head>
    <title>Shapes</title>
    <link rel="stylesheet" href="style.scss">
  </head>
  <body>
    <h1>Shapes</h1>
    <div class="shape rectangle"></div>
    <div class="shape square"></div>
 </body>

<script>
    // Get the shapes
    const rectangle = document.querySelector('.rectangle');
    const square = document.querySelector('.square');

    // Add event listeners for when the shapes are clicked
    rectangle.addEventListener('click', () => {
    alert('You clicked the rectangle!');
    });

    square.addEventListener('click', () => {
    alert('You clicked the square!');
    });
</script>

</html>