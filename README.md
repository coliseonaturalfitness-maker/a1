# Creador de presentación PPT

Este proyecto genera una presentación de PowerPoint (`.pptx`) desde un archivo JSON.

## Requisitos

```bash
pip install -r requirements.txt
```

## Uso

```bash
python ppt_creator.py ejemplo_presentacion.json salida.pptx
```

## Formato del JSON

```json
{
  "slides": [
    {
      "title": "Título",
      "bullets": ["Punto 1", "Punto 2"]
    }
  ]
}
```
