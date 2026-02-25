# 🎯 MITRE ATT&CK Interactive Learning Platform

Una aplicación web interactiva para aprender el framework MITRE ATT&CK de forma progresiva y práctica.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Pages](https://img.shields.io/badge/demo-online-success)](https://byronlainez.github.io/mitre-attack-learning)

## 🌟 Características

- ✅ **Dos Modos de Aprendizaje**: Básico y Avanzado
- ✅ **12 Tácticas Principales**: Con descripciones detalladas
- ✅ **25+ Técnicas**: Con IDs oficiales (T1566, T1190, etc.)
- ✅ **Ejemplos Reales**: Casos de uso de cada técnica
- ✅ **Detección y Mitigación**: Guías prácticas de defensa
- ✅ **100% Responsive**: Funciona en móviles, tablets y desktop
- ✅ **Sin Dependencias**: Todo en un solo archivo HTML
- ✅ **Zero Backend**: Cliente puro, sin servidor necesario

## 🚀 Demo en Vivo

👉 **[Ver Demo en GitHub Pages](https://byronlainez.github.io/mitre-attack-learning)**

![Screenshot](https://via.placeholder.com/800x400/667eea/ffffff?text=MITRE+ATT%26CK+Learning+Platform)

## 📦 Estructura del Proyecto
```
mitre-attack-learning/
├── index.html          # Aplicación completa (React + Tailwind)
├── README.md           # Documentación del proyecto
├── LICENSE            # Licencia MIT
└── .gitignore         # Archivos ignorados por Git
```

## 🛠️ Instalación Local

### Opción 1: Abrir Directamente
```bash
# Clonar el repositorio
git clone https://github.com/byronlainez/mitre-attack-learning.git
cd mitre-attack-learning

# Abrir index.html en tu navegador
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

### Opción 2: Servidor Local (Recomendado)
```bash
# Con Python 3
python -m http.server 8000

# Con Node.js
npx serve

# Con PHP
php -S localhost:8000

# Luego abre: http://localhost:8000
```

## 🌐 Deployment en GitHub Pages

### Método Automático (Recomendado)

1. **Crear repositorio en GitHub**
   - Ve a [github.com/new](https://github.com/new)
   - Nombre: `mitre-attack-learning`
   - Público ✅
   - NO inicializar con README

2. **Subir archivos**
```bash
git init
git add .
git commit -m "🚀 Initial commit: MITRE ATT&CK Learning Platform"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/mitre-attack-learning.git
git push -u origin main
```

3. **Activar GitHub Pages**
   - Ve a: `Settings` → `Pages`
   - Source: `Deploy from a branch`
   - Branch: `main` → `/` (root)
   - Click `Save`
   - ✅ Tu sitio estará en: `https://TU-USUARIO.github.io/mitre-attack-learning`

### Método Manual

1. Crea un repositorio en GitHub
2. Sube los archivos manualmente desde la interfaz web
3. Activa GitHub Pages en Settings

## 📚 Cómo Usar la Aplicación

### 🎓 Modo Básico
Ideal para principiantes que nunca han usado MITRE ATT&CK:
1. **Introducción**: ¿Qué es MITRE ATT&CK y para qué sirve?
2. **Tácticas vs Técnicas**: Entender la diferencia fundamental
3. **Resumen**: Conceptos clave aprendidos

### 🚀 Modo Avanzado
Para profesionales que quieren profundizar:
1. **Análisis Profundo**: Objetivos de cada táctica
2. **Explorador Interactivo**: Navega por todas las tácticas
3. **IDs Oficiales**: Técnicas con códigos TXXXX
4. **Ejemplos Reales**: Casos de ataques del mundo real
5. **Detección**: Cómo identificar cada técnica
6. **Mitigación**: Estrategias de defensa

## 🎯 Contenido Educativo

### Tácticas Cubiertas

| Táctica | Emoji | Descripción | Técnicas |
|---------|-------|-------------|----------|
| Reconnaissance | 🔍 | Recopilar información del objetivo | 2 |
| Initial Access | 🚪 | Obtener acceso inicial | 3 |
| Execution | ⚡ | Ejecutar código malicioso | 2 |
| Persistence | 🔒 | Mantener acceso al sistema | 2 |
| Privilege Escalation | ⬆️ | Obtener permisos superiores | 2 |
| Defense Evasion | 👻 | Evitar detección | 2 |
| Credential Access | 🔑 | Robar credenciales | 2 |
| Discovery | 🗺️ | Explorar el entorno | 2 |
| Lateral Movement | ↔️ | Moverse entre sistemas | 2 |
| Collection | 📦 | Reunir información | 2 |
| Exfiltration | 📤 | Extraer datos | 2 |
| Impact | 💥 | Causar daño | 2 |

### Información por Técnica

Cada técnica incluye:
- ✅ **ID Oficial** (formato TXXXX según MITRE)
- ✅ **Nombre** de la técnica
- ✅ **Descripción** clara y concisa
- ✅ **Ejemplo Real** de uso en ataques
- ✅ **Métodos de Detección** para Blue Team
- ✅ **Estrategias de Mitigación** recomendadas

## 🛡️ Casos de Uso

### Para Estudiantes
- Aprender los fundamentos de MITRE ATT&CK
- Prepararse para certificaciones (CCFR, GCTI, etc.)
- Entender cómo piensan los atacantes

### Para Profesionales SOC
- Referencia rápida durante análisis de incidentes
- Mapear alertas a técnicas específicas
- Comunicar hallazgos con terminología estándar

### Para Instructores
- Material educativo interactivo
- Complemento para cursos de ciberseguridad
- Herramienta de demostración en vivo

### Para Analistas de Amenazas
- Entender cadenas completas de ataque
- Identificar tácticas en reportes de threat intel
- Documentar campañas de APTs

### Para Equipos Blue Team
- Mapear defensas actuales contra ATT&CK
- Identificar gaps en cobertura de seguridad
- Priorizar inversiones en controles

## 🔧 Tecnologías Utilizadas

- **React 18.2.0** - Framework UI (vía CDN)
- **Tailwind CSS 3.x** - Framework CSS (vía CDN)
- **Babel Standalone** - Compilador JSX en navegador
- **Lucide Icons** - Íconos SVG embebidos
- **HTML5** - Estructura semántica
- **ES6+** - JavaScript moderno

### ¿Por qué sin build tools?
- ✅ Cero configuración necesaria
- ✅ Funciona abriendo el archivo directamente
- ✅ Fácil de modificar y personalizar
- ✅ Ideal para GitHub Pages
- ✅ No requiere Node.js ni npm

## 📖 Recursos Adicionales

### Oficiales de MITRE
- [MITRE ATT&CK Website](https://attack.mitre.org/)
- [ATT&CK Navigator](https://mitre-attack.github.io/attack-navigator/)
- [ATT&CK Training](https://attack.mitre.org/resources/training/)
- [ATT&CK Blog](https://medium.com/mitre-attack)

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! 

### Cómo Contribuir

1. **Fork** el proyecto
2. Crea una rama feature (`git checkout -b feature/NuevaTecnica`)
3. **Commit** tus cambios (`git commit -m '✨ Agregar técnica T1234'`)
4. **Push** a la rama (`git push origin feature/NuevaTecnica`)
5. Abre un **Pull Request**

### Ideas para Contribuir
- ✅ Agregar más técnicas del framework oficial
- ✅ Mejorar ejemplos con casos reales
- ✅ Traducir a otros idiomas (inglés, portugués, etc.)
- ✅ Agregar casos de estudio completos
- ✅ Mejorar la UI/UX
- ✅ Agregar modo oscuro
- ✅ Incluir sub-técnicas
- ✅ Exportar progreso del usuario

### Guía de Estilo
- Commits en español con emojis: 🎨 🐛 ✨ 📝 🚀
- Código limpio y comentado
- Responsive design obligatorio
- Accesibilidad (a11y) considerada

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

### ¿Qué puedes hacer?
- ✅ Usar comercialmente
- ✅ Modificar el código
- ✅ Distribuir
- ✅ Uso privado
- ⚠️ La licencia y copyright deben incluirse

## 👨‍💻 Autor

**Byron Lainez (Bals)**
- 🏢 MSS Engineer @ SISTEMAS APLICATIVOS, S.A. (SISAP)
- 🎓 Instructor @ Cyber Defensa Academy
- 🌐 Website: [byronlainez.click](https://byronlainez.click)
- 💼 LinkedIn: [Byron Lainez](https://linkedin.com/in/byron-lainez)
- 🐦 Twitter: [@byronlainez](https://twitter.com/byronlainez)
- 📧 Email: contacto@byronlainez.click

## 🙏 Agradecimientos

- **MITRE Corporation** por crear y mantener el framework ATT&CK
- **Comunidad de ciberseguridad** por compartir conocimiento
- **Todos los contribuidores** que mejoran este proyecto
- **Cyber Defensa Academy** por el apoyo educativo

## 📊 Estadísticas del Proyecto

- 📚 **12 Tácticas** principales cubiertas
- 🎯 **25+ Técnicas** con detalles completos
- 🌍 **100% Traducido** al español
- ⚡ **<100KB** de tamaño total
- 🚀 **<1s** de tiempo de carga

## 🔄 Roadmap

### v1.0 (Actual)
- [x] Modo básico y avanzado
- [x] 12 tácticas principales
- [x] 25+ técnicas con IDs
- [x] Ejemplos y mitigaciones
- [x] Responsive design

### v2.0 (Próximo)
- [ ] Sub-técnicas detalladas
- [ ] Modo oscuro
- [ ] Búsqueda de técnicas
- [ ] Exportar progreso
- [ ] Quizzes interactivos
- [ ] Casos de estudio completos

### v3.0 (Futuro)
- [ ] Multi-idioma (EN, PT)
- [ ] Integración con ATT&CK Navigator
- [ ] API pública
- [ ] Gamificación
- [ ] Certificados de completación

## 📞 Soporte

¿Necesitas ayuda?

- 🐛 [Reportar un Bug](https://github.com/byronlainez/mitre-attack-learning/issues/new?template=bug_report.md)
- 💡 [Solicitar Feature](https://github.com/byronlainez/mitre-attack-learning/issues/new?template=feature_request.md)
- 💬 [Iniciar Discusión](https://github.com/byronlainez/mitre-attack-learning/discussions)
- 📧 [Email Directo](mailto:contacto@byronlainez.click)

## ⭐ Muestra tu Apoyo

Si este proyecto te fue útil:
- ⭐ Dale una estrella al repositorio
- 🔄 Compártelo con colegas
- 🐦 Tweet sobre el proyecto
- 💰 [Sponsor](https://github.com/sponsors/byronlainez) (opcional)

---

<div align="center">

**Hecho con ❤️ para la comunidad de ciberseguridad**

[Website](https://byronlainez.click) • [GitHub](https://github.com/byronlainez) • [LinkedIn](https://linkedin.com/in/byron-lainez)

</div>
```

---

## 📁 Archivo 3: `LICENSE`
```
MIT License

Copyright (c) 2025 Byron Lainez

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 📁 Archivo 4: `.gitignore`
```
# Sistema Operativo
.DS_Store
Thumbs.db
desktop.ini

# Editores
.vscode/
.idea/
*.swp
*.swo
*~
.project
.settings/

# Logs
*.log
npm-debug.log*
yarn-debug.log*
yarn-error.log*

# Temporal
*.tmp
*.temp
.cache/

# Backups
*.bak
*.backup

# Node (si decides agregar build tools después)
node_modules/
package-lock.json
yarn.lock
dist/
build/
```

---

## 📋 Instrucciones de Guardado

1. **Crea la carpeta:** `mitre-attack-learning`
2. **Guarda cada archivo** con su nombre exacto:
   - `index.html`
   - `README.md`
   - `LICENSE`
   - `.gitignore`

3. **Verifica la estructura:**
```
mitre-attack-learning/
├── index.html
├── README.md
├── LICENSE
└── .gitignore