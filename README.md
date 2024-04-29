
<style>
        body {
    background-color: #f8f9fa;
    font-family: Arial, sans-serif;
}

.container {
    max-width: 400px;
    margin: 50px auto;
    background-color: #fff;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.1);
}

h2 {
    text-align: center;
    margin-bottom: 30px;
    color: #333;
}

.form-group {
    margin-bottom: 20px;
}

.form-control {
    border-radius: 20px;
    border: 1px solid #ced4da;
    padding: 12px 15px;
    font-size: 16px;
}

.btn-primary {
    width: 100%;
    border-radius: 20px;
    background-color: #007bff;
    border-color: #007bff;
    font-size: 16px;
    padding: 12px 15px;
}

.btn-primary:hover {
    background-color: #0056b3;
    border-color: #0056b3;
}

.btn-secondary {
    width: 100%;
    border-radius: 20px;
    background-color: #6c757d;
    border-color: #6c757d;
    font-size: 16px;
    padding: 12px 15px;
}

.btn-secondary:hover {
    background-color: #5a6268;
    border-color: #545b62;
}

.google-btn {
    width: 100%;
    border-radius: 20px;
    background-color: #ea4335;
    border: none;
    color: #fff;
    font-size: 16px;
    padding: 12px 15px;
}

.google-btn:hover {
    background-color: #d33126;
}

.input-group-prepend {
    margin-right: 10px;
}

.text-center {
    text-align: center;
}

    </style>
</head>
<body>
    <div class="container">
        <h2>ورود به سایت</h2>
        <form action="#" method="post">
            <div class="form-group">
                <input type="text" class="form-control" id="username" name="username" placeholder="نام کاربری" required>
            </div>
            <div class="form-group">
                <input type="password" class="form-control" id="password" name="password" placeholder="رمز عبور" required>
            </div>
            <button type="submit" class="btn btn-primary">ورود</button>
            <div class="text-center mt-3">
                <a href="register.html" class="btn btn-secondary">ثبت نام</a>
            </div>
            <div class="text-center mt-3">
                <button class="google-btn">ورود با حساب گوگل</button>
            </div>
        </form>
    </div>
</body>
</html>
