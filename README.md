<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>I'm Really Sorry 💛</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #ffecd2, #fcb69f);
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      text-align: center;
    }
    .card {
      background: white;
      padding: 40px;
      border-radius: 20px;
      max-width: 420px;
      box-shadow: 0 20px 40px rgba(0,0,0,0.15);
      animation: fadeIn 1.5s ease;
    }
    h1 {
      color: #ff6b6b;
      margin-bottom: 10px;
    }
    p {
      color: #555;
      font-size: 16px;
      line-height: 1.6;
    }
    button {
      margin-top: 20px;
      padding: 12px 24px;
      border: none;
      border-radius: 30px;
      background: #ff6b6b;
      color: white;
      font-size: 16px;
      cursor: pointer;
      transition: transform 0.2s, background 0.2s;
    }
    button:hover {
      background: #ff4757;
      transform: scale(1.05);
    }
    .heart {
      font-size: 40px;
      animation: beat 1s infinite;
      margin: 15px 0;
    }
    @keyframes beat {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>Hey Pookieeee🎀… I'm Really Sorry 😔</h1>
    <div class="heart">💛</div>
    <p>
      I know you’re upset, and I honestly hate that I’m the reason.
      I never meant to hurt you or make you feel bad.
    </p>
    <p>
      Your silence matters to me more than you think.
      I just want one chance to make things right.
    </p>
    <p>
      If you’re reading this, please know I care about you a lot.
    </p>
    <p style="font-style: italic; color:#777;">
      Even if you’re still mad… just say hi? 🥹
    </p>
    <p><strong>— Karthiiii 💛</strong></p>
    <button onclick="reply()">Text me back? 🥺</button>
    <br/><br/>
    <a href="https://wa.me/?text=Hey%20Karthiiii…%20I%20saw%20your%20page" target="_blank" style="text-decoration:none;">
      <button style="background:#25D366;">Reply on WhatsApp 💬</button>
    </a>
  </div>

  <script>
    function reply() {
      alert("Thank you for opening this 💛\nWhenever you're ready, I’m here.");
    }
  </script>
</body>
</html>
