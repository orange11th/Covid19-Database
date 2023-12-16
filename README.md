# Covid19-Database
> ## 코로나 19 데이터베이스 웹 연동 프로젝트 입니다.
> ### (2020년에 공부하면서 진행한 프로젝트라 퀄리티나 유지보수성이 좋지 않습니다. :cry: )

</br>

## ER Diagram
![er](https://github.com/orange11th/Covid19-Database/assets/82896260/99ed5592-ac24-443d-ba1d-2d7a68e5f130)

</br>

## Directory Structure
![dir](https://github.com/orange11th/Covid19-Database/assets/82896260/e12c4f0d-bdcd-4689-ade8-fafc3bea25dc)

</br>

## 백신접종 DB
![vaccine](https://github.com/orange11th/Covid19-Database/assets/82896260/f16b6f0c-6eb0-4202-a3f6-05a308f6dbf2)

</br>

## 확진자 DB
![confirm](https://github.com/orange11th/Covid19-Database/assets/82896260/a0ad9851-9c95-43a6-8f83-7d9331bd0c1d)
> ### 추가 기능
> #### 데이터 입력 시 백신접종 DB에서 ID를 검색해 자동으로 Y/N 표시
> #### 데이터 입력/삭제 시 격리병동 DB에 현재 날짜 기준으로 자동 입력/삭제

</br>

## 백신패스 DB
![pass](https://github.com/orange11th/Covid19-Database/assets/82896260/6f6672da-35e6-447a-ba4c-c5be60025c8d)
> ### 추가 기능
> #### 입력/수정될 때 만료일이 등록일 +6개월로 자동 입력 
> #### 동기화: 작동 시 만료일이 지난 데이터 자동으로 삭제
</br>

## 격리병동 DB
![isolated](https://github.com/orange11th/Covid19-Database/assets/82896260/fe85bac8-9e19-4caa-8f82-c9779603a57f)
> ### 추가 기능
> #### 입력/수정될 때 퇴원일이 입원일+14일로 자동 입력
> #### 동기화: 작동 시 퇴원일이 지난 데이터 자동으로 삭제

</br>

## 의료 DB
![medical](https://github.com/orange11th/Covid19-Database/assets/82896260/319cbdb1-cc41-4a37-b979-c148a3bc8561)

</br>
