## 유튜브로 알아보는 나의 독서 DNA : 유튜브 시청기록 기반 도서 추천 시스템(Youtube-based_Book_Recommendation_System)

### Preprocessing & EDA
사용 데이터 : YES24 및 유튜브 크롤링, 문화빅데이터 플랫폼 인기 대출 데이터, 빅카인즈 분야 별 뉴스 기사
도서 추천 대상 : 서울도서관 인기 대출 정보, 성균관대학교 핫북, 이달의 신간 

### 분석 기법 :
사회 이슈 추출 : TF-IDF 변형식 
유튜브 키워드 추출 : Pagerank Algorithm, KR-SBert 유사도 계산
유튜브 영상 KDC 할당 : Labeled-LDA

### Recommendation System
시청 기록 입력 - 유튜브로부터 키워드 추출 및 KDC 분야별 선호 분포 형성
협업 필터링: Bayesian 관점 적용, 분포 조정 및 최종 분포 형성
최종 분포 & 키워드 유사도 키반 도서 추천 진행
