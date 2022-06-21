# CEO_project_A

IoT 실습 - 매장 관리 시스템

## Original Architecture
![image](https://user-images.githubusercontent.com/90883981/174483264-9711bf93-7abb-4604-9121-f1eaaa2c5572.png)

## Result Architecture

![image](https://user-images.githubusercontent.com/90883981/174763860-956217e5-4408-4d81-aef2-38f6c56c57fa.png)


---
## Picture
   
![KakaoTalk_20220619_121548294](https://user-images.githubusercontent.com/96249554/174464401-2804f54a-4180-4e36-ae35-e8e62ebaa867.jpg)
   
![KakaoTalk_20220619_121548294_01](https://user-images.githubusercontent.com/96249554/174464403-51e97376-7d56-48c6-a06c-9d0950bd130d.jpg)

   
---
## Result Video
   

https://user-images.githubusercontent.com/74127841/174486560-43f47488-87a7-41a5-b098-2c50616a150e.mp4



   
   
---
## Log
   
#### (2022-06-13)
* MG90 Servo Motor 미동작 원인 찾을 필요 있음
   
(참고) Example - ESP8266_MultipleRandomServos   

https://github.com/khoih-prog/ESP8266_ISR_Servo#example-esp8266_multiplerandomservos   
   
   
#### (2022-06-15)
* Servo Motor 동작 성공
* UltraSonic 추가
* Store, Door STATE 동작 추가
* Switch 연결 후 단순 스위치 동작으로 각 STATE 변경
* Servo Motor, Buzzer 동시에 사용 시 동작이 원활하게 되지 않음   
* Buzzer의 tone 사용 후 Servo 동작 불가   
 -> 원인 발견 X   
 
 
* 보드 2개 이용하여 침입자 감지 시그널에 의해 부저가 동작하도록 작성   
**보드 1** : UltraSonic, ServoMotor, Switch   
**보드 2** : Buzzer   
   
   
#### (2022-06-18)
* HW 프레임 제작 완료   
   
* NodeRed 제작 완료   
   
* JSON 데이터로 주고 받는 동작 완성   
   
   
#### (2022-06-19)
* HW 동작 테스트 완료   
   
* 테스트 영상 1



https://user-images.githubusercontent.com/90883981/174482682-7b66854c-27f5-466c-bef9-ac5f24ce55fe.mp4


* 테스트 영상 2


https://user-images.githubusercontent.com/90883981/174482742-b26541e5-d418-43ab-bed7-3b8e9f585b3b.mp4


* Edge 연결 성공

* 테스트 영상 3




https://user-images.githubusercontent.com/74127841/174486560-43f47488-87a7-41a5-b098-2c50616a150e.mp4


