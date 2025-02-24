# Paulistudio-
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agendamiento Salón de Belleza</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Agenda tu Cita</h1>
        <form id="booking-form">
            <div class="form-group">
                <label for="service">Selecciona un Servicio:</label>
                <select id="service" name="service">
                    <option value="corte">Corte de Cabello</option>
                    <option value="color">Coloración</option>
                    <option value="manicura">Manicura</option>
                    <option value="pedicura">Pedicura</option>
                    <option value="maquillaje">Maquillaje</option>
                </select>
            </div>
            <div class="form-group">
                <label for="date">Selecciona una Fecha:</label>
                <input type="date" id="date" name="date">
            </div>
            <div class="form-group">
                <label for="time">Selecciona una Hora:</label>
                <input type="time" id="time" name="time">
            </div>
            <div class="form-group">
                <label for="name">Nombre:</label>
                <input type="text" id="name" name="name" placeholder="Tu nombre">
            </div>
            <div class="form-group">
                <label for="phone">Teléfono:</label>
                <input type="tel" id="phone" name="phone" placeholder="Tu teléfono">
            </div>
            <button type="submit">Confirmar Cita</button>
        </form>
        <div id="confirmation" class="hidden">
            <h2>Cita Confirmada</h2>
            <p id="confirmation-details"></p>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
