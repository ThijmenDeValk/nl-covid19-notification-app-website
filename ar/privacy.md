---
layout: content
lang: ar
showBreadCrumbs: true
title: بيان خصوصيه تطبيق التحذير من كورونا CoronaMelder
---
بيان خصوصيه تطبيق التحذير من كورونا CoronaMelder 


## نبذه عن CoronaMelder

تطبيق التحذير من كورونا  CoronaMelder هو عبارة عن وسيلة تقنية للحدّ من انتشار فيروس كوفيد-19. بعد أن قمت بتنزيل تطبيق CoronaMelder على هاتفك، سوف تصلك رسالة فى حالة تواجدك لفتره زمنية معينة بالقرب من شخص قام بإجراء اختبار كوفيد-19 وتبين أن نتيجة الاختبار إيجابية وقام هذا الشخص أيضًا بتنزيل تطبيق CoronaMelder على هاتفه. فى حالة احتمال إصابتك عن طريق مستخدم آخر لـ CoronaMelder، سينصحك التطبيق بإجراء اختبار عند وجود أعراض. 

فيما يلى، سنشرح باختصار كيفية عملCoronaMelder .

يقوم التطبيق عن طريق Bluetooth Low Energy بالتعرّف على الهواتف الاخرى التي  تستخدم التطبيق. يتم التعرّف على الهواتف الذكية الأخرى عن طريق رموز عشوائية (سلسلة من الأرقام) تسمى بـ (RPIs) Rolling Proximity Indicators . يتم تحديث هذه الرموز كل 10 إلى 20 دقيقة وهي مشتقة مما يسمى بـ Temorary Exposure Keys (TEKs). تعد TEKs أيضًا رموزًا عشوائية، إلا أنه يتم تجديد هذه الرموز كل يوم والاحتفاظ  بها على هاتف المستخدم لمدة 14 يومًا. 

عندما يكون هاتفك بالقرب من هاتف آخر تم تثبيت التطبيق عليه، فسيتم تبادل رموزالـ RPIs بين الهواتف وتخزينها على هذه الهواتف. إذا كانت نتيجة اختباركوفيد-19 لمستخدم التطبيق إيجابية،  فمن الممكن  للمستخدم أن يقوم بإنشاء تبليغ لهذه الإصابة طواعية عن طريق التطبيق. إذا تم اختيار ذلك، فسيرسل التطبيق الـ TEKs التى تم إنشاؤها فى آخر 14 يوم  وتخزينها على الهاتف في الواجهة الخلفية للخادم. تقبل الواجهة الخلفية للخادم الـ TEKs المرسلة إذا قام كل من المستخدم وخدمة الصحة البلدية (الـGGD) تأكيد الإرسال من خلال رمز التحقق. يتم في الواجهة الخلفية للخادم تحويل الـ TEKs الى رمز آخر يسمى بـ  Diagnosis Keys (DKs) .

بعدها تقوم الواجهة الخلفية للخادم بتوفير الـ DKs للاستخدام، بحيث يتم تحميلها بشكل أوتوماتيكي عن طريق الهواتف التى تم تثبيت التطبيق عليها. عندما يقوم هاتفك باسترداد الـ DKs من الخادم، سيتم فقدان الاتصال بالخادم. تتكررهذه العمليه الآلية عدة مرات فى اليوم لمتابعة احتمالية خطر العدوى. بعدها يقوم هاتفك على أساس الـ DKs المستحضرة حساب ما إذا كان هناك تطابق مع الـ RPIs المختلفه القادمة من الهواتف الأخرى والتي كانت متواجدة بالقرب من هاتفك. بعدها مباشرة يتم حذف الـ DKs من على هاتفك.

في حالة وجود تطابق، يتم تحديد ما إذا كان هناك احتكاك محفوف بالمخاطرعلى أساس عدد من عوامل الترجيح. إذا كان الأمر كذلك, بعبارة أخرى، إذا كنت قريبًا من شخص مصاب بـ كوفيد-19، فسيتم إبلاغك بزيادة خطر الإصابة. ينصحك التطبيق أيضًا بإجراء اختبار الإصابة بالفيروس في حالة وجود أعراض. 

### 01. من المسؤول عن معالجة البيانات الشخصية؟
وزارة الصحة والرعاية الاجتماعية والرياضة هو المسؤول عن المعالجة طالما يتم معالجة البيانات الشخصية في تصميم وإدارة CoronaMelder.

