# ATLAS — Fisioterapia y readaptación deportiva

Sitio de **dieciséis páginas** en español, inglés y árabe con RTL real, para una
clínica de fisioterapia y readaptación deportiva.

**Ver online:** https://2troll.github.io/atlas-fisio/

El atlas es la primera vértebra cervical, la que sostiene el cráneo. De ahí el
nombre y de ahí el logotipo.

## Las dieciséis páginas

`Inicio` · **`¿Qué me pasa?`** · `Tratamientos` · `Lesiones` ·
**`Mapa del cuerpo`** · **`Escala de dolor`** · `Recuperación` ·
**`Vuelta al deporte`** · `Movilidad` · **`Test de fuerza`** ·
**`Ejercicios`** · `Equipo` · `Centro` · `Precios` · `Preguntas` · `Cita`

Las seis en negrita son nuevas, y ninguna repite el formato de otra ni el de
los otros dos sitios:

| Página | Formato | Qué hace |
|---|---|---|
| **¿Qué me pasa?** | Árbol de decisión con ramas | Seis salidas según el camino: del «vaya hoy al médico» al «puede esperar». Empieza descartando señales de alarma, y deja el rastro de lo respondido |
| **Mapa del cuerpo** | SVG con zonas pulsables | Cinco zonas, con teclado además de ratón; al pulsar sale lo que más entra por la puerta en esa parte |
| **Escala de dolor** | Deslizador con bandas | Del 0 al 10, y para cada tramo qué hacer con el entrenamiento. Enseña la regla del 4/10 a 24 horas |
| **Vuelta al deporte** | Calendario mensual real | Fecha de la lesión + tipo → cuadrículas de mes con los cambios de fase y el alta marcados en el día que caen |
| **Ejercicios** | Filtros por facetas | Zona × material × fase sobre dieciséis ejercicios, con contador y aviso cuando no queda ninguno |
| **Test de fuerza** | Comparación pareada | Lado sano contra lado lesionado en tres tests; calcula la asimetría y aplica el criterio real del 10 % |

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

## Fotografía

3 fotografías reales de **Wikimedia Commons**, todas con licencia libre
(CC0, CC BY o CC BY-SA), descargadas al repositorio y no enlazadas a un
tercero: si mañana desaparecen de Commons, el sitio sigue igual.

- Cada una lleva **texto alternativo traducido a los tres idiomas**, no un
  `alt` en español dentro de la versión árabe.
- Los créditos —título, autor y licencia con enlace— se muestran dentro del
  propio sitio y también cambian de idioma.
- Se redimensionaron a 1400 px de ancho; ninguna pasa de 500 KB.

Se descartó una candidata de fisioterapia que la licencia permitía usar pero
que retrataba a **un menor identificable**. En una maqueta comercial eso no se
publica aunque sea legal.

## Comprobado

```
184 claves × 3 idiomas    paridad ✔ · 0 sin traducir
23 estructuras paralelas  todas cuadran
16 rutas × 3 idiomas      0 fugas de idioma
16 enlaces del menú       los 16 navegan
desborde horizontal       0 px en las 16 rutas
árbol de decisión         6 caminos, 6 salidas distintas
3 curvas de recuperación · 3 articulaciones · 8 zonas del cuerpo
formulario en árabe       3 estados
paleta de series          los 6 controles en claro y en oscuro
goniometría               contenido dentro del viewBox también a 180°
```

Dos fallos encontrados al verificar y corregidos: el arco de goniometría se
salía del lienzo por la izquierda con rangos grandes, y un titular tenía
caracteres cirílicos colados («Публикados»).

## Sobre el contenido clínico

La página de orientación **no diagnostica y lo dice**. Empieza descartando
señales de alarma (fiebre, pérdida de fuerza súbita, hormigueo que baja por la
extremidad, dolor nocturno) y en ese caso manda al médico sin ofrecer cita.
Cada salida lleva su nivel de urgencia y las notas de método recuerdan que
ninguna herramienta por internet sustituye una valoración presencial.

La estructura del árbol vive fuera de los diccionarios de idioma: si las ramas
estuvieran dentro de cada idioma, una versión podría acabar preguntando otra
cosa que las demás.

---

**Maqueta de demostración.** Clínica ficticia. Los plazos y los criterios de
alta son los habituales en readaptación; los precios y el equipo, de ejemplo.
