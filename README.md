# 제 7회 데이터 분석 경진대회 2019 빅콘테스트 innovation 분야 최우수상(GS리테일상) 수상작
[최종보고서](https://drive.google.com/file/d/18MR66cm9ddlI2CfiuMmbl3C9_05Veg_U/view)
- 진행기간 : 2019.07.23 ~ 2019.09.10
- 주요내용 :  미세먼지로 바뀐 라이프 스타일을 분석 후 GS25 미세먼지 상품 판촉 기획
- 사용 언어 : R
- 공헌한 점

    (1) 논문 스터디 : 설문 조사에 따르면 2018년 미세먼지가 매우 불안하다는 응답은 4년전 대비 1.5배 높아졌고 미세먼지로 바뀐 일상생활에 대한 답변으로 마스크 착용이 2위로 상위권이었음. 이를 통해 다양한 가설들을 설정하고 데이터를 확인해봄.

    (2) 데이터 전처리 : 외부 데이터 수집(네이버 트렌드 쇼핑 검색량, Airkorea 미세먼지 예보 데이터) , 이상치와 결측치 처리,  데이터 결합 

    (3) SNS 데이터 분석 : 형태소 분리(token화), corpus 구축, TF-IDF 단어 빈도 분석, LDA(Latent Dirichlet allocation)기법을 이용한 토픽 분석을 수행

    (4) 인사이트 발견 : SNS단어빈도를 시각화한 결과 미세먼지가 나쁠수록 마스크의 SNS언급량 및 네이버 쇼핑 검색이 높아짐.

- 인사이트 및 결론

    (1) (미세먼지에 대한 불안감 가중) 설문조사에 따르면 2018년 미세먼지가 매우 불안하다는 응답은 4년전 대비 1.5배 높아짐

    (2) (미세먼지가 나쁨에도 유동인구 줄지 않고 미세먼지 배출에 도움이 되는 편의점 음료 배출 감소)

    (3) (미세먼지가 나쁜날 사람들은 마스크 구매에 관심)텍스트마이닝 결과 미세먼지가 나쁠수록 마스크의 언급량 및 네이버 쇼핑 검색이 높아짐

    **(4) 결론 : 미세먼지가 나쁜날 GS25에서 전광판을 설치하여 거리의 고객에게 미세먼지에 대한 경각심을 주어 마스크 및 음료를 미세먼지 방지 아이템으로 판촉할 것을 제안**
