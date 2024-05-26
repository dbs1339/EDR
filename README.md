# EDR
Autoencoder와 Graph기반 Autoencoder의 성능 비교

사용한 Featuring 방안
![image](https://github.com/dbs1339/EDR/assets/128207214/a1f16e62-1276-421f-95b1-4bbda3ee3ec1)


Autoencoder의 탐지 결과
![image](https://github.com/dbs1339/EDR/assets/128207214/e265ef2d-1806-4aa5-9844-fdca86021166)

![image](https://github.com/dbs1339/EDR/assets/128207214/b4c700d4-ca57-4195-9797-e629fefeb283)
![image](https://github.com/dbs1339/EDR/assets/128207214/b56aca7c-dce3-4c71-9ad5-6e4c9935a6f6)

Graph 기반 Autoencoder
![image](https://github.com/dbs1339/EDR/assets/128207214/79f99520-54b1-45c3-820f-2db113b8abed)

![image](https://github.com/dbs1339/EDR/assets/128207214/e25bf17d-fd1a-4ade-bc42-a8805d7f6e1c)
![image](https://github.com/dbs1339/EDR/assets/128207214/de3d3c5c-74e4-4414-958c-48b8f415ba91)

결과 분석
현재 Autoencoder보다 Graph 기반 Autoencoder가 성능이 향상된것을 볼 수 있음
그 이유는 아마 Process들의 연결 정보를 기반으로 재구성 오류값을 Update하여 정상과 같은 패턴을 공격 패턴도 탐지가 가능하기 때문
![image](https://github.com/dbs1339/EDR/assets/128207214/b2714fa4-69be-4dcb-a610-69ad9e007736)
위 사진처럼 일반적인 프로그램을 실행하는 단계는 Autoencoder에서는 미탐이 되었으나 Graph 기반 Autoencoder를 사용함으로써 탐지가 됨
