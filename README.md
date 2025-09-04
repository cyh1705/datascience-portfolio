# datascience-portfolio
#Frist day pandas
df.head(n): 앞부분 n행 출력
df.tail(n): 뒤에서 n행 출력
df.info(): 데이터프레임 요약 정보 확인(컬럼, 데이터 타입, 결측치 여부)
df.shape : 행(row), 열(column) 개수 확인 # (행 개수, 열 개수)
df.describe() : 수치형 컬럼의 통계 요약 (평균, 표준편차, 최소/최대, 사분위수 등)
df.columns : 컬럼 이름 확인
df.index : 인덱스 확인 (행 번호나 라벨)
df. dtypes : 컬럼별 데이터 타입 확인
df.insull().sum() : 결측치(누락값) 확인
df.value_counts() : 특정 컬럼 값 빈도 세기 # df["Ciudad"].value_counts()
df.iloc[n] : 행/열 번호(index번호)로 데이터 선택 #df.iloc[0, 1] 첫 번째 행, 두 번째 열 값
df.loc[n]: 인덱스 이름, 컬럼 이름으로 데이터 선택 #df.loc[0, "Ciudad"] 인덱스 0, 컬럼 "Ciudad"
df.groupby(): 특정 컬럼 기준으로 데이터를 묶어서 합계, 평근 등 계산
df.merge(): 두 개 이상의 DataFrame을 공통 컬럼(key)으로 합치기(SQL의 JOIN과 유사)
