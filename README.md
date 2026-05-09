# Meta-Ads — Meta Ads Analyser (v2.0 PRO)

محلل إعلانات Meta بسيط، يخدم على التليفون، بدون تسجيل دخول.

## الإستعمال

افتح ملف `index.html` في أي متصفح (تليفون أو PC) — مافما حتى Backend ولا Build step.

أو حُطّو على GitHub Pages:
1. Settings → Pages → Source: `main` branch / root
2. زور الرابط مباشرة

## المنطق (Logic)

- **Strategy**: Full Funnel · Target CPA
- 10 قواعد تشخيصية مرتبة حسب الـ Priority (DISASTER_RECOVERY → SCALING)
- المؤشرات المحسوبة: CPA, CPM, CPC, CTR (All/Link), Frequency, Load Rate, ATC Rate, Checkout Drop-off, Audience Accuracy, ROAS
- المعطيات تتسجل محلياً في الـ LocalStorage (privacy-friendly)

## الميزات

- 📱 Responsive، Mobile-first، RTL
- 🔒 بدون Login / Signup / Backend
- 💾 يحفظ آخر معطيات أدخلتها على نفس التليفون
- 🎯 يبيّن أهم Action Code + التشخيص + النصيحة بالدارجة التونسية