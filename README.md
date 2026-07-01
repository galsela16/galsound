# אתר גל הגברה ותאורה

אתר סטטי (HTML/CSS/JS פשוט, בלי צורך בבנייה/Node) לעסק "גל הגברה ותאורה".

## מבנה הקבצים

- `index.html` — דף הבית
- `about.html` — אודות
- `services.html` — שירותים
- `gallery.html` — גלריית תמונות (עם מסגרות ריקות שממתינות לתמונות)
- `contact.html` — צור קשר
- `styles.css` — כל העיצוב
- `script.js` — תפריט מובייל + שנה בפוטר
- `images/` — כאן יוכנסו התמונות בהמשך

## איך מעלים ל-GitHub Pages (בלי דומיין)

1. היכנס ל-github.com וצור ריפוזיטורי חדש (Public), למשל בשם `gallight`.
2. העלה את כל הקבצים מהתיקייה הזו לריפוזיטורי (Add file → Upload files, או git push).
3. בריפוזיטורי: Settings → Pages.
4. תחת "Build and deployment" → Source, בחר **Deploy from a branch**.
5. בחר את הענף `main` והתיקייה `/ (root)`, ולחץ Save.
6. אחרי דקה-שתיים האתר יהיה זמין בכתובת:
   `https://<שם-המשתמש-שלך>.github.io/gallight/`

## עדכון תוכן בעתיד

- טקסטים: פותחים את קובץ ה-HTML הרלוונטי ועורכים ישירות.
- תמונות: ראו את הקובץ `images/README.txt`.
- צבעים/עיצוב: כל הצבעים מוגדרים למעלה בקובץ `styles.css` תחת `:root`.
