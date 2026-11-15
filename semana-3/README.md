Árbol de Componentes de Rueda Libre
Nota: Para una correcta visualización, por favor poner la opción de "code" y no el preview que pone por defecto Github, gracias.

App / Layout Principal (Estructura base de la página)
│
├── 1. Header (Cabecera de navegación)
│   ├── Logo (Marca "Rueda Libre")
│   └── Nav (Menú de navegación: Inicio, Catálogo, Tarifas, Contacto)
│
├── 2. Hero Section (Sección principal de bienvenida)
│   ├── Título principal y subtítulo descriptivo
│   └── Call to Action / Botón principal ("Reserva tu bicicleta")
│
├── 3. Catálogo / Sección de Bicicletas (Contenedor de productos)
│   └── [REPETIBLE] Card de Bicicleta (Tarjeta de producto)
│       ├── Imagen de la bicicleta
│       ├── Título / Modelo (Ej. Urbana, Montañera, Ruta)
│       ├── Descripción breve / Características
│       ├── Precio por hora/día
│       └── [REPETIBLE] Botón de acción / Selección ("Ver detalles" o "Reservar")
│
├── 4. Sección de Tarifas / Tabla de Precios
│   └── Tabla de Datos (Matrices de precios por categoría y tiempo)
│
├── 5. Sección de Reserva (Formulario de datos)
│   └── Formulario de Reserva
│       ├── [REPETIBLE] Campo de Texto / Input (Nombre, Correo, Teléfono)
│       ├── [REPETIBLE] Selector / Dropdown (Tipo de bicicleta, Horas)
│       └── [REPETIBLE] Botón de Envío / Validación
│
├── 6. Sección de Contacto e Información
│   ├── Enlaces a canales digitales (Redes sociales, WhatsApp)
│   └── Formulario o datos de contacto directo
│
└── 7. Footer (Pie de página)
    ├── Texto de derechos reservados
    └── Enlaces rápidos de navegación
