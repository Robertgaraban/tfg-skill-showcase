# Skill: MaquetaciÃ³n TFG/TFM â Facultat de NÃ utica de Barcelona (FNB/UPC)

**Robert Garaban Â· HydroAbyss Technology and Innovation**

---

## Â¿QuÃ© hace este skill?

Skill de IA para maquetar Trabajos Finales de Grado (TFG) y MÃ¡ster (TFM) segÃºn la normativa oficial de la **Facultat de NÃ utica de Barcelona (FNB/UPC)**. Aplica estilos Word, estructura obligatoria, tipografÃ­a, paginaciÃ³n, figuras, tablas, ecuaciones y citaciÃ³n ISO 690 â sin reescribir el contenido del autor.

**Regla central: maquetar, no reescribir.**

---

## QuÃ© aplica automÃ¡ticamente

### Estructura obligatoria FNB
1. Portada Â· 2. Resumen Â· 3. Abstract Â· 4. Ãndice Â· 5. IntroducciÃ³n Â· 6. CapÃ­tulos Â· 7. Conclusiones Â· 8. Referencias Â· 9. Anexos

### Estilos Word (solo estos)
`TÃ­tulo` Â· `Encabezado 1/2/3` Â· `Normal` Â· `TÃ­tulo de tabla` Â· `Pie de figura`

### TipografÃ­a
- Times New Roman 12pt Â· Interlineado 1.5 Â· Justificado
- MÃ¡rgenes: sup/inf 2.5 cm Â· izq 3.0 cm Â· der 2.5 cm

### PaginaciÃ³n
- Portada: sin nÃºmero Â· Secciones iniciales: romano Â· Desde IntroducciÃ³n: arÃ¡bigo

### Figuras y tablas
- Figura: pie debajo â `Figura X.X. TÃ­tulo. Fuente: ...`
- Tabla: tÃ­tulo encima â `Tabla X.X. TÃ­tulo`

### CitaciÃ³n ISO 690
- `(Apellido AÃ±o)` Â· hasta 3 autores; mÃ¡s de 3: `et al.` Â· bibliografÃ­a alfabÃ©tica

---

## Entregables por intervenciÃ³n

1. Lista de cambios propuestos
2. TransformaciÃ³n del contenido (estructura + estilos)
3. Actualizaciones manuales necesarias en Word

---

## Pipeline de automatizaciÃ³n complementario

| Script | FunciÃ³n |
|---|---|
| `maquetacion_master.sh` | Pipeline unificado: maquetaciÃ³n + reportes |
| `audit_valor_lectura.py` | AuditorÃ­a de legibilidad y densidad visual |
| `generate_visual_backlog.py` | Backlog visual por capÃ­tulo |
| `clean_caption_noise.py` | Limpieza de captions y fuentes duplicadas |

---

## Uso como skill

```
Usa $maquetacion-tfg-fnb-upc para maquetar este TFG en Word segÃºn FNB/UPC.
```

Desarrollado durante la elaboraciÃ³n del TFG *"NavegaciÃ³n AutÃ³noma en Embarcaciones de PequeÃ±o Calado"* en FNB/UPC. Reutilizable para cualquier TFG/TFM presentado en FNB/UPC.

---

## Acceso

Solicitar: **robertgaraban@gmail.com** â Asunto: `[RevisiÃ³n tÃ©cnica] Skill TFG FNB/UPC`

---

*Facultat de NÃ utica de Barcelona Â· UPC Â· HydroAbyss Technology and Innovation*