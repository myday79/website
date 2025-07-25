<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!-- SEO 메타 태그 -->
    <title>Showpiece 전문몰 - 최고의 상품을 최저가로 만나보세요</title>
    <meta name="description" content="Showpiece 전문몰에서 엄선된 전자제품, 생활용품, 의류 등을 최저가로 만나보세요. 빠른 배송과 품질 보장으로 안전한 쇼핑을 경험하세요.">
    <meta name="keywords" content="Showpiece, 온라인쇼핑몰, 전자제품, 생활용품, 의류, 최저가, 할인, 빠른배송">
    <meta name="author" content="Showpiece 전문몰">
    <meta name="robots" content="index, follow">
    <meta name="googlebot" content="index, follow">
    
    <!-- Open Graph 메타 태그 (소셜 미디어 공유용) -->
    <meta property="og:title" content="Showpiece 전문몰 - 최고의 상품을 최저가로">
    <meta property="og:description" content="엄선된 상품들을 최저가로 만나보세요. 빠른 배송과 품질 보장!">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://yoursite.com">
    <meta property="og:image" content="https://yoursite.com/og-image.jpg">
    <meta property="og:site_name" content="Showpiece 전문몰">
    <meta property="og:locale" content="ko_KR">
    
    <!-- Twitter Card 메타 태그 -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Showpiece 전문몰 - 최고의 상품을 최저가로">
    <meta name="twitter:description" content="엄선된 상품들을 최저가로 만나보세요. 빠른 배송과 품질 보장!">
    <meta name="twitter:image" content="https://yoursite.com/twitter-image.jpg">
    
    <!-- 구조화된 데이터 (JSON-LD) -->
    <script type="application/ld+json">
    {
        "@context": "https://schema.org",
        "@type": "WebSite",
        "name": "Showpiece 전문몰",
        "description": "최고의 상품을 최저가로 제공하는 Showpiece 전문 쇼핑몰",
        "url": "https://yoursite.com",
        "potentialAction": {
            "@type": "SearchAction",
            "target": "https://yoursite.com/?search={search_term_string}",
            "query-input": "required name=search_term_string"
        },
        "publisher": {
            "@type": "Organization",
            "name": "Showpiece 전문몰",
            "logo": {
                "@type": "ImageObject",
                "url": "https://yoursite.com/logo.png"
            }
        }
    }
    </script>
    
    <!-- canonical URL -->
    <link rel="canonical" href="https://yoursite.com">
    
    <!-- Favicon -->
    <link rel="icon" type="image/x-icon" href="/favicon.ico">
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
    
    <!-- Google Analytics (GA4) - 🔧 여기에 본인의 측정 ID를 입력하세요 -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
    <script>
        window.dataLayer = window.dataLayer || [];
        function gtag(){dataLayer.push(arguments);}
        gtag('js', new Date());
        gtag('config', 'GA_MEASUREMENT_ID'); // 🔧 실제 측정 ID로 변경 (예: G-XXXXXXXXXX)
    </script>
    
    <!-- Google AdSense - 🔧 여기에 본인의 AdSense 게시자 ID를 입력하세요 -->
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXXXXXXXXXX" crossorigin="anonymous"></script>
    
    <!-- 🔧 검색 엔진 등록 인증 메타 태그들 - 각 검색 엔진에서 제공받은 코드로 교체하세요 -->
    <!-- Google Search Console 인증 메타 태그 -->
    <meta name="google-site-verification" content="YOUR_GOOGLE_VERIFICATION_CODE">
    
    <!-- 네이버 서치어드바이저 인증 메타 태그 -->
    <meta name="naver-site-verification" content="YOUR_NAVER_VERIFICATION_CODE">
    
    <!-- 다음 검색등록 인증 메타 태그 -->
    <meta name="daum-site-verification" content="YOUR_DAUM_VERIFICATION_CODE">
    
    <!-- Bing Webmaster Tools 인증 메타 태그 -->
    <meta name="msvalidate.01" content="YOUR_BING_VERIFICATION_CODE">
    
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        /* CSS 변수 정의 */
        :root {
            --primary-color: #cc6b49;
            --secondary-color: #f5f5f5;
            --accent-color: #8b4513;
            --text-color: #333;
            --light-gray: #e9e9e9;
            --white: #ffffff;
            --success-color: #28a745;
            --warning-color: #ffc107;
            --danger-color: #dc3545;
            --info-color: #17a2b8;
        }

        /* 기본 스타일 */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--secondary-color);
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* 헤더 */
        header {
            background: linear-gradient(135deg, var(--primary-color), var(--accent-color));
            color: white;
            padding: 1rem 0;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 1rem;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            text-decoration: none;
            color: white;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .nav-buttons {
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
            justify-content: center;
        }

        /* 버튼 기본 스타일 */
        .btn {
            padding: 10px 20px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-weight: 500;
            transition: all 0.3s ease;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 0.5rem;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
        }

        .btn-primary {
            background-color: var(--white);
            color: var(--primary-color);
        }

        .btn-primary:hover {
            background-color: var(--light-gray);
        }

        .btn-secondary {
            background-color: var(--primary-color);
            color: white;
            border: 2px solid white;
        }

        .btn-secondary:hover {
            background-color: white;
            color: var(--primary-color);
        }

        .btn-success {
            background-color: var(--success-color);
            color: white;
        }

        .btn-success:hover {
            background-color: #218838;
        }

        .btn-danger {
            background-color: var(--danger-color);
            color: white;
        }

        .btn-danger:hover {
            background-color: #c82333;
        }

        .btn-info {
            background-color: var(--info-color);
            color: white;
        }

        .btn-info:hover {
            background-color: #138496;
        }

        .btn-small {
            padding: 8px 16px;
            font-size: 0.9rem;
        }

        /* SEO 설정 버튼 */
        .btn-seo {
            background: linear-gradient(135deg, #4285f4, #34a853);
            color: white;
            border: none;
            border-radius: 12px;
            padding: 15px 25px;
            font-size: 1rem;
            font-weight: 600;
            box-shadow: 0 4px 15px rgba(66, 133, 244, 0.3);
            transition: all 0.3s ease;
            cursor: pointer;
        }

        .btn-seo:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(66, 133, 244, 0.4);
            background: linear-gradient(135deg, #34a853, #4285f4);
        }

        /* 상품 등록 버튼들을 위한 특별 스타일 */
        .quick-add-buttons {
            display: flex;
            gap: 1rem;
            justify-content: center;
            margin: 2rem 0;
            flex-wrap: wrap;
        }

        .btn-quick-add {
            background: linear-gradient(135deg, var(--success-color), #20c997);
            color: white;
            border: none;
            border-radius: 12px;
            padding: 20px 30px;
            font-size: 1.1rem;
            font-weight: 600;
            box-shadow: 0 4px 15px rgba(40, 167, 69, 0.3);
            transition: all 0.3s ease;
            min-width: 250px;
            text-align: center;
            cursor: pointer;
        }

        .btn-quick-add:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(40, 167, 69, 0.4);
            background: linear-gradient(135deg, #20c997, var(--success-color));
        }

        .btn-quick-add i {
            font-size: 1.5rem;
            margin-bottom: 0.5rem;
            display: block;
        }

        /* 메인 콘텐츠 */
        main {
            flex-grow: 1;
            padding: 2rem 0;
        }

        .welcome-section {
            background: white;
            padding: 3rem 2rem;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            margin-bottom: 2rem;
            text-align: center;
        }

        .welcome-section h1 {
            color: var(--primary-color);
            margin-bottom: 1rem;
            font-size: 2.5rem;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 0.75rem;
        }

        .welcome-section p {
            font-size: 1.2rem;
            color: #666;
            margin-bottom: 2rem;
        }

        .welcome-badges {
            display: flex;
            gap: 1rem;
            justify-content: center;
            flex-wrap: wrap;
        }

        .welcome-badge {
            background: var(--primary-color);
            color: white;
            padding: 0.5rem 1rem;
            border-radius: 20px;
            font-size: 0.9rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .welcome-badge.success {
            background: var(--success-color);
        }

        .welcome-badge.warning {
            background: var(--warning-color);
        }

        /* 검색 및 필터 */
        .search-filter-section {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            margin-bottom: 2rem;
        }

        .search-container {
            display: flex;
            gap: 1rem;
            flex-wrap: wrap;
            align-items: center;
        }

        .search-input, .filter-select {
            flex: 1;
            min-width: 250px;
            padding: 12px;
            border: 2px solid var(--light-gray);
            border-radius: 5px;
            font-size: 1rem;
            transition: border-color 0.3s ease;
        }

        .search-input:focus, .filter-select:focus {
            border-color: var(--primary-color);
            outline: none;
        }

        .filter-select {
            min-width: 150px;
        }

        /* 상품 그리드 */
        .products-section {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            margin-bottom: 2rem;
        }

        .section-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 2rem;
            flex-wrap: wrap;
            gap: 1rem;
        }

        .section-title {
            color: var(--primary-color);
            font-size: 1.8rem;
            font-weight: bold;
            display: flex;
            align-items: center;
            gap: 0.75rem;
        }

        .products-grid {
            display: grid;
            /* 한 줄에 3개의 상품을 고정적으로 배열 */
            grid-template-columns: repeat(3, 1fr); 
            gap: 2rem;
            margin-top: 2rem;
        }

        .product-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border: 1px solid var(--light-gray);
        }

        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.15);
        }

        .product-image {
            width: 100%;
            height: 200px;
            object-fit: cover;
            background-color: var(--secondary-color);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3rem;
            color: var(--primary-color);
            cursor: pointer; /* 라이트박스 기능 추가를 위해 커서 변경 */
        }

        .product-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .product-info {
            padding: 1.5rem;
        }

        .product-title {
            font-size: 1.1rem;
            font-weight: bold;
            margin-bottom: 0.5rem;
            color: var(--text-color);
            line-height: 1.3;
            overflow: hidden;
            text-overflow: ellipsis;
            display: -webkit-box;
            -webkit-line-clamp: 2;
            -webkit-box-orient: vertical;
        }

        .product-price {
            font-size: 1.3rem;
            font-weight: bold;
            color: var(--primary-color);
            margin-bottom: 1rem;
        }

        .product-category-tag {
            background: var(--primary-color);
            color: white;
            padding: 0.3rem 0.8rem;
            border-radius: 15px;
            font-size: 0.8rem;
            display: inline-block;
            margin-bottom: 1rem;
        }

        .product-description {
            color: #666;
            font-size: 0.9rem;
            margin-bottom: 1rem;
            line-height: 1.4;
            overflow: hidden;
            text-overflow: ellipsis;
            display: -webkit-box;
            -webkit-line-clamp: 3;
            -webkit-box-orient: vertical;
        }

        .product-actions {
            display: flex;
            gap: 0.5rem;
            flex-wrap: wrap;
        }

        /* 관리자 패널 */
        .admin-panel {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            margin-bottom: 2rem;
            display: none;
        }

        .admin-stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
            margin-bottom: 2rem;
        }

        .stat-card {
            background: linear-gradient(135deg, var(--primary-color), var(--accent-color));
            color: white;
            padding: 1.5rem;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .stat-number {
            font-size: 2rem;
            font-weight: bold;
            margin-bottom: 0.5rem;
        }

        .stat-label {
            font-size: 0.9rem;
            opacity: 0.9;
        }

        /* 상품 폼 */
        .product-form-section {
            background: white; /* 배경색 변경 */
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1); /* 그림자 추가 */
            margin-bottom: 2rem;
            /* display: none; <-- 이 속성을 제거하여 hidden 클래스에만 의존하도록 함 */
        }

        .form-group {
            margin-bottom: 1.5rem;
        }

        .form-label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 500;
            color: var(--text-color);
        }

        .form-input, .form-textarea, .form-select { /* .form-select 추가 */
            width: 100%;
            padding: 12px;
            border: 2px solid var(--light-gray);
            border-radius: 5px;
            font-size: 1rem;
            transition: border-color 0.3s ease;
        }

        .form-input:focus, .form-textarea:focus, .form-select:focus {
            border-color: var(--primary-color);
            outline: none;
        }

        .form-textarea {
            resize: vertical;
            min-height: 100px;
        }

        .form-actions {
            display: flex;
            gap: 1rem;
            flex-wrap: wrap;
        }
        
        /* LLM 기능 추가를 위한 스타일 */
        .llm-feature-group {
            display: flex;
            align-items: center;
            gap: 10px;
            margin-top: 0.5rem;
        }

        .llm-loading-spinner {
            border: 4px solid #f3f3f3;
            border-top: 4px solid var(--primary-color);
            border-radius: 50%;
            width: 20px;
            height: 20px;
            animation: spin 1s linear infinite;
            display: none; /* 기본적으로 숨김 */
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        /* 파일 업로드 스타일 */
        .file-upload-area {
            border: 2px dashed var(--light-gray);
            border-radius: 10px;
            padding: 2rem;
            text-align: center;
            transition: all 0.3s ease;
            cursor: pointer;
            background-color: #fafafa;
        }

        .file-upload-area:hover {
            border-color: var(--primary-color);
            background-color: #f0f8ff;
        }

        .file-upload-area.dragover {
            border-color: var(--success-color);
            background-color: #f0fff4;
        }

        .file-upload-icon {
            font-size: 3rem;
            color: var(--primary-color);
            margin-bottom: 1rem;
        }

        .image-preview {
            max-width: 200px;
            max-height: 200px;
            border-radius: 10px;
            margin: 1rem auto;
            display: none;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        /* SEO 설정 모달 */
        .seo-modal {
            display: none;
            position: fixed;
            z-index: 1000;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0,0,0,0.5);
            justify-content: center;
            align-items: center;
            padding: 20px;
            opacity: 0;
            transition: opacity 0.3s ease;
        }

        .seo-modal.show {
            display: flex;
            opacity: 1;
        }

        .seo-modal-content {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            width: 90%;
            max-width: 800px;
            max-height: 90vh;
            overflow-y: auto;
            position: relative;
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);
            transform: translateY(-20px);
            transition: transform 0.3s ease;
        }

        .seo-modal.show .seo-modal-content {
            transform: translateY(0);
        }

        .seo-section {
            margin-bottom: 2rem;
            padding: 1.5rem;
            background: #f8f9fa;
            border-radius: 10px;
            border-left: 4px solid var(--primary-color);
        }

        .seo-section h3 {
            color: var(--primary-color);
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .seo-instruction {
            background: #e3f2fd;
            padding: 1rem;
            border-radius: 8px;
            margin-bottom: 1rem;
            border-left: 4px solid var(--info-color);
        }

        .seo-instruction strong {
            color: var(--info-color);
        }

        .code-block {
            background: #f1f3f4;
            padding: 1rem;
            border-radius: 8px;
            font-family: 'Courier New', monospace;
            font-size: 0.9rem;
            border: 1px solid #e0e0e0;
            margin: 1rem 0;
            overflow-x: auto;
        }

        .verification-input {
            width: 100%;
            padding: 10px;
            border: 2px solid var(--light-gray);
            border-radius: 5px;
            font-family: 'Courier New', monospace;
            font-size: 0.9rem;
        }

        .verification-input:focus {
            border-color: var(--primary-color);
            outline: none;
        }

        /* 모달 */
        .modal {
            display: none;
            position: fixed;
            z-index: 1000;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0,0,0,0.5);
            justify-content: center;
            align-items: center;
            padding: 20px;
            opacity: 0;
            transition: opacity 0.3s ease;
        }

        .modal.show {
            display: flex;
            opacity: 1;
        }

        .modal-content {
            background-color: white;
            padding: 2rem;
            border-radius: 10px;
            width: 90%;
            max-width: 600px;
            max-height: 90vh;
            overflow-y: auto;
            position: relative;
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
            transform: translateY(-20px);
            transition: transform 0.3s ease;
        }

        .modal.show .modal-content {
            transform: translateY(0);
        }

        .close-button {
            color: #aaa;
            float: right;
            font-size: 28px;
            font-weight: bold;
            cursor: pointer;
            position: absolute;
            top: 15px;
            right: 20px;
        }

        .close-button:hover,
        .close-button:focus {
            color: var(--primary-color);
            text-decoration: none;
        }

        /* 푸터 */
        footer {
            background: var(--text-color);
            color: white;
            text-align: center;
            padding: 2rem 0;
            margin-top: auto;
            position: relative;
        }

        /* 메시지 알림 */
        .message-alert {
            padding: 1rem;
            margin-bottom: 1.5rem;
            border-radius: 8px;
            color: white;
            font-weight: bold;
            text-align: center;
            opacity: 0;
            transition: opacity 0.3s ease;
        }

        .message-alert.show {
            opacity: 1;
        }

        .message-alert.success {
            background-color: var(--success-color);
        }

        .message-alert.error {
            background-color: var(--danger-color);
        }

        .message-alert.info {
            background-color: var(--info-color);
        }

        /* 로딩 및 빈 상태 */
        .loading, .empty-state {
            text-align: center;
            padding: 3rem;
            color: #666;
            grid-column: 1 / -1;
        }

        .empty-state i {
            font-size: 4rem;
            color: var(--primary-color);
            margin-bottom: 1rem;
        }

        /* 애니메이션 */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .fade-in {
            animation: fadeIn 0.5s ease-out;
        }

        /* 유틸리티 */
        .hidden {
            display: none !important;
        }

        .text-center {
            text-align: center;
        }

        .mt-2 { margin-top: 2rem; }
        .mb-2 { margin-bottom: 2rem; }

        /* 관리자 로그인 버튼을 위한 새로운 스타일 */
        .admin-secret-login-btn,
        .admin-secret-panel-btn {
            position: absolute;
            bottom: 15px; /* 푸터 하단에서 띄우기 */
            padding: 10px 20px; /* 일반 버튼과 유사하게 */
            background-color: transparent; /* 완전 투명 */
            color: var(--text-color); /* 푸터 배경색과 동일하게 */
            border: none;
            border-radius: 8px;
            font-size: 0.9rem;
            font-weight: 500;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: none; /* 기본 그림자 제거 */
            z-index: 999; /* 다른 요소 위에 표시 */
        }

        .admin-secret-login-btn:hover,
        .admin-secret-login-btn:active, /* 클릭 시에도 효과 적용 */
        .admin-secret-panel-btn:hover {
            background-color: rgba(255, 255, 255, 0.1); /* 호버 시 약간의 투명한 배경 */
            color: white; /* 호버 시 글자색 변경 */
            transform: translateY(-2px);
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
        }

        .admin-secret-login-btn {
            left: 20px; /* 푸터 왼쪽에서 띄우기 */
        }

        .admin-secret-panel-btn {
            right: 20px; /* 푸터 오른쪽에서 띄우기 */
        }

        /* 광고 영역 스타일 */
        .ad-container {
            background: #f8f9fa;
            border: 1px solid #e9ecef;
            border-radius: 8px;
            padding: 1rem;
            margin: 1rem 0;
            text-align: center;
            min-height: 90px;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
        }

        .ad-container::before {
            content: 'Advertisement';
            position: absolute;
            top: 4px;
            left: 8px;
            font-size: 0.7rem;
            color: #6c757d;
            text-transform: uppercase;
        }

        .ad-banner {
            min-height: 90px;
        }

        .ad-sidebar {
            min-height: 250px;
            width: 100%;
        }

        .ad-content {
            min-height: 280px;
        }

        .ad-footer {
            min-height: 60px;
        }

        /* 광고 반응형 */
        @media (max-width: 768px) {
            .ad-sidebar {
                min-height: 150px;
            }
            .ad-content {
                min-height: 200px;
            }
            /* 반응형 조정 */
            .admin-secret-login-btn,
            .admin-secret-panel-btn {
                position: static; /* 반응형에서 위치 고정 해제 */
                display: block; /* 블록 요소로 만들어 줄바꿈 */
                margin: 0.5rem auto; /* 중앙 정렬 */
                width: 90%; /* 너비 조정 */
                max-width: 200px; /* 최대 너비 설정 */
            }
        }
        @media (max-width: 480px) {
            .container {
                padding: 0 10px;
            }

            .welcome-section {
                padding: 2rem 1rem;
            }

            .products-grid {
                grid-template-columns: 1fr; /* 모바일에서는 1줄로 */
            }

            .btn {
                width: 100%;
                margin-bottom: 0.5rem;
            }

            .nav-buttons {
                width: 100%;
            }
        }

        /* 라이트박스 스타일 추가 */
        .lightbox-modal {
            display: none; /* 기본적으로 숨김 */
            position: fixed;
            z-index: 2000; /* 다른 모달보다 위에 */
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0,0,0,0.8); /* 어두운 배경 */
            justify-content: center;
            align-items: center;
            padding: 20px;
            opacity: 0;
            transition: opacity 0.3s ease;
        }

        .lightbox-modal.show {
            display: flex;
            opacity: 1;
        }

        .lightbox-content {
            position: relative;
            max-width: 90%;
            max-height: 90%;
            background-color: #000; /* 이미지 배경 */
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden; /* 이미지가 라이트박스 밖으로 나가지 않도록 */
        }

        .lightbox-image {
            max-width: 100%;
            max-height: 100%;
            display: block;
            object-fit: contain; /* 이미지 비율 유지 */
            transform-origin: 0 0; /* 확대/축소 기준점 */
            transition: transform 0.1s ease-out; /* 부드러운 확대/축소 */
            cursor: grab; /* 드래그 가능한 커서 */
        }
        .lightbox-image.grabbing {
            cursor: grabbing;
        }

        .lightbox-close-button {
            color: white;
            font-size: 40px;
            font-weight: bold;
            cursor: pointer;
            position: absolute;
            top: 10px;
            right: 20px;
            text-shadow: 0 0 5px rgba(0,0,0,0.5);
        }

        .lightbox-close-button:hover,
        .lightbox-close-button:focus {
            color: var(--primary-color);
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="header-content">
                <a href="#" class="logo" onclick="goToHome()">
                    <!-- 로고 이미지가 있는 경우 -->
                    <img id="logoImage" src="" alt="Showpiece 전문몰" style="height: 40px; width: auto; margin-right: 0.5rem; display: none;">
                    <!-- 기본 아이콘과 텍스트 -->
                    <span id="logoDefault">
                        <i class="fas fa-shopping-bag"></i> Showpiece 전문몰
                    </span>
                </a>
                <div class="nav-buttons">
                    <button class="btn btn-primary" onclick="showSection('home')">
                        <i class="fas fa-home"></i> 홈
                    </button>
                    <button id="seoSettingsBtn" class="btn-seo hidden" onclick="openSEOModal()">
                        <i class="fas fa-search"></i> SEO 설정
                    </button>
                    <button id="adminLogoutBtn" class="btn btn-secondary hidden" onclick="logoutAdmin()">
                        <i class="fas fa-sign-out-alt"></i> 관리자 로그아웃
                    </button>
                </div>
            </div>
        </div>
    </header>

    <main>
        <div class="container">
            <!-- 상단 배너 광고 (조건부 표시) -->
            <div id="topAdBanner" class="ad-container ad-banner" style="display: none;">
                <!-- 🔧 여기에 AdSense 광고 코드 삽입 -->
                <ins class="adsbygoogle"
                     style="display:block"
                     data-ad-client="ca-pub-XXXXXXXXXXXXXXXX"
                     data-ad-slot="XXXXXXXXXX"
                     data-ad-format="auto"
                     data-full-width-responsive="true"></ins>
                <!-- 기존 script 태그는 제거했습니다. -->
            </div>

            <!-- 메시지 알림 영역 -->
            <div id="messageAlert" class="message-alert hidden"></div>

            <!-- Home Section -->
            <div id="home-section">
                <div class="welcome-section fade-in">
                    <h1><i class="fas fa-star"></i> 최고의 상품을 만나보세요!</h1>
                    <p>Showpiece 전문몰에서 엄선된 상품들을 만나보세요. 최저가 보장과 빠른 배송으로 만족스러운 쇼핑을 경험하실 수 있습니다.</p>
                    <div class="welcome-badges">
                        <span class="welcome-badge">
                            <i class="fas fa-shipping-fast"></i> 빠른 배송
                        </span>
                        <span class="welcome-badge success">
                            <i class="fas fa-shield-alt"></i> 품질 보장
                        </span>
                        <span class="welcome-badge warning">
                            <i class="fas fa-tag"></i> 최저가 보장
                        </span>
                    </div>
                </div>

                <!-- 관리자 로그인 시에만 보이는 상품 등록 버튼들 -->
                <div id="quickAddSection" class="quick-add-buttons hidden">
                    <button class="btn-quick-add" onclick="showSection('add-product', '전자제품')">
                        <i class="fas fa-laptop"></i>
                        <span>전자제품 등록</span>
                    </button>
                    <button class="btn-quick-add" onclick="showSection('add-product', '생활용품')">
                        <i class="fas fa-home"></i>
                        <span>생활용품 등록</span>
                    </button>
                    <button class="btn-quick-add" onclick="showSection('add-product', '의류')">
                        <i class="fas fa-tshirt"></i>
                        <span>의류 등록</span>
                    </button>
                </div>

                <div class="search-filter-section fade-in">
                    <div class="search-container">
                        <input type="text" class="search-input" id="searchInput" placeholder="상품명을 입력하세요...">
                        <select class="filter-select" id="categoryFilter">
                            <option value="">모든 카테고리</option>
                            <option value="전자제품">전자제품</option>
                            <option value="의류">의류</option>
                            <option value="생활용품">생활용품</option>
                            <option value="식품">식품</option>
                            <option value="화장품">화장품</option>
                            <option value="도서">도서</option>
                            <option value="스포츠">스포츠</option>
                            <option value="기타">기타</option>
                        </select>
                        <select class="filter-select" id="priceFilter">
                            <option value="">모든 가격대</option>
                            <option value="0-10000">1만원 이하</option>
                            <option value="10000-50000">1만원 - 5만원</option>
                            <option value="50000-100000">5만원 - 10만원</option>
                            <option value="100000-max">10만원 이상</option>
                        </select>
                        <button class="btn btn-primary" onclick="applyFilters()">
                            <i class="fas fa-filter"></i> 필터 적용
                        </button>
                    </div>
                </div>

                <div class="products-section fade-in">
                    <div class="section-header">
                        <h2 class="section-title"><i class="fas fa-box-open"></i> 모든 상품</h2>
                        <button id="addProductBtn" class="btn btn-success hidden" onclick="showSection('add-product')">
                            <i class="fas fa-plus-circle"></i> 새 상품 등록
                        </button>
                    </div>
                    <div id="productsGrid" class="products-grid">
                        <!-- 상품 카드들이 여기에 동적으로 로드됩니다 -->
                        <div class="loading">
                            <i class="fas fa-spinner fa-spin"></i> 상품을 불러오는 중...
                        </div>
                    </div>
                </div>
            </div>

            <!-- Admin Panel Section -->
            <div id="admin-panel-section" class="admin-panel">
                <h2 class="section-title mb-2"><i class="fas fa-chart-line"></i> 관리자 대시보드</h2>
                <div class="admin-stats">
                    <div class="stat-card">
                        <div class="stat-number" id="totalProductsCount">0</div>
                        <div class="stat-label">총 상품 수</div>
                    </div>
                    <div class="stat-card">
                        <div class="stat-number" id="totalCategoriesCount">0</div>
                        <div class="stat-label">총 카테고리</div>
                    </div>
                    <div class="stat-card">
                        <div class="stat-number" id="lastProductAdded">N/A</div>
                        <div class="stat-label">최근 등록 상품</div>
                    </div>
                </div>
                <div class="text-center">
                    <button class="btn btn-info" onclick="showSection('add-product')">
                        <i class="fas fa-plus-circle"></i> 새 상품 등록
                    </button>
                </div>
            </div>

            <!-- Product Add/Edit Form Section -->
            <div id="add-product-section" class="product-form-section hidden"> <!-- hidden 클래스 유지 -->
                <h2 id="productFormTitle" class="section-title mb-2"><i class="fas fa-plus-circle"></i> 새 상품 등록</h2>
                <p class="mb-2">새로운 상품 정보를 입력하거나 기존 상품을 수정하세요.</p>
                <form id="productForm">
                    <input type="hidden" id="productId"> <!-- 상품 ID 저장을 위한 hidden input -->
                    <div class="form-group">
                        <label for="productName" class="form-label">상품명</label>
                        <input type="text" id="productName" class="form-input" placeholder="상품명을 입력하세요" required>
                    </div>
                    <div class="form-group">
                        <label for="productCategory" class="form-label">카테고리</label>
                        <select id="productCategory" class="form-select" required>
                            <option value="">카테고리를 선택하세요</option>
                            <option value="전자제품">전자제품</option>
                            <option value="의류">의류</option>
                            <option value="생활용품">생활용품</option>
                            <option value="식품">식품</option>
                            <option value="화장품">화장품</option>
                            <option value="도서">도서</option>
                            <option value="스포츠">스포츠</option>
                            <option value="기타">기타</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label for="productPrice" class="form-label">가격 (원)</label>
                        <input type="number" id="productPrice" class="form-input" placeholder="가격을 입력하세요" required min="0">
                    </div>
                    <div class="form-group">
                        <label for="productDescription" class="form-label">상품 설명</label>
                        <textarea id="productDescription" class="form-textarea" placeholder="상품에 대한 자세한 설명을 입력하세요" required></textarea>
                        <div class="llm-feature-group">
                            <button type="button" class="btn btn-info btn-small" id="generateDescriptionBtn">
                                ✨ 설명 자동 생성
                            </button>
                            <div id="llmLoadingSpinner" class="llm-loading-spinner"></div>
                        </div>
                    </div>
                    <div class="form-group">
                        <label for="productImage" class="form-label">상품 이미지 (URL 또는 파일 업로드)</label>
                        <input type="text" id="productImageUrl" class="form-input mb-2" placeholder="이미지 URL을 입력하세요 (예: https://example.com/image.jpg)">
                        <div class="file-upload-area" id="fileUploadArea">
                            <i class="fas fa-cloud-upload-alt file-upload-icon"></i>
                            <p>또는 파일을 여기에 드래그 앤 드롭하거나 클릭하여 업로드</p>
                            <input type="file" id="productImageFile" accept="image/*" class="hidden">
                        </div>
                        <img id="imagePreview" src="" alt="Image Preview" class="image-preview mt-2">
                    </div>
                    <div class="form-actions">
                        <button type="submit" class="btn btn-success" id="submitProductBtn">
                            <i class="fas fa-save"></i> 상품 저장
                        </button>
                        <button type="button" class="btn btn-danger" onclick="cancelProductForm()">
                            <i class="fas fa-times-circle"></i> 취소
                        </button>
                    </div>
                </form>
            </div>
        </div>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2024 Showpiece 전문몰. All rights reserved.</p>
            <!-- 쿠팡 파트너스 공정위 문구 추가 -->
            <p style="font-size: 0.8rem; color: rgba(255, 255, 255, 0.7); margin-top: 0.5rem;">
                이 포스팅은 쿠팡 파트너스 활동의 일환으로, 이에 따른 일정액의 수수료를 제공받습니다.
            </p>
            <button id="adminLoginBtn" class="admin-secret-login-btn" onclick="openLoginModal()">관리자 로그인</button>
            <button id="adminPanelBtn" class="admin-secret-panel-btn hidden" onclick="showSection('admin-panel')">관리자 패널</button>
        </div>
    </footer>

    <!-- 관리자 로그인 모달 -->
    <div id="loginModal" class="modal">
        <div class="modal-content">
            <span class="close-button" onclick="closeLoginModal()">&times;</span>
            <h3 class="section-title mb-2"><i class="fas fa-user-shield"></i> 관리자 로그인</h3>
            <p class="mb-2">관리자 비밀번호를 입력하세요.</p>
            <div class="form-group">
                <label for="adminPassword" class="form-label">비밀번호</label>
                <input type="password" id="adminPassword" class="form-input" placeholder="비밀번호를 입력하세요" required>
            </div>
            <div class="form-actions justify-content-center">
                <button class="btn btn-primary" onclick="loginAdmin()">
                    <i class="fas fa-sign-in-alt"></i> 로그인
                </button>
                <button class="btn btn-secondary" onclick="closeLoginModal()">
                    <i class="fas fa-times-circle"></i> 취소
                </button>
            </div>
        </div>
    </div>

    <!-- SEO 설정 모달 -->
    <div id="seoModal" class="seo-modal">
        <div class="seo-modal-content">
            <span class="close-button" onclick="closeSEOModal()">&times;</span>
            <h2 class="section-title mb-2"><i class="fas fa-cogs"></i> SEO 설정 가이드</h2>
            
            <div class="seo-instruction">
                <strong>안내:</strong> 이 섹션은 검색 엔진 최적화(SEO)를 위한 중요한 메타 태그 및 설정을 관리하는 곳입니다. 각 항목을 정확히 입력하여 검색 엔진 노출을 개선하세요.
            </div>

            <div class="seo-section">
                <h3><i class="fas fa-globe"></i> 기본 메타 태그</h3>
                <div class="form-group">
                    <label for="seoTitle" class="form-label">사이트 제목 (Title)</label>
                    <input type="text" id="seoTitle" class="form-input" placeholder="사이트 제목을 입력하세요">
                    <p class="text-small">브라우저 탭 및 검색 결과에 표시됩니다. 60자 이내 권장.</p>
                </div>
                <div class="form-group">
                    <label for="seoDescription" class="form-label">사이트 설명 (Description)</label>
                    <textarea id="seoDescription" class="form-textarea" placeholder="사이트 설명을 입력하세요"></textarea>
                    <p class="text-small">검색 결과에 제목 아래에 표시됩니다. 160자 이내 권장.</p>
                </div>
                <div class="form-group">
                    <label for="seoKeywords" class="form-label">키워드 (Keywords)</label>
                    <input type="text" id="seoKeywords" class="form-input" placeholder="키워드를 쉼표로 구분하여 입력하세요">
                    <p class="text-small">검색 엔진이 사이트 내용을 이해하는 데 도움을 줍니다. (선택 사항)</p>
                </div>
                <div class="form-group">
                    <label for="seoAuthor" class="form-label">작성자 (Author)</label>
                    <input type="text" id="seoAuthor" class="form-input" placeholder="작성자 또는 회사 이름을 입력하세요">
                </div>
                <div class="form-group">
                    <label for="seoRobots" class="form-label">로봇 (Robots)</label>
                    <select id="seoRobots" class="form-select">
                        <option value="index, follow">index, follow (기본값)</option>
                        <option value="noindex, follow">noindex, follow</option>
                        <option value="index, nofollow">index, nofollow</option>
                        <option value="noindex, nofollow">noindex, nofollow</option>
                    </select>
                    <p class="text-small">검색 엔진 크롤러의 동작을 지시합니다.</p>
                </div>
            </div>

            <div class="seo-section">
                <h3><i class="fas fa-share-alt"></i> 소셜 미디어 (Open Graph & Twitter Card)</h3>
                <div class="form-group">
                    <label for="ogTitle" class="form-label">OG 제목</label>
                    <input type="text" id="ogTitle" class="form-input" placeholder="소셜 미디어 공유 시 표시될 제목">
                </div>
                <div class="form-group">
                    <label for="ogDescription" class="form-label">OG 설명</label>
                    <textarea id="ogDescription" class="form-textarea" placeholder="소셜 미디어 공유 시 표시될 설명"></textarea>
                </div>
                <div class="form-group">
                    <label for="ogUrl" class="form-label">OG URL</label>
                    <input type="url" id="ogUrl" class="form-input" placeholder="사이트의 정식 URL (예: https://yoursite.com)">
                </div>
                <div class="form-group">
                    <label for="ogImage" class="form-label">OG 이미지 URL</label>
                    <input type="url" id="ogImage" class="form-input" placeholder="소셜 미디어 공유 시 사용될 이미지 URL">
                </div>
                <div class="form-group">
                    <label for="twitterImage" class="form-label">Twitter 이미지 URL</label>
                    <input type="url" id="twitterImage" class="form-input" placeholder="Twitter 공유 시 사용될 이미지 URL">
                </div>
            </div>

            <div class="seo-section">
                <h3><i class="fas fa-code-branch"></i> 구조화된 데이터 (JSON-LD)</h3>
                <p class="seo-instruction">
                    JSON-LD는 검색 엔진이 웹사이트의 콘텐츠를 더 잘 이해하도록 돕는 데이터 형식입니다.
                    이 섹션의 내용은 자동으로 생성되므로, 로고 이미지 URL만 업데이트하세요.
                </p>
                <div class="form-group">
                    <label for="jsonLdLogoUrl" class="form-label">JSON-LD 로고 이미지 URL</label>
                    <input type="url" id="jsonLdLogoUrl" class="form-input" placeholder="조직 로고 이미지 URL">
                </div>
            </div>

            <div class="seo-section">
                <h3><i class="fas fa-link"></i> Canonical URL</h3>
                <div class="form-group">
                    <label for="canonicalUrl" class="form-label">Canonical URL</label>
                    <input type="url" id="canonicalUrl" class="form-input" placeholder="사이트의 정식 URL (중복 콘텐츠 방지)">
                </div>
            </div>

            <div class="seo-section">
                <h3><i class="fas fa-chart-bar"></i> 웹마스터 도구 및 분석</h3>
                <p class="seo-instruction">
                    각 검색 엔진의 웹마스터 도구에서 제공하는 인증 코드를 입력하세요.
                    이 코드를 통해 사이트 소유권을 확인하고 검색 성능을 모니터링할 수 있습니다.
                </p>
                <div class="form-group">
                    <label for="gaMeasurementId" class="form-label">Google Analytics 4 측정 ID (GA_MEASUREMENT_ID)</label>
                    <input type="text" id="gaMeasurementId" class="form-input" placeholder="예: G-XXXXXXXXXX">
                </div>
                <div class="form-group">
                    <label for="adsensePublisherId" class="form-label">Google AdSense 게시자 ID (ca-pub-XXXXXXXXXXXXXXXX)</label>
                    <input type="text" id="adsensePublisherId" class="form-input" placeholder="예: ca-pub-1234567890123456">
                </div>
                <div class="form-group">
                    <label for="googleVerification" class="form-label">Google Search Console 인증 코드</label>
                    <input type="text" id="googleVerification" class="form-input" placeholder="YOUR_GOOGLE_VERIFICATION_CODE">
                </div>
                <div class="form-group">
                    <label for="naverVerification" class="form-label">네이버 서치어드바이저 인증 코드</label>
                    <input type="text" id="naverVerification" class="form-input" placeholder="YOUR_NAVER_VERIFICATION_CODE">
                </div>
                <div class="form-group">
                    <label for="daumVerification" class="form-label">다음 검색등록 인증 코드</label>
                    <input type="text" id="daumVerification" class="form-input" placeholder="YOUR_DAUM_VERIFICATION_CODE">
                </div>
                <div class="form-group">
                    <label for="bingVerification" class="form-label">Bing Webmaster Tools 인증 코드</label>
                    <input type="text" id="bingVerification" class="form-input" placeholder="YOUR_BING_VERIFICATION_CODE">
                </div>
            </div>

            <div class="form-actions mt-2">
                <button type="button" class="btn btn-success" onclick="saveSEOChanges()">
                    <i class="fas fa-save"></i> SEO 설정 저장
                </button>
                <button type="button" class="btn btn-danger" onclick="closeSEOModal()">
                    <i class="fas fa-times-circle"></i> 닫기
                </button>
            </div>
        </div>
    </div>

    <!-- 확인 모달 (삭제 등) -->
    <div id="confirmationModal" class="modal">
        <div class="modal-content">
            <span class="close-button" onclick="closeConfirmationModal()">&times;</span>
            <h3 id="confirmationModalTitle" class="section-title mb-2"><i class="fas fa-question-circle"></i> 확인</h3>
            <p id="confirmationModalMessage" class="mb-2">정말로 이 작업을 수행하시겠습니까?</p>
            <div class="form-actions justify-content-center">
                <button id="confirmActionButton" class="btn btn-danger"><i class="fas fa-check-circle"></i> 확인</button>
                <button class="btn btn-secondary" onclick="closeConfirmationModal()">
                    <i class="fas fa-times-circle"></i> 취소
                </button>
            </div>
        </div>
    </div>

    <!-- 라이트박스 모달 -->
    <div id="lightboxModal" class="lightbox-modal">
        <div class="lightbox-content">
            <span class="lightbox-close-button" onclick="closeLightbox()">&times;</span>
            <img id="lightboxImage" class="lightbox-image" src="" alt="확대된 상품 이미지">
        </div>
    </div>

    <script>
        // Global variables
        let isAdmin = false;
        let products = []; // Array to store product data
        let editingProductId = null; // ID of the product being edited

        // Lightbox zoom and pan variables
        let currentZoom = 1;
        let currentPanX = 0;
        let currentPanY = 0;
        let isDragging = false;
        let startX, startY;

        // Cache DOM elements
        const sections = {
            'home': document.getElementById('home-section'),
            'admin-panel': document.getElementById('admin-panel-section'),
            'add-product': document.getElementById('add-product-section')
        };
        const productForm = document.getElementById('productForm');
        const productIdInput = document.getElementById('productId');
        const productNameInput = document.getElementById('productName');
        const productCategorySelect = document.getElementById('productCategory');
        const productPriceInput = document.getElementById('productPrice');
        const productDescriptionTextarea = document.getElementById('productDescription');
        const productImageUrlInput = document.getElementById('productImageUrl');
        const productImageFileInput = document.getElementById('productImageFile');
        const imagePreview = document.getElementById('imagePreview');
        const fileUploadArea = document.getElementById('fileUploadArea');
        const productFormTitle = document.getElementById('productFormTitle');
        const submitProductBtn = document.getElementById('submitProductBtn');
        const productsGrid = document.getElementById('productsGrid');
        const searchInput = document.getElementById('searchInput');
        const categoryFilter = document.getElementById('categoryFilter');
        const priceFilter = document.getElementById('priceFilter');
        const messageAlert = document.getElementById('messageAlert');
        const adminLogoutBtn = document.getElementById('adminLogoutBtn');
        const quickAddSection = document.getElementById('quickAddSection');
        const addProductBtn = document.getElementById('addProductBtn');
        const seoSettingsBtn = document.getElementById('seoSettingsBtn');
        const logoImage = document.getElementById('logoImage');
        const logoDefault = document.getElementById('logoDefault');
        const topAdBanner = document.getElementById('topAdBanner');

        // New login modal related DOM elements
        const loginModal = document.getElementById('loginModal');
        const adminLoginBtn = document.getElementById('adminLoginBtn');
        const adminPanelBtn = document.getElementById('adminPanelBtn');
        const adminPasswordInput = document.getElementById('adminPassword');

        // Lightbox related DOM elements
        const lightboxModal = document.getElementById('lightboxModal');
        const lightboxImage = document.getElementById('lightboxImage');
        const lightboxContent = document.querySelector('.lightbox-content'); // Get the content div for pan limits

        // LLM related DOM elements
        const generateDescriptionBtn = document.getElementById('generateDescriptionBtn');
        const llmLoadingSpinner = document.getElementById('llmLoadingSpinner');

        // SEO modal related DOM elements
        const seoModal = document.getElementById('seoModal');
        const seoTitleInput = document.getElementById('seoTitle');
        const seoDescriptionInput = document.getElementById('seoDescription');
        const seoKeywordsInput = document.getElementById('seoKeywords');
        const seoAuthorInput = document.getElementById('seoAuthor');
        const seoRobotsSelect = document.getElementById('seoRobots');
        const ogTitleInput = document.getElementById('ogTitle');
        const ogDescriptionInput = document.getElementById('ogDescription');
        const ogUrlInput = document.getElementById('ogUrl');
        const ogImageInput = document.getElementById('ogImage');
        const twitterImageInput = document.getElementById('twitterImage');
        const jsonLdLogoUrlInput = document.getElementById('jsonLdLogoUrl');
        const canonicalUrlInput = document.getElementById('canonicalUrl');
        const gaMeasurementIdInput = document.getElementById('gaMeasurementId');
        const adsensePublisherIdInput = document.getElementById('adsensePublisherId');
        const googleVerificationInput = document.getElementById('googleVerification');
        const naverVerificationInput = document.getElementById('naverVerification');
        const daumVerificationInput = document.getElementById('daumVerification');
        const bingVerificationInput = document.getElementById('bingVerification');

        // Confirmation modal related DOM elements
        const confirmationModal = document.getElementById('confirmationModal');
        const confirmationModalTitle = document.getElementById('confirmationModalTitle');
        const confirmationModalMessage = document.getElementById('confirmationModalMessage');
        const confirmActionButton = document.getElementById('confirmActionButton');

        // Initial load execution
        document.addEventListener('DOMContentLoaded', () => {
            console.log("Script loaded and DOMContentLoaded fired."); // Debug: Script load confirmation
            loadProducts();
            loadSEOConfig();
            applyFilters(); // Initial product load and filter application
            showSection('home'); // Initial screen is home section
            updateAdminPanelVisibility(); // Initial admin UI visibility setting
            addLightboxEventListeners(); // Add event listeners for lightbox zoom/pan
        });

        // -------------------- Utility Functions --------------------

        /**
         * Displays a message alert to the user.
         * @param {string} message - The message to display.
         * @param {'success'|'error'|'info'} type - The type of message.
         */
        function showMessage(message, type) {
            messageAlert.textContent = message;
            messageAlert.className = `message-alert show ${type}`;
            setTimeout(() => {
                messageAlert.classList.remove('show');
            }, 3000);
        }

        /**
         * Hides all sections and displays a specific section.
         * @param {string} sectionId - The ID of the section to display.
         * @param {string} [category] - Pre-select category when navigating to 'add-product' section.
         */
        function showSection(sectionId, category = '') {
            console.log(`Navigating to section: ${sectionId}`); // Debug: Confirm section navigation
            for (let id in sections) {
                sections[id].classList.add('hidden');
            }
            sections[sectionId].classList.remove('hidden');
            sections[sectionId].classList.add('fade-in');
            console.log(`Visibility of ${sectionId}: ${window.getComputedStyle(sections[sectionId]).display}`); // Debug: Check computed display style

            // Logic related to product add/edit form
            if (sectionId === 'add-product') {
                productFormTitle.textContent = '새 상품 등록';
                submitProductBtn.textContent = '상품 저장';
                submitProductBtn.innerHTML = '<i class="fas fa-save"></i> 상품 저장';
                productForm.reset(); // Reset form
                imagePreview.style.display = 'none';
                imagePreview.src = '';
                editingProductId = null; // Exit edit mode
                console.log("Add Product Section is now visible and form reset."); // Debug: Confirm form visibility

                if (category) {
                    productCategorySelect.value = category;
                }
            } else if (sectionId === 'home') {
                applyFilters(); // Re-apply filters when returning to home
            }
            updateAdminPanelVisibility(); // Update admin UI on section change
        }

        /**
         * Navigates to the home section.
         */
        function goToHome() {
            showSection('home');
        }

        // -------------------- Admin Functions --------------------

        /**
         * Opens the admin login modal.
         */
        function openLoginModal() {
            loginModal.classList.add('show');
            adminPasswordInput.value = ''; // Clear password input field
            adminPasswordInput.focus(); // Focus on password input field
        }

        /**
         * Closes the admin login modal.
         */
        function closeLoginModal() {
            loginModal.classList.remove('show');
        }

        /**
         * Handles admin login.
         */
        function loginAdmin() {
            const password = adminPasswordInput.value;
            // 비밀번호 변경 위치: 아래 "CoupangMall2024!@#" 부분을 원하는 비밀번호로 수정하세요.
            if (password === "CoupangMall2024!@#") { 
                isAdmin = true;
                showMessage('관리자 로그인 성공!', 'success');
                closeLoginModal(); // 로그인 모달 닫기
                updateAdminPanelVisibility();
                showSection('home'); // 로그인 후 홈으로 이동
            } else {
                showMessage('잘못된 비밀번호입니다.', 'error');
            }
        }

        /**
         * Handles admin logout.
         */
        function logoutAdmin() {
            isAdmin = false;
            showMessage('관리자 로그아웃 되었습니다.', 'info');
            updateAdminPanelVisibility();
            showSection('home'); // 로그아웃 후 홈으로 이동
        }

        /**
         * Updates the visibility of admin-related UI elements.
         */
        function updateAdminPanelVisibility() {
            if (isAdmin) {
                adminLoginBtn.classList.add('hidden'); // Hide login button
                adminLogoutBtn.classList.remove('hidden'); // Show logout button
                adminPanelBtn.classList.remove('hidden'); // Show admin panel button
                quickAddSection.classList.remove('hidden');
                addProductBtn.classList.remove('hidden');
                seoSettingsBtn.classList.remove('hidden');
                // Show edit/delete buttons on all product cards
                document.querySelectorAll('.product-actions .admin-action-btn').forEach(btn => {
                    btn.classList.remove('hidden');
                });
                generateDescriptionBtn.classList.remove('hidden'); // Show LLM button
            } else {
                adminLoginBtn.classList.remove('hidden'); // Show login button
                adminLogoutBtn.classList.add('hidden'); // Hide logout button
                adminPanelBtn.classList.add('hidden'); // Hide admin panel button
                quickAddSection.classList.add('hidden');
                addProductBtn.classList.add('hidden');
                seoSettingsBtn.classList.add('hidden');
                // Hide edit/delete buttons on all product cards
                document.querySelectorAll('.product-actions .admin-action-btn').forEach(btn => {
                    btn.classList.add('hidden');
                });
                generateDescriptionBtn.classList.add('hidden'); // Hide LLM button
            }
            updateAdminStats(); // Update admin statistics
        }

        /**
         * Updates admin statistics data.
         */
        function updateAdminStats() {
            if (isAdmin) {
                document.getElementById('totalProductsCount').textContent = products.length;
                const categories = new Set(products.map(p => p.category));
                document.getElementById('totalCategoriesCount').textContent = categories.size;
                if (products.length > 0) {
                    const lastProduct = products[products.length - 1];
                    document.getElementById('lastProductAdded').textContent = lastProduct.name;
                } else {
                    document.getElementById('lastProductAdded').textContent = 'N/A';
                }
            }
        }

        // -------------------- Product Management Functions --------------------

        /**
         * Loads product list from local storage.
         */
        function loadProducts() {
            const storedProducts = localStorage.getItem('products');
            if (storedProducts) {
                products = JSON.parse(storedProducts);
            } else {
                // Initial dummy data (if no data in local storage)
                products = [
                    { id: Date.now() + 1, name: "삼성 갤럭시 S24", category: "전자제품", price: 1200000, description: "최신 플래그십 스마트폰", imageUrl: "https://placehold.co/400x200/cc6b49/ffffff?text=Galaxy+S24" },
                    { id: Date.now() + 2, name: "LG 스탠바이미", category: "전자제품", price: 900000, description: "이동식 스크린 TV", imageUrl: "https://placehold.co/400x200/8b4513/ffffff?text=StandbyMe" },
                    { id: Date.now() + 3, name: "다이슨 에어랩", category: "생활용품", price: 600000, description: "혁신적인 헤어 스타일러", imageUrl: "https://placehold.co/400x200/28a745/ffffff?text=Dyson+Airwrap" },
                    { id: Date.now() + 4, name: "나이키 에어포스 1", category: "의류", price: 130000, description: "클래식한 디자인의 스니커즈", imageUrl: "https://placehold.co/400x200/17a2b8/ffffff?text=Nike+Air+Force" },
                    { id: Date.now() + 5, name: "애플 아이패드 프로", category: "전자제품", price: 1500000, description: "강력한 성능의 태블릿", imageUrl: "https://placehold.co/400x200/dc3545/ffffff?text=iPad+Pro" }
                ];
                saveProducts(); // Save initial data
            }
            renderProducts(products); // Render product list
            updateAdminStats(); // Update admin statistics
        }

        /**
         * Saves the product list to local storage.
         */
        function saveProducts() {
            localStorage.setItem('products', JSON.stringify(products));
        }

        /**
         * Renders the product list on the screen.
         * @param {Array<Object>} productsToRender - Array of products to render.
         */
        function renderProducts(productsToRender) {
            productsGrid.innerHTML = ''; // Clear existing products

            if (productsToRender.length === 0) {
                productsGrid.innerHTML = `
                    <div class="empty-state">
                        <i class="fas fa-box-open"></i>
                        <p>등록된 상품이 없습니다.</p>
                    </div>
                `;
                return;
            }

            productsToRender.forEach(product => {
                const productCard = document.createElement('div');
                productCard.className = 'product-card fade-in';
                // Add onclick event to product-image div for lightbox
                productCard.innerHTML = `
                    <div class="product-image" onclick="openLightbox('${product.imageUrl || 'https://placehold.co/400x200/cc6b49/ffffff?text=No+Image'}')">
                        ${product.imageUrl ? `<img src="${product.imageUrl}" alt="${product.name}" onerror="this.onerror=null;this.src='https://placehold.co/400x200/cc6b49/ffffff?text=No+Image';">` : `<i class="fas fa-image"></i>`}
                    </div>
                    <div class="product-info">
                        <span class="product-category-tag">${product.category}</span>
                        <h3 class="product-title">${product.name}</h3>
                        <p class="product-price">${product.price.toLocaleString()}원</p>
                        <p class="product-description">${product.description}</p>
                        <div class="product-actions">
                            <a href="${product.coupangLink || '#'}" target="_blank" class="btn btn-primary btn-small">
                                <i class="fas fa-shopping-cart"></i> 구매하기
                            </a>
                            <!-- Admin-only edit/delete buttons -->
                            <button class="btn btn-info btn-small admin-action-btn ${isAdmin ? '' : 'hidden'}" onclick="editProduct('${product.id}')">
                                <i class="fas fa-edit"></i> 수정
                            </button>
                            <button class="btn btn-danger btn-small admin-action-btn ${isAdmin ? '' : 'hidden'}" onclick="confirmDeleteProduct('${product.id}', '${product.name}')">
                                <i class="fas fa-trash-alt"></i> 삭제
                            </button>
                        </div>
                    </div>
                `;
                productsGrid.appendChild(productCard);
            });
        }

        /**
         * Handles product registration or editing.
         * @param {Event} event - Form submission event.
         */
        productForm.addEventListener('submit', (event) => {
            event.preventDefault();

            const id = productIdInput.value ? parseInt(productIdInput.value) : Date.now();
            const name = productNameInput.value;
            const category = productCategorySelect.value;
            const price = parseInt(productPriceInput.value);
            const description = productDescriptionTextarea.value;
            let imageUrl = productImageUrlInput.value;

            // If a file is uploaded (requires server-side upload logic in a real app)
            if (productImageFileInput.files.length > 0) {
                const file = productImageFileInput.files[0];
                // For simplicity, convert to Data URL here. In a real service,
                // images should be uploaded to a server and their URLs stored.
                const reader = new FileReader();
                reader.onload = (e) => {
                    imageUrl = e.target.result; // Use Data URL
                    saveOrUpdateProduct({ id, name, category, price, description, imageUrl });
                };
                reader.readAsDataURL(file);
                return; // Call save function after file read completes
            }

            saveOrUpdateProduct({ id, name, category, price, description, imageUrl });
        });

        /**
         * Saves or updates product data.
         * @param {Object} productData - Product data to save or update.
         */
        function saveOrUpdateProduct(productData) {
            if (editingProductId) {
                // Edit product
                const index = products.findIndex(p => p.id === editingProductId);
                if (index !== -1) {
                    products[index] = { ...products[index], ...productData }; // Update while preserving existing data
                    showMessage('상품이 성공적으로 수정되었습니다!', 'success');
                } else {
                    showMessage('상품을 찾을 수 없습니다.', 'error');
                }
                editingProductId = null; // Exit edit mode
            } else {
                // Register new product
                products.push(productData);
                showMessage('새 상품이 성공적으로 등록되었습니다!', 'success');
            }

            saveProducts();
            applyFilters(); // Re-apply filters to reflect changes
            showSection('home'); // Return to home
        }

        /**
         * Populates the product edit form and switches to edit mode.
         * @param {string} productId - ID of the product to edit.
         */
        function editProduct(productId) {
            const productToEdit = products.find(p => p.id === parseInt(productId));
            if (productToEdit) {
                editingProductId = productToEdit.id;
                productFormTitle.textContent = '상품 수정';
                submitProductBtn.textContent = '상품 업데이트';
                submitProductBtn.innerHTML = '<i class="fas fa-save"></i> 상품 업데이트';

                productIdInput.value = productToEdit.id;
                productNameInput.value = productToEdit.name;
                productCategorySelect.value = productToEdit.category;
                productPriceInput.value = productToEdit.price;
                productDescriptionTextarea.value = productToEdit.description;
                productImageUrlInput.value = productToEdit.imageUrl || '';

                if (productToEdit.imageUrl) {
                    imagePreview.src = productToEdit.imageUrl;
                    imagePreview.style.display = 'block';
                } else {
                    imagePreview.style.display = 'none';
                    imagePreview.src = '';
                }

                showSection('add-product'); // Display product add/edit form section
            } else {
                showMessage('수정할 상품을 찾을 수 없습니다.', 'error');
            }
        }

        /**
         * Displays a confirmation modal for product deletion.
         * @param {string} productId - ID of the product to delete.
         * @param {string} productName - Name of the product to delete (for confirmation message).
         */
        function confirmDeleteProduct(productId, productName) {
            confirmationModalTitle.textContent = '상품 삭제 확인';
            confirmationModalMessage.innerHTML = `'<strong>${productName}</strong>' 상품을 정말로 삭제하시겠습니까? 이 작업은 되돌릴 수 없습니다.`;
            confirmActionButton.onclick = () => deleteProduct(productId);
            confirmationModal.classList.add('show');
        }

        /**
         * Deletes a product.
         * @param {string} productId - ID of the product to delete.
         */
        function deleteProduct(productId) {
            closeConfirmationModal(); // Close confirmation modal
            const initialLength = products.length;
            products = products.filter(p => p.id !== parseInt(productId));
            if (products.length < initialLength) {
                saveProducts();
                applyFilters(); // Re-apply filters to reflect changes
                showMessage('상품이 성공적으로 삭제되었습니다.', 'success');
            } else {
                showMessage('상품 삭제에 실패했습니다.', 'error');
            }
        }

        /**
         * Cancels the product add/edit form and returns to home.
         */
        function cancelProductForm() {
            productForm.reset();
            imagePreview.style.display = 'none';
            imagePreview.src = '';
            editingProductId = null;
            showSection('home');
        }

        // -------------------- Image Upload and Preview --------------------

        fileUploadArea.addEventListener('click', () => {
            productImageFileInput.click();
        });

        fileUploadArea.addEventListener('dragover', (e) => {
            e.preventDefault();
            fileUploadArea.classList.add('dragover');
        });

        fileUploadArea.addEventListener('dragleave', () => {
            fileUploadArea.classList.remove('dragover');
        });

        fileUploadArea.addEventListener('drop', (e) => {
            e.preventDefault();
            fileUploadArea.classList.remove('dragover');
            const files = e.dataTransfer.files;
            if (files.length > 0) {
                productImageFileInput.files = files;
                displayImagePreview(files[0]);
            }
        });

        productImageFileInput.addEventListener('change', (e) => {
            if (e.target.files.length > 0) {
                displayImagePreview(e.target.files[0]);
            }
        });

        productImageUrlInput.addEventListener('input', (e) => {
            if (e.target.value) {
                imagePreview.src = e.target.value;
                imagePreview.style.display = 'block';
            } else {
                imagePreview.style.display = 'none';
                imagePreview.src = '';
            }
        });

        /**
         * Displays the selected image file as a preview.
         * @param {File} file - Image file object.
         */
        function displayImagePreview(file) {
            const reader = new FileReader();
            reader.onload = (e) => {
                imagePreview.src = e.target.result;
                imagePreview.style.display = 'block';
            };
            reader.readAsDataURL(file);
        }

        // -------------------- Search and Filtering --------------------

        searchInput.addEventListener('input', applyFilters);
        categoryFilter.addEventListener('change', applyFilters);
        priceFilter.addEventListener('change', applyFilters);

        /**
         * Applies search term, category, and price filters to render products.
         */
        function applyFilters() {
            const searchTerm = searchInput.value.toLowerCase();
            const selectedCategory = categoryFilter.value;
            const selectedPriceRange = priceFilter.value;

            let filteredProducts = products.filter(product => {
                const matchesSearch = product.name.toLowerCase().includes(searchTerm) ||
                                      product.description.toLowerCase().includes(searchTerm);
                const matchesCategory = selectedCategory === '' || product.category === selectedCategory;

                let matchesPrice = true;
                if (selectedPriceRange !== '') {
                    const [minStr, maxStr] = selectedPriceRange.split('-');
                    const minPrice = parseInt(minStr);
                    const maxPrice = maxStr === 'max' ? Infinity : parseInt(maxStr);
                    matchesPrice = product.price >= minPrice && product.price <= maxPrice;
                }

                return matchesSearch && matchesCategory && matchesPrice;
            });

            renderProducts(filteredProducts);
        }

        // -------------------- SEO Settings Modal --------------------

        /**
         * Opens the SEO settings modal.
         */
        function openSEOModal() {
            if (!isAdmin) {
                showMessage('관리자만 SEO 설정을 변경할 수 있습니다.', 'error');
                return;
            }
            loadSEOConfigToForm();
            seoModal.classList.add('show');
        }

        /**
         * Closes the SEO settings modal.
         */
        function closeSEOModal() {
            seoModal.classList.remove('show');
        }

        /**
         * Loads SEO settings into the form.
         */
        function loadSEOConfigToForm() {
            const config = JSON.parse(localStorage.getItem('seoConfig') || '{}');

            seoTitleInput.value = config.title || document.title;
            seoDescriptionInput.value = config.description || document.querySelector('meta[name="description"]').content;
            seoKeywordsInput.value = config.keywords || document.querySelector('meta[name="keywords"]').content;
            seoAuthorInput.value = config.author || document.querySelector('meta[name="author"]').content;
            seoRobotsSelect.value = config.robots || document.querySelector('meta[name="robots"]').content;

            ogTitleInput.value = config.ogTitle || document.querySelector('meta[property="og:title"]').content;
            ogDescriptionInput.value = config.ogDescription || document.querySelector('meta[property="og:description"]').content;
            ogUrlInput.value = config.ogUrl || document.querySelector('meta[property="og:url"]').content;
            ogImageInput.value = config.ogImage || document.querySelector('meta[property="og:image"]').content;
            twitterImageInput.value = config.twitterImage || document.querySelector('meta[name="twitter:image"]').content;

            jsonLdLogoUrlInput.value = config.jsonLdLogoUrl || 'https://yoursite.com/logo.png'; // Default value
            canonicalUrlInput.value = config.canonicalUrl || document.querySelector('link[rel="canonical"]').href;

            gaMeasurementIdInput.value = config.gaMeasurementId || 'GA_MEASUREMENT_ID';
            adsensePublisherIdInput.value = config.adsensePublisherId || 'ca-pub-XXXXXXXXXXXXXXXX';
            googleVerificationInput.value = config.googleVerification || 'YOUR_GOOGLE_VERIFICATION_CODE';
            naverVerificationInput.value = config.naverVerification || 'YOUR_NAVER_VERIFICATION_CODE';
            daumVerificationInput.value = config.daumVerification || 'YOUR_DAUM_VERIFICATION_CODE';
            bingVerificationInput.value = config.bingVerification || 'YOUR_BING_VERIFICATION_CODE';

            // Update logo image preview (within SEO settings modal)
            if (config.logoImageUrl) {
                logoImage.src = config.logoImageUrl;
                logoImage.style.display = 'inline-block';
                logoDefault.style.display = 'none';
            } else {
                logoImage.style.display = 'none';
                logoDefault.style.display = 'inline-block';
            }
            // Top ad banner visibility
            if (config.showTopAdBanner) {
                topAdBanner.style.display = 'flex';
            } else {
                topAdBanner.style.display = 'none';
            }
        }

        /**
         * Saves and applies SEO settings from the form.
         */
        function saveSEOChanges() {
            const config = {
                title: seoTitleInput.value,
                description: seoDescriptionInput.value,
                keywords: seoKeywordsInput.value,
                author: seoAuthorInput.value,
                robots: seoRobotsSelect.value,
                ogTitle: ogTitleInput.value,
                ogDescription: ogDescriptionInput.value,
                ogUrl: ogUrlInput.value,
                ogImage: ogImageInput.value,
                twitterImage: twitterImageInput.value,
                jsonLdLogoUrl: jsonLdLogoUrlInput.value,
                canonicalUrl: canonicalUrlInput.value,
                gaMeasurementId: gaMeasurementIdInput.value,
                adsensePublisherId: adsensePublisherIdInput.value,
                googleVerification: googleVerificationInput.value,
                naverVerification: naverVerificationInput.value,
                daumVerification: daumVerificationInput.value,
                bingVerification: bingVerificationInput.value,
                logoImageUrl: logoImage.src && logoImage.src !== window.location.href ? logoImage.src : '', // Save logo image URL
                showTopAdBanner: topAdBanner.style.display === 'flex' // Save top ad banner visibility
            };

            localStorage.setItem('seoConfig', JSON.stringify(config));
            applySEOConfig(config);
            closeSEOModal();
            showMessage('SEO 설정이 저장되었습니다!', 'success');
        }

        /**
         * Applies saved SEO settings to the HTML document.
         * @param {Object} config - SEO settings object to apply.
         */
        function applySEOConfig(config) {
            document.title = config.title;
            document.querySelector('meta[name="description"]').content = config.description;
            document.querySelector('meta[name="keywords"]').content = config.keywords;
            document.querySelector('meta[name="author"]').content = config.author;
            document.querySelector('meta[name="robots"]').content = config.robots;

            document.querySelector('meta[property="og:title"]').content = config.ogTitle;
            document.querySelector('meta[property="og:description"]').content = config.ogDescription;
            document.querySelector('meta[property="og:type"]').content = 'website'; // type is fixed
            document.querySelector('meta[property="og:url"]').content = config.ogUrl;
            document.querySelector('meta[property="og:image"]').content = config.ogImage;
            document.querySelector('meta[property="og:site_name"]').content = 'Showpiece 전문몰'; // site_name is fixed
            document.querySelector('meta[property="og:locale"]').content = 'ko_KR'; // locale is fixed

            document.querySelector('meta[name="twitter:card"]').content = 'summary_large_image'; // card is fixed
            document.querySelector('meta[name="twitter:title"]').content = config.ogTitle; // Twitter title is same as OG title
            document.querySelector('meta[name="twitter:description"]').content = config.ogDescription; // Twitter description is same as OG description
            document.querySelector('meta[name="twitter:image"]').content = config.twitterImage;

            document.querySelector('link[rel="canonical"]').href = config.canonicalUrl;

            // Update JSON-LD
            const jsonLdScript = document.querySelector('script[type="application/ld+json"]');
            if (jsonLdScript) {
                const jsonLd = JSON.parse(jsonLdScript.textContent);
                jsonLd.name = config.title;
                jsonLd.description = config.description;
                jsonLd.url = config.canonicalUrl;
                if (jsonLd.publisher && jsonLd.publisher.logo) {
                    jsonLd.publisher.logo.url = config.jsonLdLogoUrl;
                }
                jsonLdScript.textContent = JSON.stringify(jsonLd, null, 2);
            }

            // Update Google Analytics
            const gaScript = document.querySelector('script[src*="googletagmanager.com"]');
            if (gaScript) {
                const gaConfigScript = gaScript.nextElementSibling;
                if (gaConfigScript && gaConfigScript.textContent.includes("gtag('config'")) {
                    gaConfigScript.textContent = gaConfigScript.textContent.replace(/gtag\('config', 'GA_MEASUREMENT_ID'\);/, `gtag('config', '${config.gaMeasurementId}');`);
                }
            }

            // Update Webmaster Tools verification meta tags
            document.querySelector('meta[name="google-site-verification"]').content = config.googleVerification;
            document.querySelector('meta[name="naver-site-verification"]').content = config.naverVerification;
            document.querySelector('meta[name="daum-site-verification"]').content = config.daumVerification;
            document.querySelector('meta[name="msvalidate.01"]').content = config.bingVerification;

            // Update logo image
            if (config.logoImageUrl) {
                logoImage.src = config.logoImageUrl;
                logoImage.style.display = 'inline-block';
                logoDefault.style.display = 'none';
            } else {
                logoImage.style.display = 'none';
                logoDefault.style.display = 'inline-block';
            }

            // Display and push top ad banner
            if (config.showTopAdBanner) {
                topAdBanner.style.display = 'flex';
                // Only push ad if it's displayed
                try {
                    (adsbygoogle = window.adsbygoogle || []).push({});
                } catch (e) {
                    console.error("adsbygoogle.push() error:", e);
                }
            } else {
                topAdBanner.style.display = 'none';
            }
        }

        /**
         * Loads SEO settings from local storage and applies them.
         */
        function loadSEOConfig() {
            const config = JSON.parse(localStorage.getItem('seoConfig'));
            if (config) {
                applySEOConfig(config);
            }
        }

        // -------------------- Confirmation Modal --------------------

        /**
         * Closes the confirmation modal.
         */
        function closeConfirmationModal() {
            confirmationModal.classList.remove('show');
            confirmActionButton.onclick = null; // Reset event handler
        }

        // Close modals when clicking outside
        window.addEventListener('click', (event) => {
            if (event.target === confirmationModal) {
                closeConfirmationModal();
            }
            if (event.target === seoModal) {
                closeSEOModal();
            }
            if (event.target === loginModal) { // Close login modal when clicking outside
                closeLoginModal();
            }
            if (event.target === lightboxModal) { // Close lightbox modal when clicking outside
                closeLightbox();
            }
        });

        // -------------------- Lightbox Functions (with Zoom/Pan) --------------------

        /**
         * Adds event listeners for lightbox zoom/pan functionality.
         */
        function addLightboxEventListeners() {
            lightboxImage.addEventListener('wheel', handleZoom);
            lightboxImage.addEventListener('mousedown', handlePanStart);
            lightboxImage.addEventListener('mousemove', handlePanMove);
            lightboxImage.addEventListener('mouseup', handlePanEnd);
            lightboxImage.addEventListener('mouseleave', handlePanEnd); // End pan if mouse leaves image
            lightboxModal.addEventListener('dblclick', resetLightboxTransform); // Double click to reset
        }

        /**
         * Opens the lightbox modal with the specified image.
         * @param {string} imageUrl - The URL of the image to display in the lightbox.
         */
        function openLightbox(imageUrl) {
            lightboxImage.src = imageUrl;
            resetLightboxTransform(); // Reset zoom/pan when opening
            lightboxModal.classList.add('show');
        }

        /**
         * Closes the lightbox modal.
         */
        function closeLightbox() {
            lightboxModal.classList.remove('show');
            lightboxImage.src = ''; // Clear image source
            resetLightboxTransform(); // Ensure reset on close
        }

        /**
         * Resets the zoom and pan of the lightbox image.
         */
        function resetLightboxTransform() {
            currentZoom = 1;
            currentPanX = 0;
            currentPanY = 0;
            applyLightboxTransform();
        }

        /**
         * Applies the current zoom and pan values to the lightbox image.
         */
        function applyLightboxTransform() {
            lightboxImage.style.transform = `scale(${currentZoom}) translate(${currentPanX}px, ${currentPanY}px)`;
        }

        /**
         * Handles mouse wheel event for zooming.
         * @param {WheelEvent} e - The wheel event.
         */
        function handleZoom(e) {
            e.preventDefault(); // Prevent page scrolling

            const scaleAmount = 0.1;
            const oldZoom = currentZoom;

            if (e.deltaY < 0) { // Zoom in
                currentZoom += scaleAmount;
            } else { // Zoom out
                currentZoom -= scaleAmount;
            }

            currentZoom = Math.max(0.1, Math.min(5, currentZoom)); // Limit zoom between 0.1x and 5x

            // Adjust pan to zoom towards the mouse cursor
            const rect = lightboxImage.getBoundingClientRect();
            const mouseX = e.clientX - rect.left;
            const mouseY = e.clientY - rect.top;

            currentPanX = currentPanX - (mouseX / oldZoom) * (currentZoom - oldZoom);
            currentPanY = currentPanY - (mouseY / oldZoom) * (currentZoom - oldZoom);

            applyLightboxTransform();
        }

        /**
         * Handles mouse down event for starting pan.
         * @param {MouseEvent} e - The mouse event.
         */
        function handlePanStart(e) {
            if (currentZoom > 1) { // Only allow pan if zoomed in
                isDragging = true;
                startX = e.clientX - currentPanX;
                startY = e.clientY - currentPanY;
                lightboxImage.classList.add('grabbing');
            }
        }

        /**
         * Handles mouse move event for panning.
         * @param {MouseEvent} e - The mouse event.
         */
        function handlePanMove(e) {
            if (!isDragging) return;
            e.preventDefault(); // Prevent selection

            currentPanX = e.clientX - startX;
            currentPanY = e.clientY - startY;

            // Optional: Add boundaries to prevent panning too far
            // This requires calculating the image's zoomed dimensions and the lightbox content's dimensions
            // For simplicity, we'll omit complex boundary calculations for now,
            // but the image will be clipped by `overflow: hidden` on `.lightbox-content`

            applyLightboxTransform();
        }

        /**
         * Handles mouse up event for ending pan.
         */
        function handlePanEnd() {
            isDragging = false;
            lightboxImage.classList.remove('grabbing');
        }


        // -------------------- Gemini API Integration: Auto-generate Product Description --------------------

        generateDescriptionBtn.addEventListener('click', generateProductDescription);

        /**
         * Generates product description automatically using Gemini API.
         */
        async function generateProductDescription() {
            if (!isAdmin) {
                showMessage('관리자만 상품 설명을 자동 생성할 수 있습니다.', 'error');
                return;
            }

            const productName = productNameInput.value.trim();
            const productCategory = productCategorySelect.value;
            const currentDescription = productDescriptionTextarea.value.trim();

            if (!productName) {
                showMessage('상품명을 입력해야 설명을 생성할 수 있습니다.', 'info');
                return;
            }

            llmLoadingSpinner.style.display = 'block'; // Show loading spinner
            generateDescriptionBtn.disabled = true; // Disable button

            let prompt = `상품명: "${productName}"`;
            if (productCategory) {
                prompt += `\n카테고리: "${productCategory}"`;
            }
            if (currentDescription) {
                prompt += `\n현재 설명: "${currentDescription}"`;
                prompt += `\n\n위 정보를 바탕으로 이 상품에 대한 매력적이고 상세한 설명을 200자 내외로 작성해주세요. 기존 설명이 있다면 이를 보완하거나 새롭게 작성해주세요.`;
            } else {
                prompt += `\n\n위 상품명과 카테고리를 바탕으로 이 상품에 대한 매력적이고 상세한 설명을 200자 내외로 작성해주세요.`;
            }
            
            try {
                let chatHistory = [];
                chatHistory.push({ role: "user", parts: [{ text: prompt }] });
                const payload = { contents: chatHistory };
                const apiKey = ""; // Provided automatically by Canvas environment.
                const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${apiKey}`;

                const response = await fetch(apiUrl, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                });

                const result = await response.json();

                if (result.candidates && result.candidates.length > 0 &&
                    result.candidates[0].content && result.candidates[0].content.parts &&
                    result.candidates[0].content.parts.length > 0) {
                    const generatedText = result.candidates[0].content.parts[0].text;
                    productDescriptionTextarea.value = generatedText;
                    showMessage('상품 설명이 성공적으로 생성되었습니다!', 'success');
                } else {
                    showMessage('상품 설명을 생성하지 못했습니다. 다시 시도해주세요.', 'error');
                    console.error('Gemini API 응답 오류:', result);
                }
            } catch (error) {
                showMessage('상품 설명 생성 중 오류가 발생했습니다.', 'error');
                console.error('Gemini API 호출 오류:', error);
            } finally {
                llmLoadingSpinner.style.display = 'none'; // Hide loading spinner
                generateDescriptionBtn.disabled = false; // Enable button
            }
        }
    </script>
</body>
</html>
