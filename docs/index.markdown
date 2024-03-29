---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: תלוש השכר - מדריך למתחילים
description: מדריך לחישוב סעיפי הצעת השכר, לרבות כל סעיפי התלוש ומענקי המניות לעובדים
date: 2024-01-11 10:30:00 +0200
---

<center>
<h2>הקדמה</h2>
</center>
בבלוג הזה אעבור נושא-נושא במטרה להראות שלקרוא (ולהבין) את תלוש השכר שלנו זו לא משימה בלתי אפשרית, ושמדובר בנושאים פשוטים שאין סיבה שלא נבין. כחלק מזה, הבלוג כולל מחשבוני שכר מברוטו לנטו, כדי שכשנקבל הצעת שכר נוכל לדעת מה השורה התחתונה שלה.

להלן לינק לטבלאות פומביות לחישוב **כל** סעיפי תלוש השכר לשכירים (ברוטו לנטו, מס הכנסה, ביטוח לאומי, תנאים סוציאליים, הכל), מחולקות לפי כל שנת מס החל משנת 2018: [לינק](https://drive.google.com/drive/folders/1JZmJg2pkD97mQ_fJOBcbuyMOiO_fFsCr?usp=sharing).

המחשבונים (כמו האתר הזה) הם קוד פתוח (open source) כך שאתם יותר ממוזמנים לעיין, להחכים ואפילו לשלוח הצעות לתיקונים ושיפורים במידה ומצאתם כאלה. על המיסוי שמאחורי הנוסחאות השונות שבמחשבונים אני אפרט במאמרים על סעיפי התלוש המתאימים כדי שנדע לא רק "מה" אלא גם "למה".

<center>
<h2>על תלוש השכר</h2>
</center>

<ul>
  {% for post in site.tags["payslip"] reversed %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

<center>
<h2>מענקי מניות לעובדים</h2>
</center>

<ul>
  {% for post in site.tags["stocks"] reversed %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

<center>
<h2>על עצמי</h2>
</center>
הכותב **אינו** רו"ח או יועץ פיננסי/פנסיוני ואין להתייחס לתוכן אתר זה כאל יעוץ כלכלי מכל סוג שהוא. הכותב (אני) בסה"כ שכיר בהייטק שמנסה לעשות סדר במושגי יסוד לרווחת שכירים אחרים. בניגוד לבלוגים כאלה ואחרים שראיתי ברחבי הרשת, אין לי שום כוונה להפיק רווח אישי מהבלוג. אני לא מעביר סדנאות מודעות פיננסית בתשלום, אני לא מקבל כסף מפרסום בבלוג, כלום. המטרה בשיתוף טבלאות לחישוב השכר, ופרסום הפוסטים השונים המפרטים את סעיפי החישוב השונים, היא לחלוק עם הציבור את המסקנות שהגעתי אליהן בתהליך פיענוח תלוש השכר הישראלי במטרה להנגיש את המידע לציבור הרחב. קריאה מהנה
