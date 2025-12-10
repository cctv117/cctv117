<!跳动的心形 -->
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
