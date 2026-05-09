# Ex_Final
Repositorio del examen final de Estructura de Datos 

# Sistema de Gestión de Tráfico y Caché - Evaluación Final

# MOISES GABRIEL MALPARTIDA ZABALETA

## Desarrollo del examen

### Lenguaje elegido / C#

### Justificación de la elección
Elegi C#, ya que ya cuento con una base más solida de conocimiento con el mismo lenguaje. 

Para el Motor de Búsqueda (Caché), se usa la clase `Dictionary<TKey, TValue>` como tabla hash.
Para colisiones (cuando dos claves distintas generan el mismo código hash), C# maneja encadenamiento (chaining), almacenando los elementos en una lista enlazada interna para ese valor.

---

## Pruebas y Logs de la Consola
### Procesamiento de Paquetes

``text
  SISTEMA DE GESTION DE TRAFICO Y CACHE 
1. Encolar nuevo paquete, agregando una nueva IP
2. Procesar paquetes en cola, agregando la IP al cache
3. Mostrar historial de IPs, dentro del cache
4. Buscar una IP dentro del cache
5. Ejecutar limpieza, eliminando una IP en especifico
6. Simular trafico alto (Prueba limite 100)
7. Salir
Elija una opcion: 2

Desencolando paquetes
Procesando paquete X... IP origen 192.168.0.1
IP anadida al historial...
IP guardada en cache de confianza.

Procesando paquete X... IP origen 10.0.0.3
IP anadida al historial...
IP guardada en cache de confianza.