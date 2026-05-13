<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>测测谁是你的kpop男友</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:"PingFang SC","Microsoft YaHei",sans-serif;
    }

    body{
      min-height:100vh;
      display:flex;
      justify-content:center;
      align-items:center;
      background:linear-gradient(135deg,#ffd6ec,#d9e7ff);
      padding:20px;
    }

    .card{
      width:100%;
      max-width:500px;
      background:rgba(255,255,255,0.9);
      backdrop-filter:blur(10px);
      border-radius:24px;
      padding:35px;
      box-shadow:0 10px 30px rgba(0,0,0,0.1);
      text-align:center;
    }

    h1{
      font-size:32px;
      margin-bottom:18px;
      color:#ff4f9a;
    }

    .desc{
      color:#666;
      margin-bottom:28px;
      line-height:1.7;
    }

    button{
      border:none;
      cursor:pointer;
      transition:0.25s;
    }

    .start-btn,
    .submit-btn{
      background:#ff4f9a;
      color:white;
      padding:14px 28px;
      border-radius:999px;
      font-size:18px;
      font-weight:bold;
    }

    .start-btn:hover,
    .submit-btn:hover{
      transform:translateY(-2px);
      box-shadow:0 8px 18px rgba(255,79,154,0.3);
    }

    .question{
      margin-bottom:28px;
      text-align:left;
    }

    .question h3{
      margin-bottom:14px;
      color:#333;
      font-size:20px;
    }

    .options{
      display:flex;
      gap:12px;
      flex-wrap:wrap;
    }

    .options label{
      flex:1;
      min-width:120px;
      background:#f5f6ff;
      border:2px solid transparent;
      padding:14px;
      border-radius:14px;
      cursor:pointer;
      transition:0.2s;
      text-align:center;
    }

    .options label:hover{
      border-color:#ff4f9a;
      background:#fff0f7;
    }

    input[type="radio"]{
      display:none;
    }

    input[type="radio"]:checked + span{
      color:#ff4f9a;
      font-weight:bold;
    }

    .hidden{
      display:none;
    }

    .result{
      animation:pop 0.5s ease;
    }

    .result h2{
      color:#ff4f9a;
      font-size:30px;
      margin-bottom:18px;
    }

    .boyfriend{
      font-size:42px;
      font-weight:bold;
      color:#222;
      margin-top:10px;
    }

    @keyframes pop{
      from{
        transform:scale(0.8);
        opacity:0;
      }
      to{
        transform:scale(1);
        opacity:1;
      }
    }
  </style>
</head>

<body>

  <div class="card">

    <!-- 首页 -->
    <div id="startPage">
      <h1>测测谁是你的kpop男友</h1>
      <p class="desc">
        只需要回答四道题，看看命运会把谁送到你身边 ✨
      </p>

      <button class="start-btn" onclick="startTest()">
        开始测试
      </button>
    </div>

    <!-- 题目 -->
    <div id="quizPage" class="hidden">

      <div class="question">
        <h3>1. 你喜欢男宝还是女宝？</h3>

        <div class="options">
          <label>
            <input type="radio" name="q1">
            <span>男宝</span>
          </label>

          <label>
            <input type="radio" name="q1">
            <span>女宝</span>
          </label>
        </div>
      </div>

      <div class="question">
        <h3>2. 你喜欢猫塑还是狗塑？</h3>

        <div class="options">
          <label>
            <input type="radio" name="q2">
            <span>猫塑</span>
          </label>

          <label>
            <input type="radio" name="q2">
            <span>狗塑</span>
          </label>
        </div>
      </div>

      <div class="question">
        <h3>3. 你本人是一个温柔的人吗？</h3>

        <div class="options">
          <label>
            <input type="radio" name="q3">
            <span>是</span>
          </label>

          <label>
            <input type="radio" name="q3">
            <span>不是</span>
          </label>
        </div>
      </div>

      <div class="question">
        <h3>4. 你喜欢年上还是年下？</h3>

        <div class="options">
          <label>
            <input type="radio" name="q4">
            <span>年上</span>
          </label>

          <label>
            <input type="radio" name="q4">
            <span>年下</span>
          </label>
        </div>
      </div>

      <button class="submit-btn" onclick="showResult()">
        提交查看结果
      </button>

    </div>

    <!-- 结果 -->
    <div id="resultPage" class="hidden result">
      <h2>恭喜你 🎉</h2>

      <p style="font-size:22px;color:#555;">
        你的kpop男友是
      </p>

      <div class="boyfriend">
        贺鑫隆
      </div>
    </div>

  </div>

  <script>
    function startTest(){
      document.getElementById("startPage").classList.add("hidden");
      document.getElementById("quizPage").classList.remove("hidden");
    }

    function showResult(){
      document.getElementById("quizPage").classList.add("hidden");
      document.getElementById("resultPage").classList.remove("hidden");
    }
  </script>

</body>
</html>
