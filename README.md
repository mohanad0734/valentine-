
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Valentine 💖</title>

  <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">

  <style>
    body {
      background: pink;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: Arial, sans-serif;
    }

    .box {
      text-align: center;
      background: white;
      padding: 30px;
      border-radius: 15px;
      width: 90%;
      max-width: 400px;
    }

    button {
      padding: 10px 20px;
      margin: 10px;
      font-size: 18px;
      cursor: pointer;
    }

    .hidden {
      display: none;
    }

    .game-text {
      font-family: 'Press Start 2P', cursive;
      font-size: 14px;
      color: red;
      margin-top: 15px;
    }

    .retry-box {
      margin-top: 20px;
      padding: 15px;
      border: 3px solid black;
      cursor: pointer;
      font-family: 'Press Start 2P', cursive;
      font-size: 14px;
      color: red;
      margin-top: 15px;
    }
    
     .go-back {
      margin-top: 20px;
      padding: 15px;
      border: 3px solid black;
      font-family: 'Press Start 2P', cursive;
      cursor: pointer;
    }

  </style>
</head>
<body>

<div class="box">

  <h1 id="title">سوسي Will you be my Valentine? 💘</h1>
<img alt="bonfos" height="223" src="WhatsApp%20Sticker%202026-02-02%20at%207.43.11%20PM.11%20PM.png" width="225">
  <div id="choices">
    <button onclick="yes()">Yes ❤️</button>
    <button onclick="no()">No 💔</button>
  </div>

   <div id="yesText" class="hidden">
  <p>  سوسي حياتي الصراحة ما بعرف شو بدي اكتب بس أنا بتذكر انو انتي بتحبي لما حد يكتبلك فقرة طويلة و هيك فا بس حابب احكي و احاول اعبر عن قديش أنا بحبك و قديش انتي مهمة الي انتي من احلا البنات لاشفتها في حياتي و جد بتمنى انو نضل مع بعض للابد لانو انتي من احلا الأشياء الي صارو بحياتي و بعرف اني حكيتلك هاد الحكي ألف مرا بس رح ارجع أعيد و أضل أعيد حتى أموت بحبك و بحبك شعرك الحلو عيونك الحلوين الي جد بقدر أضل صافن فيهم ساعات و أضيع جواتهم وانا ما عندي مانع و غمازاتك الحلوين المشكلة انو كلمة حلوة و حلوين جد ما بكفو عشان أوصف جمالك ولا اي كلمة في اللغة العربية رح تكون كفية اني أوصف حبي إلك 
  </p>	
 <div class="go-back" onclick="goback()">
      GO BACK</div> </div>
      
  <div id="noScreen" class="hidden">
     <h1>بشرفك؟</h1>

    <div class="retry-box" onclick="reset()">
      TRY AGAIN
    </div>
  </div>


<script>
  function yes() {
    document.getElementById("choices").classList.add("hidden");
    document.getElementById("noScreen").classList.add("hidden");
    document.getElementById("yesText").classList.remove("hidden");
  }

  function no() {
    document.getElementById("choices").classList.add("hidden");
    document.getElementById("yesText").classList.add("hidden");
    document.getElementById("noScreen").classList.remove("hidden");
  }

  function reset() {
    document.getElementById("choices").classList.remove("hidden");
    document.getElementById("yesText").classList.add("hidden");
    document.getElementById("noScreen").classList.add("hidden");
  }
  
  function goback() {
    document.getElementById("choices").classList.remove("hidden");
    document.getElementById("yesText").classList.add("hidden");
    document.getElementById("noScreen").classList.add("hidden");
  }

</script>

</div>
<p>&nbsp;</p>

</body>
</html>
