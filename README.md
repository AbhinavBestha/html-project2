# html-project2
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Login page</title>
    <style>
        body {
            background: linear-gradient(to right, #1cd8d2, #93edc7);
            ;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;

        }

        .h1 {
            color: #0d172a;
            font-weight: 900;
        }

        .container {

            width: 22%;
            background: #0d172a;
            border-radius: 20px;
            box-shadow: 0px 10px 20px -10px rgba(0, 0, 0, 0.75);
            color: #B3B8CD;
            padding: 40px;
            position: relative;
            top: 50%;

        }

        label {
            font-size: 25px;
            border: 4px solid #fff;
            padding: 10px;
            box-sizing: border-box;
            border-radius: 10px;



        }

        input[type=text],
        input[type=password] {
            width: 100%;
            margin-top: 2vw;
            margin-bottom: 2vw;
            padding: 12px 20px;
            border: 2px solid green;
            box-sizing: border-box;
            border-radius: 20px;
        }

        .button {
            background-color: #fff;
            border: 0 solid #e2e8f0;
            border-radius: 20%;
            box-sizing: border-box;
            color: #0d172a;
            cursor: pointer;
            display: inline-block;
            font-family: "Basier circle", -apple-system, system-ui, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
            font-size: 1.1rem;
            font-weight: 600;
            line-height: 1;
            padding: 0 20px 0 20px;
            text-align: center;
            text-decoration: none #0d172a solid;
            box-shadow: 0px 1px 2px rgba(166, 175, 195, 0.25);

        }
        h1{
            text-align: center;
        }
    </style>
</head>

<body>
    <h1 class="h1">Change Password
    </h1>
    <center>
        <form>
            <div class="container">
                <label>New Password</label><br>
                <input type="text" placeholder="new password" name="username" required></p>
                <p><label>Confirm Password</label><br>
                    <input type="password" placeholder="confirm password" name="password" required>
                </p>
                <p>forgot password ??</p>
                <a style="text-decoration: none;" href="" target="_blank"><button type="submit"
                        class="button">
                        
                        <h3 style="background-color: yellow;">Login</h3>
                    </button></a>

            </div>
        </form>
    </center>
</body>

</html>
