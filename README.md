<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Sport's by Jakaria</title>
  <style>
    body {
      background: #181818;
      margin: 0;
      font-family: Arial, sans-serif;
    }
    .header {
      background: #000;
      color: #fff;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 14px 18px;
    }
    .header-left {
      display: flex;
      align-items: center;
      gap: 12px;
    }
    .logo-link {
      display: inline-block;
    }
    .logo-img {
      width: 32px;
      height: 32px;
      background: #fff;
      border-radius: 50%;
      padding: 3px;
      margin-right: 2px;
      box-shadow: 0 1px 4px #0003;
    }
    .site-name {
      color: #14b800;
      font-size: 1.5em;
      font-weight: bold;
      letter-spacing: 1px;
    }
    .owner {
      background: #fff;
      color: #000;
      border-radius: 8px;
      padding: 7px 18px;
      font-weight: bold;
      font-size: 1em;
      border: 2px solid #14b800;
      transition: background 0.2s, color 0.2s;
    }
    .owner span {
      color: #14b800;
    }
    .owner:hover {
      background: #14b800;
      color: #fff;
    }
    .content {
      max-width: 430px;
      margin: 32px auto 0 auto;
      background: #232323;
      border-radius: 14px;
      box-shadow: 0 6px 30px #0005;
      padding: 25px 12px 30px 12px;
      text-align: center;
    }
    .subtitle {
      color: #00eaff;
      font-size: 1.1em;
      margin-bottom: 10px;
      font-weight: bold;
    }
    .desc {
      color: #fff;
      margin-bottom: 18px;
      font-size: 1.05em;
    }
    .servers {
      display: flex;
      flex-direction: column;
      gap: 12px;
      margin: 18px 0;
    }
    .server-link {
      background: #14b800;
      color: #fff;
      padding: 10px 0;
      border-radius: 7px;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.08em;
      transition: background 0.2s;
      box-shadow: 0 2px 8px #0002;
    }
    .server-link:hover {
      background: #0e8600;
    }
    @media (max-width: 500px) {
      .content { max-width: 98vw; }
      .site-name { font-size: 1.1em; }
    }
  </style>
</head>
<body>
  <div class="header">
    <div class="header-left">
      <a class="logo-link" href="https://t.me/sylhetystream" target="_blank">
        <img class="logo-img" src="https://upload.wikimedia.org/wikipedia/commons/8/82/Telegram_logo.svg" alt="Telegram">
      </a>
      <a class="logo-link" href="https://facebook.com" target="_blank">
        <img class="logo-img" src="https://upload.wikimedia.org/wikipedia/commons/5/51/Facebook_f_logo_%282019%29.svg" alt="Facebook">
      </a>
      <span class="site-name">Sport's by Jakaria</span>
    </div>
    <div class="owner">owner by <span>Jakaria</span></div>
  </div>
  <div class="content">
    <div class="subtitle">Football & Cricket Live</div>
    <div class="desc">সম্পূর্ণ খেলা দেখুন ফ্রীতে</div>
    <div class="servers">
      <a class="server-link" href="https://edge3-moblive.yuppcdn.net/drm/smil:tencricketdrm.smil/index.m3u8" target="_blank">Server 1</a>
      <a class="server-link" href="https://edge3-moblive.yuppcdn.net/drm/smil:tencricketdrm.smil/index.m3u8" target="_blank">Server 2</a>
      <a class="server-link" href="https://live-stream.iblups.com/video/68fccd3c75e206b5a341d181308a4c130a2de6bd.m3u8" target="_blank">Server 3</a>
      <a class="server-link" href="https://dai.google.com/linear/hls/event/HynNobMPSu6nQCgpxsK0lQ/master.m3u8" target="_blank">Server 4</a>
    </div>
  </div>
</body>
</html>
