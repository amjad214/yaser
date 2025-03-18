<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الأستاذ القدير ياسر عبود - رمضان كريم</title>
    <style>
        /* تنسيق عام */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #1e1e1e; /* خلفية داكنة */
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            direction: rtl; /* للنصوص العربية */
            color: #f0f0f0; /* لون النص */
        }

        /* تنسيق العنوان */
        h1 {
            font-size: 3em;
            color: #f0f0f0;
            animation: fadeIn 2s ease-in-out;
            position: relative;
            text-align: center;
            padding: 20px; /* إضافة مسافة داخلية */
        }

        /* تأثير التحويم */
        h1:hover {
            color: #f39c12; /* لون ذهبي */
            transform: scale(1.1);
            transition: all 0.3s ease;
        }

        /* تأثير الظهور */
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* تأثير الإضاءة */
        h1::after {
            content: '';
            display: block;
            width: 100%;
            height: 3px;
            background-color: #27ae60; /* لون أخضر */
            transform: scaleX(0);
            transition: transform 0.3s ease;
        }

        h1:hover::after {
            transform: scaleX(1);
        }

        /* زخارف رمضانية */
        .decoration {
            position: absolute;
            font-size: 1.5em;
            color: #f1c40f; /* لون ذهبي */
        }

        .moon {
            top: -40px; /* زيادة المسافة من الأعلى */
            left: -60px; /* زيادة المسافة من اليسار */
        }

        .star {
            top: -40px; /* زيادة المسافة من الأعلى */
            right: -60px; /* زيادة المسافة من اليمين */
        }

        /* توهج النص */
        h1 {
            text-shadow: 0 0 10px #f1c40f, 0 0 20px #f1c40f, 0 0 30px #f1c40f;
        }
    </style>
</head>
<body>
    <h1>
        <span class="decoration moon">🌙</span> <!-- هلال -->
        الأستاذ القدير ياسر عبود
        <span class="decoration star">🌟</span> <!-- نجمة -->
    </h1>

    <script>
        // تأثيرات إضافية باستخدام JavaScript
        const title = document.querySelector('h1');

        title.addEventListener('mouseover', () => {
            title.style.textShadow = '0 0 15px #f1c40f, 0 0 25px #f1c40f, 0 0 35px #f1c40f';
        });

        title.addEventListener('mouseout', () => {
            title.style.textShadow = '0 0 10px #f1c40f, 0 0 20px #f1c40f, 0 0 30px #f1c40f';
        });
    </script>
</body>
</html>
