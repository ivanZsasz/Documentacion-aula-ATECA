# Aula ATECA — Documentación e Ingeniería de Inteligencia Artificial

> Portafolio técnico y documentación de proyectos de Inteligencia Artificial desarrollados en el **Aula ATECA del instituto Calderón del Barca de Pinto**. Incluye desde el desarrollo de modelos desde cero hasta técnicas de optimización, cuantización y despliegue en hardware local.

🌐 **Demo en vivo:** [Documentación Aula ATECA](https://ivanzsasz.github.io/Documentacion-IA/AULA_ATECA/)

---

## 🛠️ Proyectos Documentados

| Proyecto | Tecnologías | Descripción Técnica |
| :--- | :--- | :--- |
| **Creación de un LLM desde Cero** | `PyTorch`, `Transformers`, `Python` | Implementación pura de una arquitectura estilo GPT entrenada desde inicialización aleatoria para un asistente de recetas. |
| **Fine-Tuning con MLX** | `Apple Silicon`, `LoRA`, `MLX`, `Mistral-7B` | Adaptación eficiente de bajo rango (LoRA) sobre Mistral-7B en hardware de consumo de Apple. |
| **Agente de Código Local** | `LM Studio`, `VS Code`, `Kilo Code` | Integración de un ecosistema de desarrollo 100% privado y local para asistencia en programación. |
| **Cuantización de Modelos** | `C++`, `llama.cpp`, `GGUF` | Compilación nativa y compresión de modelos de FP16 a 4 bits para reducir el consumo de VRAM en dispositivos con recursos reducidos. |
| **Pre-entrenamiento en NVIDIA Blackwell** | `NVIDIA Blackwell`, `WSL2`, `PyTorch Nightly` | Entrenamiento de *Cervantes-GPT* resolviendo incompatibilidades de hardware de última generación mediante compilación manual. |
| **Destilación de Conocimiento** | `Knowledge Distillation`, `BERT-Tiny`, `Teacher-Student` | Compresión de modelos masivos en arquitecturas reducidas manteniendo altos niveles de precisión. |

---

## 💻 Stack Tecnológico

* **Frameworks y Librerías:** PyTorch (Stable & Nightly), MLX, Transformers, llama.cpp.
* **Técnicas de IA:** LoRA, Fine-Tuning, Quantization (GGUF 4-bit), Knowledge Distillation, Tokenización y Arquitecturas Decoder-only.
* **Entornos y Hardware:** Apple Silicon, NVIDIA Blackwell, WSL2, LM Studio, VS Code.
* **Web / Frontend:** HTML5, CSS3, JavaScript, Canvas API, GitHub Pages.

---

## 📁 Estructura del Repositorio

```text
Documentacion-IA/
└── AULA_ATECA/
    ├── index.html            # Landing page principal del portafolio
    ├── CreacionLLM/          # Documentación técnica del LLM en PyTorch
    ├── Fine-Tunning/         # Guía de ajuste fino con MLX y LoRA
    ├── Agente/               # Configuración del entorno local de desarrollo
    ├── Cuantizacion/         # Proceso de compilación de llama.cpp y GGUF
    ├── PreEntrenamiento/     # Registro de entrenamiento de Cervantes-GPT
    └── Destilacion/          # Documentación de destilación Profesor-Estudiante

---

## ⚙️ Requisitos e Instalación

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/ivanZsasz/Documentacion-IA.git](https://github.com/ivanZsasz/Documentacion-IA.git)
    ```
2.  **Abrir el proyecto:**
    Navegar a la carpeta `AULA_ATECA/` y abrir el archivo `index.html` en cualquier navegador web o desplegar con la extensión *Live Server* en VS Code.

---

## 📄 Licencia

Proyecto desarrollado dentro del Grado Superior de Desarrollo de Aplicaciones Multiplataforma (DAM) en el espacio **Aula ATECA**.
