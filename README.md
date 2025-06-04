<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Visiting Card</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #111;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .card {
      display: flex;
      align-items: center;
      background: linear-gradient(135deg, #3f0d91, #791e94);
      border-radius: 15px;
      padding: 30px;
      color: white;
      width: 450px;
      box-shadow: 0 10px 25px rgba(229, 178, 13, 0.3);
    }

    .profile img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #fff;
      margin-right: 30px;
    }
