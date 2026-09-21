# | Aitor Funes del Pino | 
### Estudiante de Desarrollo de Aplicaciones Web (DAW)

---

## > 🃁 About Me

Me encuentro formándome en el área de Desarrollo de Aplicaciones Web **(DAW)**. Disfruto de la configuración y puesta en marcha de servidores, así como de la preparación del hardware necesario para mis proyectos. Al mismo tiempo, me interesa seguir desarrollando y perfeccionando mis habilidades de programación. 

Anteriormente cursé ~~Bachillerato~~, pero tras finalizarlo descubrí que quería orientar mi formación hacia el desarrollo profesional en el ámbito de la **ingeniería de hardware y software**.

---

## > ⚙ Technologies & Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

---

## > 🜂 Fields of Interest
* **Infraestructura y Homelabs:** Diseño, despliegue y mantenimiento de entornos de servidor locales y autoalojados.
* **Automatización de Procesos:** Desarrollo de scripts y flujos de trabajo orientados a la optimización operativa y eficiencia de tareas.
* **Transformación Digital:** Análisis e implementación de soluciones tecnológicas aplicadas a la digitalización y modernización de negocios.

---

## > 🃆 Roadmap & Objectives

1. **Titulación Académica:** Culminar con éxito el ciclo formativo de Grado Superior en Desarrollo de Aplicaciones Web (DAW).
2. **Desarrollo Integral End-to-End:** Dominar la arquitectura, gestión e implementación autónoma de proyectos Full Stack (Frontend & Backend).
3. **Puesta en Producción:** Diseñar, construir y desplegar en un entorno de producción real mi primera solución web integral.

---

### > ⬡ Hitos y Progreso Académico DAW

- [x] Superar con éxito el primer curso de DAW.
- [x] Publicar el README de perfil profesional en GitHub.
- [ ] Mantener un rendimiento de excelencia académica (calificación media de 9–10).
- [ ] Desarrollar, presentar y defender el Proyecto Final de Ciclo (PFC).

---
## > ◈ Portfolio & Builds

| Proyecto | Tecnologías | Estado |
| :--- | :--- | :---: |
| **Automated File Sanitizer** | `Python` `CLI` | ![Completed](https://img.shields.io/badge/Completed-2ea44f?style=flat-square) |
| **Web Data Scraper** | `Python` | ![In Progress](https://img.shields.io/badge/In%20Progress-e3b341?style=flat-square) |
| **Personal Web Portfolio** | `HTML5` `CSS3` `JavaScript` | ![Planned](https://img.shields.io/badge/Planned-6e7681?style=flat-square) |

---

"""
Profile Automation & Routine
"""
from dataclasses import dataclass
from typing import List

@dataclass
class Developer:
    name: str
    focus: str
    stack: List[str]
    is_learning: bool = True

    def run_daily_routine(self) -> str:
        return f"{self.name} is building and automating systems with {', '.join(self.stack[:3])}."

me = Developer(
    name="Aitor",
    focus="Web Applications & Scripting",
    stack=["Python", "JavaScript", "Linux", "Docker"]
)

if __name__ == "__main__":
    print(me.run_daily_routine())

<!--
**AitorFunes-prog/AitorFunes-prog** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
