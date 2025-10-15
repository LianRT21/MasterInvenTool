# Patrones de Diseño en Manager_InvenTool

## 1. Patrón Singleton
**Clase:** `DatabaseConnection`  
**Rol:** Asegura que exista una única instancia de la conexión a la base de datos.  
**Motivo:** Control centralizado de acceso a datos y recursos compartidos.

## 2. Patrón MVC (Modelo-Vista-Controlador)
**Aplicación general:**  
- **Modelo:** Clases como `Producto`, `Empleado`, `Cliente` representan los datos.
- **Vista:** Interfaces gráficas (`.java` con JFrame o JPanel).
- **Controlador:** Clases que manejan los eventos de los botones y comunican vista ↔ modelo.

## 3. Patrón DAO (Data Access Object)
**Clases:** `InventarioDAO`, `ClienteDAO`, etc. (si existen o si planeas crearlas)  
**Rol:** Separar la lógica de negocio del acceso a datos, simplificando mantenimiento y pruebas.

## 4. Patrón Observer (opcional si hay eventos GUI)
**Contexto:** Ventanas que reaccionan a eventos del usuario.  
**Ejemplo:** Listeners que observan cambios en componentes de interfaz.

---

### Conclusión

La arquitectura del sistema combina principios de **MVC** con componentes tipo **DAO** y uso puntual de **Singleton** para la gestión de recursos. Esto facilita la escalabilidad, la mantenibilidad y la posibilidad de migrar el proyecto a una arquitectura modular o Maven.
