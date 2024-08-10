## English Readme... 
---
The database includes the information of 393 people given to the program. 
Information affecting diabetes such as: 
number of pregnancies, glucose, blood pressure, skin thickness, insulin in the blood, body mass index (estimation of height and weight ratio), susceptibility to diabetes (hereditary genetics), age and the result, which includes 0 (not having diabetes) and 1 (diseased) to diabetes).
The artificial intelligence program learns by examining the dataset to predict the probability of new people developing diabetes.

Note: by removing rows from the data set that are empty or zero, the data set is correct and correct and the prediction will be more accurate.

After calling the data file, a logistic regression model is created. 

We introduce 0.2 percent of the lines (X_train) as training data along with the output (Y_Train) for learning and training to the model. 
A number of rows of the dataset are introduced as test data without output (X_test).
Finally, with these data, we compare the correct percentage of machine prediction with the dataset outputs. 

X_test is given to the model to predict the output. 
The output is displayed as an array of zeros and ones. 
For each person, 0 means no possibility of getting diabetes and 1 means the possibility of getting diabetes.

Now you can ask artificial intelligence about the probability of getting diabetes with the following template:

*---example Data* 
*(Pregnancies,Glucose,BloodPressure,SkinThickness,Insulin,BMI(body mass index),DiabetesPedigreeFunction,Age)*
```python
z = np.array([[2,100,50,35,243,30.5,0.138,36]])
example = model.predict(z)
print(example)
```
---
## persion Readme...
دیتاستی شامل اطلاعات 393 نفر به برنامه داده می شود. 
اطلاعاتی تأثیرگذار بر ابتلا به دیابت از قبیل: 
تعداد حاملگی، گلوکز، فشارخون، ضخامت پوست، انسولین در خون، شاخص توده بدنی(تخمین تناسب قد و وزن)، استعداد ابتلا به دیابت(ژنتیک وارث)، سن و نتیجه که شامل 0 (عدم ابتلا به دیابت) و 1 (مبتلا به دیابت).
برنامه هوش مصنوعی با بررسی دیتاست یاد می گیرد تا احتمال ابتلای افراد جدید به دیابت را پیش بینی کند.

تذکر: با حذف سطرهایی از دیتاست که داده خالی یا صفر دارند، دیتا ست منطقی تر و درست تر و قطعا پیش بینی دقیق تر خواهد بود.

پس از فراخوانی فایل دیتاست، مدلی لاجستیک رگرسیون ایجاد می شود. 
0.2 درصد از سطرها (X_train( را به عنوان داده های آموزشی به همراه خروجی(Y_Train) برای یادگیری و تمرین به مدل معرفی می کنیم. 
تعدادی از سطرهای دیتاست به عنوان داده های تست بدون خروجی معرفی می شود.(X_test(
در نهایت با این داده ها، درصد درستی پیش بینی ماشین را با خروجی های دیتاست مقایسه می کنیم. 

X_test برای پیش بینی خروجی به مدل داده می شود. 
خروجی به صورت آرایه ای از صفر و یک نمایش داده می شود. 
برای هر فرد 0 به منزله ی عدم احتمال ابتلا به دیابت و 1 به منزله ی احتمال ابتلای فرد به دیابت است.
حالا با الگوی زیر می توانید احتمال ابتلای خود را به دیابت از هوش مصنوعی بپرسید:

*---نمونه داده* 
*(تعداد حاملگی، گلوکز، فشارخون، ضخامت پوست، انسولین در خون، شاخص توده بدنی(تخمین تناسب قد و وزن)، استعداد ابتلا به دیابت(ژنتیک وارث)، سن)*

```python
z = np.array([[2,100,50,35,243,30.5,0.138,36]])
example = model.predict(z)
print(example)
```

 
