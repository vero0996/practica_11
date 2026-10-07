Verónica Paola Zapata Sánchez 
A01199193

Ejercicio 0: las pruebas de validación de título y formato de tiempo son locales porque utilizan código de Kotlin puro ejecutándose directamente sobre la JVM, mientras que las pruebas del ViewModel y de TalkBack son instrumentadas debido a que requieren componentes propios del framework de Android (tales como Context, Uri o el renderizado de elementos de la interfaz en un emulador).

Ejercicio C3:la prueba de TalkBack / accesibilidad es de tipo instrumentada porque requiere instanciar y renderizar la interfaz con Compose UI dentro de un dispositivo o emulador Android para navegar por la jerarquía de vistas; su propósito es comprobar que los elementos interactivos e imágenes contengan descripciones de contenido (contentDescription) o etiquetas semánticas para que los lectores de pantalla puedan anunciarlos correctamente a usuarios con discapacidad visual.