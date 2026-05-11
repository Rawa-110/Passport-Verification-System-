# Passport-Verification-System-
Passport Verification  System 

�
�
 :فﺋﺎظوﻟا 
1. ةءارﻗ تﺎﻧﺎﯾﺑ زاوﺟﻟا ) OCR ( 
2. لﯾﻠﺣﺗ ةروﺻﻟا ) CNN ( 
3. صﺣﻓ رﯾوزﺗﻟا ) ELA + Features ( 
4. ءﺎطﻋإ :ﺔﺟﯾﺗﻧ 
○ لﻣﺗﺣﻣ ﻲﻘﯾﻘﺣ 
○ لﻣﺗﺣﻣ فﯾزﻣ 
 
�
�
 تﺎﻧوﻛﻣ عورﺷﻣﻟا 
1. ةءارﻗ صﻧﻟا ) OCR ( 
:مدﺧﺗﺳا 
● Tesseract OCR 
�
�
 ةرﻛﻔﻟا ﺔﻣﺎﻌﻟا 
�
�
 :فدﮭﻟا 
فﯾﻧﺻﺗ ةروﺻ زاوﺟﻟا :ﻰﻟإ 
● Real (ﻲﻘﯾﻘﺣ) 
● Fake (فﯾزﻣ) 
�
�
 تاوطﺧ عورﺷﻣﻟا مادﺧﺗﺳﺎﺑ CNN 
1. زﯾﮭﺟﺗ تﺎﻧﺎﯾﺑﻟا مھأ) (ةوطﺧ 
مزﻻ نوﻛﯾ كدﻧﻋ Dataset اذﮭﺑ :لﻛﺷﻟا 
/
passport_dataset
│
/
/
train
real
──├
──├
/
fake
/
──└
test
│
│
│
──├
/
/نﻵا
ثدﺣﯾﺳ
:ﺎﮭﯾﻓ
ﺔﮭﺟاو
📤
كﻟ
اذﺎﻣ
رﮭظﺗﺳ
🎯
لﯾﻐﺷﺗﻟا
ةروﺻ
ةروﺻﻟا
+
ﻊﻓر
🖼
رز
ضرﻋ
🧠
رﯾوزﺗﻟا
ﺔﺑﺳﻧ
ﺔﺟﯾﺗﻧﻟا
● 
● 
●<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c2d6ccb4-15ec-4d78-9fa4-486f57e2c47a" />
�
�
 :ًﻻوأ تاودﻷا ﺔﻣدﺧﺗﺳﻣﻟا ﻲﻓ عورﺷﻣﻟا 
�
�
 1( ءﺎﻛذﻟا ﻲﻋﺎﻧطﺻﻻا ) CNN ( 
● TensorFlow 
● Keras 
● مدﺧﺗﺳﺗ ءﺎﻧﺑﻟ جذوﻣﻧ مﻠﻌﺗﯾ زﯾﯾﻣﺗﻟا نﯾﺑ زاوﺟﻟا ﻲﻘﯾﻘﺣﻟا فﯾزﻣﻟاو 
 
�
�
 2( ﺔﺟﻟﺎﻌﻣ روﺻﻟا 
● PIL (Pillow ( 
● NumPy 
● لﯾوﺣﺗﻟ روﺻﻟا ﺎھزﯾﮭﺟﺗو جذوﻣﻧﻠﻟ 
 
�
�
 3( ضرﻋ ﺞﺋﺎﺗﻧﻟا 
 
●  
● Gradio → ءﺎﻧﺑﻟ ﺔﮭﺟاو مدﺧﺗﺳﻣﻟا 
 
�
�
 4( ﺔﺋﯾﺑﻟا 
● Google Colab / Jupyter Notebook 
● Google Drive نﯾزﺧﺗﻟ تﺎﻧﺎﯾﺑﻟا 
 
�
�
 :ًﺎﯾﻧﺎﺛ لﺣ لﻛﺎﺷﻣﻟا ﻲﻠﻟا كﺗﮭﺟاو 
❌
 ﺔﻠﻛﺷﻣﻟا 1: FileNotFoundError 
:بﺑﺳﻟا 
:بﺑﺳﻟ 
رﺎﺳﻣﻟا طﻠﻏ وأ دﻠﺟﻣﻟا رﯾﻏ دوﺟوﻣ 
:لﺣﻟا 
os.path.exists("path") 
❌
 ﺔﻠﻛﺷﻣﻟا 2: No images found 
:بﺑﺳﻟا 
تادﻠﺟﻣﻟا ﺔﯾﺿﺎﻓ وأ روﺻﻟا وﻣ ﺔﻣظﻧﻣ 
:لﺣﻟا 
مزﻻ نوﻛﯾ لﻛﯾﮭﻟا :اذﻛ 
train/ 
  real/ 
  fake/

real
fake
