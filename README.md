<!DOCTYPE html>
<html lang="zh-Hant">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>履歷</title>

<style>
body{
  margin:0;
  background:#eaeaea;
  font-family: Arial, sans-serif;
}

/* 整體 */
.container{
  width:900px;
  margin:40px auto;
  display:flex;
  box-shadow:0 10px 30px rgba(0,0,0,0.2);
}

/* 左側 */
.left{
  width:35%;
  background:#2c2c30;
  color:white;
  padding:30px 20px;
  text-align:center;
}

/* 圓形照片 */
.left img{
  width:140px;
  height:140px;
  border-radius:50%;
  object-fit:cover;
  border:5px solid #fff;
  margin-bottom:15px;
}

.name{
  font-size:20px;
  margin:10px 0;
}

.title{
  font-size:13px;
  color:#ccc;
  margin-bottom:20px;
}

/* 左側區塊 */
.left-section{
  margin-top:25px;
  text-align:left;
}

.left-section h3{
  font-size:13px;
  border-bottom:1px solid #888;
  padding-bottom:5px;
  margin-bottom:10px;
}

.left-section p{
  font-size:13px;
  margin:5px 0;
}

/* 右側 */
.right{
  width:65%;
  background:white;
  padding:30px;
}

/* 標題 */
.right h2{
  border-bottom:2px solid #333;
  padding-bottom:5px;
  margin-top:20px;
}

/* 時間軸 */
.timeline{
  position:relative;
  margin-left:20px;
  padding-left:20px;
  border-left:2px solid #999;
}

.timeline-item{
  margin-bottom:20px;
  position:relative;
}

.timeline-item::before{
  content:"";
  width:10px;
  height:10px;
  background:#3498db;
  border-radius:50%;
  position:absolute;
  left:-26px;
  top:5px;
}

.year{
  font-size:13px;
  color:#666;
}

.skills span{
  display:inline-block;
  background:#3498db;
  color:white;
  padding:5px 10px;
  margin:5px 5px 0 0;
  border-radius:5px;
  font-size:12px;
}

button{
  margin-top:20px;
  padding:10px;
  background:#333;
  color:white;
  border:none;
  cursor:pointer;
}

</style>
</head>

<body>

<div class="container">

  <!-- 左 -->
  <div class="left">
    <img src="images/myphoto.jpg">

    <div class="name">陳沛慈</div>
    <div class="title">Interior Design Student</div>

    <div class="left-section">
      <h3>基本資料</h3>
      <p>亞洲大學</p>
      <p>室內設計系</p>
      <p>學號: 114055028</p>
    </div>

    <div class="left-section">
      <h3>聯絡方式</h3>
      <p>Email:<br>ann20975099770@gmail.com</p>
      <p>電話:<br>0910-221-772</p>
    </div>
  </div>

  <!-- 右 -->
  <div class="right">

    <h2>自我介紹</h2>
    <p>
      喜歡小動物，有耐心，喜歡做模型，
      對室內設計與空間創作有興趣，
      希望透過實習累積實務經驗。
    </p>

    <h2>學歷</h2>
    <div class="timeline">
      <div class="timeline-item">
        <div class="year">2025 - 現在</div>
        亞洲大學 室內設計系
      </div>
    </div>

    <h2>技能</h2>
    <div class="skills">
      <span>模型製作</span>
      <span>繪圖設計</span>
      <span>空間規劃</span>
    </div>

    <h2>經歷</h2>
    <div class="timeline">
      <div class="timeline-item">
        無正式工作經驗，具備快速學習與團隊合作能力
      </div>
    </div>

    <button onclick="showMessage()">點我</button>
    <p id="msg"></p>

  </div>

</div>

<script>
function showMessage(){
  document.getElementById("msg").innerText="謝謝觀看我的履歷！";
}
</script>

</body>
</html>
