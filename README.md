# N0CTRA · Café de día, noche con sonido

Sitio web de N0CTRA (León, Gto.). Un solo archivo (`index.html`), sin dependencias ni build.

**En vivo:** https://adrian-crypto13.github.io/noctra-web/

## Qué hace
- Cambia sola entre **modo día** (8:00 a 19:00, luz fría) y **modo noche** (22:00 a 3:00, luz cálida) según la hora real de León. Entre 19:00 y 22:00 muestra el "Intermedio".
- Banner de **promociones en bucle infinito**, filtradas por día de la semana y por acto.
- **Reservas por WhatsApp**: arma el mensaje y abre el chat.
- Carta por acto y cartelera de noches.
- Forzar un acto al compartir: agregar `#dia` o `#noche` al final del link.

## Cómo editar contenido
Todo está al inicio del `<script>` en `index.html`, en la sección **CONFIGURACIÓN**:
- `WHATSAPP`: número con lada 52, sin espacios.
- `PROMOS`: título, descripción, precio, acto (`"dia"` o `"noche"`), días (`0` = domingo … `6` = sábado) y horario.
- `CARTA`, `AGENDA`, `CINTA1`, `CINTA2`.

> Productos, precios, promos y número de WhatsApp son de ejemplo y deben confirmarse.
