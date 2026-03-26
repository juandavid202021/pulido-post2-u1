# Análisis 3: Petición POST — API REST (Postman)  

## Información general  
- URL: https://jsonplaceholder.typicode.com/posts  
- Método: POST  
- Código de estado: 201 Created  

## Headers de Request  
| Header | Valor |  
|--------|-------|  
| Content-Type | application/json |  
| User-Agent | PostmanRuntime |  
| Accept | */* |  

## Headers de Response  
| Header | Valor | Significado |  
|--------|-------|-------------|  
| Content-Type | application/json | Indica que la respuesta está en formato JSON |  
| X-Powered-By | Express | Indica la tecnología del servidor |  
| Date | Thu, 26 Mar 2026 | Fecha en que el servidor envía la respuesta |  
| Connection | keep-alive | Mantiene la conexión abierta para futuras peticiones |  

## Tiempos de carga  
| Fase | Tiempo (ms) |  
|------|------------|  
| DNS Lookup | 0 (no visible) |  
| Initial Connection | ~3 |  
| SSL | (no visible) |  
| TTFB | ~100 |  
| Content Download | ~1 |  

# Conclusión
La petición POST realizada a la API permitió enviar datos al servidor y crear un nuevo recurso, lo cual se confirma con el código 201 Created. A diferencia de las peticiones GET, esta incluye un cuerpo con información en formato JSON, lo que permite la creación de datos en el servidor. La respuesta incluye un campo id generado automáticamente, evidenciando la creación del recurso. Además, los tiempos de respuesta son bajos, lo que indica un buen rendimiento del servicio.

## Response (Cuerpo)  
```json
{
  "title": "Laboratorio Programacion Web",
  "body": "Analisis de peticiones HTTP con Postman.",
  "userId": 1,
  "id": 101
}
