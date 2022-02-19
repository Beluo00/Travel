# Travel

## 프로젝트의 목적 및 용도
퍼블리셔가 되기 위한 필수 코스인 반응형을 만들어 보았습니다.
미디어 쿼리를 사용해서 피씨, 모바일 태블릿 버전으로 나눴습니다. 

## 사용 기술
1. PhotoShop
2. HTML
3. CSS
4. JAVASCRIPT
5. Slick

## 구현 방법
**폰트**
구글 폰트 : Poppins

**색상**
영상이 푸른 바다이기 때문에 바다의 색으로 나타내기 위해 푸른색 위주로 골랐습니다.
시원을 느낌과 심플하게 조합하여 웹페이지를 만들었습니다.
![색상](https://user-images.githubusercontent.com/85346880/154807025-58768d32-2e27-4571-a072-347f3315b71d.png)


**첫 화면**
<img width="1259" alt="첫배경" src="https://user-images.githubusercontent.com/85346880/154807320-93cd9d48-b58b-443a-b30c-2a90dc69ff60.png">

백그라운드를 영상으로 배치를 하였고, 반복적으로 재생할 수 있도록 설정 했습니다.
<video class="video-slide" src="video/video1.mp4" autoplay muted loop></video>

<img width="1277" alt="스크롤" src="https://user-images.githubusercontent.com/85346880/154807389-31251010-e267-4447-93b3-a6dff8823a89.png">
상단 왼쪽에는 로고, 오른쪽으로는 메뉴 입니다. 이 색상은 하얀색이므로 스크롤을 할 때 흰 바탕에는 안 보이는 것을 방지하기 위해
header에 스크롤을 할 때 bar가 나타날 수 있도록 디자인 했습니다. 그러면 글씨의 색상은 검정색으로 바뀝니다.

왼쪽에는 내용 오른쪽에는 sns로 배치하여 빈공간을 채웠습니다. 
버튼을 누르면 home으로 이동합니다. 이 때 scroll-behavior: smooth;을 써서 스무스하게 내려갑니다.

<img width="689" alt="태블릿_배경" src="https://user-images.githubusercontent.com/85346880/154807471-f771cce3-ba6e-4791-8c89-e97587ed3d12.png">

태블릿 화면일 때의 모습 입니다.

<img width="682" alt="태블릿_메뉴" src="https://user-images.githubusercontent.com/85346880/154807561-3ec8e5f9-717c-4efe-8e62-036a0023e348.png">

메뉴의 리스트를 display:none으로 해두고 아이콘으로 배치하였습니다.
navigation에 클래스를 추가하여 아이콘을 눌렀을 때 메뉴를 보여줍니다.

<img width="688" alt="태블릿_네비게이션" src="https://user-images.githubusercontent.com/85346880/154807631-427efac4-b258-4df4-b913-7a3488a077ef.png">

모바일 화면일 때의 모습입니다.

<img width="353" alt="모바일" src="https://user-images.githubusercontent.com/85346880/154807668-3fa3f395-5eeb-4b2e-b692-8346820212e7.png">

요소들을 모두 가운데에 배치해서 모바일의 맞춤을 보여줍니다.

**about**

<img width="1216" alt="about" src="https://user-images.githubusercontent.com/85346880/154807730-9d310116-f67e-4cbd-8396-43a40b7a43c2.png">
이 부분은 웹페이지의 대한 설명을 대신해서 Lorem으로 채웠습니다.

타이틀 부분에는 border-bottom을 사용해서 꾸몄습니다.

**contents**
<img width="1184" alt="contens" src="https://user-images.githubusercontent.com/85346880/154807810-0ed543b8-8ee6-46f2-83e4-02c76cfdcd1d.png">

박스를 만들어서 사진과 내용 그리고 버튼을 넣었습니다. display:flex의 wrap을 사용해서 자동으로 줄바꿈을 하여,
디스플레이의 크기대로 맞춰집니다.

**gallery**
<img width="1155" alt="슬라이드" src="https://user-images.githubusercontent.com/85346880/154807880-7f4587bc-af63-499d-b718-2c18c54da933.png">

slick 기술을 사용하여 슬라이드를 구현 했습니다. 슬릭의 반응형 코드도 같이 사용하여 화면의 크기에 따라 슬라이드의 수가 줄어듭니다.
피씨일 땐 4개의 사진, 태블릿일 때 3개의 사진, 모바일 일 땐 2개의 사진으로 구현 하였습니다.

**contact**
<img width="1244" alt="컨택트" src="https://user-images.githubusercontent.com/85346880/154807995-dbc13c12-577f-4b50-b3ac-3f536530827a.png">

폼을 작성할 수 있는 부분입니다. 컨택트는 백그라운드에 영상을 추가 하였습니다.
해가 지는 영상을 추가한 이유는 웹페이지의 끝을 알리기 위해서 이 영상으로 설정 했습니다.

<img width="352" alt="모바일 컨택트" src="https://user-images.githubusercontent.com/85346880/154808067-68450b83-7f0b-4777-a9be-f5b022162e70.png">

이 폼이 모바일 화면일 때는 요소들을 가운데로 배치하여 모바일 맞춤으로 디자인 하였습니다.


<img width="1253" alt="footer" src="https://user-images.githubusercontent.com/85346880/154808132-fbf45f89-5474-4381-a98a-5dd1ec038ae8.png">

마지막으로 푸터의 색상은 해변의 모래의 색으로 설정하여 이 웹페이지가 전체적인 바다의 틀로 갖춘 화면으로 만들어 보았습니다.
밑에 허전해 보이지 않게 아이콘을 추가하였습니다. 마우스를 올렸을 때 크기가 커집니다.

## 개선사항
웹페이지를 만들 때의 속도 입니다. 처음 해보는 반응형이라서 그런지 막히는 부분이 많았기에 그것을 해결 하느라 시간을 많이 쓴 거 같습니다.
웹 페이지를 만드는 데에 소요시간은 하루 정도 걸렸습니다. 
많은 페이지를 만들면서 문제를 해결 할 수 있는 속도를 향상 시키겠습니다.

## 후기
반응형을 혼자 독학한 지 2주 째 입니다. 첫 주는 이론 위주로 공부하고 둘 째주는 실습 위주로 공부하였습니다.
이로써 2주의 시간을 걸쳐 첫 반응형 페이지를 완성 하였습니다. 
이 반응형의 다음 목표는 인터렉티브 웹 페이지 입니다.
아직 기술로는 부족하지만 노력해서 다양한 웹페이지를 만드는 것이 저의 목표입니다.



