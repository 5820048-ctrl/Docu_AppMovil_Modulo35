# Especificación de Consumo de API REST
## Endpoint 1: Autenticación de Usuario
* **Método HTTP:** `POST`
* **Ruta:** `/api/v1/auth/login`
* **Formato de Envío (JSON):**
```json
{
"usuario": "ejemplo@correo.com",
"password": "password123"
}

• Respuesta Exitosa (200 OK):
JSON
{
"status": "success",
"token": "eyJhbGciOiJIUzI1NiIsIn..."
}