<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>لوحة تحكم السائق</title>
    <script src="https://www.gstatic.com/firebasejs/9.6.10/firebase-app-compat.js"></script>
    <script src="https://www.gstatic.com/firebasejs/9.6.10/firebase-database-compat.js"></script>
    <style>
        body { font-family: sans-serif; padding: 20px; background: #2c3e50; color: white; margin: 0; }
        .order-card { background: white; color: #333; padding: 15px; border-radius: 10px; margin-bottom: 15px; border-right: 5px solid #e67e22; }
        .btn-map { background: #e67e22; color: white; padding: 10px 15px; border: none; border-radius: 5px; text-decoration: none; display: inline-block; margin-top: 10px; font-weight: bold; }
        h2 { text-align: center; }
    </style>
</head>
<body>
    <h2>الطلبات الجاهزة للتوصيل 🚚</h2>
    <div id="ordersList">جاري تحميل الطلبات...</div>

<script>
    const firebaseConfig = {
        apiKey: "AIza...", 
        authDomain: "aman-audoi.firebaseapp.com",
        projectId: "aman-audoi",
        databaseURL: "https://aman-audoi-default-rtdb.firebaseio.com/",
        storageBucket: "aman-audoi.appspot.com",
        messagingSenderId: "946545859812",
        appId: "1:946545859812:web:06fbd35603a1cf68b9a0f1"
    };
    firebase.initializeApp(firebaseConfig);
    const database = firebase.database();

    database.ref('shipments').on('value', (snapshot) => {
        const ordersList = document.getElementById('ordersList');
        ordersList.innerHTML = '';
        
        snapshot.forEach((childSnapshot) => {
            const order = childSnapshot.val();
            if (order.latitude) { 
                const card = `
                    <div class="order-card">
                        <p><strong>📞 الهاتف:</strong> ${order.phone}</p>
                        <p><strong>📍 المنطقة:</strong> ${order.city}</p>
                        <p><strong>📝 ملاحظة:</strong> ${order.note || 'لا يوجد'}</p>
                        <a class="btn-map" href="https://www.google.com/maps?q=${order.latitude},${order.longitude}" target="_blank">📍 افتح الموقع في Google Maps</a>
                    </div>`;
                ordersList.innerHTML += card;
            }
        });
        if(ordersList.innerHTML === '') ordersList.innerHTML = "لا توجد طلبات بمواقع محددة حالياً.";
    });
</script>
</body>
</html>
