# FoodPlease – Mockups y Propuesta de Solución

Este repositorio contiene los mockups de la aplicación FoodPlease, un sistema multiplataforma pensado para mejorar la experiencia de clientes, locales y repartidores en el proceso de compra y entrega de alimentos.  
La idea central es digitalizar y optimizar cada paso de la cadena: desde la selección de productos con stock en tiempo real, hasta la entrega con navegación GPS y confirmación de entrega.


## Objetivo del Proyecto
FoodPlease busca resolver problemas comunes en la entrega de alimentos:
- Falta de visibilidad de **stock actualizado** para clientes.
- Gestión limitada de pedidos en los locales (solo desde PC).
- Ausencia de **geolocalización y trazabilidad en tiempo real**.
- Carencia de herramientas de **navegación moderna y confirmación digital** para repartidores.
- Experiencia incompleta del usuario por falta de feedback y seguimiento.


##  Arquitectura Propuesta
La solución está diseñada con una arquitectura moderna y escalable:
- MVC (Modelo–Vista–Controlador) → separación clara de lógica, datos y visualización.
- API REST → comunicación modular y extensible.
- Firebase → backend como servicio (autenticación, base de datos en tiempo real, notificaciones y hosting).
- Flutter → desarrollo multiplataforma para clientes, locales y repartidores.


## Flujo de Uso (Mockups)
Los mockups incluidos en este repositorio representan cada paso del flujo de FoodPlease:
1. Cliente accede y se registra desde web o app móvil.  
2. Visualiza un menú dinámico con productos disponibles en stock.  
3. Selecciona productos, ingresa dirección, método de pago y confirma pedido.  
4. Local acepta y cambia estado a “En preparación”.  
5. El sistema sugiere repartidores cercanos.  
6. Repartidor acepta la entrega y obtiene una ruta GPS optimizada.  
7. Entrega el pedido, gestionando pago (online o efectivo).  
8. Confirma entrega desde la app.  
9. Cliente califica el servicio y el pedido queda archivado en su historial.  

Cada mockup está nombrado según el **flujo de la vista** para facilitar la navegación.


## Estilo de Diseño
- Minimalista → uso de espacios amplios y tipografía legible.  
- Color `#81C784` (verde suave).  


## Roles de Usuario

- Cliente: navegar menú, ver stock, pagar online, rastrear pedido, confirmar con PIN/QR.  
- Local (Tienda): aceptar pedidos, cambiar estados, gestionar stock y promociones.  
- Repartidor: recibir asignaciones, navegar con GPS, confirmar entregas.  


## Futuras Mejoras
- Recomendaciones de menú basadas en IA.  
- Integración con sistemas de gestión de restaurantes.  
- PWA para funcionamiento offline en zonas con baja conectividad.  


## 📜 Créditos
Proyecto desarrollado como propuesta académica por Alejandra Marín Olavarría 
