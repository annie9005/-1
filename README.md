<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KK94CHFLLe+nY2dmCWGMq91rCGa5gtU4mk92HdvYe+M/SXH301p5ILy+dN9+nJOZ" crossorigin="anonymous">
    <link rel="stylesheet" href="bootest.css">
    <title>首頁</title>
</head>

<body>
    <!--導航欄-->
      <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">BK</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNavDropdown">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="homepage.html">首頁</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" data-bs-toggle="dropdown"  role="button" aria-expanded="false">五十音</a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                  <li><a class="dropdown-item" href="平假名.html">平假名</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="片假名.html">片假名</a></li>


                </ul>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" data-bs-toggle="dropdown"  role="button" aria-expanded="false">單字</a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                  <li><a class="dropdown-item" href="N5單字.html">N5單字</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">N4單字</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">N3單字</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">N2單字</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">N1單字</a></li>
                </ul>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" data-bs-toggle="dropdown" role="button"  aria-expanded="false">文法</a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                  <li><a class="dropdown-item" href="N5文法.html">N5文法</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">N4文法</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">N3文法</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">N2文法</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">N1文法</a></li>
                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="小故事.html">小故事</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" data-bs-toggle="dropdown" role="button"  aria-expanded="false">
                  其他工具
                </a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                  <li><a class="dropdown-item" href="map.html">地圖</a></li>
                  <li><hr class="dropdown-divider"></li>

                  <li><a class="dropdown-item" href="解析器.html">聊天機器人</a></li>

                </ul>
              </li>
            </ul>
          </div>
        </div>
      </nav>
       <!--內容-->
        <div class="col text-center bg-danger"style="--bs-bg-opacity: .5;">


            <div class="col-md-12 py-5 text-black">
              <body>
           
            
              
    <title>自動照片幻燈片</title>
    <style>
        /* 幻燈片容器的樣式 */
        .slideshow-container {
            position: relative;
            max-width: 1500px;
            max-height: 200px;
            margin: 0 auto;
            object-fit: cover;
            top: -50px;
        }

        /* 個別幻燈片的樣式 */
        .mySlides {
            display: none;
            z-index: 1;
        }

        /* 幻燈片圖片的樣式 */
        .mySlides img {
            width: 100%;
        }
    </style>
</head>
<body>

<div class="slideshow-container">
    <div class="mySlides">
        <img src="https://img.onl/ZQ8wQD">
    
    
    </div>

    <div class="mySlides">
        <img src="https://img.onl/9W7bUn">
    </div>

    <div class="mySlides">
        <img src="https://img.onl/zOnA9m">
    </div>
</div>

<script>
    let slideIndex = 0;
    showSlides();

    function showSlides() {
        const slides = document.querySelectorAll('.mySlides');

        for (let i = 0; i < slides.length; i++) {
            slides[i].style.display = 'none';
        }

        slideIndex++;
        if (slideIndex > slides.length) {
            slideIndex = 1;
        }

        slides[slideIndex - 1].style.display = 'block';

        setTimeout(showSlides, 3000); // 切換時間（毫秒）
    }
</script>

</body>

  </style>

              <br><br><br><br><br><br><br><br>
              <h1 style="font-family:DFKai-sb;">
                高校學習日文<br><br>
              </h1>
              <img src="https://img.onl/udaqiL"  style="width:150px;height:50px;position:absolute;top:600px;left:150px;">
              <br>
              <img src="https://img.onl/udaqiL"  style="width:150px;height:50px;position:absolute;top:600px;left:700px;">
              <br>
              <br>
              
              <div>
          <div> <br> <br><br>
          </div>
          </body></div>


        </div>



    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ENjdO4Dr2bkBIFxQpeoTz1HIcje39Wm4jDKdf19U8gI4ddQ3GYNS7NTKfAdVQSZe" crossorigin="anonymous"></script>

  </body>
</html>