طالما  تقوم الـ GGD باستخدام البيانات الشخصية التي تم الحصول عليها عبر التطبيق لتتبع المصدر والاحتكاك، فإن الـ GGD في منطقتك هي المتحكمة. من خلال الموقع <a href="https://www.ggd.nl" target="_blank" rel="noopener noreferrer">www.ggd.nl</a> يمكنك العثور على الـ GGD التي تخضع لها وذلك من خلال إدخال الرمز البريدي لعنوان منزلك. إذا لم يكن لديك عنوان سكني في هولندا، يمكنك إدخال الرمز البريدي لمكان إقامتك.

### 02.	 ما الهدف من معالجة البيانات الشخصيه؟
تم تطوير هذا التطبيق كتكملة لتتبع مصدر العدوى والاحتكاك الخاص بـالـ GGD. والغرض منه هو إعلام المستخدمين الذين هم أكثر عرضة للإصابة بطريقة سريعة وسهلة، مع الحرص الشديد على عدم  الكشف عن هويتهم.

### 03.	 أساس معالجة البيانات الشخصيه
يمكن معالجة البيانات الشخصية في التطبيق. إن أساس معالجة البيانات الشخصية هو باختصار تأدية خدمة عامة. بالنسبة  لوزارة الصحة والرعاية الاجتماعية والرياضة، فإن هذا ينطوي على الخدمة العامة، وهي باختصار إدارة مكافحة COVID-19 والحفاظ على بنية الدعم على صعيد الوطن وتحسينها.

بالنسبة لـلـ GGD، يتعلق الأمر بمهمة تتبع المصدر والاحتكاك من خلال الإشعارات عند التعرض للإصابة بـ COVID-19.

وبالتالي فإنه من خلال استخدام CoronaMelder كوسيلة دعم لتتبع المصدر والاحتكاك، يتم تأدية الخدمات العامة المذكورة أعلاه لكل من وزارة الصحة والرعاية الاجتماعية والرياضة والـ GGD.
أن استخدام CoronaMelder  طوعي. لذلك يطلب CoronaMelder موافقتك قبل أن تتمكن من استخدام التطبيق. إذا لم تقم بمنح الإذن ،فلن تتمكن من استخدام CoronaMelder. سيُطلب موافقتك أيضًا قبل أن تتمكن -إذا كان الاختبار إيجابي- من مشاركة بياناتك مع الـ GGD.

### 04.	 ما هي البيانات الشخصية التي يتم معالجتها؟
فى التطبيق يتم التعامل مع البيانات التاليه :
Rolling Proximity indicators (RPIs)
Temporary Exposure Keys (TEKs)
Diagnosis Keys (DKs)
عنوان وهمى للتعرف على الهاتف
شدة الإشارة و مدة الاتصال
أول يوم مرض
رمز التحقق 
نسبة خطر التعرض (عالية ، متوسطة ، منخفضة)
IP-adresعنوان بروتوكول الانترنت 
قد تكون هذه البيانات بيانات شخصية.

TEK هو عبارة عن سلسله من الارقام العشوائية المشفّرة تستخدم كمرجع مؤقت وهى تتحول في الواجهة الخلفية للخادم من TEKs إلى DKs. بالإضافة إلى ذلك، يتم كل 10 إلى 20 دقيقة إنشاء RPI, أي سلسلة أرقام مؤقته يتم إنشاؤها أيضًا بشكل مشفّر. يُشتق هذا التسلسل الرقمي من الـ TEK، ويتم تبادله مع الهواتف الأخرى التي تم تثبيت التطبيق عليها والتي كانت موجودة بالقرب من الهاتف المعني لفترة زمنية محددة. يتم تلقي الـ RPIs وإرسالها عبر الـ Bluetooth منخفض الطاقة. لذلك يتم استخدام الـ RPI بالتوافق مع شدة الإشارة، سواء المرسلة أم المستقبلة (لتحديد المسافة بين المستخدمين)، ومدة الاتصال (Bluetooth). سيتم حذف الـ RPIs المستلمة من الهواتف بعد 14 يومًا.

TEKs, DKs, RPIs عبارة عن مفاتيح تعريف ذات أسماء مستعارة.

