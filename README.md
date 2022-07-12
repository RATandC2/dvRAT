<div dir="rtl">
# dvRAT

بسم الله الرحمن الرحيم

مشروع : dvRAT<br/>
نسخة : 0.0.1 تجريبية

----------------------------------------------------------------------------------------------------------------------------------------------------------------

دڤرات هو عبارة عن مشروع يتكون من سيرفر وبرمجية خبيثة تقوم بالتحكم بها عن طريق السيرفر بإرسال أوامر لها وهي تقوم بالتنفيذ .

----------------------------------------------------------------------------------------------------------------------------------------------------------------

# معلومات عن المشروع

البيئة التطويرية الخاصة بالمشروع: Visual Studio
<br/>
اللغات البرمجية المستعملة في المشروع: C#, C
<br/>
إسم السليوشن الخاصة بالمشروع: dvRAT
<br/>
إسم المشروع الخاص بالسيرفر: CSServer
<br/>
إسم المشروع الخاص بالكلاينت: Cclient
<br/>


# مسارات المشروع

dvrat.sln (السليوشن)
<br/>
Server/ (الملف الحاوي للمشروع)
<br/>
"يحتوي بداخله ايضا على ملفات الاكواد الخاصه بالسيرفر وايضا الكلاينت لكن الكلاينت يوجد في ملف اخر داخله"
<br/>
<br/>
Server/res (ملف ال resources)
<br/>
"يحتوي على ايقونات وملفات يتم استعمالها من السيرفر اثناء التشغيل وايضا يحتوي على مشروع ال Cclient الخاص بالبرمجية الخبيثه او الكلاينت"
<br/>
<br/>
Server/res/Client (الملف الحاوي لمشروع وملفات البرمجية الخبيثة)
<br/>
"يحتوي هذا الملف على الاكواد ومشروع البرمجية الخبيثة"<br/>

# اسألة محتمله

- لماذا يوجد مشروع البرمجية الخبيثة في ملف مرجعي / resource؟

- بشكل مبسط لأن الكود الخاص بالبرمجية الخبيثه يفترض ان يتم بنائه من خلال برنامج السيرفر وتخصيص بعض المعلومات مثل المستضيف(HOST) و المنفذ(PORT) من خلال السيرفر ثم يتم وضعها في الكود لكن هذا سيكون في النسخه النهائية وليس في النسخ التجريبية .

- ما التقدم الذي احرزته في المشروع للان؟

- افضل تقدم احرزته هو اني اضفت خاصية تصفح الملفات في جهاز الضحية ليست بالشكل الكامل او الي اتمناه لكن شيء احسن من لاشيء .

# أهداف المشروع

١- تغيير العادة والفكرة النمطية لبرامج ال RAT انها تكون مبرمجة بلغات عالية المستوى مثل .Net او Go في هذا المشروع البرمجية الخبيثة بالكامل مبرمجة بلغة C بدون استعمال اي مكتبة طرف ثالث .

٢- يكون المشروع مطورينه عرب فقط والتحديثات المكتوبه عنه باللغة العربية .

٣- أن يكون مشروع متكامل بحيث كل شيء تحتاجه في برمجية خبيثة تسطيع ان تجده في دڤرات .
</div>
