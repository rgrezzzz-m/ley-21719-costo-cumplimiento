# Costo de cumplir la Ley 21.719 — método y fuentes

Metodología abierta detrás de la estimación de costo de cumplimiento de la Ley N° 21.719 de protección de datos personales (Chile), publicada en LinkedIn.

Autor: Ricardo Grez · Rúbrica-Grezner
Última actualización: 12 de noviembre de 2026

Cualquiera puede revisar, discutir o corregir estos números. Si tienes un dato transado que contradiga un rango, abre un issue.

---

## 1. Qué se estima y qué no

Se estima el **costo para la empresa de alcanzar y mantener el cumplimiento**, dividido en:

```
Año 1       = implementación (pago único) + plataforma (12 meses) + DPO externo (12 meses)
Recurrente  = plataforma (12 meses) + DPO externo (12 meses)
```

**No se estima** el costo de las horas internas de la organización, que no aparece en ninguna cotización y que el inventario de datos exige de forma inevitable. Tampoco se estima la multa esperada, que es un problema distinto.

Los rangos son extremos observados, no promedios: el piso de cada componente es el precio de lista más bajo aplicable al segmento y el techo el más alto. Por eso son anchos.

## 2. Unidades y conversiones

| Parámetro | Valor | Fuente |
|---|---|---|
| UF | $41.316,06 | Banco Central de Chile, 12-11-2026 |
| UTM | $72.440 | SII, noviembre de 2026 |
| EUR | $1.091,56 | Tasa media de mercado, 12-11-2026 |
| IVA | Excluido en todos los montos | |

Los contratos plurianuales se llevan a base anual dividiendo por su plazo en meses y multiplicando por doce.

## 3. Segmentación

Según los tramos de ventas anuales de la Ley 20.416:

| Segmento | Ventas anuales |
|---|---|
| Empresa mediana | 25.000 a 100.000 UF |
| Gran empresa | sobre 100.000 UF |
| Corporación | sobre 1.000.000 UF |

## 4. Precios de lista observados en Chile

Consultados en noviembre de 2026 en las páginas públicas de cada proveedor.

### Implementación (pago único)

| Proveedor | Alcance | Precio |
|---|---|---|
| datOK | Hasta 10 trabajadores, sin datos sensibles | 15 UF |
| datOK | 11 a 50 trabajadores, sin datos sensibles | 25 UF |
| datOK | Datos sensibles, sector regulado o más de 50 trabajadores | desde 45 UF |
| IDATA Chile | Diagnóstico (descontable) | 10 UF |
| IDATA Chile | Implementación | 25 UF |
| IDATA Chile | Integral, datos sensibles (1 razón social, 15 tratamientos, 2 sedes) | 50 UF |
| aGo lab | Mapa técnico | 12 UF |
| aGo lab | Implementación técnica en sistemas | desde 120 UF |
| Apollo.TI | Rango startup / microempresa | 26 a 67 UF |
| Apollo.TI | Rango PYME mediana | 62 a 150 UF |
| Apollo.TI | Rango empresa mediana-grande | 148 a 350 UF |

### Plataforma de cumplimiento (recurrente)

| Proveedor | Plan | Mensual | Anual |
|---|---|---|---|
| Confirmer360 | Esencial, hasta 10.000 titulares | 1 UF | 12 UF |
| Confirmer360 | Profesional, hasta 100.000 titulares | 6 UF | 72 UF |
| Confirmer360 | Corporativo | desde 14 UF | desde 168 UF |
| SmartDPO | Esencial, hasta 5.000 titulares | 5 UF | 60 UF |
| SmartDPO | Cumplimiento, hasta 50.000 titulares | 18 UF | 216 UF |
| SmartDPO | Empresa, titulares ilimitados | 40 UF | 480 UF |
| datOK | Pro (IVA incluido) | $49.990 | $599.880 |
| datOK | Business (IVA incluido) | $99.990 | $1.199.880 |

### DPO externo (recurrente)

| Proveedor | Alcance | Mensual | Anual |
|---|---|---|---|
| SilocyData | Estándar, hasta 5 solicitudes ARCOP/mes | 10 UF | 120 UF |
| SilocyData | Gestión completa, hasta 15 ARCOP/mes, incidentes y fiscalizaciones | 15 UF | 180 UF |
| IDATA Chile | Esencial, 5 horas/mes | desde 10 UF | desde 120 UF |
| IDATA Chile | Recomendado para plan Integral | desde 15 UF | desde 180 UF |
| Apollo.TI | Revisión mensual más gestión de incidentes | 10 a 20 UF | 120 a 240 UF |
| aGo lab | Mantención técnica continua | desde 20 UF | desde 240 UF |