للحد من مخاطر التعرف على هوية المستخدمين قدر الإمكان، يتم عند تبادل الارقام العشوائية المشفرة RPIs استبدال عنوان التعرف على الهاتف MAC-adres (وهو عبارة عن رقم جهاز فريد لناقل الـ Bluetooth)، برمز وهمي تم إنشاؤه عشوائيًا, وهو  MAC-adresمزيف. يتم تغيير هذا الرمز كما هو الحال مع الـ RPIs، كل 10 إلى 20 دقيقه .

يتم إنشاء رمز التحقق باستخدام وظيفة متوفرة ومعروضة في التطبيق. يتم استخدام رمز التحقق من قبل الـ GGD للتحقق من صحة الـ TEKs المرسلة إلى الـ GGD. تضع الـ GGD رمز التحقق هذا، مع تاريخ اليوم الأول للمرض، في بوابة الـ GGD. بوابة الـ GGD هذه متاحة فقط لموظفي الـ GGD. لا تقبل الواجهة الخلفية للخادم TEKs من المستخدمين إلا إذا تم توفير رمز تحقق تم التحقق من صحته بهذه الطريقة من قبل الـ GGD. أثناء مرحلة التحقق من الصحة، يتم معالجة الـ IP-adres  لأغراض التحكم والحماية.

بالإضافة إلى الـ DKs واليوم الأول للمرض ورمز التحقق، يتم أيضًا إرسال الـ IP-adres إلى الواجهة الخلفية للخادم. هذا مرتبط بالضرورة باستخدام الإنترنت وتكنولوجيا IP. يتم تخزين الـ IP-adres بشكل منفصل عن البيانات الأخرى، بحيث لا يتم تخزين الـ IP-adres في الواجهة الخلفية للخادم. نتيجة لذلك، لا يمكن معرفة من قام بإرسال المعلومات ولا محتوى المعلومات التي قام بإرسالها . 

### 05.	 البيانات الإحصائية
تستخدم البيانات التى تم الحصول عليها عن طريق التطبيق فقط للاغراض المذكورة في بيان الخصوصية هذا. لا يتم إنشاء معلومات إحصائية.

### 06.	 لمن يتم اعطاء البيانات الشخصية؟
يتم إرسال و استقبال الـ RPIs محليًا على الهواتف. إذا تبين أن هناك إصابة، يمكن للمستخدم أن يختار إرسال الـ TEKs الخاصة به مع رمز التحقق الفريد من نوعه الى  الواجهة الخلفية للخادم. يتم التحكم بالواجهة الخلفية للخادم بواسطة CIBG مع KPN كمقاول فرعي (معالج).

تقوم الـ GGD بمعالجة رمز التحقق في بوابة الـ GGD الالكترونية في التطبيق ، مع تاريخ اليوم الأول للمرض. يستطيع فقط موظفي الـ GGD المصرّح لهم بدخول البوابة.

تقوم الهواتف الذكية للمستخدمين الآخرين عدة مرات في اليوم باستحضار الـ DKs  الموجودة في الواجهة الخلفية للخادم.

### 07.	 حفظ البيانات الشخصيه
يتم تخزين البيانات المخزنة محليًا على هاتفك الذكي لمدة 14 يومًا. يتم حذف هذه البيانات تلقائيًا وبشكل نهائي بعد 14 يومًا. يمكنك أيضًا حذف البيانات المحفوظة بنفسك في أي وقت.

طالما يتم تخزين البيانات الخاصة بك على الجهة الحلفية للخادم، فسيتم تخزين البيانات لمدة 14 يومًا من وقت التحميل. سيتم حذف البيانات بعد 14 يومًا.

يتم حذف الـ  IP-adressen التي تم معالجتها لأغراض التحكم والحماية بعد مدة أقصاها 7 أيام.

### 08.	 حقوقك بخصوص بياناتك الشخصية
 لديك عدة حقوق من أجل التحكم في بياناتك الشخصية. يمكنك أن تجدها هنا على الصفحه الخاصة بالتحكم في البيانات الشخصية.

نظرًا لأن CoronaMelder مصمم وفقًا لمبادئ تقليل البيانات والخصوصية في التصميم، ستتمكن من المطالبة بحقوقك وفقًا للقانون العام لحماية البيانات (AVG) على نطاق محدود. فتتم معالجة نسبة محدودة من البيانات فقط. علاوة على ذلك، يكاد يكون من المستحيل تتبع البيانات ويتم تخزينها فقط لفترة قصيرة. يترتب على المادة 11 من القانون العام لحماية البيانات (AVG) بأن الحقوق الواردة في المواد 15 لغاية 20 من القانون العام لحماية البيانات (AVG) لا تنطبق إذا لم يتمكن المتحكم (بعد الآن) من تحديد هوية المعني بالأمر.

