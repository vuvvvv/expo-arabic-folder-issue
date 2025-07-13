# expo arabic folder issue 
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;

عند تشغيل مشروع React Native باستخدام Expo Go، قد تواجه مشكلة في عدم تعرف التطبيق على المشروع أو عدم عمله بشكل صحيح.
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;


# مشكلة تطبيق Expo Go 

&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
**رسالة الخطاء*
![رسالة الخطاء من التطبيق ](Im/فشل_wrong.jpg)

&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;


**عدم تعرف تطبيق Expo Go على المشروع يعود إلى أن مسار ملف المشروع يحتوي على أحرف عربية، حتى لو تم تغيير لغة النظام إلى الإنجليزية. السبب هو أن بعض المجلدات (مثل مجلد المستخدم) تبقى باللغة العربية إذا كانت لغة تثبيت نظام ويندوز الأصلية هي العربية، وهذا يؤدي إلى مشاكل في تشغيل المشروع عبر Expo Go.**

&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
**مسار خطاء*
![السبب](Im/مسار_يوجد_فيه_كلمة_عربية.JPG)
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;


 # الحل 
 &nbsp;&nbsp;&nbsp;
 &nbsp;&nbsp;&nbsp;

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  **نقل المشروع الى القرص C:// مباشرة**
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  &nbsp;&nbsp;&nbsp;
  &nbsp;&nbsp;&nbsp;

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
**مسار صحيح*
  ![الحل تجنب مسار يوجد به كلمة عربية ](Im/مسار_مباشر_من_C.JPG)
 &nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;


*النتيجة*
 ![البرنامج يعمل بشكل جيد بعد تغير المسار ](Im/work_fine.jpg)

 &nbsp;&nbsp;&nbsp;
 &nbsp;&nbsp;&nbsp;
 &nbsp;&nbsp;&nbsp;
 &nbsp;&nbsp;&nbsp;
 &nbsp;&nbsp;&nbsp;
 **الحل اخر تثبيت نظام الويندوز باللغة الإنجليزية من البداية أفضل للمبرمجين لتجنب كثير من المشاكل المستقبلية في التعامل مع الأدوات والبيئات التطويرية.**
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

**موقع يوضح صعوبة اللغه العربية في البرمجة بشكل عام*
![اللغه العربية من اصعب اللغة تطبيقا في البرمج بسبب طريقة الكتابة ](https://www.w3.org/International/alreq/images/laam-alef-ligature.png)
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
اتمنى ان تكون المشكلة حلة
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

@vuvvvv



 