**Máximo observado para DPO externo en Chile: 20 UF al mes.** Ningún proveedor publica por encima de eso.

## 5. Contratos públicos españoles

Se usan como referencia de cumplimiento en régimen, porque España lleva más de ocho años con una autoridad que inspecciona y sanciona bajo el RGPD. Los precios chilenos de hoy corresponden a un mercado sin fiscalizador operativo.

| Entidad | Expediente | Monto | Plazo | Base anual | UF/año |
|---|---|---|---|---|---|
| Fundación Hospital Gregorio Marañón | Fibhgm PA 02-2020 | €23.940 sin IVA, adjudicado | 36 meses | €7.980 | 211 |
| Ayuntamiento de Piélagos | CSER 2026/4457 | €11.120 presupuesto base | 12 meses | €11.120 | 294 |
| Ayuntamiento de Collado Villalba | 37CON/2026 | €24.793 sin IVA | 24 meses | €12.396 | 327 |
| Ministerio de Inclusión, Seguridad Social y Migraciones | 202601JC0007 | €73.872 valor estimado, **no adjudicado** | 12 meses | €73.872 | 1.952 |
| Osakidetza, Servicio Vasco de Salud | 2025/00942 | €299.640 sin IVA, adjudicado a PricewaterhouseCoopers el 07-01-2026 | 24 meses | €149.820 | 3.958 |

**Advertencia sobre Osakidetza:** su objeto incluye el Esquema Nacional de Seguridad además de protección de datos, por lo que su alcance es más amplio que el de los otros contratos y su monto no es comparable uno a uno.

Fuentes: BOE, Contratación Pública de Euskadi, Contratos Públicos de la Comunidad de Madrid, portales de licitación.

## 6. El factor de paridad: banda 0,60 a 0,80

Para trasladar los contratos españoles a referencia chilena hace falta un factor de paridad. Se usa una **banda, no un punto**, porque los dos extremos responden a criterios distintos y ambos son defendibles.

**Techo: 0,80.** Es el cociente medido entre los índices de nivel de precios de Chile (88,3) y España (110,7), con el promedio mundial en 100, según el Programa de Comparación Internacional del Banco Mundial, año de referencia 2021. Es la única cifra de este documento que proviene de una medición oficial comparable entre ambos países.

**Piso: 0,60.** Los servicios profesionales son intensivos en mano de obra y no transables, por lo que su brecha de precios entre países suele ser mayor que la de la canasta general, que incluye bienes transables cuyos precios convergen. Es el efecto Balassa-Samuelson. No existe un índice de precios específico de servicios profesionales entre Chile y España, así que 0,60 es una elección dentro del rango que esa regularidad predice, no una medición.

**Declaración de honestidad:** la versión original de este análisis usaba 0,60 como punto único y sin fuente. La banda es la corrección.

## 7. Derivación de cada fila

### Empresa mediana · 230 a 606 UF el primer año

| Componente | Piso | Origen | Techo | Origen |
|---|---|---|---|---|
| Implementación | 50 UF | IDATA Integral, datos sensibles | 150 UF | Apollo.TI, techo PYME mediana |
| Plataforma | 60 UF/año | SmartDPO Esencial, 5 UF/mes | 216 UF/año | SmartDPO Cumplimiento, 18 UF/mes |
| DPO externo | 120 UF/año | SilocyData e IDATA, 10 UF/mes | 240 UF/año | Apollo.TI, 20 UF/mes |
| **Año 1** | **230 UF** | | **606 UF** | |
| **Recurrente** | **180 UF/año** | | **456 UF/año** | |

En pesos: año 1 de $9,5 a $25,0 millones; recurrente de $7,4 a $18,8 millones.

**Trazabilidad: completa.** Las seis cifras se verifican abriendo la página de precios del proveedor.

### Gran empresa · 498 a 1.070 UF el primer año

| Componente | Piso | Origen | Techo | Origen |
|---|---|---|---|---|
| Implementación | 150 UF | Apollo.TI, techo PYME mediana | 350 UF | Apollo.TI, techo mediana-grande |
| Plataforma | 168 UF/año | Confirmer360 Corporativo, 14 UF/mes | 480 UF/año | SmartDPO Empresa, 40 UF/mes |
| DPO externo | 180 UF/año | SilocyData gestión completa, 15 UF/mes | 240 UF/año | Máximo observado en Chile, 20 UF/mes |
| **Año 1** | **498 UF** | | **1.070 UF** | |
| **Recurrente** | **348 UF/año** | | **720 UF/año** | |

