# FakeNewsDetection
# Dataset
ข่าวปลอม : Fake.CSV
ข่าวจริง : REAL.CSV
รวมไฟล์ข่าวปลอมและช่าวจริง : manual_testing.csv โดนไฟล์นี้จะกำหนดclassว่าFake คือ 0 และ Real คือ 1
# Libraries
pythainlp
numpy
sklearn
matplotlib
seaborn
wordcloud
re
nltk
warnings
# Neural Network 
Random Forest

# ขั้นตอนการทำงาน
1.ติดตั้ง pip install pythainlp และ Libraries
2.รวมไฟล์ Fake News แะ Real Newsไว้ที่ manual_testing.csv
3.StopWords 'ราย'
4.WordCloud ตัดคำจากไฟล์ แต่ละclass
5.ใช้ Random Forest ในตรวจสอบความแม่นยำในการตรวจจับข่าวปลอม ที่มีความแม่นยำถึง 79 %
