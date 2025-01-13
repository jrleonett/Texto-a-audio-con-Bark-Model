# 🎤 Generador de Texto a Audio con Bark 🎧

¡Bienvenido al generador de texto a audio utilizando **Bark**, un modelo de conversión de texto a audio basado en transformadores! Este cuaderno te permite convertir cualquier texto en español (u otros idiomas) en audio de alta calidad con un tono de voz realista. Desarrollado por **José R. Leonett** para la comunidad de Peritos Forenses Digitales de Guatemala.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1gjIAn-tigNDK4nQje3dPzFFf0WmTjZK3?usp=sharing)
---

## **¿Qué es Bark?**
Bark es un modelo de texto a audio desarrollado por **Suno**. Puede generar:
- Voz multilingüe altamente realista

El programa está diseñado para ejecutarse en **Google Colab** y se divide en tres módulos principales:

1. **Módulo 1**: Carga los modelos de Bark y crea una carpeta para almacenar los archivos generados.
2. **Módulo 2**: Permite ingresar texto, seleccionar una voz y generar el audio correspondiente.
3. **Módulo 3**: Comprime y descarga todos los archivos generados en un archivo `.zip`.

---

## Características principales

- **Generación de audio**: Convierte texto en voz utilizando el modelo Bark.
- **Multilingüe**: Soporta múltiples idiomas, incluyendo español, inglés, francés, alemán, chino, japonés y más.
- **Expresiones no verbales**: Permite agregar risas, suspiros, llantos y otros efectos de sonido.
- **Interfaz interactiva**: Utiliza widgets de Google Colab para una experiencia de usuario sencilla.
- **Descarga automática**: Comprime y descarga los archivos generados en un archivo `.zip`.

---

## Requisitos

- **Google Colab**: El programa está diseñado para ejecutarse en Google Colab.
- **Conexión a Internet**: Se requiere conexión a Internet para instalar dependencias y generar audio.
- **GPU**: Se recomienda el uso de una GPU para acelerar la generación de audio.

---

## Instrucciones de uso

### Módulo 1: Carga de modelos y creación de carpeta
1. Ejecuta el **Módulo 1** para instalar las dependencias, cargar los modelos de Bark y crear la carpeta `EVIDENCIAS`.

### Módulo 2: Generación de audio
1. Ejecuta el **Módulo 2**.
2. Ingresa el texto que deseas convertir a audio en el cuadro de texto.
3. Selecciona la voz en el menú desplegable (hay opciones masculinas y femeninas en varios idiomas).
4. Haz clic en "Generar Audio".
5. El audio se guardará en la carpeta `EVIDENCIAS` junto con un archivo `.txt` que contiene el texto original.

### Módulo 3: Descarga de archivos
1. Ejecuta el **Módulo 3**.
2. El programa comprimirá la carpeta `EVIDENCIAS` en un archivo `.zip` y lo descargará automáticamente.

---

## Estructura de la carpeta `EVIDENCIAS`

Después de ejecutar el programa, la carpeta `EVIDENCIAS` contendrá:
- `texto_original.txt`: Archivo con el texto original y la voz seleccionada.
- `audio_generado.wav`: Archivo de audio generado a partir del texto.

---

## Ejemplo de uso

1. **Selecciona una voz**: Por ejemplo, "Speaker 3 (ES) - Masculino".
2. **Ingresa un texto**:

3. **Genera el audio**: Haz clic en "Generar Audio".
4. **Descarga los archivos**: Ejecuta el **Módulo 3** para descargar la carpeta `EVIDENCIAS` en formato `.zip`.

---

## Expresiones no verbales y efectos de sonido

Puedes mejorar la calidad del audio utilizando expresiones no verbales y efectos de sonido. Aquí tienes algunos ejemplos:

### Expresiones no verbales
- `[risas]`: Una risa genérica.
- `[suspiro]`: Un suspiro de alivio o cansancio.
- `[llanto]`: Un llanto suave.
- `[toser]`: Una tos.
- `[estornudo]`: Un estornudo.

### Efectos de sonido ambientales
- `[sonido de viento]`: Viento soplando.
- `[sonido de lluvia]`: Lluvia cayendo.
- `[sonido de trueno]`: Truenos en una tormenta.
- `[sonido de pájaros]`: Pájaros cantando.
- `[música suave]`: Música de fondo relajante.

---

## Notas adicionales

- **Calidad del audio**: La calidad del audio puede variar según la voz seleccionada.
- **Límites de texto**: Bark tiene un límite de aproximadamente 13 segundos por fragmento de texto. Para textos largos, el programa divide el texto en fragmentos y combina los audios generados.
- **Compatibilidad**: El programa es compatible con múltiples idiomas y voces.

---

## Contribuciones

Si deseas contribuir a este proyecto, ¡eres bienvenido! Puedes abrir un **issue** o enviar un **pull request** con tus mejoras.

---

# Cómo citar este trabajo.
Usa la siguiente entrada BibTeX si utilizas este trabajo en tu investigación:
```bash
@article{joséRLeonett,
  title={Convertir texto a audio en español con Bark Model},
  author={José R. Leonett},
  year={2023}
}

```

**Licencia.**
- Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.

---

¡Gracias por usar este programa! 😊