En pesos: año 1 de $20,6 a $44,2 millones; recurrente de $14,4 a $29,7 millones.

**Trazabilidad: completa.** Una versión anterior usaba 30 UF al mes como techo de DPO externo, cifra que ningún proveedor publica. Corregida al máximo observado de 20 UF al mes.

### Corporación · 1.680 a 4.690 UF el primer año

Ninguna firma publica precio corporativo en Chile. Esta fila se deriva de los contratos españoles con la banda de paridad.

**Recurrente**, anclado directamente:

| Extremo | Cálculo | Resultado |
|---|---|---|
| Piso | Ministerio de Inclusión, 1.952 UF/año × 0,60 | 1.171 UF/año |
| Techo | Osakidetza, 3.958 UF/año × 0,80 | 3.159 UF/año |

En pesos: de $48,4 a $130,5 millones al año.

**Implementación**, derivada por proporción. En los dos tramos con dato observado, la implementación equivale a entre 0,28 y 0,49 veces el recurrente anual (mediana 0,28 a 0,33; gran empresa 0,43 a 0,49). Aplicando esa proporción al recurrente corporativo se obtiene de 505 a 1.535 UF.

**Año 1:** de 1.676 a 4.694 UF, es decir de $69,2 a $193,9 millones.

**Trazabilidad: derivada, no observada.** El recurrente descansa en dos contratos españoles y en la banda de paridad. La implementación descansa además en una proporción tomada de los tramos inferiores. Los contratos españoles son servicios recurrentes anuales, no proyectos de implementación, así que no pueden anclar ese componente directamente.

## 8. Resumen

| Segmento | Año 1 (UF) | Año 1 (CLP) | Recurrente (UF/año) | Recurrente (CLP/año) | Base |
|---|---|---|---|---|---|
| Empresa mediana | 230 – 606 | $9,5 – $25,0 MM | 180 – 456 | $7,4 – $18,8 MM | Observada |
| Gran empresa | 498 – 1.070 | $20,6 – $44,2 MM | 348 – 720 | $14,4 – $29,7 MM | Observada |
| Corporación | 1.680 – 4.690 | $69,2 – $193,9 MM | 1.170 – 3.160 | $48,4 – $130,5 MM | Derivada |

## 9. Límites conocidos

1. **Son precios de lista, no transados.** El descuento efectivo en una negociación real no está medido.
2. **Los proveedores que publican tienden a los orientados a volumen PYME.** Las firmas grandes y los estudios jurídicos no publican tarifas, así que el tramo alto del mercado chileno no está representado.
3. **No se incluyen las horas internas de la organización**, que son un costo real y probablemente comparable al honorario externo.
4. **El factor de paridad es una banda, no una medición de servicios profesionales.** Solo el techo tiene fuente oficial.
5. **El contrato de Osakidetza incluye seguridad**, lo que infla el techo corporativo en una magnitud no cuantificada.
6. **No hay serie chilena de contratos públicos de adecuación**, porque la ley aún no rige. Debería existir desde 2027 y permitiría reemplazar el ancla española.
7. **El ICP del Banco Mundial tiene año de referencia 2021.** Una actualización podría mover el techo de la banda.

## 10. Estado legislativo

Al 12 de noviembre de 2026 la vigencia de la Ley 21.719 sigue fijada al 1 de diciembre de 2026. El Senado aprobó el 28 de octubre, en primer trámite, trasladarla al 15 de octubre de 2027 (Boletín N° 18.623-07), y la Comisión de Constitución de la Cámara de Diputadas y Diputados la aprobó en general el 4 de noviembre. No es ley hasta su publicación en el Diario Oficial.

El tope sancionatorio de 20.000 UTM para infracciones gravísimas equivale a $1.449 millones con la UTM de noviembre de 2026.

## 11. Cómo corregir estos números

Si tienes una cotización real, un contrato adjudicado o una tarifa transada que contradiga alguno de estos rangos, abre un issue indicando el segmento, el componente, el monto y la fecha. El dato transado vale más que el de lista y se incorpora.

Igual interés tiene cualquier fuente que permita medir el factor de paridad para servicios profesionales entre Chile y España, que es hoy el eslabón más débil del cálculo.
