# Panel DCA

Panel de solo lectura para seguir un bot DCA que compra ETH con USDC en la red Base (Uniswap).

Lee datos públicos de la blockchain de Base (saldos, compras y el precio de Chainlink) y el historial de precios de CoinGecko, directamente desde el navegador. No guarda claves y no puede mover dinero.

La billetera que se muestra va en el enlace, después del `#`, y nunca se envía a este sitio:

```
https://<usuario>.github.io/panel-dca/#direccion=0x…&monto=1&tope=8&horas=24
```

| Parámetro | Qué es |
|---|---|
| `direccion` | Dirección pública de la billetera |
| `monto` | USDC por compra |
| `tope` | Total de USDC del plan |
| `horas` | Horas entre compras |
| `desde` | (Opcional) Bloque desde el que buscar compras |
| `repo` | (Opcional) `usuario/repositorio` del bot, para el enlace a GitHub Actions |
