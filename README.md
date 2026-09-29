# قاموس التحريك · Motion Lexicon

مرجع مصوّر بالعربي والإنجليزي لكل ما تحتاجه قبل التحريك بالذكاء الاصطناعي.
An illustrated Arabic/English reference for everything you need before animating with AI.

- 255 مصطلح حركة بمثال حي وبرومبت جاهز للنسخ / 255 motion terms with live demos and copy-ready prompts
- حركات الكاميرا، اللقطات والزوايا والتكوين، حركة الموضوع والبيئة، الإضاءة، السرعة والعدسة، الانتقالات
- موشن الـ UI والموشن جرافيك
- مُركّب برومبت، قائمة مراجعة، حلول المشاكل الشائعة، وقاموس مصطلحات

صفحة واحدة بدون أي مكتبات أو build. / Single static page, no dependencies or build step.

## النشر على GitHub Pages
1. ارفع الملفات لجذر الريبو (`index.html`, `favicon.svg`, `.nojekyll`).
2. Settings → Pages → Source: **Deploy from a branch** → Branch: `main` / `(root)` → Save.
3. الموقع يظهر بعد دقيقة أو اثنتين على `https://USERNAME.github.io/REPO/`.

## الدومين: motioneffectname.com
ملف `CNAME` في الريبو فيه الدومين. في لوحة DNS عند مزوّد الدومين أضف:

| Type | Name | Value |
|---|---|---|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| AAAA | @ | 2606:50c0:8000::153 |
| AAAA | @ | 2606:50c0:8001::153 |
| AAAA | @ | 2606:50c0:8002::153 |
| AAAA | @ | 2606:50c0:8003::153 |
| CNAME | www | USERNAME.github.io |

ثم Settings → Pages → Custom domain → `motioneffectname.com` → Save، وبعد ما يتفعل الـ DNS فعّل **Enforce HTTPS**.
