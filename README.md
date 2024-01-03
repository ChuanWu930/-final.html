final.html
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>組裝電腦教學</title>
    <link href="https://cdn.bootcss.com/flexslider/2.6.3/flexslider.min.css" rel="stylesheet">
    <script src="https://cdn.bootcss.com/jquery/2.2.2/jquery.min.js"></script>
    <script src="https://cdn.bootcss.com/flexslider/2.6.3/jquery.flexslider-min.js"></script>
    <script>
        $(window).load(function() {
            $('.flexslider').flexslider({
                animation: "slide",
                rtl: true
            });
        });
    </script>
    <style>
        /* ...（您提供的原始樣式）... */
        
        /* 新增電腦教學區塊樣式 */
        .tutorial {
            background-color: #f8f8f8;
            padding: 40px;
        }
        .tutorial h2 {
            font-size: 25px;
            color: rgb(50,51,52);
            margin-bottom: 20px;
        }
        .tutorial ul {
            list-style-type: none;
            padding: 0;
        }
        .tutorial li {
            margin-bottom: 15px;
        }

        /* 新增價格區間樣式 */
        .price-range {
            background-color: #eaeaea;
            padding: 40px;
        }
        .price-range h2 {
            font-size: 25px;
            color: rgb(50,51,52);
            margin-bottom: 20px;
        }
        .price-list {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }
        .price-item {
            text-align: center;
            padding: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        /* ...（其他樣式）... */
    </style>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>組裝電腦教學</title>
    <link href="https://cdn.bootcss.com/flexslider/2.6.3/flexslider.min.css" rel="stylesheet">
    <script src="https://cdn.bootcss.com/jquery/2.2.2/jquery.min.js"></script>
    <script src="https://cdn.bootcss.com/flexslider/2.6.3/jquery.flexslider-min.js"></script>
    <script>
        $(window).load(function() {
            $('.flexslider').flexslider({
                animation: "slide",
                rtl: true
            });
        });
        $(document).ready(function(){
            $(".price-item").click(function(){
                var target = $(this).text();
                var targetId = "#part-" + target;
                $('html, body').animate({
                    scrollTop: $(targetId).offset().top - 100
                }, 1000);
            });
        });
    </script>
    <style>
        

        .tutorial {
            background-color: #f8f8f8;
            padding: 40px;
        }
        .tutorial h2 {
            font-size: 25px;
            color: rgb(50,51,52);
            margin-bottom: 20px;
        }
        .tutorial ul {
            list-style-type: none;
            padding: 0;
        }
        .tutorial li {
            margin-bottom: 15px;
        }

        /* 新增價格區間樣式 */
        .price-range {
            background-color: #eaeaea;
            padding: 40px;
        }
        .price-range h2 {
            font-size: 25px;
            color: rgb(50,51,52);
            margin-bottom: 20px;
        }
        .price-list {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }
        .price-item {
            cursor: pointer; 
            text-align: center;
            padding: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        /* 新增電腦零件區塊樣式 */
        .part {
            background-color: #fff;
            padding: 40px;
            margin: 20px 0;
        }
        .part h3 {
            font-size: 20px;
            color: rgb(50,51,52);
            margin-bottom: 20px;
        }

    </style>
</head>
<body>
    <div class="top">

    </div>
    <div class="nav">   

    </div>
    <div class="slider">
        <div class="flexslider">
            <ul class="slides">
                <li><img src="https://www.nvidia.com/content/dam/en-zz/Solutions/about-nvidia/logo-and-brand/01-nvidia-logo-horiz-500x200-2c50-p@2x.png" /></li>
                <li><img src="https://s4.itho.me/sites/default/files/styles/picture_size_large/public/amd_v2_3.jpg?itok=eWsirx1KG" /></li>
                <li><img src="https://www.macnica.com/apac/galaxy/zh_tw/products-support/products/intel-fpga.coreimg.jpeg/structure/_jcr_content/root/container/container/bannerimage/1678869825274/intel-fpga-logo.jpeg" /></li>
            </ul>
        </div>
    </div>
    <div class="banner" id="introduction">

    </div>
    <div class="faculty" id="faculty">

    </div>
    <div class="tutorial" id="tutorial">
        <h2>組裝電腦教學</h2>
        <ul>
            <li>了解不同電腦零件的功能和作用。</li>
            <li>選擇適合您需求的 CPU、顯示卡、記憶體等零件。</li>
            <li>學習如何安裝主機板、連接電源供應器等基本組裝步驟。</li>
            <li>調校 BIOS 設定和進行基本的作業系統安裝。</li>
            <li>優化電腦散熱、管理電纜，使您的電腦看起來整潔。</li>
        </ul>
    </div>
    <div class="price-range" id="price-range">
        <h2>價格區間</h2>
        <div class="price-list">
            <div class="price-item">1萬</div>
            <div class="price-item">3萬</div>
            <div class="price-item">4萬</div>
            <div class="price-item">7萬</div>
        </div>
    </div>

    <div class="part" id="part-1萬">
        <h3>電腦零件 1 ~ 2萬價格區間</h3>
        <li>i3文書機／1~2萬
基本上，如果說只要求電腦具備一般文書上網需求，像是查找資料、文書撰寫、簡單的影像處理等，小唐會建議組裝一台i3文書機的電腦菜單就很夠用了，預算會介於1-2萬之間。

而在記憶體選擇上，如果想要使用簡單的PS、AI修圖軟體的話，一般來說，16G和32G的記憶體電腦菜單都算夠用的。不過，如果你在處理影像時，會習慣一次性開啟多個圖檔的話，小唐會建議可以升級到16G的電腦菜單喔！

另外，因1-2萬文書機CPU有內顯，如果只是簡單繪圖的話，建議可以先用內顯跑跑看，若效果覺得不足再加裝也可以喔！
</li>
    </div>

    <div class="part" id="part-3萬">
        <h3>電腦零件 3 ~ 4萬價格區間</h3>
        <li>I5遊戲機／3~4萬
想打中度遊戲又想繪圖的你，如果預算介於3-4萬的話，小唐會建議你組裝I5遊戲機的電腦菜單。另外，3-4萬以上的遊戲機菜單會需要增加顯示卡，因顯示卡的價位跟效果有著絕對的關係，如果你想要有更好的遊戲體驗，可以選擇好一些的顯示卡。

至於繪圖需求的部分，如果你是需要3D繪畫的話，會建議升級到32G以上。但是，如果你的需求是2D繪製時，16G就夠用。
    </li>
    </div>
    <div class="part" id="part-4萬">
        <h3>電腦零件 4 ~ 5萬價格區間</h3>
        <li>I7遊戲機／4~5萬
如果你使用電腦的用途不僅想要玩遊戲，還想要剪輯影片、繪圖，這時候小唐會建議你組裝I7的遊戲機電腦菜單。因CPU有大小核混合的架構，在系統選擇上可以安裝Win11，優點是能夠處理一些大小核多工分配問題，預算會介於4-5萬之間。在散熱器功能上，由於I7原廠散熱器的功效普遍客人反應不佳，我們會建議額外加裝塔扇替代原廠散熱器的電腦菜單。
    </li>
    </div>
    <div class="part" id="part-7萬">
        <h3>電腦零件 7 ~ 8萬萬價格區間</h3>
        <li>I9遊戲機／7~8萬
想要很順暢地玩高階遊戲，且預算8萬以內的話，小唐建議你直接組裝I9的遊戲機，可以直接使用32G以上，像是：16G*2條或是32G*2條。

而在散熱器上， 使用現階段散熱最好的散熱產品，直接上到水冷，成效會更好
    </li>
    </div>
 

    <div class="contact" id="about">

    </div>
    <div class="footer">

    </div>
    <h2>相關資訊</h2>
                <div class="infos">
                    <div class="left">
                        <b>原價屋</b>
                        <span>32042桃園市中壢區中正路332號</span>
                        <b> 電話:032706322</b>
                    </div>
                    <div class="right">
                        <iframe src="https://www.google.com/maps/place/%E5%8E%9F%E5%83%B9%E5%B1%8B-%E4%B8%AD%E5%A3%A2%E4%B8%AD%E6%AD%A3%E5%BA%97/@24.9554781,121.2147526,17z/data=!3m1!4b1!4m6!3m5!1s0x3468224b2e396f9f:0xf05fdd2d4e2764b7!8m2!3d24.9554781!4d121.2173275!16s%2Fg%2F12ml2y37n?entry=ttu" frameborder="0" style="border:0" allowfullscreen></iframe>
                    </div>
                </div>
</body>
</html>
