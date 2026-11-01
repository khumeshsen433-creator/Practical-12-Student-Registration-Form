# Practical-12-Student-Registration-Form

<!DOCTYPE html>
<html>
<head>
    <title>Student Registration</title>
    <style>
        body {
            font-family: Arial;
            background: lightblue;
        }

        form {
            width: 300px;
            margin: 30px auto;
            padding: 20px;
            background: white;
            border-radius: 10px;
        }

        input:not([type="radio"]):not([type="checkbox"]),
        select {
            width: 100%;
            padding: 8px;
            margin: 8px 0;
            box-sizing: border-box;
        }

        input:focus, select:focus {
            outline: 2px solid blue;
        }

        button {
            background: green;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
        }

        button:hover {
            background: darkgreen;
        }
    </style>
</head>
<body>
    <form>
        <h2>Registration Form</h2>

        <input type="text" placeholder="Enter Name" required>
        <input type="email" placeholder="Enter Email" required>
        <input type="password" placeholder="Password" required>

        <p>Select Course</p>
        <select>
            <option>BCA</option>
            <option>B.Tech</option>
            <option>B.Sc</option>
        </select>

        <p>Gender:</p>
        <label>
            <input type="radio" name="gender" value="male">
            Male
        </label>
        <label>
            <input type="radio" name="gender" value="female">
            Female
        </label>

        <p>Hobbies:</p>
        <label>
            <input type="checkbox" name="hobby" value="sports">
            Sports
        </label>
        <label>
            <input type="checkbox" name="hobby" value="music">
            Music
        </label>

        <br><br>
        <button type="submit">Register</button>
        <button type="reset">Reset</button>
    </form>
</body>
</html>
