# pulido-post2-u1
Analisis de peticiones HTTP con DevTools y Postman

# Análisis de Peticiones HTTP — Unidad 1
## Descripción
Repositorio de análisis de peticiones HTTP/HTTPS realizado con
Chrome DevTools y Postman como parte del laboratorio 2 de
Programación Web — Séptimo Semestre.
## Herramientas utilizadas
- Google Chrome + DevTools (panel Network)
- Postman (petición POST con tests)
## Análisis realizados
| # | Tipo | URL | Código |
|---|------|-----|--------|
| 1 | GET HTML | https://example.com | 200 OK |
| 2 | GET JSON (exitoso) | /posts/1 | 200 OK |
| 3 | GET JSON (fallido) | /posts/999 | 404 Not Found |
| 4 | POST JSON | /posts | 201 Created |

## Conclusiones
El análisis de las peticiones HTTP permitió comprender el funcionamiento de los métodos GET y POST, así como la importancia de los códigos de estado y los headers en la comunicación cliente-servidor. Se evidenció la diferencia entre el manejo de páginas web (HTML) y APIs REST (JSON), además del uso de herramientas como DevTools y Postman para inspeccionar y validar peticiones. En general, la práctica fortaleció la capacidad de analizar el tráfico web y entender cómo se intercambian los datos en aplicaciones modernas.