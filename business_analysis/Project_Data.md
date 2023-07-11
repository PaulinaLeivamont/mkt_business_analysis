# Descripción de los datos
1. La tabla 'visits' (registros del servidor con datos sobre las visitas al sitio web):
- Uid: identificador único del usuario;
- Device: dispositivo del usuario;
- Start Ts: fecha y hora de inicio de la sesión;
- End Ts: fecha y hora de término de la sesión;
- Source Id: identificador de la fuente de anuncios de la que proviene el usuario.
* Todas las fechas de esta tabla están en formato AAAA-MM-DD.

2. La tabla 'orders' (datos sobre pedidos):
- Uid: identificador único del usuario que realiza un pedido;
- Buy Ts: fecha y hora del pedido;
- Revenue: ingresos de Y.Afisha de este pedido.

3. La tabla costs (datos sobre gastos de marketing):
- source_id: identificador de la fuente de anuncios
- dt: fecha;
- costs: gastos en esta fuente de anuncios en este día.


# Libraries used:
pandas
matplotlib.pyplot
seaborn
numpy 
scipy.stats

# What I have learned 
- calcular los períodos de pago de las empresas y la rentabilidad de la inversión en marketing;
- trazar embudos de marketing y de productos en Python;
- analizar cohortes de varias maneras;
- encontrar la tasa de retención y la tasa de cancelación;
- analizar cohortes por comportamiento;
- calcular la economía unitaria por ventas;
- calcular la economía unitaria por cliente;
- medir la actividad de usuario;
- obtener datos de la API de Metrica y trabajar con ellos.  
