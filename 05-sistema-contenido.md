# 05 — Sistema de contenido (cómo pedir más sin repetir)

## Palabra clave

```
PALANCA+3
```

Escribe eso en el chat y significa: **"dame el siguiente lote de 3 días de
contenido para redes, distinto a todo lo anterior."**

Variantes que también valen:
- `PALANCA+3 [canal]` → solo ese canal. Ej: `PALANCA+3 reels`
- `PALANCA+7` → lote de una semana
- `PALANCA+3 [tema]` → sesga el lote. Ej: `PALANCA+3 objeciones de precio`

---

## Qué debe hacer Claude cuando recibe `PALANCA+3`

1. **Leer `contenido/REGISTRO.md` primero.** Ahí está todo lo ya entregado.
2. **Generar 3 días nuevos**, uno por día, cubriendo los tres canales:
   - WhatsApp (canal del conjunto **o** canal propio — alternar, ver abajo)
   - YouTube (idea de video puente + gancho + outro adaptado)
   - Reels IG/FB (guion segundo a segundo + caption + hashtags)
3. **Verificar contra el registro** que ningún ángulo, gancho ni caso se repite.
4. **Añadir el lote nuevo al final de `REGISTRO.md`** con su número y fecha.
5. Entregar el lote como archivo `contenido/dias-XX-XX.md`.

## Reglas de no repetición

Un lote nuevo es válido solo si cumple **las cuatro**:

- [ ] **Ángulo distinto.** Ningún gancho comparte la misma estructura retórica
      con uno ya publicado (ver la lista de ángulos abajo).
- [ ] **Caso de uso distinto.** Si ya usaste "revisar un contrato", no vuelve a
      salir en 6 lotes.
- [ ] **Profesión distinta.** Rota entre contador, comerciante, docente, médico,
      abogado, ingeniero, freelancer, ama de casa, estudiante.
- [ ] **Emoción distinta.** Rota entre: curiosidad, alivio, urgencia, vergüenza
      productiva ("llevo años haciendo esto mal"), orgullo, sorpresa.

## Banco de ángulos (rotar, no repetir en 3 lotes seguidos)

1. **Demostración cruda** — "mira esto" sin explicación previa.
2. **Antes/después con cronómetro** — 3 horas → 12 minutos.
3. **Confesión** — "llevo dos años haciendo esto mal".
4. **Mito** — "todo el mundo cree X y está mal".
5. **Comparación** — cómo lo hace alguien que sabe vs alguien que no.
6. **Pregunta que incomoda** — "¿cuántas horas de tu semana son copiar y pegar?"
7. **Detrás de cámaras** — te grabas construyendo algo real.
8. **Objeción de frente** — "esto no sirve para mi profesión" y lo desmontas.
9. **Caso de un tercero** — un vecino, un cliente, un miembro.
10. **Lo que nadie explica** — el detalle técnico que sí importa.

## Ritmo por canal

| Canal | Frecuencia | Función |
|---|---|---|
| WhatsApp conjunto | 2× semana máx | Valor puro, mover al canal propio |
| WhatsApp propio | 4-5× semana | Calentar y vender |
| YouTube | 1-2× semana | Alcance frío (gaming) |
| Reels IG/FB | 5× semana | Volumen, materia prima para pauta |

**Sobre el canal del conjunto:** máximo 2 publicaciones semanales y nunca dos
seguidas con mención del producto. Son tus vecinos. Ese canal es un préstamo, no
un activo.

## Qué NO publicar nunca

- Promesas de ingresos ("gana $X con IA"). Ni una vez. Es lo que hace que Meta
  te tumbe la cuenta publicitaria y lo que hace que la audiencia deje de creerte.
- Video de otro creador republicado como propio.
- Capturas con datos de clientes, correos o nombres reales sin difuminar.
- Datos de producto de Anthropic (precios, planes, límites) sin verificarlos ese
  mismo día en `claude.com/pricing`. Cambian.
- Comparaciones falsas con otras herramientas. Si dices "X no puede hacer esto",
  compruébalo. Un comentario que te desmiente en público cuesta más que el reel.
