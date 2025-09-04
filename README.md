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
