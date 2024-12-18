# Binary-Rain
This code creates a visually dynamic and interactive container for Wordpress Landing Page
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Chatbot Revolution</title>
  <style>
    body {
      font-family: 'Roboto', sans-serif;
    }
    .container {
      display: flex;
      justify-content: space-between;
      align-items: center;
      width: 100%;
      padding: 70px;
      height: 60vh;
      margin: 0;
      position: relative;
    }
    .text-section {
      color: white;
      max-width: 70%;
      margin-left: 70px;
      margin-right: 90px;
    }
    .text-section h1 {
      font-size: 36px;
      font-weight: bold;
      margin-bottom: 20px;
    }
    .text-section p {
      font-size: 24px;
      margin-bottom: 20px;
    }
    .text-section .btn {
      background: linear-gradient(135deg, #691EE9, #ff80ab);
      color: white;
      padding: 15px 30px;
      border: none;
      font-size: 18px;
      cursor: pointer;
      border-radius: 50px;
      transition: background 0.3s ease, transform 0.2s ease;
    }
    .text-section .btn:hover {
      background: linear-gradient(135deg, #EFF00C, #ff4081);
      transform: scale(1.1);
    }
    .robot img {
      max-width: 500px;
      height: auto;
      animation: zoom-in 2s infinite alternate;
    }
    @keyframes zoom-in {
      0% {
        transform: scale(1);
      }
      100% {
        transform: scale(1.1);
      }
    }
    .binary-rain {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: 1;
      pointer-events: none;
      overflow: hidden;
    }
    .column {
      position: absolute;
      top: -100%;
      width: 20px;
      text-align: center;
      font-family: 'Courier New', monospace;
      color: lime;
      font-size: 20px;
      animation: fall 5s infinite linear;
    }
    .column span {
      display: block;
    }
    @keyframes fall {
      0% {
        top: -100%;
      }
      100% {
        top: 100%;
      }
    }
    .column:nth-child(1) { left: 5%; animation-duration: 4s; }
    .column:nth-child(2) { left: 15%; animation-duration: 5s; }
    .column:nth-child(3) { left: 25%; animation-duration: 6s; }
    .column:nth-child(4) { left: 35%; animation-duration: 7s; }
    .column:nth-child(5) { left: 45%; animation-duration: 8s; }
    .column:nth-child(6) { left: 55%; animation-duration: 9s; }
    .column:nth-child(7) { left: 65%; animation-duration: 10s; }
    .column:nth-child(8) { left: 75%; animation-duration: 11s; }
    .column:nth-child(9) { left: 85%; animation-duration: 12s; }
    .column:nth-child(10) { left: 95%; animation-duration: 13s; }
    @media (max-width: 768px) {
      .container {
        flex-direction: column;
        padding: 0px;
        height: auto;
      }
      .text-section {
        max-width: 100%;
        margin-left: 0;
        margin-right: 0;
        text-align: center;
      }
      .text-section h1 {
        font-size: 20px;
      }
      .text-section p {
        font-size: 16px;
      }
      .text-section .btn {
        font-size: 14px;
        padding: 10px 20px;
      }
      .robot img {
        max-width: 80%;
        padding-top: 10px;
        padding-left: 60px;
      }
      .binary-rain .column {
        font-size: 15px;
        width: 15px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="binary-rain">
      <div class="column" style="left: 5%;"><span>1</span><span>0</span><span>1</span><span>0</span><span>1</span><span>0</span><span>1</span></div>
      <div class="column" style="left: 15%;"><span>1</span><span>0</span><span>1</span><span>0</span><span>1</span><span>0</span><span>1</span></div>
      <div class="column" style="left: 25%;"><span>1</span><span>0</span><span>1</span><span>0</span><span>1</span><span>0</span><span>1</span></div>
      <div class="column" style="left: 35%;"><span>1</span><span>0</span><span>1</span><span>0</span><span>1</span><span>0</span><span>1</span></div>
      <div class="column" style="left: 45%;"><span>1</span><span>0</span><span>1</span><span>0</span><span>1</span><span>0</span><span>1</span></div>
      <div class="column" style="left: 55%;"><span>1</span><span>0</span><span>1</span><span>0</span><span>1</span><span>0</span><span>1</span></div>
      <div class="column" style="left: 65%;"><span>1</span><span>0</span><span>1</span><span>0</span><span>1</span><span>0</span><span>1</span></div>
      <div class="column" style="left: 75%;"><span>1</span><span>0</span><span>1</span><span>0</span><span>1</span><span>0</span><span>1</span></div>
      <div class="column" style="left: 85%;"><span>1</span><span>0</span><span>1</span><span>0</span><span>1</span><span>0</span><span>1</span></div>
      <div class="column" style="left: 95%;"><span>1</span><span>0</span><span>1</span><span>0</span><span>1</span><span>0</span><span>1</span></div>
    </div>
    <div class="text-section">
      <h1>Revolutionize Your Business with Custom Chatbots by Goophis</h1>
      <p>Boost customer satisfaction, automate workflows, and drive growth with tailor-made chatbot solutions.</p>
      <button class="btn">Get Started Today</button>
    </div>
    <div class="robot">
      <img src="https://testing.levyandco.net/wp-content/uploads/2024/12/Chatbot.webp" alt="Robot" />
    </div>
  </div>
</body>
</html>
