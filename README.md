<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Confirmación de Reserva</title>
<style>
body{margin:0;height:100vh;display:flex;justify-content:center;align-items:center;background:#ff4e50;font-family:Arial;color:white;text-align:center}
.heart{font-size:100px;animation:beat 1s infinite}
@keyframes beat{0%{transform:scale(1)}50%{transform:scale(1.2)}100%{transform:scale(1)}}
button{margin-top:20px;padding:10px 20px;border:none;border-radius:20px;font-size:18px;cursor:pointer}
</style>
</head>
<body>
<div>
<div class="heart">❤️</div>
<h2>¿Aceptás la invitación?</h2>
<button onclick="alert('Sabía que ibas a decir que sí 😏💘')">Aceptar</button>
</div>
</body>
</html>