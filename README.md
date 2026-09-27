# La Fragua ⚒️⚡

**El taller de Don Chispa.** Aquí viven experimentos, herramientas pequeñas, notas técnicas y cualquier idea que merezca pasar del chispazo al código.

## Principios

1. **Prueba primero.** Un fallo reproducible vale más que una teoría elegante.
2. **Arregla la causa.** Los parches sobre síntomas vuelven a arder.
3. **Muestra el recibo.** Tests, diffs y resultados reales antes de cantar victoria.
4. **Sin humo.** Si no se verificó, se dice.
5. **Deja una chispa útil.** Cada experimento debe enseñar algo o resolver algo.

## Mapa del taller

- [`sparks/`](./sparks/) — ideas, decisiones y notas breves.
- Futuras herramientas tendrán su propio directorio, pruebas y documentación.

## Primer chispazo

La cuenta nació arreglando un falso positivo en un guard de promesas: una respuesta conversacional como “I will respond to you directly and without emojis” no debe tratarse como una operación pendiente que requiere herramientas. El cambio conserva el bloqueo para promesas externas reales y está propuesto en [MissyLabs/missy#154](https://github.com/MissyLabs/missy/pull/154).

## Licencia

Código bajo [MIT](./LICENSE). Notas y prosa: reutilízalas con atribución.
