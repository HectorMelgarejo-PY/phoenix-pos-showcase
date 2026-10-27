<img src="banner.png" width="100%" alt="Phoenix POS · Punto de venta para minimercados · Rápido, liviano y confiable">

<p align="center">
  Sistema de punto de venta para minimercados y tiendas de barrio.<br>
  Rápido, liviano y pensado para el día a día del comercio.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C%2B%2B-17-00599C?logo=cplusplus&logoColor=white" alt="C++17">
  <img src="https://img.shields.io/badge/Qt-6-41CD52?logo=qt&logoColor=white" alt="Qt 6">
  <img src="https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white" alt="SQLite">
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white" alt="Supabase">
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4?logo=windows&logoColor=white" alt="Windows 10 y 11">
  <img src="https://img.shields.io/badge/versi%C3%B3n-1.0.6-1E3A8A" alt="Versión 1.0.6">
</p>

---

![Inicio](capturas/inicio.png)

## Sobre el proyecto

Phoenix POS es un sistema de punto de venta de escritorio que desarrollo y
mantengo en **Phoenix TS**. Lo usan comercios reales: está hecho para cobrar
rápido, controlar el stock sin complicaciones y funcionar bien incluso en
computadoras de pocos recursos.

> El código fuente es privado. Este repositorio muestra el producto.

## Funciones principales

| | |
|---|---|
| **Ventas** | Lector de código de barras, búsqueda por nombre o precio, productos frecuentes, ventas en espera y ticket imprimible o en PDF. |
| **Formas de pago** | Efectivo, transferencia o pago mixto, con cálculo del vuelto. |
| **Inventario** | Productos con o sin código de barras, venta por unidad o por paquete, costo y porcentaje de ganancia, aviso de stock bajo. |
| **Compras y proveedores** | Registro de compras e historial de costos y precios. |
| **Reportes** | Ventas del día por hora, totales por forma de pago, productos más vendidos y exportación a Excel. |
| **Usuarios** | Administrador y vendedores con permisos separados y cierre de sesión por inactividad. |
| **Datos seguros** | Copias de seguridad automáticas, recuperación de una base dañada y sincronización con la nube. |
| **Interfaz** | Modo claro y oscuro, textos grandes y legibles, adaptada a distintas escalas de pantalla. |

## Capturas

### Vender
![Ventas](capturas/ventas.png)

### Inventario
![Inventario](capturas/inventario.png)

### Reportes
![Reportes](capturas/reportes.png)

## Tecnología

- **C++17** y **Qt 6 (Widgets)** para una aplicación nativa, rápida y de bajo consumo.
- **SQLite** como base local, con migraciones versionadas e integridad verificada al arrancar.
- **Supabase (PostgreSQL)** para la sincronización en la nube, con conexión cifrada.
- Sistema de licencias por equipo e instalador **.msi**.
- Batería de pruebas automáticas: funcionales, de interfaz, de rendimiento con bases de
  100.000 productos y 500.000 ventas, y de resistencia ante cortes de luz y disco lleno.

## Licencia

Software propietario. © 2026 Hector Melgarejo, Phoenix TS. Todos los derechos reservados.

<img src="pie.png" width="100%" alt="">
