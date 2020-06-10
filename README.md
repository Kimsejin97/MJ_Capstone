# MJ_Capstone
인공지능을 이용한 농산물 가격예측

## 프로젝트 구조
1. 농산물 별 주산지 선정
2. 농산물 가격, 생산량, 공급량, 수입량, 수출량, 날씨 데이터 수집
3. mysql테이블에 저장
4. 농산물별 생산량과 생육기간 전체의 기상요인 상관관계 조사
5. 농산물의 공급량, 생산량, 수출량, 수입량에 따른 농산물 가격 상관관계 조사
6. 날씨데이터를 받아 서버에서 계산하는 파일 만들고 json형식으로 넘겨주기
7. 농산물 가격 에측을 위한 데이터를 읽어 예측모델 실행하고 가격예측 데이터 json형식으로 넘겨주기
8. 서버에 농산물 위험도분석을 일주일에 한번, 농산물 가격 예측은 하루에 한번 파일이 실행되도록 cron 구성
9. json형식으로 받은 데이터 시각화하기

## 데이터 수집방법
1. [kamis](https://www.kamis.or.kr/customer/reference/openapi_list.do) 에서 농산물 데이터 오픈 API활용하여 수집
2. [oasis](http://oasis.krei.re.kr/basicInfo/etc/kma.do) 에서 날씨 데이터 수집

## 데이터 분석방법


## 분석결과
