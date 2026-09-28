# sojaehoon.github.i
소지호 첫돌 초대장
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>소지호 첫돌 초대장</title>
    <!-- 명조체 폰트 적용 -->
    <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+KR:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-color: #fdfbf7;
            --text-color: #4a4a4a;
            --highlight: #c1a88b;
        }
        body {
            font-family: 'Noto Serif KR', serif;
            background-color: #eeeeee; /* 배경 여백 색상 */
            color: var(--text-color);
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        .container {
            max-width: 420px; /* 모바일 화면 너비 */
            width: 100%;
            background-color: var(--bg-color);
            padding: 50px 20px;
            box-sizing: border-box;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            min-height: 100vh;
            text-align: center;
        }
        .header {
            margin-bottom: 30px;
        }
        .header h1 {
            font-size: 1.8rem;
            font-weight: 600;
            color: var(--highlight);
            margin-bottom: 5px;
        }
        .header p {
            font-size: 1.1rem;
            letter-spacing: 3px;
            color: #777;
        }
        .photo-area {
            width: 100%;
            aspect-ratio: 4/5;
            background-color: #eae3d9;
            border-radius: 12px;
            margin-bottom: 40px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #8f7d6a;
            font-size: 0.95rem;
            border: 1px dashed #c1a88b;
            overflow: hidden;
        }
        /* 실제 사진이 들어갈 때 사용할 스타일 */
        .photo-area img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        .greeting {
            line-height: 2.2;
            font-size: 1.05rem;
            margin-bottom: 40px;
        }
        .parents {
            font-size: 1.1rem;
            margin-bottom: 50px;
            line-height: 1.8;
            padding: 20px 0;
            border-top: 1px solid #e5d8c8;
            border-bottom: 1px solid #e5d8c8;
        }
        .parents span {
            font-size: 0.9rem;
            color: #888;
            margin-right: 5px;
        }
        .details {
            background-color: #fff;
            padding: 35px 20px;
            border-radius: 12px;
            margin-bottom: 30px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.02);
        }
        .details h2 {
            font-size: 1.2rem;
            margin-bottom: 25px;
            color: var(--highlight);
            letter-spacing: 1px;
        }
        .info-row {
            margin-bottom: 20px;
        }
        .info-row strong {
            display: block;
            font-size: 0.9rem;
            color: #999;
            margin-bottom: 8px;
        }
        .info-row p {
            margin: 0;
            font-size: 1.05rem;
            line-height: 1.5;
            word-break: keep-all;
        }
        .map-btn {
            display: inline-block;
            padding: 12px 30px;
            background-color: var(--highlight);
            color: #fff;
            text-decoration: none;
            border-radius: 30px;
            font-size: 0.95rem;
            margin-top: 15px;
            transition: background-color 0.3s;
        }
        .map-btn:hover {
            background-color: #a89279;
        }
        
        /* 스크롤 시 부드럽게 나타나는 애니메이션 (Fade-in) */
        .fade-in {
            opacity: 0;
            transform: translateY(30px);
            transition: opacity 1s ease-out, transform 1s ease-out;
        }
        .fade-in.visible {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header fade-in">
            <h1>소지호</h1>
            <p>첫 번째 생일</p>
        </div>

        <!-- 사진 영역 -->
        <!-- 지호의 사진을 웹에 올린 후 아래 텍스트 대신 <img src="사진URL" alt="지호 사진"> 을 넣으시면 됩니다 -->
        <div class="photo-area fade-in">
            (여기에 지호의 예쁜 사진이 들어갑니다)
        </div>

        <div class="greeting fade-in">
            열 달의 기다림, 그리고 1년이라는 시간 동안<br>
            저희 부부에게 가장 큰 행복이 되어준 지호.<br><br>
            꼬물거리던 작은 발로<br>새로운 세상을 향해 내딛는 첫걸음에<br>
            소중한 분들의 따뜻한 축복을<br>더해주고 싶습니다.<br><br>
            꼭 걸음하시어 지호의 맑은 웃음을<br>함께 나누어 주세요.
        </div>

        <div class="parents fade-in">
            <span>아빠</span> 소재훈 &nbsp;·&nbsp; <span>엄마</span> 강영혜<br>
            <span>아들</span> 소지호
        </div>

        <div class="details fade-in">
            <h2>초대합니다</h2>
            
            <div class="info-row">
                <strong>일시</strong>
                <p>2026년 10월 31일 토요일 오후 12시</p>
            </div>
            
            <div class="info-row">
                <strong>장소</strong>
                <p>롯데시티호텔구로 3F 씨카페</p>
                <p style="font-size: 0.9rem; color: #666; margin-top: 5px;">서울 구로구 디지털로 300</p>
            </div>
            
            <!-- 길찾기 버튼 (네이버 지도 검색결과로 바로 연결됩니다) -->
            <a href="https://map.naver.com/p/search/%EB%A1%AF%EB%8D%B0%EC%8B%9C%ED%8B%B0%ED%98%B8%ED%85%94%EA%B5%AC%EB%A1%9C%20%EC%94%A8%EC%B9%B4%ED%8E%98" target="_blank" class="map-btn">지도 보기</a>
        </div>
    </div>

    <script>
        // 스크롤 시 요소들이 스르륵 나타나게 하는 자바스크립트 코드입니다.
        document.addEventListener('DOMContentLoaded', () => {
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('visible');
                    }
                });
            }, { threshold: 0.1 });

            document.querySelectorAll('.fade-in').forEach(el => observer.observe(el));
        });
    </script>
</body>
</html>
