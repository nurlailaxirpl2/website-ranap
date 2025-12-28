<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Login RME Klinik</title>
    <style>
        body { font-family: 'Segoe UI', sans-serif; background: #eef2f7; display: flex; justify-content: center; align-items: center; height: 100vh; margin: 0; }
        .login-box { background: white; padding: 40px; border-radius: 12px; box-shadow: 0 10px 25px rgba(0,0,0,0.1); width: 350px; }
        h2 { text-align: center; color: #333; margin-bottom: 30px; }
        .input-group { margin-bottom: 20px; }
        label { display: block; margin-bottom: 8px; font-weight: 600; color: #555; }
        input { width: 100%; padding: 12px; border: 1px solid #ddd; border-radius: 8px; box-sizing: border-box; }
        button { width: 100%; padding: 12px; background: #3498db; color: white; border: none; border-radius: 8px; cursor: pointer; font-size: 16px; font-weight: bold; }
        button:hover { background: #2980b9; }
    </style>
</head>
<body>
    <div class="login-box">
        <h2>Login Sistem RME</h2>
        <form action="pendaftaran.html">
            <div class="input-group">
                <label>Username</label>
                <input type="text" required placeholder="ID Petugas">
            </div>
            <div class="input-group">
                <label>Password</label>
                <input type="password" required placeholder="******">
            </div>
            <button type="submit">MASUK KE PENDAFTARAN</button>
        </form>
    </div>
</body>
</html>
