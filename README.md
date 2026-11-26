# נר חמישי בהנשיאים · Hanukkah invitation

הזמנה אינטראקטיבית להדלקת הנר החמישי של חנוכה תשפ״ז.

- **מתי:** יום שלישי, 08.12.26 · 19:00
- **איפה:** הנשיאים 12, תל אביב

סצנת "נייר חתוך" שנבנית בגלילה: חנוכייה, הדלקת נרות אחד אחד, סביבון שאפשר לסובב, ספירה לאחור ופרטי האירוע עם קישורים לוויז, גוגל מפות ויומן.

## הרצה מקומית

זה קובץ HTML יחיד, בלי שלב build. פותחים את `index.html` בדפדפן, או מריצים שרת:

```bash
npx serve .
# או
python3 -m http.server 8000
```

## פרסום ב-GitHub Pages

1. מעלים את הריפו ל-GitHub.
2. Settings → Pages → Source: **Deploy from a branch** → `main` / `root`.
3. האתר יעלה בכתובת `https://<username>.github.io/<repo-name>/`.

## טכנולוגיות

- HTML / CSS / SVG בקובץ אחד
- [GSAP 3.12.5](https://gsap.com/) + ScrollTrigger (CDN)
- [Lenis 1.1.13](https://github.com/darkroomengineering/lenis) לגלילה חלקה (CDN)
- גופנים: Fredoka, Rubik (Google Fonts)

הדף עובד גם בלי הספריות החיצוניות (בלי האנימציות של הגלילה), ומכבד `prefers-reduced-motion`.
