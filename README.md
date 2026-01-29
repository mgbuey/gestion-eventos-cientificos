# Aplicación de gestión de eventos científicos

**Descripción del proyecto:

Proyecto de software orientado a la organización y administración de eventos científicos, como congresos y talleres. Permite gestionar participantes, ponentes, contribuciones y el programa del evento de forma centralizada.

**Funcionalidades previstas:

- Crear y editar eventos.
- Registrar contribuciones científicas (charlas, pósters, sesiones) en un evento.
- Gestionar ponentes y asistentes en un evento.

**Estructura básica del proyecto:

```sh
nombre_del_proyecto/
│
├── README.md              # Descripción y uso del proyecto
├── requirements.txt       # Dependencias del proyecto
├── setup.py               # Script de instalación del paquete
│
├── src/                   # Directorio raíz del código fuente (opcional pero recomendado)
│   └── event_manager/     # Código fuente principal del proyecto
│       ├── __init__.py    # Hace que el directorio sea un paquete
│       ├── main.py        # Punto de entrada de la aplicación
│       └── interface.py   # Módulo que se encarga de la interacción con el usuario
│
├── tests/                 # Pruebas unitarias
│   ├── __init__.py
│   └── test_interface.py  # Tests del módulo de interacción con el usuario
│
└── docs/                  # Documentación del proyecto
```
