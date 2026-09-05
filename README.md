<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>

  <style>
    :root {
      --primary: #db3f34;
      --secondary: #cca22e;
     --text-color: white;
     --radius: 10px;
     --padding: 10px 20px;
}
    button {
  color: var(--text-color);
  padding: var(--padding);
  border-radius: var(--radius);
  border: none;
}
    .button1 {
      background: var(--primary);
      color: rgb(255, 255, 255);
    }

    .button2 {
      background: var(--secondary);
      color: rgb(255, 255, 255);
    }

    .button3 {
      background: var(--primary);
      color: rgb(255, 255, 255);
    }
  </style>

</head>

<body>

  <button class="button1">Save</button>
  <button class="button2">Delete</button>
  <button class="button3">Continue</button>

</body>

</html>
