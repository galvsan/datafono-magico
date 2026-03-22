# Diseño del TPV Infantil - BankPlay

Este documento detalla el diseño de la interfaz de usuario para la aplicación **BankPlay TPV**, basado en el proyecto de Stitch `11223049103931347727`.

## Flujo de Pantallas

### 1. Menú de Productos (V2)
La pantalla principal donde los niños pueden seleccionar los productos a vender. Cada producto tiene un emoji representativo y su precio.
![Menú de Productos](https://lh3.googleusercontent.com/aida/ADBb0ujrrDPqI9m9tG_TbJtSBEJSFp8f-KIYhaGXmIPfdZmI83JQ8xmh38ejv3aFGi3bIzCPS2EDZR6XLlsNQTr7sf1Lp7VnSp-KwPfj-vo3GInnuYKWB9M1eQ0DEotdgZSvYCEbQp-yqfyjOrT0xWeDK1wJgdA8-ErBcmWpHRtToZURGo1Lup2KjajBAHk9opidujpHQATU8II18mMBlwSoqk2DjfvO0FSuRQy2wNwRHotyVw0dSRmaByFFpN7E)

### 2. Pedido Actual (Flujo de Cobro)
Una vista detallada del carrito de compras antes de proceder al pago. Permite revisar las cantidades y el total acumulado.
![Pedido Actual](https://lh3.googleusercontent.com/aida/ADBb0uiETaM0EQi9Bu-5IdJtlf5zHdL-2UraDShJTUnfzYtREreU4f5DB_t9SgZ-BYGsyv4W2DrQCTo7Bcdo9fa81kQhD_aEFIU4gU4Y-EFO5QhozMfZ0sCee3YQsZkzhEM1xsmpybI5jRVxHgZegSidfFcqPIHYlsDC21to9SbpZT50MT6FnaqM2YWH9Mo-GibMXD8ccNrnfMD58nO--BQbOJf6-98axiMNWYnDN-LMzNCV1AjJwo8PyQjKDlj-)

### 3. Cobro Contactless
Pantalla de pago con tarjeta. Simula el escaneo NFC con una animación de ondas concéntricas y un aviso de "Acerque su Tarjeta".
![Cobro Contactless](https://lh3.googleusercontent.com/aida/ADBb0ujBoJQ23KnO8pSHc2C6UbH4gtrZLGB_vdT72VU1S_2vK9Ue_WiYNIlGdoH5ahQIrTXD26MvhXBBpw0ThlmZqs9LX170MG53Q9Yj1f5MsVncMxNAMqeeECK6PYI4X7ArurNoyuErRzUHdtlZazdKZ_mi3Wmg0Em_RORCLcbOGbgASR0R42fgnqVNUGo-RqKyM0suFzNdv5GVGPqNp_pIuji8omomRj3e38OBfkkVNqgAJawDEuQTAYyQKExj)

### 4. Cobro en Efectivo
Pantalla para el pago físico. Incluye un teclado numérico para registrar cuánto dinero entrega el cliente y calcula automáticamente el cambio.
![Cobro en Efectivo](https://lh3.googleusercontent.com/aida/ADBb0uiWhnhSvemh0byxuA4fJhx6vR_Y7fLnwAnb8LNG73Jo7yTnDnjR1kdufPf7tlS-_VJYfaPwALV_vsDLqAwc-knnaACHf5apFvnqtSzIdyFmQMRf83CBxIVCZMw0gWWknwLHr_1f82Vgtv4Gqy5PERC55_4DHdjRtLyqqL8EV9Js6Z-4yWh091FizUxMz2t7F509Oqq2krsSNvfg2RKAsVEz4uHoECwKgRVDnbRYtDfynNPyB61XT-msMi_b)

### 5. Ticket de Venta (V2)
Simulación de un ticket térmico impreso. El diseño es hiperrealista, con bordes dentados y tipografía estilo máquina de escribir.
![Ticket de Venta](https://lh3.googleusercontent.com/aida/ADBb0ujrzAygKsG-WR8Xz-H5Cor15iacJuWkIVcOp98Cb9ekc2SMG8RXqVd3kS5vVsRPSpG8bHSAE_Q9N_5ph0XDC2OfsWH-huw9cN0g0vR56tF7TlGwsLQQyVuZGsn2FgH1Ro3L8Fv7cVHMMEyJuRwBb3h7bu_tJD_C60ghOdFiCEQeGoWBSa-Z0DM0WXLTGbL3LEnvI2Zu1kR-wVb-KRxEJLbL0TTmbK2DPUPE1qpM4AtMOlcEvB-TE347QdU)

## Características de Diseño
- **Paleta de Colores**: Fondo oscuro (`#0f172a`) con acentos en azul eléctrico y contrastes tipo neón.
- **Estilo Visual**: Moderno, "premium" y amigable para niños.
- **Interacciones**: Micro-animaciones en botones y transiciones suaves entre pantallas.
- **PWA**: Instalable como aplicación nativa para una experiencia inmersiva.
