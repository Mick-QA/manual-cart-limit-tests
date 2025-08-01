# Pruebas Manuales - Límite de Artículos en Cesta

Este repositorio contiene un caso de prueba para verificar que el sistema de una app de comida respete el límite de 30 artículos en la cesta de compra.

**ID:** QAUG-K3  
**Nombre del caso:** Validar límite de 30 artículos en la cesta  
**Precondiciones:** Usuario registrado con sesión iniciada  

**Pasos:**
1. Iniciar sesión en la app
2. Navegar al menú de productos
3. Agregar 30 artículos iguales al carrito
4. Verificar que los 30 artículos se muestran correctamente
5. Intentar agregar un artículo adicional (número 31)
6. Verificar la respuesta del sistema

**Resultado esperado:**
- El sistema debe aceptar hasta 30 artículos.
- Al intentar agregar un artículo adicional, debe mostrar un mensaje de error o bloquear la acción.

**Resultado obtenido:**
✅ El sistema permitió agregar hasta 30 artículos.  
❌ Al intentar agregar el artículo 31, se mostró un mensaje: *“Has alcanzado el límite de artículos permitidos”*.  
✔️ Comportamiento coincide con lo esperado.

**Estado de la prueba:** PASADA ✅
