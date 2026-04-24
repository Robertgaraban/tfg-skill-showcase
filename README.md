# Skill: Maquetación TFG/TFM — Facultat de Nàutica de Barcelona (FNB/UPC)

**Robert Garaban · HydroAbyss Technology and Innovation**

---

## ¿Qué hace este skill?

Skill de IA para maquetar Trabajos Finales de Grado (TFG) y Máster (TFM) según la normativa oficial de la **Facultat de Nàutica de Barcelona (FNB/UPC)**. Aplica estilos Word, estructura obligatoria, tipografía, paginación, figuras, tablas, ecuaciones y citación ISO 690 — sin reescribir el contenido del autor.

**Regla central: maquetar, no reescribir.**

---

## Qué aplica automáticamente

### Estructura obligatoria FNB
1. Portada · 2. Resumen · 3. Abstract · 4. Índice · 5. Introducción · 6. Capítulos · 7. Conclusiones · 8. Referencias · 9. Anexos

### Estilos Word (solo estos)
`Título` · `Encabezado 1/2/3` · `Normal` · `Título de tabla` · `Pie de figura`

### Tipografía
- Times New Roman 12pt · Interlineado 1.5 · Justificado
- Márgenes: sup/inf 2.5 cm · izq 3.0 cm · der 2.5 cm

### Paginación
- Portada: sin número · Secciones iniciales: romano · Desde Introducción: arábigo

### Figuras y tablas
- Figura: pie debajo → `Figura X.X. Título. Fuente: ...`
- Tabla: título encima → `Tabla X.X. Título`

### Citación ISO 690
- `(Apellido Año)` · hasta 3 autores; más de 3: `et al.` · bibliografía alfabética

---

## Entregables por intervención

1. Lista de cambios propuestos
2. Transformación del contenido (estructura + estilos)
3. Actualizaciones manuales necesarias en Word

---

## Pipeline de automatización complementario

| Script | Función |
|---|---|
| `maquetacion_master.sh` | Pipeline unificado: maquetación + reportes |
| `audit_valor_lectura.py` | Auditoría de legibilidad y densidad visual |
| `generate_visual_backlog.py` | Backlog visual por capítulo |
| `clean_caption_noise.py` | Limpieza de captions y fuentes duplicadas |

---

## Uso como skill

```
Usa $maquetacion-tfg-fnb-upc para maquetar este TFG en Word según FNB/UPC.
```

Desarrollado durante la elaboración del TFG *"Navegación Autónoma en Embarcaciones de Pequeño Calado"* en FNB/UPC. Reutilizable para cualquier TFG/TFM presentado en FNB/UPC.

---

## Acceso

Solicitar: **robertgaraban@gmail.com** — Asunto: `[Revisión técnica] Skill TFG FNB/UPC`

---

*Facultat de Nàutica de Barcelona · UPC · HydroAbyss Technology and Innovation*