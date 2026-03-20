<!DOCTYPE html>

<html lang="zh-TW">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>個人履歷</title>

<style>

body{
    font-family: Arial, sans-serif;
    background:#f5f5f5;
    margin:0;
    padding:0;
}

.container{
    width:80%;
    max-width:900px;
    margin:40px auto;
    background:white;
    padding:30px;
    border-radius:10px;
    box-shadow:0 5px 15px rgba(0,0,0,0.1);
}

h1{
    color:#333;
}

h2{
    border-bottom:2px solid #eee;
    padding-bottom:5px;
}

.section{
    margin-bottom:25px;
}

button{
    padding:10px 20px;
    border:none;
    background:#4CAF50;
    color:white;
    border-radius:5px;
    cursor:pointer;
}

button:hover{
    background:#45a049;
}

.hidden{
    display:none;
}

/* 新增照片樣式 */
.profile{
    width:150px;
    height:150px;
    object-fit:cover;
    border-radius:50%;
    display:block;
    margin:0 auto 20px;
}

</style>

</head>

<body>

<div class="container">

<!-- 照片 -->

<img src="images/myphoto.jpg" alt="個人照片" class="profile">

<h1>陳沛慈</h1>
<p>第一學年 • 亞洲大學 • 應屆生</p>
<p>學號:114055028</p>

<div class="section">
<h2>個人簡介</h2>
<p>
喜歡小動物，有耐心，喜歡做模型，
對室內設計與空間創作有興趣，
希望透過實習累積實務經驗。
</p>
</div>

<div class="section">
<h2>學歷</h2>
<p><b>亞洲大學</b></p>
<p>第一學年（在學）</p>
<p>主修：室內設計系</p>
</div>

<div class="section">
<h2>技能</h2>
<ul>
<li>模型製作</li>
<li>繪畫設計圖</li>
<li>空間設計概念</li>
</ul>
</div>

<div class="section">
<h2>經歷</h2>
<p>
目前無正式工作經驗，
可於實習或見習期間快速學習，
並配合輪班與團隊合作。
</p>
</div>

<div class="section">
<h2>聯絡方式</h2>
<p>Email：ann20975099770@gmail.com</p>
<p>電話：0910-221-772</p>
</div>

<button onclick="showMessage()">聯絡我</button>

<p id="message" class="hidden">謝謝觀看我的履歷！</p>

</div>

<script>
function showMessage(){
    document.getElementById("message").classList.remove("hidden");
}
</script>

</body>
</html>

