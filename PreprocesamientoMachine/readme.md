# Proyecto de Clasificación de Hojas de Costa Rica 🌿

Este proyecto tiene como objetivo el preprocesamiento de imágenes de hojas de plantas de Costa Rica y el entrenamiento de una red neuronal convolucional (CNN) para la clasificación de especies.

## 1. Crear entorno virtual

```bash
py -3.10 -m venv venv
```

## 2. Activar entorno virtual

```bash
venv\Scripts\activate
```

Verás el nombre del entorno `(venv)` al inicio de la línea de comandos.

## 3. Instalar librerías necesarias

Dentro del entorno activo:

```bash
pip install -r requirements.txt
```

## 4. Configurar Jupyter (opcional, recomendado)

Para poder seleccionar tu entorno en Jupyter Notebook:

```bash
pip install ipykernel
python -m ipykernel install --user --name=venv --display-name "Python (venv hojas)"
```

---

## 🛑 Desactivar entorno virtual

Cuando termines de trabajar:

```bash
deactivate
```

---

## ✅ Buenas prácticas

- Genera un `requirements.txt` actualizado después de instalar nuevas librerías:

```bash
pip freeze > requirements.txt
```

---

## 📦 Comandos útiles

### Ver paquetes instalados en el entorno

```bash
pip list
```

### Verificar versión de Python y pip

```bash
python --version
pip --version
```
