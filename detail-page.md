api 디테일 추가
 # 3초간 슬라이드 
 var slideInterval = setInterval nextSlide,3000
  
# 새 페이지로 리다이렉트
        window.location.href = 'detail.html';

 # 이미지 소스와 alt 값을 세션 스토리지에 저장
        sessionStorage.setItem('imgSrc', src);
        sessionStorage.setItem('imgAlt', alt);
