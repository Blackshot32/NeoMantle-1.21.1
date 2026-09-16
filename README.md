# Neo Mantle — Unofficial 1.21.1 NeoForge Port (WIP / AI-Assisted)

> [!WARNING]
> ### ⚠️ AVISO IMPORTANTE / EXPERIMENTAL (UNOFFICIAL FORK)
> Este proyecto es un **port NO OFICIAL y experimental** de Mantle para **Minecraft 1.21.1 (NeoForge)**, adaptado y compilado con asistencia de Inteligencia Artificial (Hermes / DeepSeek) como biblioteca base para Tinkers' Construct.
> 
> * **ESTADO**: **Work In Progress (WIP)**. Preparado con urgencia ("a las puras") para habilitar pruebas en 1.21.1.
> * **ESPERA A LA VERSIÓN OFICIAL**: Se recomienda encarecidamente **esperar a la versión oficial y terminada de [SlimeKnights](https://github.com/SlimeKnights/Mantle)**. Este repositorio no busca reemplazar el trabajo del equipo original.
> * **CRÉDITOS TOTALES**: Todo el código original, diseño y arquitectura pertenecen a **SlimeKnights**. Este fork se apoya en el trabajo de migración comunitaria de [vancevoj/neomantle](https://github.com/vancevoj/neomantle).

---

## 📦 Descripción y Requisitos

Neo Mantle es la biblioteca de soporte requerida por **Tinkers' Construct (NeoTinkers)**. No añade contenido jugable por sí sola, pero contiene:
- Manejo de renderizado dinámico de fluidos (`FluidRenderer`, `FluidCuboid`).
- Infraestructura de datos de recetas e inventarios inteligentes (`SmartInventory`).
- Soporte para capacidades de bloque (`BlockCapability`) y registro en NeoForge.

---

## 🔨 Compilación

```bash
export JAVA_HOME=/ruta/a/tu/jdk-21
export PATH=$JAVA_HOME/bin:$PATH

./gradlew jar
```

---

## ⚖️ Licencia
Conserva las licencias originales de SlimeKnights / MIT.
