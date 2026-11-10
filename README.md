# 🫓 ord-tak — POS para Pupuserías

App sencilla para tomar órdenes y llevar la caja de una pupusería desde el celular.

👉 **Probala aquí:** https://franlopez9.github.io/ord-tak/

## ¿Qué hace?

- **Órdenes por mesa, para llevar o delivery** (12 mesas + barra)
- **Comanda táctil** con pupusas de maíz o arroz, y bebidas
- **Formas de pago:** efectivo, Wompi, transferencia o fiado
- **Dividir la cuenta** entre varias personas
- **Gastos del día:** quesillo, masa, gas, verduras, desechables, ayudante
- **Libreta de fiados** para anotar y cobrar deudas
- **Cierre de caja:** cuánto efectivo debe haber al final del día

## Cómo usarla

1. Abrí el link en el celular.
2. En el menú del navegador, elegí **"Agregar a pantalla de inicio"** para usarla como app.
3. Listo, no necesita instalación ni cuenta.

> ⚠️ Los datos se guardan **solo en el navegador de ese dispositivo**. Si borrás los datos del navegador o cambiás de celular, se pierden.

## Cambiar el menú o los precios

Todo está en `index.html`. Buscá la lista `MENU` y editá nombres o precios:

```js
{ id: 'queso', nombre: 'Queso', emoji: '🧀', precioMaiz: 1.25, precioArroz: 1.50, esPupusa: true },
