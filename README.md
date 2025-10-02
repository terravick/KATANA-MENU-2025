<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>KATANA - Menú Interactivo</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #f5f5f5;
      margin: 0;
      padding: 20px;
      color: #333;
    }
    .container {
      max-width: 1200px;
      margin: auto;
      background: #fff;
      border-radius: 15px;
      padding: 20px 30px;
      box-shadow: 0px 5px 20px rgba(0,0,0,0.2);
    }
    h1 {
      text-align: center;
      color: #0d355d;
      font-size: 3em;
      margin-bottom: 10px;
    }
    h2 {
      border-bottom: 3px solid #ff7b00;
      padding-bottom: 5px;
      margin-top: 40px;
      color: #0d355d;
    }
    .menu-item {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      align-items: center;
      padding: 12px;
      border-bottom: 1px dashed #ccc;
    }
    .item-info {
      flex: 3;
    }
    .item-name {
      font-weight: bold;
      font-size: 1.2em;
      color: #ff7b00;
    }
    .item-description {
      font-size: 0.95em;
      color: #555;
    }
    .item-price {
      font-weight: bold;
      color: #0d355d;
      margin-top: 4px;
    }
    .item-options {
      flex: 2;
      display: flex;
      flex-direction: column;
      align-items: flex-end;
      gap: 6px;
    }
    input[type="number"], input[type="text"] {
      padding: 6px;
      border-radius: 6px;
      border: 1px solid #aaa;
      font-size: 0.9em;
      width: 100%;
    }
    input[type="number"] {
      max-width: 70px;
      text-align: center;
    }
    .order-btn {
      display: block;
      background: linear-gradient(135deg, #ff7b00, #d32f2f);
      color: white;
      padding: 18px 40px;
      margin: 20px auto;
      border-radius: 50px;
      border: none;
      cursor: pointer;
      font-size: 1.5em;
      font-weight: bold;
      text-transform: uppercase;
      box-shadow: 0px 5px 15px rgba(0,0,0,0.3);
      transition: 0.3s;
    }
    .order-btn::before {
      content: "🍣 ";
    }
    .order-btn:hover {
      transform: scale(1.05);
      box-shadow: 0px 8px 20px rgba(0,0,0,0.4);
    }
    .total-box {
      text-align: right;
      font-size: 1.3em;
      font-weight: bold;
      margin-top: 30px;
      color: #0d355d;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>KATANA - Menú Interactivo</h1>

<div class="quote">✨ Gracias por dejarnos ser parte de tus momentos más especiales ✨</div>

    <div class="instructions">
      <strong>📋 Instrucciones para ordenar:</strong><br>
      ✅ Indica la <b>cantidad</b> en el recuadro correspondiente.<br>
      ✅ En la casilla de <b>comentarios</b> puedes personalizar tu pedido. Ejemplo: <i>“Sin alga”, “Natural”, “Cambiar pollo por res”</i>.<br>
      ✅ Al ir seleccionando tus productos, verás reflejado el <b>total a pagar</b>.<br>
      ✅ Para finalizar tu orden, presiona el botón <b>"ORDENAR AHORA"</b>. Tu pedido junto con el total será enviado directo a nuestro WhatsApp 📲.
    </div>

    <!-- AQUÍ SIGUE TODO TU MENÚ (no lo modifiqué) -->

     <!-- ======================= -->
    <!-- SUSHIS -->
    <!-- ======================= -->
    <h2>Sushis Naturales</h2>
    <div class="menu-item"><div class="item-info"><div class="item-name">California</div><div class="item-description">Pepino, aguacate, philadelphia y surimi.</div><div class="item-price">Orden $145 | ½ $95</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Dragón Roll</div><div class="item-description">Pepino, aguacate, philadelphia y camarón empanizado, forrado en aguacate con tampico.</div><div class="item-price">Orden $165 | ½ $115</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Arcoiris</div><div class="item-description">Pepino, aguacate, philadelphia y camarón empanizado, cubierto con atún, salmón y aguacate, con tampico spicy.</div><div class="item-price">Orden $165 | ½ $115</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Macho Roll</div><div class="item-description">Pepino, aguacate, philadelphia y camarón empanizado, topping spicy de salmón y aguacate.</div><div class="item-price">Orden $165 | ½ $115</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Cordon Blue</div><div class="item-description">Pepino, aguacate, philadelphia, pollo y tocino, cubierto de queso chihuahua gratinado.</div><div class="item-price">Orden $165 | ½ $115</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Sunshine</div><div class="item-description">Pepino, aguacate, philadelphia, camarón empanizado y ají amarillo, aderezo de ajonjolí.</div><div class="item-price">Orden $175 | ½ $125</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>

    <h2>Empanizados</h2>
    <div class="menu-item"><div class="item-info"><div class="item-name">Cielo, Mar y Tierra</div><div class="item-description">Pepino, aguacate, philadelphia, pollo, res y camarón.</div><div class="item-price">$155 | ½ $105</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Tres Quesos</div><div class="item-description">Pepino, aguacate, philadelphia y camarón, cubierto con quesos philadelphia, chihuahua y americano.</div><div class="item-price">$155 | ½ $105</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Bacon Roll</div><div class="item-description">Pepino, aguacate, philadelphia y chile caribe, topping de tampico con tocino crujiente.</div><div class="item-price">$155 | ½ $105</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>

    <h2>Capeados</h2>
    <div class="menu-item"><div class="item-info"><div class="item-name">Sin Nombre</div><div class="item-description">Alga, pepino, aguacate, philadelphia y camarón empanizado, arriba camarón, tampico y salsa de anguila.</div><div class="item-price">$165 | ½ $115</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Crunch Roll</div><div class="item-description">Alga, pepino, aguacate, philadelphia y camarón, con láminas de salmón y salsa de anguila.</div><div class="item-price">$165 | ½ $115</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Cilantro Roll</div><div class="item-description">Alga, pepino, aguacate, philadelphia y pollo, bañado en aderezo de cilantro.</div><div class="item-price">$165 | ½ $115</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>

    <h2>Horneados</h2>
    <div class="menu-item"><div class="item-info"><div class="item-name">Supremo</div><div class="item-description">Empanizado, pepino, aguacate, philadelphia y res, topping de tocino y queso cheddar.</div><div class="item-price">$165 | ½ $115</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Unagui Roll</div><div class="item-description">Natural, pepino, aguacate, philadelphia y camarón cocido, con láminas de anguila y salmón en salsa de cacahuate.</div><div class="item-price">$155 | ½ $105</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Gratin Roll</div><div class="item-description">Empanizado, pepino, aguacate, philadelphia, res y pollo, topping de queso chihuahua y chile serrano.</div><div class="item-price">$165 | ½ $115</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Popeye</div><div class="item-description">Empanizado, pepino, aguacate, philadelphia y pollo, topping de espinaca y tocino.</div><div class="item-price">$165 | ½ $115</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Tuna Spicy</div><div class="item-description">Natural, pepino, aguacate, philadelphia y camarón empanizado, topping de atún ahumado gratinado.</div><div class="item-price">$165 | ½ $115</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Maara Especial</div><div class="item-description">Natural, pepino, aguacate, philadelphia y camarón, horneado con topping cremoso de camarón.</div><div class="item-price">$165 | ½ $115</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>

    <h2>De la Parrilla</h2>
    <div class="menu-item"><div class="item-info"><div class="item-name">Burro Percherón</div><div class="item-description">Tortilla de 40 cm, carne asada, queso chihuahua, frijol y aderezos.</div><div class="item-price">$155 | ½ $105</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Papa con Carne Asada</div><div class="item-description">Puré de papa, carne asada, queso chihuahua, champiñones y tocino con tortillas de harina.</div><div class="item-price">$155</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Burro de Pechuga Empanizada</div><div class="item-description">Pechuga empanizada, lechuga, cebolla morada, queso de cabra, aguacate y aderezo cremoso.</div><div class="item-price">$155</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>

    <h2>Ingredientes Extra</h2>
    <div class="menu-item"><div class="item-info"><div class="item-name">Pollo, Tocino, Philadelphia, Chile Caribe, Aguacate, Res, Surimi</div><div class="item-price">$20</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Camarón</div><div class="item-price">$25</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Atún, Salmón</div><div class="item-price">$40</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Tampico</div><div class="item-price">$20</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Servicio a Domicilio</div><div class="item-price">$20</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."></div></div>

    <!-- ======================= -->
    <!-- ENTRADAS -->
    <!-- ======================= -->
    <h2>Entradas</h2>
    <div class="menu-item"><div class="item-info"><div class="item-name">Brochetas</div><div class="item-description">3 brochetas de pollo o surimi y philadelphia sobre arroz con verduras.</div><div class="item-price">$155 | ½ $65</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Brochetas Mixtas</div><div class="item-description">3 brochetas de pollo, camarón y philadelphia, sobre arroz con verduras.</div><div class="item-price">$165 | ½ $70</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Sushiles</div><div class="item-description">4 porciones de chile caribe con arroz y tampico especial empanizado.</div><div class="item-price">$135 | ½ $90</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Tempura de Vegetales</div><div class="item-description">Vegetales en tempura sobre arroz, bañados en salsa de anguila.</div><div class="item-price">$145 | ½ $95</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Tempura de Camarón</div><div class="item-description">Camarones en tempura sobre arroz, bañados en salsa de anguila.</div><div class="item-price">$165 | ½ $115</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Sopas</div><div class="item-description">Sopa miso, sopa especial de mariscos y ramen.</div><div class="item-price">$95 - $155</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>

    <!-- ======================= -->
    <!-- ENSALADAS -->
    <!-- ======================= -->
    <h2>Ensaladas</h2>
    <div class="menu-item"><div class="item-info"><div class="item-name">Ensalada Tropical</div><div class="item-description">Verduras frescas con aderezo ranch y frutas tropicales.</div><div class="item-price">$145</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Ensalada Katana</div><div class="item-description">Verduras frescas, aguacate, queso, surimi y aderezo de ajonjolí.</div><div class="item-price">$145</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>

    <!-- ======================= -->
    <!-- KIDS -->
    <!-- ======================= -->
    <h2>Kids</h2>
    <div class="menu-item"><div class="item-info"><div class="item-name">Nuggets con Papas</div><div class="item-description">Acompañados de aderezo y bebida pequeña.</div><div class="item-price">$95</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Mini Sushi</div><div class="item-description">6 piezas de sushi natural sencillo con philadelphia y aguacate.</div><div class="item-price">$95</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."></div></div>

    <!-- ======================= -->
    <!-- PLATILLOS -->
    <!-- ======================= -->
    <h2>Platillos</h2>
    <div class="menu-item"><div class="item-info"><div class="item-name">Yakimeshi</div><div class="item-description">Arroz frito con verduras, huevo y proteína a elección (pollo, res, camarón).</div><div class="item-price">$155</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Pollo Teriyaki</div><div class="item-description">Pechuga de pollo a la plancha con salsa teriyaki, acompañado de arroz y ensalada.</div><div class="item-price">$155</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Camarones Empanizados</div><div class="item-description">Camarones empanizados acompañados de arroz y ensalada.</div><div class="item-price">$165</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Carne Asada</div><div class="item-description">Carne asada al carbón con guarnición de arroz y ensalada.</div><div class="item-price">$175</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."><input type="text" placeholder="Comentario"></div></div>

    <!-- ======================= -->
    <!-- BEBIDAS -->
    <!-- ======================= -->
    <h2>Bebidas</h2>
    <div class="menu-item"><div class="item-info"><div class="item-name">Refrescos</div><div class="item-description">Variedad de Coca-Cola, Fanta, Sprite, Fresca.</div><div class="item-price">$35</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Aguas Frescas</div><div class="item-description">Horchata, Jamaica, Limón.</div><div class="item-price">$30</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Cervezas</div><div class="item-description">Corona, Modelo, Victoria, Pacífico.</div><div class="item-price">$50</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."></div></div>

    <!-- ======================= -->
    <!-- POSTRES -->
    <!-- ======================= -->
    <h2>Postres</h2>
    <div class="menu-item"><div class="item-info"><div class="item-name">Helado Frito</div><div class="item-description">Bola de helado empanizado en tempura.</div><div class="item-price">$85</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Flan Casero</div><div class="item-description">Porción individual de flan de vainilla.</div><div class="item-price">$75</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."></div></div>
    <div class="menu-item"><div class="item-info"><div class="item-name">Crepas Dulces</div><div class="item-description">Rellenas de philadelphia, frutas y cajeta.</div><div class="item-price">$95</div></div><div class="item-options"><input type="number" min="0" placeholder="Cant."></div></div>


    <!-- Caja de Total -->
    <div class="total-box" id="totalBox">Total: $0</div>

    <button class="order-btn" onclick="sendOrder()">ORDENAR AHORA</button>
  </div>

  <script>
    // Función para obtener el precio numérico de un item
    function getPrice(text) {
      let match = text.match(/\$([0-9]+)/);
      return match ? parseInt(match[1]) : 0;
    }

    // Actualizar el total automáticamente
    function updateTotal() {
      const items = document.querySelectorAll('.menu-item');
      let total = 0;
      items.forEach(item => {
        const qty = item.querySelector('input[type=number]')?.value;
        if (qty && qty > 0) {
          const priceText = item.querySelector('.item-price').innerText;
          const unitPrice = getPrice(priceText);
          total += unitPrice * qty;
        }
      });
      document.getElementById("totalBox").innerText = "Total: $" + total;
      return total;
    }

    // Detectar cambios en cantidad
    document.querySelectorAll('input[type=number]').forEach(input => {
      input.addEventListener('input', updateTotal);
    });

    function sendOrder() {
      const items = document.querySelectorAll('.menu-item');
      let orderText = "🍣 *Pedido KATANA* 🍣\n\n";
      let total = updateTotal();

      items.forEach(item => {
        const qty = item.querySelector('input[type=number]')?.value;
        const comment = item.querySelector('input[type=text]') ? item.querySelector('input[type=text]').value : "";
        if (qty && qty > 0) {
          const name = item.querySelector('.item-name').innerText;
          orderText += `• ${qty} x ${name}`;
          if (comment) orderText += ` (${comment})`;
          orderText += "\n";
        }
      });

      if (orderText === "🍣 *Pedido KATANA* 🍣\n\n") {
        alert("⚠️ No has seleccionado nada para ordenar.");
        return;
      }

      // Agregar total al mensaje
      orderText += `\n💰 *Total a pagar:* $${total}`;

      const phone = "526471065375";
      const url = `https://wa.me/${phone}?text=${encodeURIComponent(orderText)}`;
      window.open(url, '_blank');
    }
  </script>
</body>
</html>
