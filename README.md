📦 Desktop Catalog Manager
Sistema de gestión de inventario y catálogo de productos desarrollado como aplicación de escritorio (Desktop) sobre la plataforma .NET.
Este proyecto implementa un CRUD (Create, Read, Update, Delete) completo, permitiendo administrar artículos, marcas y categorías con persistencia de datos en SQL Server.

⚙️ Tecnologías y Arquitectura
- Lenguaje: C#
- Framework: .NET Framework / Windows Forms
- Base de Datos: Microsoft SQL Server
- Arquitectura: Diseño en 3 capas (Modelo-Vista-Negocio) para desacoplar la lógica de la interfaz.

✨ Funcionalidades Principales
- Gestión de Artículos: Altas, bajas y modificaciones de productos con validación de datos.
- Búsqueda y Filtrado: Filtros rápidos y búsqueda avanzada contra base de datos.
- Manejo de Imágenes: Carga y previsualización de imágenes de productos vía URL.
- Administración de Entidades: ABM de Marcas y Categorías.

🛠️ Instalación y Despliegue
1. Clonar el repositorio.
2. Ejecutar el script "CATALOGO_DB_v3.sql" en SQL Server Management Studio para crear la base de datos y cargar los datos de prueba.
3. Abrir la solución .sln en Visual Studio.
4. Configurar la cadena de conexión en la clase AccesoDatos si es necesario.
5. Compilar y ejecutar.
