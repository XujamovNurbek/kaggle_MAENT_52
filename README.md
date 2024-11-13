#UZ
# Ish bajarish davomida quyidagilarni amalga oshirdim.
## 1. Birinchi o'rinda bizga kerak bo'lishi mumkin bo'lgan kutubxonalarni chaqirib oldim.
## 2. Keyin esa bizga berilgan datasetni yuklab oldim va uni ochib undagi ma'lumotlarni ko'rib chiqdim.
## 3. Ular haqida iloji boricha ma'lumot olishga harakat qilib  aynan ustunning nomi bo'yicha bizda shu ustunda qanday qiymatlar kelishi mumkinligi to'g'risida ma'lumotlar oldim va berdim.
## 4. Datasetni tekshirib chiqdim, undagi NaN qiymatlar bor yoki yuqligi va shunga o'xshash ma'lumotlarni ko'rib chiqdim.
## 5. Men berilgan ma'lumotlar snosida yana qanday ustunlar hosil qilishim mumkinligi haqida ham ancha bosh qotirdim. Va bir necha ustun ham hosil qildim, lekin ulardan faqat ikkitasini qoldirdim. Sababi ulargina menga ko'proq ma'lumot bera olishi mumkin ekan.
## 6. Hammasi tugagach  koralatsiyasini tekshirdim va bir-biriga bo'liqlik darajasini tekshirdim, ularda menga juda kam ma'lumot olib kegan ustunlar ham bor edi. Ularni o'chirib ko'rib model yasab ko'rdim va o'chirmasdan ham model yasab ko'rdim alohida alohida ikkisi uchun ham ishladim.
## 7. Optuna orqali RandomForestRegressor uchun eng yaxshi giperparametrlarni aniqladim va bunda oraliqlarni va aylanishlar sonini turlicha qilib ko'rdim. Eng ko'p kutgan vaqtim 8 soat 1 daqiqa va 3.1 soniya bo'ldi.
## 8. StackingRegressor orqali bir nechta modellarni birlashtirb ko'rdim va bu uchun ham ishlab ko'rdim.



#EN
# During the work, I did the following.
## 1. First, I called the libraries that we might need.
## 2. Then I downloaded the dataset that was given to us, opened it, and looked at the data in it.
## 3. I tried to get as much information about them as possible, and based on the name of the column, I got and gave information about what values ​​​​we can get in this column.
## 4. I checked the dataset, whether there are NaN values ​​​​in it, and looked at similar information.
## 5. I also thought a lot about what other columns I could create in the given data set. And I created several columns, but I left only two of them. The reason is that only they can give me more information.
## 6. When everything was done, I checked the correlation and the degree of dependence on each other, there were also columns that gave me very little information. I tried deleting them and building a model, and I tried building a model without deleting them, and I worked on both separately.
## 7. I determined the best hyperparameters for RandomForestRegressor using Optuna, and I tried varying the intervals and the number of iterations. The longest I waited was 8 hours 1 minute and 3.1 seconds.
## 8. I tried combining several models using StackingRegressor and worked on this too.

#RU
# Во время выполнения я сделал следующее.
##1. В первую очередь я назвал библиотеки, которые могут нам понадобиться.
## 2. Затем я скачал предоставленный нам набор данных, открыл его и посмотрел данные в нем.
##3. Пытаясь получить о них как можно больше информации, я получил и отдал информацию о возможных значениях в этом столбце по названию столбца.
## 4. Я проверил набор данных, чтобы узнать, есть ли в нем значения NaN и тому подобное.
## 5. Я также не понимаю, какие еще столбцы я могу создать в данном наборе данных. И я тоже сделал несколько столбцов, но оставил только две из них. Потому что только они могут дать мне больше информации.
## 6. Когда все было сделано я проверил корреляцию и проверил степень перекрытия, были столбцы, которые давали мне очень мало информации. Пробовал сделать модель с их выключенными, и пробовал сделать модель не выключая, у меня работало на двоих отдельно.
##7. С помощью Optuna я определил лучшие гиперпараметры для RandomForestRegressor, варьируя интервалы и количество итераций. Моё самое долгое ожидание составило 8 часов 1 минуту и ​​3,1 секунды.
## 8. Попробовал объединить несколько моделей с помощью StackingRegressor, тоже получилось.
