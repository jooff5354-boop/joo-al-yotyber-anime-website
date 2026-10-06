# 𝗝𝗢𝗢  𝗔𝗟 𝗬𝗢𝗧𝗬𝗕𝗘𝗥 — Termux Host

## التشغيل على Termux
```bash
pkg update -y
pkg install python unzip -y
termux-setup-storage
cd ~/storage/downloads
unzip -o MERO_HOST_TERMUX.zip -d MERO_HOST_TERMUX
cd MERO_HOST_TERMUX/MERO_HOST_FINAL
python -m pip install -r requirements.txt
export DEV_USERNAME='اسم_المطور'
export DEV_PASSWORD='كلمة_سر_قوية'
export SECRET_KEY='ضع_سر_عشوائي_طويل'
python app.py
```

افتح: http://127.0.0.1:5000

- المستخدمون يدخلون من `/login`.
- المطور يدخل من `/developer-login`.
- لا يوجد تسجيل عام؛ المطور فقط ينشئ الحسابات.
- الخط المجاني: حد أقصى 2 سيرفر و2 ملف.
- الخطط المدفوعة/الاحترافية تُعيّن من لوحة المطور.
- ZIP يمكن رفعه ثم فك ضغطه من مدير الملفات.
- دعم التشغيل يعتمد على البرامج المثبتة على الجهاز (Python/Node/PHP/Ruby/Perl/Bash/Go وغيرها)، ولا يمكن للمشروع تشغيل لغة لم يتم تثبيت مشغلها.


## JOO AL YOTYBER - إعدادات المطور
- يوزر المطور الافتراضي: `@JOOFF`
- كلمة المرور الافتراضية: `YOUSSEF142026`
- يمكن تغييرهما من متغيرات البيئة `DEV_USERNAME` و `DEV_PASSWORD`.
- تواصل تلجرام وواتساب موجودان أسفل لوحة المستخدم.
