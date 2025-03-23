# comingsoon
노엘의 팬 페이지 웹사이트로, 최신 음반 정보, 공연 일정, SNS 링크 등을 제공합니다.
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>noel comingsoon</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .button {
            padding: 10px 20px;
            margin: 10px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }
        h2 {
            color: #333;
        }
        .album-category {
            margin-bottom: 20px;
        }
        .album-cover {
            width: 300px;
            height: 300px;
            background-size: cover;
            background-position: center;
            cursor: pointer;
            border: 2px solid #ccc;
            margin: 10px;
        }
    </style>
</head>
<body>
    <h1>노엘 팬 페이지</h1>
    
    <!-- 노엘 공식 인스타그램 버튼 -->
    <button class="button" onclick="window.location.href='https://www.instagram.com/noel____________?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw=='">노엘 공식 인스타그램</button>

    <!-- 팬페이지 인스타그램 버튼 추가 -->
    <button class="button" onclick="window.location.href='https://www.instagram.com/yes.noel?igsh=aXo5NTVqNjNobWph'">팬페이지 인스타그램</button>

    <h2>음반 목록</h2>

    <!-- 정규 앨범 카테고리 -->
    <div class="album-category">
        <h3>정규 앨범</h3>
        <!-- ELLEONOEL 앨범 커버 이미지 버튼 -->
        <div class="album-cover" style="background-image: url('https://upload.wikimedia.org/wikipedia/commons/3/3f/ELLEONOEL_%28Album_cover%29.jpg');" onclick="window.location.href='https://search.naver.com/search.naver?where=nexearch&sm=tab_etc&mra=bkhH&x_csa=%7B%22theme%22%3A%22music_top%22%2C%20%22pkid%22%3A%22634%22%7D&pkid=634&os=16828711&qvt=0&query=ELLEONOEL'"></div>
        <!-- 다른 앨범들 (추가적으로 원하시면 여기에 추가) -->
    </div>

    <!-- EP 카테고리 -->
    <div class="album-category">
        <h3>EP</h3>
        <button class="button" onclick="window.location.href='https://example.com/ep1'">EP 1</button>
        <button class="button" onclick="window.location.href='https://example.com/ep2'">EP 2</button>
    </div>

    <!-- 싱글 카테고리 -->
    <div class="album-category">
        <h3>싱글</h3>
        <button class="button" onclick="window.location.href='https://example.com/single1'">싱글 1</button>
        <button class="button" onclick="window.location.href='https://example.com/single2'">싱글 2</button>
        <button class="button" onclick="window.location.href='https://example.com/single3'">싱글 3</button>
    </div>
</body>
</html>
