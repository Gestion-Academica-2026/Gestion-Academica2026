# Sistema de Gestion Academica

## Datos Generales
* **Nombre del Proyecto:** Sistema de Gestion Academica
* **Descripcion:** Aplicacion web para la administracion y gestion de modulos academicos, estudiantes y docentes.
* **Integrantes del Equipo:**
    Fase inicial
  * Genesis Quinonez - Integrante 1 (Configuracion e Infraestructura)
  * Cristina Arbelaez Jaramillo - Integrante 2 (Responsable de Documentacion)
  * Isaac Garcia Yepes - Integrante 2 (Responsable de tablero de gestion segun lo dialogado por el equipo)

---

Estrategia de Ramas (GitFlow)
El equipo utiliza la metodologia **GitFlow** para la gestion del codigo fuente:

* main: Rama de produccion con el codigo estable y listo para despliegue.
* develop: Rama base de integracion donde se unen las nuevas funcionalidades.
* feature: Ramas temporales de trabajo creadas a partir de develop para tareas especificas como ejm documentacion

## Reglas de Colaboración

Para entender facil que hizo cada uno en el historial de Git, usamos este formato simple (tipo: lo que hice):

ejemplos

* feat: Cuando agregamos una funcion o pantalla nueva.
* fix: Cuando arreglamos algun error o bug que salto.
* docs: Cuando editamos texto en la documentacion o el README.
* style: Ajustes visuales, espacios o diseno sin tocar la logica.
* refactor: Cuando mejoramos o limpiamos el codigo para que quede mas organizado.

Reglas para Pull Requests (PR) y Merges
1. Cero subidas directas:** Nadie hace git push directo a main ni a develop.
2. Paso por PR: Todo cambio en una rama feature/...se manda a develop creando un **Pull Request**.
3. Revision en equipo: Antes de unir el codigo (merge), al menos un companero tiene que revisar el PR y darle el visto bueno (aprobacion).
4. **Limpieza:** Una vez aprobado el PR y unido a `develop`, borramos la rama `feature` que usamos para no llenar el repositorio de ramas viejas.