في المرحلة الأولى - وقبل تحميل المستخدمين TEK إلى الواجهة الخلفية للخادم - تتم معالجة البيانات فقط على الهواتف الذكية لمستخدمي CoronaMelder. ليس لدى وزارة الصحة والرعاية الاجتماعية والرياضة والـ GGD حق الدخول إلى هذه البيانات. لا يمكن في هذه المرحلة على سبيل المثال تلبية طلب تغيير البيانات أو حذفها، على الرغم من أن هذه البيانات ستختفي بالطبع تلقائيًا من الهاتف بعد أربعة عشر يومًا كحد أقصى.
 
بسبب تصميم التطبيق على أساس مبدأ "الخصوصية عن طريق التصميم")   (privacy by design ،لا يمكن معرفة الرموز المتعلقة بالمستخدم المصاب  حتى عند إدخال الـ TEKs ( فيما بعد DKs (. لا يمكن لوزارة الصحه والرفاهية والرياضة VWS والـ GGD من الناحية التقنية ربط الرموز المحفوظة (مؤقتًا) على الواجهة الخلفية من الخادم، بالمستخدم الذي قام بتحميل TEKs الخاصة به. نظرًا لاستحالة التعرف على هوية المستخدم عن طريق الرموز، فإن  المواد 15 لغاية 20 من قانون حماية البيانات الشخصية لا تنطبق.

وبشكل عام، ضرورة تنفيذ حقوق حماية البيانات الشخصية سيكون محدودًا، لأنه ببساطة لا يمكن تتبع بيانات المستخدم أو يمكن فقط تتبع بيانات المستخدم على نطاق محدود للغاية أو لأن هذه البيانات لم تعد متاحة بسبب فترات الاحتفاظ القصيرة الأمد. يتماشى هذا مع المادة 11 من قانون حماية البيانات الشخصية، والتي يترتب عليها أن الحقوق المدرجة في المواد 15 لغاية 20 من القانون العام لحماية البيانات لا تنطبق إذا لم يعد من الممكن تحديد هوية المعنيين بالأمر.

إلا أن إمكانية تقديم طلب للمطالبة بحقوقك المتعلقة بالخصوصية تظل قائمة. يمكنك إرسال طلبك إلى الـ GGD المسؤولة في مكان سكنك. يمكنك من خلال الموقع <a href="https://www.ggd.nl" target="_blank" rel="noopener noreferrer">www.ggd.nl</a> إدخال الرمز البريدي لعنوان سكنك لمعرفة من هي الـ GGD المسؤولة في مكان سكنك. إذا لم يكن لديك عنوان سكني في هولندا، فيمكنك إدخال الرمز البريدي لمكان إقامتك.

لديك دائمًا الحق في تقديم شكوى بخصوص معالجة بياناتك الشخصية إلى هيئة حماية البيانات الهولندية أو إلى المحكمة. يمكنك العثورعلى المزيد من المعلومات حول هذا هنا.

يمكن العثور على تفاصيل الاتصال الخاصة بمسؤول حماية البيانات لدى الـ GGD المسؤولة في مكان إقامتك عبر الموقع الالكتروني  لمكتب الـ GGD هذا.

يمكن العثور على تفاصيل الاتصال بمسؤول حماية البيانات في وزارة الصحة والرعاية الاجتماعية والرياضة على الموقع الإلكتروني لهذه الوزارة.

### 09.	 حماية بياناتك الشخصية
يأخذ كل من وزير الصحة والرعاية الاجتماعية والرياضة والـGGD  حماية بياناتك على محمل الجد ويتخذان التدابير المناسبة لمنع سوء الاستخدام والضياع  والوصول غير المصرح به إلى هذه البيانات والنشر غير المرغوب فيه أو إدخال التعديلات غير المصرّح بها.

### 10 .	 تغيير فى البيانات الشخصيه 
أن بيان الخصوصية هذا عرضة للتغيير. سنقوم في هذه الحالة بنشر بيان الخصوصية المعدّل على موقعنا، وسيصبح بيان الخصوصية هذا بعدها مباشرة ساري المفعول. آخر تحديث: 10 سبتمبر/أيلول 2020
