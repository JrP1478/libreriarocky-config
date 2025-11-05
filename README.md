# 🏪 LibreriaRocky - Configuración Centralizada

Repositorio de configuración para la arquitectura de microservicios de LibreriaRocky.

## 📁 Estructura
configs/
├── application.yml # Configuración global
├── usuarios-service.yml # Microservicio de usuarios
├── inventario-service.yml # Microservicio de inventario
├── ventas-service.yml # Microservicio de ventas
├── api-gateway.yml # API Gateway
└── service-discovery.yml # Eureka Server


## 🚀 Servicios

| Servicio | Puerto | Descripción |
|----------|--------|-------------|
| Config Server | 8888 | Configuración centralizada |
| Eureka Server | 8761 | Service Discovery |
| API Gateway | 8080 | Puerta de entrada única |
| Usuarios Service | 8081 | Gestión de usuarios y auth |
| Inventario Service | 8082 | Productos y stock |
| Ventas Service | 8083 | Procesamiento de pedidos |

## 🔧 Desarrollo

### Config Server URL
http://localhost:8888/{service-name}/{profile}


### Ejemplos:
- http://localhost:8888/usuarios-service/default
- http://localhost:8888/inventario-service/dev

## 👥 Equipo
- Desarrollo: [Tu nombre]
- Proyecto: LibreriaRocky E-commerce
