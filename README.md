## 배포된 주소 
 https://eunkyung0927.github.io/momentum/

## 실행 화면 
![image](https://user-images.githubusercontent.com/28224655/201647078-426c6b05-55d4-49de-b9e2-aae30fc7e53a.png)

## 구현 내용
```css
       /*가운데 정렬*/
        .quote{
            display:flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }
            
     /* 배경요소에만 필터 적용 */
        body::before{
            content: "";
            opacity: 0.3;
            position: absolute;
            top: 0px;
            left: 0px;
            right: 0px;
            bottom: 0px;
            background-color: rgb(179 179 179);
        }
            
```

## 사용한 api  
   
현재 시간 : `https://worldtimeapi.org/api/timezone/Asia/Seoul`  
랜덤한 명언 : `https://api.quotable.io/random`

## 배포  
github pages 기능이용하여 배포  

## 적용  
크롬 설정> 모양> 홈버튼 표시 체크 후 위의 주소 
