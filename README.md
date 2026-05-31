# HEALEL — אמאלה אני אמא

## הוראות התקנה

### 1. העלאה ל-GitHub
1. כנסי ל-github.com וצרי Repository חדש בשם `healel-site`
2. סמני **Public** ולחצי Create
3. לחצי על "uploading an existing file"
4. גרורי את כל הקבצים מהתיקייה לדף

### 2. חיבור ל-Netlify
1. כנסי ל-netlify.com
2. לחצי **Add new site** → **Import an existing project**
3. בחרי **GitHub** → בחרי את `healel-site`
4. לחצי **Deploy site**

### 3. הפעלת Git Gateway (חובה!)
1. ב-Netlify: **Site settings** → **Identity** → **Enable Identity**
2. גללי למטה → **Git Gateway** → **Enable Git Gateway**
3. חזרי ל-Identity → **Invite users** → הכניסי את המייל שלך

### 4. כניסה לעורך
- כנסי ל: `https://שם-האתר-שלך.netlify.app/admin`
- קבלי את ההזמנה במייל → הגדירי סיסמה
- ערכי תוכן!

## מבנה הקבצים
- `index.html` — האתר עצמו
- `admin/` — ממשק העריכה
- `content/*.json` — קבצי התוכן הניתנים לעריכה
