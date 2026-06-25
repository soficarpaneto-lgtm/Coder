# Avatar con Voz Sintética (ElevenLabs + HeyGen)

## 🎯 Objetivo

Crear un avatar digital hablando con una voz generada mediante inteligencia artificial, combinando dos herramientas de IA generativa:

- **ElevenLabs**: generación de voz sintética a partir de un guion de texto.
- **HeyGen**: animación del avatar (sincronización labial, gestos y movimiento) a partir del audio generado.

El resultado final es un video (.mp4) donde el avatar reproduce el guion con una voz natural y movimientos coherentes.

---

## 🛠️ Herramientas utilizadas

| Herramienta | Función |
|---|---|
| ElevenLabs | Generación de audio (texto a voz) |
| HeyGen | Animación del avatar y sincronización labial |

---

## 📋 Proceso de trabajo

### 1. Pre-producción
- Redacción del guion a utilizar como base del audio.
- Revisión del guion para evitar errores de pronunciación y asegurar pausas naturales.

### 2. Producción
- **Generación de audio en ElevenLabs**: se ingresó el guion y se seleccionó una voz adecuada al tono del mensaje. Se ajustaron parámetros de estabilidad y claridad para lograr un audio limpio, evitando ruido de fondo (que puede provocar que los labios del avatar "vibren" de forma extraña).
- **Animación en HeyGen**: se subió el audio generado y se seleccionó el avatar. Se insertaron pausas en el guion para que el avatar parpadee o mueva la cabeza sutilmente, evitando que quede "inmóvil" mientras habla.

### 3. Post-producción
- Revisión de la sincronización entre audio y movimiento labial.
- Nivelación del volumen de la música/audio integrado en el video final.
- Exportación del video final en formato .mp4.

---

## 📁 Estructura del repositorio

```
Coder/
├── README.md
├── assets/
│   ├── audio/      # Audio generado en ElevenLabs
│   ├── script/     # Guion utilizado
│   └── video/      # Video final (.mp4)
└── docs/           # Documentación adicional / capturas del proceso
```

---

## ▶️ Resultado final

El video final se encuentra en `assets/video/`.

---

## 📝 Notas y aprendizajes

- Un audio "sucio" (con ruido de fondo) afecta directamente la calidad del movimiento labial del avatar.
- Insertar pausas estratégicas en el guion mejora el realismo del avatar, evitando que permanezca estático mientras "habla".
