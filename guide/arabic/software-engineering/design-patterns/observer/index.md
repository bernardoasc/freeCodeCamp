---
title: Observer pattern
localeTitle: نمط المراقب
---
يقدم نموذج Observer نموذج اشتراك حيث تشارك الكائنات في حدث ويتم إعلامك عند وقوع الحدث.

## نمط المراقب

هذا النمط هو أساس البرمجة المعتمدة على الحدث. في Front End Development ، يعد هذا نمطًا أساسيًا لتوسيع نطاق منطق التطبيق الخاص بك. في هذا النمط ، تحدث فرقاً بين **الموضوع** **والمراقبين** . الموضوعات هي الأحداث نفسها مثل _نقرة_ أو _ضغطة مفتاح_ أو إشارة من الخادم. يتم إعلام جميع **المراقبين** المشتركين عندما تتغير حالة الموضوع (عند إطلاق الحدث). لمزيد من المعلومات حول الأحداث اقرأ هنا [برمجة Evenet Drived](https://www.technologyuk.net/software-development/designing-software/event-driven-programming.shtml)

### الاشتراك

تتمثل ميزة هذا النمط في وجود مجموعة من الكائنات المشتركة التي تستجيب لحدث ما بدلاً من استدعاء دالة على كل كائن يجب إعلامه. ميزة أخرى هي أن المراقبين مشتركين من خلال واجهة ، والتي تسمح للتغييرات في وظيفة الحدث ليكون فقط داخل الوظيفة.

## موارد آخرى

رمز المثال وأكثر في [Observer Design Pattern](http://www.dofactory.com/javascript/observer-design-pattern)