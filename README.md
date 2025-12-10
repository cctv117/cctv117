<!-- 彩虹渐变文字 -->
<div align="center">
  <h2 style="
    background: linear-gradient(90deg, 
      #ff0000, #ff9900, #ffff00, #00ff00, 
      #00ffff, #0000ff, #9900ff, #ff00ff
    );
    background-size: 400% 100%;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    animation: rainbow 3s linear infinite;
  ">
    🎨 创意无限 · 代码有形
  </h2>
</div>

<!-- 呼吸灯效果 -->
<div align="center" style="margin:30px 0">
  <div style="
    display:inline-block;
    padding:15px 30px;
    border-radius:25px;
    background:linear-gradient(135deg, #667eea, #764ba2);
    color:white;
    font-weight:bold;
    animation:breathing 2s ease-in-out infinite;
    box-shadow:0 0 20px rgba(102,126,234,0.5);
  ">
    ✨ 动态开发者宣言 ✨
  </div>
</div>

<!-- 旋转加载圈（技术栈轮播） -->
<div align="center" style="position:relative;width:120px;height:120px;margin:0 auto">
  <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/react.svg" width="30" style="position:absolute;top:0;left:50%;transform:translateX(-50%);animation:orbit 6s linear infinite" />
  <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/vue-dot-js.svg" width="30" style="position:absolute;top:50%;right:0;transform:translateY(-50%);animation:orbit 6s linear infinite 1.5s" />
  <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/angular.svg" width="30" style="position:absolute;bottom:0;left:50%;transform:translateX(-50%);animation:orbit 6s linear infinite 3s" />
  <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/node-dot-js.svg" width="30" style="position:absolute;top:50%;left:0;transform:translateY(-50%);animation:orbit 6s linear infinite 4.5s" />
  <div style="width:20px;height:20px;background:#00ffff;border-radius:50%;position:absolute;top:50%;left:50%;transform:translate(-50%,-50%)"></div>
</div>

<!-- 跳动的心形 -->
<div align="center" style="font-size:40px;margin:20px 0">
  <span style="color:#ff0000;animation:heartBeat 1s infinite">❤️</span>
  <span style="color:#ff6b6b;animation:heartBeat 1s infinite 0.2s">💙</span>
  <span style="color:#4ecdc4;animation:heartBeat 1s infinite 0.4s">💚</span>
  <span style="color:#ffd166;animation:heartBeat 1s infinite 0.6s">💛</span>
  <span style="color:#9b5de5;animation:heartBeat 1s infinite 0.8s">💜</span>
</div>

<style>
  @keyframes rainbow {
    0% { background-position: 0% 50%; }
    100% { background-position: 400% 50%; }
  }
  
  @keyframes breathing {
    0%, 100% { transform: scale(1); opacity: 0.8; }
    50% { transform: scale(1.05); opacity: 1; }
  }
  
  @keyframes orbit {
    0% { transform: rotate(0deg) translateX(50px) rotate(0deg); }
    100% { transform: rotate(360deg) translateX(50px) rotate(-360deg); }
  }
  
  @keyframes heartBeat {
    0%, 100% { transform: scale(1); }
    50% { transform: scale(1.2); }
  }
</style>
