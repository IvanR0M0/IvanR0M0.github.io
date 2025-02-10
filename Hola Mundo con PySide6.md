# Hola Mundo con PySide6

Este proyecto documenta la instalación y ejecución de una aplicación simple de "Hola Mundo" utilizando PySide6.

### Creación del Archivo `main.py`

Crea un archivo `main.py` con el siguiente contenido:

```python
import sys
from PySide6.QtWidgets import QApplication, QLabel

app = QApplication(sys.argv)
window = QLabel("¡Hola, Mundo!")
window.show()
sys.exit(app.exec())
```

