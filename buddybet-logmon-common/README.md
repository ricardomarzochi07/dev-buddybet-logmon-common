# buddybet-logmon-common

Librería de logging estructurado en formato **JSON** para aplicaciones Python.
Permite generar trazas con niveles de log (`DEBUG`, `INFO`, `ERROR`, etc.), incluyendo datos adicionales, módulo, función y excepciones.

---

## 🚀 Instalación

Desde **PyPI** (una vez publicada):

```bash
pip install buddybet-logmon-common


## 🚀 USO BASICO

# Logger genérico
from buddybet_logmon_common.logger import get_logger
logger = get_logger()
logger.info("Hello JSON logger!")

# Integración con FastAPI
from buddybet_logmon_common.fastapi_logger import setup_fastapi_logging
setup_fastapi_logging(app)