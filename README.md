# 📅 PlanDay

> Aplicación móvil de planificación semanal inteligente para Android

![Estado](https://img.shields.io/badge/Estado-En%20desarrollo-yellow)
![Plataforma](https://img.shields.io/badge/Plataforma-Android-green)
![Flutter](https://img.shields.io/badge/Flutter-3.x-blue)

---

## 📌 Descripción del problema que resuelve

Hoy en día es fácil llegar al final del día sintiendo que hiciste muchas cosas pero no avanzaste en lo que realmente importaba. Las tareas se acumulan en notas dispersas, los compromisos se olvidan y la semana pasa sin un plan claro.

PlanDay resuelve esto dándote una vista completa de tu semana desde el primer momento: sabés qué tenés pendiente, a qué hora, en qué categoría, y cuánto has avanzado. Sin complicaciones, sin apps de más.

---

## 🎯 Objetivo de la aplicación

Brindar a los usuarios una herramienta móvil simple y efectiva para **organizar su semana**, gestionar tareas por día, establecer recordatorios y hacer seguimiento de su productividad personal — todo desde su teléfono Android.

---

## 👤 Historias de usuario — MVP

| # | Historia | Criterio de aceptación |
|---|----------|------------------------|
| HU-01 | Como usuario quiero **crear tareas** para registrar mis actividades pendientes | El usuario puede ingresar título, descripción, fecha, hora, categoría y prioridad |
| HU-02 | Como usuario quiero **organizar tareas por días de la semana** para tener una visión clara de mi semana | Las tareas se muestran agrupadas por día en una vista semanal navegable |
| HU-03 | Como usuario quiero **recibir recordatorios de mis actividades** para no olvidar compromisos importantes | El sistema envía una notificación antes de la hora programada de la tarea |
| HU-04 | Como usuario quiero **marcar tareas como completadas** para hacer seguimiento de mi progreso | Las tareas completadas se marcan visualmente y se separan de las pendientes |

---

## 🛠️ Tecnología utilizada

| Tecnología | Uso |
|------------|-----|
| **Flutter** | Framework principal de desarrollo |
| **Dart** | Lenguaje de programación |
| **Android Studio** | Entorno de desarrollo |
| **Git + GitHub** | Control de versiones |
| **Local Notifications** | Recordatorios y alertas |

---

## 🚀 Instrucciones de instalación

### Requisitos previos

- Flutter SDK `>=3.0.0`
- Android Studio instalado
- Git instalado
- Dispositivo físico o emulador Android (API 21+)

### Pasos

```bash
# 1. Clonar el repositorio
git clone https://github.com/iandrango/PlanDay1.git

# 2. Entrar a la carpeta del proyecto
cd PlanDay1

# 3. Instalar dependencias
flutter pub get

# 4. Ejecutar la aplicación
flutter run
```

> **Nota:** Asegúrate de tener un emulador activo o un dispositivo conectado con depuración USB habilitada.

### Configuración de Git (primera vez)

```bash
git config --global user.email "tu-email@gmail.com"
git config --global user.name "tu-usuario"
```

---

## 📸 Capturas de pantalla

![PlanDay Screens](planday_screenshots.png)

| Pantalla | Descripción |
|----------|-------------|
| **Login** | Acceso con correo/contraseña o Google. Incluye recuperación de contraseña |
| **Dashboard** | Vista semanal con indicador de productividad diaria y lista de actividades por categoría |
| **Nueva actividad** | Formulario completo con título, descripción, fecha, hora, categoría y prioridad |

---

## 📊 Estado actual del proyecto

```
🟡 EN DESARROLLO — Versión 0.1.0 (MVP)
```

| Funcionalidad | Estado |
|---------------|--------|
| Pantalla de Login | ✅ Diseñada |
| Vista semanal / Dashboard | ✅ Diseñada |
| Crear actividad | ✅ Diseñada |
| Categorías (Trabajo, Personal, Estudio) | ✅ Diseñada |
| Indicador de productividad | ✅ Diseñado |
| Recordatorios con notificación | 🔄 En progreso |
| Marcar como completada | 🔄 En progreso |
| Pruebas unitarias | ⏳ Pendiente |

---

## 📁 Estructura del proyecto

```
PlanDay/
├── lib/
│   ├── main.dart
│   ├── models/
│   ├── screens/
│   │   ├── login_screen.dart
│   │   ├── dashboard_screen.dart
│   │   └── nueva_actividad_screen.dart
│   ├── widgets/
│   └── services/
├── android/
├── assets/
├── test/
└── pubspec.yaml
```

---

## 🤝 Contribuciones

1. Haz un fork del repositorio
2. Crea una rama: `git checkout -b feature/nueva-funcionalidad`
3. Commit: `git commit -m "Agrega nueva funcionalidad"`
4. Push: `git push origin feature/nueva-funcionalidad`
5. Abre un Pull Request

---

## 📄 Licencia

Este proyecto está bajo la licencia **MIT**.

---

<p align="center">
  Desarrollado con ❤️ por <a href="https://github.com/iandrango">@iandrango</a>
</p>
