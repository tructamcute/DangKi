<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biểu Mẫu Đặt Vé Du Lịch</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
            display: flex;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }
        .form-container {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 100%;
            max-width: 500px;
        }
        .form-container h2 {
            text-align: center;
            margin-bottom: 20px;
            color: #333;
        }
        .form-container label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
            color: #555;
        }
        .form-container input,
        .form-container select,
        .form-container button {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .form-container button {
            background-color: #007BFF;
            color: white;
            border: none;
            cursor: pointer;
            font-size: 16px;
        }
        .form-container button:hover {
            background-color: #0056b3;
        }
    </style>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="form-container">
        <a>Đăng kí thành viên</a>
        <form action="/submit-tour" method="POST">
            <label for="fullname">Họ và Tên</label>
            <input type="text" id="fullname" name="fullname" placeholder="Nhập họ và tên của bạn" required>
            <label for="email">Email</label>
            <input type="email" id="email" name="email" placeholder="Nhập email" required>
            <label for="phone">Số Điện Thoại</label>
            <input type="tel" id="phone" name="phone" placeholder="Nhập số điện thoại" required>
            <label for="date">Ngày sinh</label>
            <input type="date" id="date" name="date" required>
            <button class="btn" onclick="window.location.href='https://tructamcute.github.io/nhom6_12L/'">
                Đặt vé
            </button>
        </form>
    </div>
</body>
</html>
