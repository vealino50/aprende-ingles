# Inglés Fácil 🇺🇸 — app Android

App para personas que **no saben nada de inglés**. Todo está en español, con botones grandes, dibujos (emojis) y la pronunciación escrita "a la española".

## Qué hace

| Modo | Cómo funciona |
|---|---|
| 👂 **Escuchar** | El teléfono dice una palabra en inglés y eliges qué significa entre 4 opciones. Botón 🐢 para oírla despacio. |
| 🗣️ **Hablar** | Ves la palabra, cómo se dice (ej. *water → «uó-ter»*), la escuchas y la repites con el micrófono. La app te dice si se entendió. |
| ✍️ **Escribir** | Ves el dibujo y la palabra en español y la escribes en inglés. 💡 Pista va mostrando letras. |

- 50 palabras y frases en 7 temas: Saludos, Números, Colores, Comida, Familia, Casa, Frases útiles.
- Guarda las ⭐ estrellas (aciertos) de cada modo.
- Para añadir palabras, edita `app/src/main/java/com/inglesfacil/app/Vocabulario.kt` — una línea por palabra.

## Cómo instalarla en tu teléfono

1. Instala **Android Studio** (gratis): https://developer.android.com/studio
2. Descomprime este .zip y en Android Studio elige **File → Open** y abre la carpeta `InglesFacil`.
3. Espera a que termine "Gradle sync" (la primera vez descarga cosas, tarda unos minutos).
4. En el teléfono activa **Opciones de desarrollador → Depuración USB** y conéctalo por cable.
5. Pulsa el botón verde ▶ **Run**. La app se instala sola.

Para tener un archivo **.apk** y pasárselo a otras personas: **Build → Build App Bundle(s) / APK(s) → Build APK(s)**.

## Requisitos del teléfono

- Android 8.0 o más nuevo.
- Voz en inglés: *Ajustes → Idioma → Salida de texto a voz* (la app te avisa si falta).
- Para el modo Hablar: la app **Google** instalada y conexión a internet (el reconocimiento de voz lo hace Google).
