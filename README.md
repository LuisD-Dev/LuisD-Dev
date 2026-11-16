<div align="center">

<img src="assets/profile-header.svg" width="100%" alt="Luis Diego Campos Murillo" />

**Software Engineering Student | Junior Software Developer**

[Contribuciones](#contribuciones-destacadas)　·　[Proyectos](#proyectos-destacados)　·　[LinkedIn](https://www.linkedin.com/in/luis-diego-campos-b1225b424)

</div>

Soy **Luis Diego Campos Murillo**, de Costa Rica, y estoy cursando el bachillerato de Ingeniería del Software en la **Universidad Técnica Nacional**. Desarrollo aplicaciones con C#, React y SQL Server. También colaboro en proyectos abiertos donde trabajo con procesamiento de eventos, integridad de datos y pruebas automatizadas.

## Contribuciones destacadas

| Proyecto | Qué aporté | Cambio integrado |
| :--- | :--- | :--- |
| **Velo** · Stellar / Soroban | Construí un indexador que guarda en **PostgreSQL** los eventos de fondos bloqueados, liberados o en disputa. Expuse ese historial mediante **GraphQL** y las actualizaciones en vivo mediante **WebSocket**. | [Ver PR #354 ↗](https://github.com/Nullifier-Systems/velo/pull/354) |
| **GuildPass** · Auditoría | Encadené las entradas del registro en **PostgreSQL** con hashes **SHA-256**. Un administrador puede verificar el historial y localizar la primera entrada afectada por una modificación. | [Ver PR #315 ↗](https://github.com/Adamantine-guild/guildpass-app/pull/315) |
| **Teclia Academy** · Pagos | Integré el SDK oficial de **Stripe** en **Express** para verificar las notificaciones de pago y evitar que un reintento procese dos veces el mismo evento. | [Ver PR #89 ↗](https://github.com/Teclia-Academy/Teclia-Academy/pull/89) |
| **Nester** · Contratos inteligentes | Escribí pruebas en **Rust** para comprobar quién puede ejecutar operaciones privilegiadas y qué ocurre después de revocar un rol. La suite del PR pasó 396 pruebas. | [Ver PR #797 ↗](https://github.com/Suncrest-Labs/nester/pull/797) |

## Proyectos destacados

### 🚚 Mantenimiento de Flota

API que desarrollé con Oscar Rojas García para administrar vehículos, órdenes de mantenimiento y repuestos. Un encargado puede buscar piezas por debajo del stock mínimo y comparar el precio y el plazo de entrega de sus proveedores.

**Cómo lo implementé.** Usé **ASP.NET Core** para los endpoints, **EF Core y SQL Server** para las relaciones entre activos, órdenes y repuestos, y **JWT** para identificar al usuario autenticado.

[Repositorio y ejemplos de la API](https://github.com/LuisD-Dev/ProyectoFlota#readme) · [Mi implementación del inicio de sesión](https://github.com/LuisD-Dev/ProyectoFlota/commit/20b85650489e334c4a9906bcf6f8fe01d888724f)

### 🧪 Reservas-Labs

Sistema de reservas de laboratorios de la UTN. El formulario en **React** envía la solicitud a una API en **C#**, que valida horarios, disponibilidad y propietario. Las reservas se almacenan en **SQL Server**.

**Mi aporte.** Escribí pruebas para el caso en que dos reservas se cruzan solo durante parte del horario. También configuré **Azure Pipelines** para compilar la API, ejecutar las pruebas y publicar sus resultados con cada cambio en la rama principal. La ejecución documentada en el PR pasó **209 pruebas**.

[Repositorio](https://github.com/LuisD-Dev/Reservas-Labs) · [Pruebas de traslapes](https://github.com/LuisD-Dev/Reservas-Labs/commit/2744e0402d209e888cdb29e6d202436dc1a5a204) · [Integración continua](https://github.com/LuisD-Dev/Reservas-Labs/pull/14)

### 🏘️ CondoGest

Aplicación de escritorio para administrar un condominio. Desde una propiedad se pueden consultar cargos, facturas y pagos. También cubre reservas de áreas comunes y registro de visitas mediante QR.

**Cómo funciona.** Los formularios en **WinForms** recogen los datos, la capa de negocio en **C#** aplica las reglas y la capa de persistencia usa **ADO.NET** para consultar y actualizar **SQL Server**.

[Repositorio y manuales](https://github.com/LuisD-Dev/CondoGest_ISW524) · [Arquitectura por capas](https://github.com/LuisD-Dev/CondoGest_ISW524/blob/main/ARQUITECTURA.md)

### 📦 Simulador de mensajería

Modelé una red de entregas en **C++** con una lista de adyacencia. **Dijkstra** calcula el recorrido más corto. Sobre el mismo grafo comparé dos formas de asignar paquetes: priorizar los urgentes o elegir el destino más cercano. Al simular ambas durante la misma cantidad de *ticks*, puedo medir cómo cambian la espera promedio y el total de entregas.

**Otros proyectos.** En **Chema Style** trabajé con React para la interfaz y Supabase para los datos. **Patitas CR** es un sitio web de adopción de mascotas. En **Teclia Academia**, la interfaz de aprendizaje en React se comunica con una API de Express que controla el acceso al contenido según el plan. [Explorar Teclia](https://github.com/LuisD-Dev/luis-rama/tree/develop)

<p align="center"><img src="https://skillicons.dev/icons?i=cs,dotnet,react,js,cpp,postgres,rust,git&theme=dark" alt="C#, .NET, React, JavaScript, C++, PostgreSQL, Rust y Git" /></p>

[Más contribuciones integradas](https://github.com/pulls?q=is%3Apr+is%3Amerged+author%3ALuisD-Dev) · [Todos mis repositorios](https://github.com/LuisD-Dev?tab=repositories)
