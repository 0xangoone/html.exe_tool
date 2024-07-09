# html.exe
![html exe](https://github.com/MRbreaddz/html.exe_tool/assets/170880303/57d916cd-3684-4369-a730-784f9ed9fb1a)
# هي اداة بسيطة تسمح لك بتحويل مشاريعك الي تطبيق ويندوز 


# مع القدرة على تغيير الايقونة و الاسم

# تم تطويرها بأستخدام

[pyside2](https://pypi.org/project/PySide2/)

[pyinstaller](https://pypi.org/project/pyinstaller/)

[bs4](https://pypi.org/project/beautifulsoup4/)

# الاسئلة

# هل هذه الاداة مجانية؟

نعم, انها مجانية و مفتوحة المصدر


# هل هذه الاداة بالفعل تقوم بتحويل html الى exe?

في الحقيقة لا, هذه الاداة تقوم بأنشاء تطبيق webview لتشغيل مشروعك من خلال البرنامج

مع  القدرة على تغيير الايقونة و اسم البرنامج


# ما هي متطلبات هذه الاداة؟

ستحتاج ويندوز 7 مع تحديث SP1 او اعلى

مع بيثون 3.8 او اعلى


# انا لدي ويندوز 7 لكن لا يمكنني استخدام الاداة

ببساطة , قم بتحميل تحديث SP1 من موقع ميكروسوفت الاصلي

في حالة انك تملك التحديث قم بأستخدام هذا الامر داخل مجلد الاداة

    pip install -r requirement.txt

# كيف اغير عنوان النافذة؟

عنوان النافذة هو نفسه عنوان مشروعك الموجود في ملف index.html

# هل توجد طريقة لتجربة مشروعي قبل تصديره؟

نعم توجد طريقة 

فقط شغل هذا الملف main.py

# هل يمكن التعديل على ملفات المشروع بعد عملية التصدير؟

بعد التحديث 0.2.1 اصبحت الملفات الخاصة بالمشروع مخزنة داخل ملف exe مما يعني انه لا توجد طريقة للتعديل على المشروع بعد التصدير

# كيف استخدم هذه الاداة


قم بتحميل الاداة

بعد تحميل الاداة قم بفك ضغط الملف

ثم ادخل الي مجلد الاداة و استخدم هذا الامر داخل cmd

    pip install -r requirement.txt

ثم انقل ملف مشروعك داخل مجلد الاداة (بشرط ان يكون اسم الملف index.html)

لا بأس اذا كان مشروعك عبارة عن ملفات متفرقة (script1.js ,script2.js , styles.css)
 
فقط ادخل جميع ملفات المشروع هناك

ثم قم بتغيير ايقونة المشروع (icon.png)

ثم شغل الملف التالي setup.py

بعد انتهاء عمليت التحويل اذهب الي المجلد صاحب الاسم التالي
dist

سوف تجد مجلد اسمه main هنالك سوف تجد التطبيق الخاص بك
