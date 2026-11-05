# ONIX Fideliza — biblioteca de recursos

## Fuente web
`web-cards/source-originals/` contiene las cuatro tarjetas finales entregadas por diseño, con nombre y puntos de ejemplo. Son referencias, no se usan directamente como tarjeta dinámica.

`web-cards/clean-bases/` contiene las bases limpias para la tarjeta web dinámica. La página `tarjeta-web-fiel-v5.html` superpone nombre, puntos, etiqueta y enlace.

## Wallet
`wallet/active/hero-basic-vertical.png` es el único hero activo por ahora: textura básica de Wallet + logo ONIX vertical a la izquierda.

`wallet/candidates/` contiene los cuatro heroes generados para estudiar niveles; no se activan todavía.

## Logos
`logos/onix-vertical.png` es el recurso vertical original. `logos/isotipo-square.png` es el logo cuadrado para el encabezado nativo de Google Wallet.

## Regla de activación
La tarjeta web puede usar Básico, Bronce, Plata y Oro. Wallet comienza con el hero Básico. Más adelante, el backend puede cambiar `object.heroImage` solo para el `LoyaltyObject` del cliente cuando cambie su nivel.
