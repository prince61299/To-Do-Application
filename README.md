# To-Do-Application

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Simple Todo Appplication</title>
</head>

<body>
    <div id="container">
        <div class="controls">
            <h1>My Awesome TODO</h1>
            <input type="text" id="input"><br>
            <button type="button" id="add">Add TODO</button>
            <button type="button" id="remove">Remove TODO</button>
            <button type="button" id="removeall">Remove Everything</button>
        </div>
        <ul id="list">
            <li class="mycheck">
                <input type="checkbox" name="" id="check">
                <label>Go to gym</label>
            </li>
            <li class="mycheck">
                <input type="checkbox" name="" id="check" checked>
                <label>Record YT Video</label>
            </li>
            <li class="mycheck">
                <input type="checkbox" name="" id="check">
                <label>Go to gym</label>
            </li>
            <li class="mycheck">
                <input type="checkbox" name="" id="check" checked>
                <label>Record YT Video</label>
            </li>
        </ul>

    </div>
    <script src="todo.js"></script>

</body>

</html>
