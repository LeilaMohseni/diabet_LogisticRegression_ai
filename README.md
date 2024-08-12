## English Readme...
A dataset containing information on 393 individuals is provided to the program. The information includes factors influencing the likelihood of developing diabetes, such as:
Number of pregnancies
Glucose levels
Blood pressure
Skin thickness
Insulin levels in the blood
Body Mass Index (BMI) (estimate of height and weight fitness)
Genetic predisposition to diabetes
Age
Result, which includes 0 (not diabetic) and 1 (diabetic). The artificial intelligence program learns by analyzing the dataset to predict the likelihood of new individuals developing diabetes.

Note: By removing rows from the dataset that contain empty or zero values, the dataset becomes more logical and accurate, leading to more precise predictions.

After loading the dataset file, a logistic regression model is created.

0.2 percent of the rows (X_train) are introduced to the model as training data along with the output (Y_Train) for learning and practice.

Some rows of the dataset are introduced as test data without output (X_test).

Finally, with this data, we compare the machine’s prediction accuracy with the dataset's outputs.

X_test is given to the model for output prediction.

The output is displayed as an array of zeros and ones.

For each individual, 0 indicates a low probability of developing diabetes, and 1 indicates a higher probability of developing diabetes.

Now, you can ask the AI about your own likelihood of developing diabetes using the following pattern:

---Sample data (Number of pregnancies, glucose levels, blood pressure, skin thickness, insulin levels in the blood, BMI (estimate of height and weight fitness), genetic predisposition to diabetes, age)

z = np.array([[2, 100, 50, 35, 243, 30.5, 0.138, 36]])

example = model.predict(z)

print(example)


## persion Readme...
دیتاستی شامل اطلاعات 393 نفر به برنامه داده می شود. اطلاعاتی تأثیرگذار بر ابتلا به دیابت از قبیل: تعداد حاملگی، گلوکز، فشارخون، ضخامت پوست، انسولین در خون، شاخص توده بدنی(تخمین تناسب قد و وزن)، استعداد ابتلا به دیابت(ژنتیک وارث)، سن و نتیجه که شامل 0 (عدم ابتلا به دیابت) و 1 (مبتلا به دیابت). برنامه هوش مصنوعی با بررسی دیتاست یاد می گیرد تا احتمال ابتلای افراد جدید به دیابت را پیش بینی کند.

تذکر: با حذف سطرهایی از دیتاست که داده خالی یا صفر دارند، دیتا ست منطقی تر و درست تر و قطعا پیش بینی دقیق تر خواهد بود.

پس از فراخوانی فایل دیتاست، مدلی لاجستیک رگرسیون ایجاد می شود. 0.2 درصد از سطرها (X_train( را به عنوان داده های آموزشی به همراه خروجی(Y_Train) برای یادگیری و تمرین به مدل معرفی می کنیم. تعدادی از سطرهای دیتاست به عنوان داده های تست بدون خروجی معرفی می شود.(X_test( در نهایت با این داده ها، درصد درستی پیش بینی ماشین را با خروجی های دیتاست مقایسه می کنیم.

X_test برای پیش بینی خروجی به مدل داده می شود. خروجی به صورت آرایه ای از صفر و یک نمایش داده می شود. برای هر فرد 0 به منزله ی عدم احتمال ابتلا به دیابت و 1 به منزله ی احتمال ابتلای فرد به دیابت است.

حالا با الگوی زیر می توانید احتمال ابتلای خود را به دیابت از هوش مصنوعی بپرسید:

---نمونه داده (تعداد حاملگی، گلوکز، فشارخون، ضخامت پوست، انسولین در خون، شاخص توده بدنی(تخمین تناسب قد و وزن)، استعداد ابتلا به دیابت(ژنتیک وارث)، سن)


z = np.array([[2, 100, 50, 35, 243, 30.5, 0.138, 36]])

example = model.predict(z)

print(example)

