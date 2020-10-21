# 배달의민족 맛집랭킹 진입 업체의 월간 매출액 예측

          - 배달의민족 앱 이용행태 데이터를 기반으로 업체별 매출액 선형회귀 분석 -
          
                                             by. 우아한 남매들 (김재욱, 박경원)
                                             
## 목차
1. 프로젝트 진행 목적
2. 데이터 소개
3. 데이터 전처리
4. 탐색적 데이터 분석 (EDA)
5. 선형회귀 예측 결과
6. 개선점


## 프로젝트 진행 목적

### 주제 선정 배경
**" 배달 전문 업체는 한 달에 얼마나 벌까? "**
> "언택트 시대"의 도래로 각광을 받고 있는 <*배달 서비스 창업*>에 대한 관심

**" 성공한 배달 업체의 매출액을 <배달의민족> 데이터로 예측해보자 "**

> 국내 1위 소비자-외식배달업체 연결 플랫폼인 "배달의민족" 어플 내\
상위 랭킹 업체의 데이터를 기반으로\
<*외식배달전문업체의 월간 매출액 예측*>이 가능할 것으로 판단


### 예측 결과 활용 목적
**" 돈 많이 버는 업체의 성공 비결이 뭘까? "**
> '배달의민족' 어플에서 얻을 수 있는 데이터를 중심으로,\
<*매출액이 높은 외식배달전문업체가 되기 위한 조건*> 탐구

**" 만약 이렇게 운영한다면, 본전은 뽑을 수 있을까? "**  
> 임의의 자본금으로 외식배달전문업체를 창업해\
'배달의민족'에 입점한 상황을 가정하고,\
매출액 예측을 위해 필요한 조건 데이터를 임의로 대입한 경우,\
<*손익분기점을 넘기는 매출액을 얻을 수 있을지*> 확인



## 데이터 소개

### 데이터 수집방법
**"모바일앱 크롤링 못하는 자, 구석기 시대로 돌아가라"**
> 업체별 데이터 모두 수작업으로 수집

>
> 1) "배달의민족" 모바일앱 접속
> 2) 기준지 전철역을 주소지로 등록
> 3) 맛집랭킹 메뉴의 한식 탭 소속 업체 데이터 확인
> 4) PC 엑셀에 확인한 데이터 직접 타이핑

>
> - 수집 기간 : 8월 5일(수) ~ 8월 11일(화)
> - 소요 시간 : 데이터 20개 당 약 30분 소요
