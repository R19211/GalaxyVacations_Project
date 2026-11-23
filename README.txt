GALAXY VACATIONS – פרויקט HTML + CSS

מבנה:
index.html                  דף הבית (קובץ הכניסה)
favicon.ico                 אייקון האתר
css/style.css               עיצוב משותף לכל הדפים
css/home.css                עיצוב ייחודי לדף הבית
css/about.css               עיצוב ייחודי לדף אודות
css/order.css               עיצוב ייחודי לטופס
css/success.css             עיצוב ייחודי לדף האישור
css/products.css            עיצוב משותף לשני דפי המוצרים
pages/                      כל שאר דפי ה-HTML
assets/images/              תמונות SVG מקוריות
assets/files/               מדריך PDF להורדה

איך לפתוח:
1. חלצו את קובץ ZIP לתיקייה.
2. פתחו ב-Visual Studio Code את התיקייה GalaxyVacations.
3. פתחו את index.html בדפדפן (מומלץ Live Server).

נושאים שנעשה בהם שימוש:
- Flexbox: header-inner, main-nav, feature-row, info-strip.
- Grid: hero, cards, order-layout, form-grid.
- Position: header.site-header הוא sticky; order-aside הוא sticky במסכים רחבים; hero-bubble הוא absolute.
- Display: flex, grid, block.
- Media Queries: התאמת התפריט, הכרטיסיות, הטופס והפריסה למסכים קטנים.
- אנימציות: float בתמונת דף הבית ו-glow בדף האישור.
- נושאים ללמידה עצמית:
  1. CSS variables – משתנים המוגדרים ב-:root ומשמשים לצבעים ולצללים כדי לשמור על אחידות.
  2. CSS animations – @keyframes float ו-glow ליצירת תנועה והדגשה.

הערה:
הטופס משתמש ב-action לדף success.html ומדמה שליחה. אין שרת אמיתי ואין שמירה של פרטי משתמש.
כל התוכן, המחירים וזמני הטיסה הם דמיוניים לצורך הפרויקט.
