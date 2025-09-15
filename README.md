# ⚡ Test de Estructuras de Distribución Eléctrica

> Una aplicación web interactiva para el aprendizaje y evaluación de conocimientos sobre estructuras de líneas de media tensión.

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

## 🚀 Características

### 🎯 **Dos Niveles de Dificultad**
- **Fácil**: Sin límite de tiempo, ideal para aprendizaje pausado
- **Difícil**: Contrarreloj de 15 segundos por pregunta para expertos

### 🎨 **Interfaz Moderna**
- **Modo oscuro/claro** con toggle dinámico
- **Animaciones CSS** fluidas y naturales
- **Diseño responsivo** optimizado para móviles y escritorio
- **Gradientes y sombras** para una experiencia visual atractiva

### 🔊 **Sistema de Audio Inmersivo**
- **Web Audio API** para sonidos generados dinámicamente
- Sonidos diferenciados para respuestas correctas/incorrectas
- **Efectos de tiempo**: tic-tac, advertencias y tiempo agotado
- Control de activación/desactivación

### 📊 **Seguimiento de Progreso**
- **Barra de progreso animada** en tiempo real
- **Temporizador circular** con cambios de color progresivos
- **Sistema de estrellas** (1-5) basado en rendimiento
- **Estadísticas detalladas** de tiempo y precisión

### 🏆 **Sistema de Gamificación**
- **Logros dinámicos**: Perfección Total, Velocista, Racha Perfecta
- **Logros especiales** para modo difícil: Maestro del Tiempo
- **Medallas por rendimiento**: Oro (90%+), Plata (70%+), Bronce (50%+)
- **Animaciones de celebración** al completar el test

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica y accesible
- **CSS3**: Variables CSS, animaciones, flexbox, grid
- **JavaScript ES6+**: Clases, async/await, módulos
- **Web Audio API**: Generación de sonidos en tiempo real
- **LocalStorage**: Persistencia de preferencias de usuario

## 📁 Estructura del Proyecto

```
├── prototipo_test.html     # Versión original
├── test_mejorado.html      # Versión con mejoras UX/UI
├── README.md               # Este archivo
└── images/                 # Imágenes de estructuras eléctricas
    ├── 1757470908683blob.jpg
    ├── 1757470908686blob.jpg
    └── ...
```

## 🚀 Instalación y Uso

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/[usuario]/test-estructuras-electricas.git
   cd test-estructuras-electricas
   ```

2. **Abre en el navegador**:
   ```bash
   # Simplemente abre test_mejorado.html en tu navegador favorito
   # No requiere servidor local ni dependencias adicionales
   ```

3. **¡Disfruta del test!**:
   - Selecciona el número de preguntas (1-20)
   - Elige tu nivel de dificultad
   - Responde las preguntas sobre estructuras eléctricas
   - Obtén tu puntuación y logros

## 🎮 Cómo Jugar

### Modo Fácil 🎯
- Sin límite de tiempo
- Perfecto para aprender a tu ritmo
- Feedback detallado en cada respuesta

### Modo Difícil ⏱️
- 15 segundos por pregunta
- Temporizador visual con alertas sonoras
- Logros especiales por velocidad y precisión

### Controles
- **🌙/☀️**: Cambiar entre modo oscuro y claro
- **🔊/🔇**: Activar/desactivar sonidos
- **Zoom en imágenes**: Haz clic en las imágenes para ampliar

## 📋 Base de Datos de Estructuras

El test incluye 19 tipos diferentes de estructuras eléctricas:

- **A-I-1**: Estructura primaria una fase en tangente (0° - 5°)
- **A-I-2**: Estructura primaria una fase en ángulo (5° - 30°)
- **A-I-3**: Estructura primaria una fase de paso vertical (30° - 60°)
- **A-I-4**: Estructura primaria una fase en remate
- **A-I-5**: Estructura primaria una fase en doble remate (0° - 60°)
- Y muchas más...

## 🔧 Personalización

### Agregar Nuevas Estructuras
```javascript
// En el archivo test_mejorado.html, modifica el array quizDatabase:
const quizDatabase = [
    {
        id: "NUEVO-ID",
        nombre: "Descripción de la nueva estructura",
        imagenUrl: "ruta/a/la/imagen.jpg"
    },
    // ... más estructuras
];
```

### Modificar Tiempos y Dificultades
```javascript
// Cambiar tiempo límite en modo difícil (línea ~700):
timeRemaining = 20; // Cambiar de 15 a 20 segundos

// Modificar umbrales de logros:
if (percentage >= 80) { // Cambiar de 90 a 80
    achievements.push('🏆 Perfección Total');
}
```

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Si tienes ideas para mejorar el proyecto:

1. Fork el repositorio
2. Crea una rama para tu feature (`git checkout -b feature/nueva-funcionalidad`)
3. Commit tus cambios (`git commit -am 'Agregar nueva funcionalidad'`)
4. Push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Abre un Pull Request

## 📝 Roadmap

- [ ] **Modo multijugador** en tiempo real
- [ ] **Exportar resultados** a PDF/Excel
- [ ] **Categorías por tipo** de estructura
- [ ] **Sistema de usuarios** con historial de progreso
- [ ] **Modo de estudio** con explicaciones detalladas
- [ ] **API REST** para gestión de preguntas
- [ ] **PWA** para uso offline

