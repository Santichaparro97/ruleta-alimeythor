# Ruleta Mágica de Alimeythor

Ruleta interactiva para stands, parte del universo de [Alimeythor](https://www.alimeythor.com/).
Pensada para correr todo el día en una tablet, en vivo.

## Cómo usarla en el stand

Abrí `index.html`. **No necesita internet ni servidor**: todo (fuentes, imágenes del
personaje, sonidos) está embebido en el archivo.

En la tablet, abrilo en Chrome y usá **"Agregar a pantalla de inicio"**: arranca a pantalla
completa, sin barra de direcciones, y los chicos no pueden salirse tocando de más.

## Los 4 premios

| Premio | Color |
|---|---|
| Molinete de colores | Rojo `#F8231C` |
| Lápiz | Verde `#3FB411` |
| Cubo de las intenciones | Naranja `#F8A00A` |
| Desafío de motricidad | Celeste `#33AFED` |

## Cambiar las probabilidades (poco stock de un premio)

Editá el bloque `CONFIG` al principio del `<script>` en `index.html`:

- `peso: 1` — normal
- `peso: 0.4` — sale menos de la mitad de seguido
- `peso: 0` — no sale nunca (sigue visible en la ruleta)

Los porcentajes se recalculan solos. Por defecto los cuatro están en `1` (25% cada uno).

También se pueden ajustar `duracionGiro`, `vueltasMin`/`vueltasMax` y `segundosFestejo`.

## Controles del equipo del stand

- Botón de silencio: arriba a la derecha.
- Barra espaciadora / Enter: girar.
- Tocar el festejo: volver antes al modo atracción (igual vuelve solo a los 9 segundos).

## Identidad visual

Colores y tipografías (Chewy + Poppins) tomados del sitio real de Alimeythor.
