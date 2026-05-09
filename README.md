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

<img width="391" height="96" alt="4 BuscarIP" src="https://github.com/user-attachments/assets/22f0f795-9671-4c91-bab7-6863f26ae1a4" />
<img width="374" height="156" alt="3 Historial" src="https://github.com/user-attachments/assets/dbddb873-b43b-44a6-a22a-194fd7e526ad" />
<img width="421" height="113" alt="2 Procesado" src="https://github.com/user-attachments/assets/39148996-8654-479d-8495-cc3feeffb558" />
<img width="356" height="77" alt="1 Encolado" src="https://github.com/user-attachments/assets/68f58ffa-d26f-4a88-9067-2789079cf3a7" />
<img width="462" height="154" alt="Menu" src="https://github.com/user-attachments/assets/02a98f93-aa20-41e0-97ce-ae7e6405b377" />
<img width="377" height="126" alt="6 Historial_Desbordado" src="https://github.com/user-attachments/assets/0473e54b-5b98-44d7-9449-9907f9d7d778" />
<img width="611" height="147" alt="6 Desbordar" src="https://github.com/user-attachments/assets/7ca45313-530b-4d69-bbb5-ce9a12a55760" />
<img width="541" height="126" alt="5 Eliminar" src="https://github.com/user-attachments/assets/193a3ea6-7c19-4cea-b2b0-d462a5013004" />
