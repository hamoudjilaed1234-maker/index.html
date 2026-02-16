# index.html
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>نتيجة الاختبار</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            direction: rtl;
            text-align: center;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 600px;
            margin: 20px auto;
            background: #fff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }
        .header {
            color: green;
            font-size: 18px;
            margin-bottom: 20px;
        }
        .result-table {
            width: 100%;
            border-collapse: collapse;
        }
        .result-table th, .result-table td {
            border: 1px solid #ddd;
            padding: 10px;
        }
        .result-table th {
            background-color: #f1f1f1;
        }
        .result-table .green-cell {
            background-color: #98e66c;
            font-weight: bold;
            color: white;
        }
        .qr-code {
            margin: 20px 0;
        }
        .important-note {
            color: red;
            font-size: 14px;
            margin-top: 20px;
        }
        .button {
            margin-top: 20px;
        }
        .button button {
            background-color: #33cc66;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
        }
        .button button:hover {
            background-color: #28a745;
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="https://via.placeholder.com/150" alt="شعار المجلس الطبي">
        <div class="header">تمت المطابقة بنجاح</div>
        <table class="result-table">
            <tr>
                <th>اسم المتقدم</th>
                <th>الاختبار</th>
                <th>المحافظة</th>
                <th>التخصص</th>
                <th>النتيجة</th>
            </tr>
            <tr>
                <td>حمود علي علي جديد</td>
                <td>الأول 2026</td>
                <td>صنعاء</td>
                <td>بكالوريوس الطب</td>
                <td class="green-cell">موافق</td>
            </tr>
        </table>
        <div class="qr-code">
            <img src="https://via.placeholder.com/200" alt="QR Code">
        </div>
        <div class="important-note">
            تعميم هام للمتقدمين (الناجحين في اختبار الكفاءة)<br>
            عليهم الحضور إلى المجلس الطبي لغرض استكمال إجراءات استخراج ترخيص مزاولة المهنة.
        </div>
        <div class="button">
            <button onclick="window.print()">طباعة</button>
        </div>
    </div>
</body>
</html>
````

### الطريقة:
1. قم بإنشاء ملف باسم `index.html`.
2. انسخ الكود أعلاه والصقه في الملف.
3. ضع صورة شعار المجلس الطبي في رابط الصورة (`<img src="URL">`) أو استخدم الصورة المرسلة عندك حسب الحاجة.
4. افتح الملف في المتصفح لرؤية النتيجة، ويمكنك طباعة النتيجة عند النقر على زر "طباعة".

إذا كنت تريد تحسيناً إضافياً أو إضافة ميزات مثل تخزين البيانات باستخدام **LocalStorage**، فأخبرني وسأقوم بمساعدتك!
