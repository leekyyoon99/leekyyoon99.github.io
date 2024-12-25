<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>블로그</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            display: flex;
        }
        .sidebar {
            width: 200px;
            background-color: #f4f4f4;
            padding: 20px;
            box-shadow: 2px 0 5px rgba(0,0,0,0.1);
            height: 100vh;
        }
        .content {
            flex: 1;
            padding: 20px;
        }
        .sidebar a {
            display: block;
            padding: 10px;
            color: #333;
            text-decoration: none;
            margin-bottom: 5px;
            border-radius: 4px;
        }
        .sidebar a:hover {
            background-color: #ddd;
        }
    </style>
</head>
<body>
    <div class="sidebar">
        <h2>카테고리</h2>
        <a href="#소개">소개</a>
        <a href="#프로젝트">프로젝트</a>
        <a href="#연락하기">연락하기</a>
    </div>
    <div class="content">
        <h1>안녕하세요!</h1>
        <p>GitHub Pages로 만든 블로그입니다.</p>
        <h2 id="소개">소개</h2>
        <p>GitHub Pages는 무료 호스팅을 제공합니다.</p>
        <h2 id="프로젝트">프로젝트</h2>
        <p>다양한 프로젝트를 공유합니다.</p>
        <h2 id="연락하기">연락하기</h2>
        <p>이메일: your-email@example.com</p>
    </div>
</body>
</html>
