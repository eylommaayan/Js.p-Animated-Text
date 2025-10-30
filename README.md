<img width="625" height="579" alt="image" src="https://github.com/user-attachments/assets/9d9e0924-484d-4852-bf13-c8ad1585ecca" />



מצוין 👇
הנה גרסת **README.md** מעוצבת ומוכנה להעתקה ישירות ל־GitHub — כולל כותרות, אמוג׳ים ותצוגת תמונה שתראה טוב בעמוד הפרויקט שלך:

---

```markdown
# ✨ אפקט טקסט אוטומטי (Typing Effect)

### 🎯 תיאור הפרויקט  
פרויקט זה מדגים איך ליצור **אפקט כתיבה אוטומטית** בעזרת **JavaScript, HTML ו־CSS**, שבו הטקסט נכתב מחדש שוב ושוב על המסך — והמשתמש יכול לשלוט במהירות האנימציה.

<p align="center">
  <img src="https://user-images.githubusercontent.com/0000000/auto-text-effect-demo.gif" alt="Auto Typing Effect Demo" width="500">
</p>

---

## 🧠 מה נלמד כאן
🔹 שליטה ב־DOM באמצעות `document.getElementById()`  
🔹 שימוש ב־`setTimeout()` ליצירת אנימציה מבוססת זמן  
🔹 חיתוך מחרוזות בעזרת `slice()`  
🔹 האזנה לאירועים בזמן אמת עם `addEventListener()`  
🔹 עיצוב מודרני בעזרת CSS ו־Flexbox  

---

## 🧩 מבנה הקבצים
```

📂 auto-text-effect/
├── index.html     # מבנה הדף
├── style.css      # עיצוב הדף
└── script.js      # לוגיקת האפקט

````

---

## ⚙️ איך מפעילים
1. הורד את הקבצים או שכפל את המאגר:
   ```bash
   git clone https://github.com/your-username/auto-text-effect.git
````

2. פתח את הקובץ `index.html` בדפדפן שלך.
3. שנה את הערך בתיבת "מהירות" כדי לשלוט במהירות ההקלדה.

---

## 💡 קטע קוד מרכזי

```js
const textEl = document.getElementById('text')
const speedEl = document.getElementById('speed')
const text = 'We Love Programming!'
let idx = 1
let speed = 300 / speedEl.value

function writeText() {
  textEl.innerText = text.slice(0, idx)
  idx++
  if (idx > text.length) idx = 1
  setTimeout(writeText, speed)
}

speedEl.addEventListener('input', (e) => speed = 300 / e.target.value)
writeText()
```

---

## 🎨 עיצוב בסיסי (style.css)

```css
body {
  background-color: rgb(173, 186, 214);
  font-family: 'Roboto', sans-serif;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
  margin: 0;
}
```

---

## 🚀 רעיונות להרחבה

* הוסף כפתור **Pause / Resume** לעצירת האפקט.
* אפשר למשתמש לבחור טקסט חדש להזנה.
* הוסף צבע משתנה לכל אות שנכתבת.
* הוסף תמיכה בעברית עם כיוון RTL.

---

## 🧩 טכנולוגיות בשימוש

* HTML5
* CSS3
* JavaScript (Vanilla JS)

---

## 👨‍💻 נכתב כחלק מקורס JavaScript למתחילים

פרויקט זה נועד להמחיש עקרונות חשובים:

* שליטה באלמנטים דרך ה־DOM
* שימוש בלולאות זמן (Timers)
* יצירת אנימציות פשוטות בקוד
* שילוב בין עיצוב, מבנה ולוגיקה



### ⭐️ אם אהבת – אל תשכח ללחוץ על ★ ב־GitHub!


