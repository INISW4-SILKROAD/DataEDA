# DataEDA
학습용 DATA 전처리

이 Repository는 SILKROAD 프로젝트 모델학습에 사용하는 Data 전처리 코드들이 있습니다.  
  
TextureSurvey_csv - 원단 촉감 설문 결과를 모아둔 폴더  
  
FiberData.csv - 촉감 분류모델에 학습에 사용할 원단들의 혼용율 정보  
  
SurveyData.ipynb - 설문결과들을 하나의 csv파일로 만들고 설문에 사용하는 원단의 혼용율을 정리하는 코드 
(설문결과: result.csv, 원단 혼용율 정보: use_data.csv)  

Boxplot.ipynb - 설문결과에 대한 Boxplot
  
CorrelationCoefficient.ipynb - 상관 관계 계수를 이용 하여 혼방율에 따른 학습용 데이터 생성

FuzzyComprehensiveEvaluation.ipynb - Fuzzy Comprehensive Logic에 Entropy Weight를 활용하여 학습용 데이터 생성

TouchDataAugmentation.ipynb - 촉감 분류 모델 학습용 원단 이미지를 Augmentation 하는 코드  
  
requirements.txt - DataEDA에 있는 코드에 필요한 모든 패키지
