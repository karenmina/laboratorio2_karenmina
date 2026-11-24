# Laboratorio 2 – Arquitectura de Datos

**Estudiante:** Karen Mina  
**Repositorio:** `laboratorio2_karenmina`  
**Asignatura:** Arquitectura de Datos  
**Universidad:** Universidad Dr. José Matías Delgado

## 1. Descripción del proyecto

Este repositorio contiene el desarrollo del Laboratorio 2 de la asignatura Arquitectura de Datos.

El proyecto trabaja con una base de datos relacional PostgreSQL alojada en Neon, cuya información se conecta con Power BI para su preparación, modelado y visualización mediante informes interactivos.

Este laboratorio se desarrolla de manera independiente del proyecto KRAF y de las prácticas anteriores de la asignatura.

## 2. Tecnologías utilizadas

| Tecnología | Aplicación |
|---|---|
| PostgreSQL | Base de datos relacional |
| Neon | Alojamiento de PostgreSQL en la nube |
| Power BI Web | Conexión, modelado y elaboración de informes |
| GitHub | Control de versiones y documentación |
| SQL | Consulta y gestión de datos |

## 3. Estructura de la base de datos

La conexión con PostgreSQL permite acceder al esquema `public`, que contiene cinco tablas:

| Tabla | Descripción |
|---|---|
| `catalogo` | Catálogo de productos, categorías y precios |
| `clientes` | Información y segmentación de clientes |
| `detalle_operacion` | Productos, cantidades, precios y descuentos por operación |
| `operaciones` | Registro de operaciones, fechas, estados, canales, clientes y sedes |
| `sedes` | Información de sedes y ciudades |

## 4. Conexión y herramientas

La base de datos se encuentra alojada en Neon y se conecta mediante el conector PostgreSQL de Power BI.

La información se carga en Power BI para preparar el modelo semántico y desarrollar visualizaciones a partir de los datos disponibles.

## 5. Organización del repositorio

```text
laboratorio2_karenmina/
│
├── database/
│   └── Scripts SQL
│
├── power-bi/
│   └── Archivos e información del informe
│
├── evidencias/
│   └── Capturas del desarrollo
│
├── README.md
└── .gitignore
```

## 6. Avance del laboratorio

- [x] Creación del repositorio en GitHub.
- [x] Conexión de PostgreSQL alojado en Neon.
- [x] Identificación de las cinco tablas del esquema `public`.
- [x] Carga de datos en Power BI Web.
- [x] Creación del modelo semántico.
- [ ] Configuración y validación de relaciones.
- [ ] Desarrollo de medidas y cálculos.
- [ ] Diseño del informe interactivo.
- [ ] Documentación de resultados y conclusiones.

## 7. Seguridad

Por seguridad, este repositorio no debe contener contraseñas, cadenas de conexión completas, archivos con credenciales ni información de acceso a la base de datos.

## 8. Estado del proyecto

**En desarrollo.**

La documentación, los scripts SQL y las evidencias se actualizarán conforme avance el laboratorio.
:::
