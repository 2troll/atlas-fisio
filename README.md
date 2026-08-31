# ATLAS — Fisioterapia y readaptación deportiva

Sitio de **diez páginas** en español, inglés y árabe con RTL real, para una
clínica de fisioterapia y readaptación deportiva.

**Ver online:** https://2troll.github.io/atlas-fisio/

El atlas es la primera vértebra cervical, la que sostiene el cráneo. De ahí el
nombre y de ahí el logotipo.

## Las diez páginas

`Inicio` · `Tratamientos` · `Lesiones` · `Recuperación` · `Movilidad` ·
`Equipo` · `Centro` · `Precios` · `Preguntas` · `Cita`

## Las tres piezas que no son adorno

- **Curva de recuperación.** Función recuperada por semanas para tres lesiones,
  con las tres fases del tratamiento como bandas de fondo y el punto de alta
  deportiva marcado. La curva es una exponencial saturante con constante propia
  por lesión: el esguince sube rápido y engaña, la tendinopatía sube despacio.
- **Goniometría.** Arcos de rango articular con la medida de la primera sesión,
  la de las seis semanas y el objetivo, en grados y sobre el mismo centro.
  Contesta a la pregunta que un paciente hace de verdad: ¿voy mejor o no?
- **Esquema corporal** en SVG con las zonas que se tratan señaladas.

Contesta a lo que una clínica suele esquivar: cuánto se tarda en volver, y con
qué criterio se da el alta. Todo lleva su nota de método declarando que son
plazos orientativos.

## Comprobado

```
109 claves × 3 idiomas    paridad ✔ · 0 sin traducir
13 estructuras paralelas  todas cuadran
10 rutas × 3 idiomas      0 fugas de idioma
3 curvas de recuperación · 3 articulaciones · 8 zonas del cuerpo
formulario en árabe       3 estados
paleta de series          los 6 controles en claro y en oscuro
goniometría               contenido dentro del viewBox también a 180°
```

Dos fallos encontrados al verificar y corregidos: el arco de goniometría se
salía del lienzo por la izquierda con rangos grandes, y un titular tenía
caracteres cirílicos colados («Публикados»).

---

**Maqueta de demostración.** Clínica ficticia. Los plazos y los criterios de
alta son los habituales en readaptación; los precios y el equipo, de ejemplo.
