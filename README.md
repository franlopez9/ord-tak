# 🫓 ord-tak — POS para Pupuserías

App sencilla para **tomar órdenes** y llevar el control del día en una pupusería, desde el celular.

👉 **Probala aquí:** https://franlopez9.github.io/ord-tak/

> 🚧 **En desarrollo.** Por ahora la app sirve para tomar órdenes y llevar las cuentas. **No procesa pagos**: solo registra cómo pagó el cliente. La integración con pasarela de pago viene más adelante.

## ¿Qué hace hoy?

- **Órdenes por mesa, para llevar o delivery** (12 mesas + barra)
- **Comanda táctil** con pupusas de maíz o arroz, y bebidas
- **Registro de forma de pago:** efectivo, Wompi, transferencia o fiado
- **Dividir la cuenta** entre varias personas
- **Gastos del día:** quesillo, masa, gas, verduras, desechables, ayudante
- **Libreta de fiados** para anotar y cobrar deudas
- **Cierre de caja:** cuánto efectivo debe haber al final del día

## Próximamente

- [ ] Integración con pasarela de pago (cobro directo desde la app)
- [ ] Guardar datos en la nube para usar en varios dispositivos

## Cómo usarla

1. Abrí el link en el celular.
2. En el menú del navegador, elegí **"Agregar a pantalla de inicio"** para usarla como app.
3. Listo, no necesita instalación ni cuenta.

> ⚠️ Los datos se guardan **solo en el navegador de ese dispositivo**. Si borrás los datos del navegador o cambiás de celular, se pierden.

## Cambiar el menú o los precios

Todo está en `index.html`. Buscá la lista `MENU` y editá nombres o precios:

```js
{ id: 'queso', nombre: 'Queso', emoji: '🧀', precioMaiz: 1.25, precioArroz: 1.50, esPupusa: true },
```

**Importante:** el `id` no puede llevar guion bajo (`_`).

## ¿Querés mejorarla?

1. Hacé **Fork** de este repositorio.
2. Hacé tus cambios en tu copia.
3. Mandame un **Pull Request** con lo que cambiaste y por qué.

## Hecha con

- HTML + React 18
- Tailwind CSS
- Todo en un solo archivo (`index.html`)
