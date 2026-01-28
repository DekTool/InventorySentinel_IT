# INVENTORY SENTINEL IT DOCUMENTAL 

El proyecto **InventorySentinel-IT** es una aplicación React + TypeScript. Puede ejecutarse en entorno local para desarrollo o desplegarse fácilmente en producción usando plataformas como Vercel o Netlify.

https://github.com/user-attachments/assets/b4f77d0b-fd70-4791-b1ea-10559cc07f0a

## ⚙️ Instalación y uso

Para instalar y ejecutar el proyecto, sigue estos pasos:
**Clonar el repositorio**
   ```bash
   git clone https://github.com/DekTool/InventorySentinel_IT.git
   cd InventorySentinel_IT

 ```
## Instalar dependencias
```bash
  npm install
   ```
### Inicia el entorno de desarrollo
```bash
  npm start
   ```
### La aplicación estará disponible en:
```bash
   http://localhost:3000
```
### Compilar para producción
```bash
  npm run build
   ```
Esto generará una carpeta llamada build/ con los archivos listos para ser desplegados en cualquier servidor web o plataforma de hosting

---🧠 Autor DekTools
## ⚙️ Requisitos previos 

Antes de comenzar, asegúrate de tener instalado:
Node.js (versión 18 o superior recomendada)
npm o yarn
Una cuenta en GitHub
(Opcional) Cuenta en Vercel o Netlify para despliegue

### Funcionalidades Clave y su Uso Empresarial:

### ☁️Despliegue en Vercel (recomendado)

Accede a https://vercel.com
Inicia sesión con tu cuenta de GitHub
Haz clic en “New Project”
Selecciona el repositorio InventorySentinel_IT
Configuración:
Framework: React
Build Command: npm run build
Output Directory: build
Pulsa Deploy
Vercel detectará automáticamente la configuración y publicará la aplicación.

### ☁️ Despliegue en Netlify

Accede a https://www.netlify.com
Conecta tu cuenta de GitHub
Selecciona el repositorio
Configuración:
Build Command: npm run build
Publish Directory: build
Pulsa Deploy

### ☁️ Despliegue en servidor propio (Nginx / Apache)

Ejecuta el build:

npm run build
Copia el contenido de la carpeta build/ al servidor
Configura el servidor web para servir archivos estáticos
Ejemplo con Nginx:

root /var/www/inventorysentinel/build;
index index.html;

### Gestión de Inventario (/inventory):

Registro Centralizado: La empresa puede registrar todos sus activos de TI (portátiles, móviles, monitores, periféricos, servidores, etc.) en un solo lugar.
Seguimiento del Ciclo de Vida: Se puede rastrear el estado de cada activo: "En Stock", "Asignado", "Mantenimiento", "Retirado". Esto es crucial para saber cuándo reemplazar equipos, planificar compras o gestionar reparaciones.
Asignación a Usuarios: Se puede ver claramente qué equipo está asignado a qué empleado, junto con detalles específicos del equipo (N/S, MAC, configuraciones de software, etc.). Esto es vital para la responsabilidad y para la recuperación de equipos cuando un empleado deja la empresa.
Información Detallada: Los campos detallados para portátiles/sobremesas y móviles permiten documentar configuraciones específicas, software instalado, códigos de Bitlocker, IMEIs, etc., lo que es invaluable para el soporte técnico y la seguridad.
Escaneo de Códigos (/scan): El personal de TI puede escanear rápidamente un código de barras o ID de activo para obtener información instantánea sobre un equipo o usuario, facilitando las auditorías o el soporte en sitio.
Gestión de Usuarios (/users y /settings):

Directorio de Empleados: Mantiene una lista de los usuarios de la empresa, sus departamentos, información de contacto y, fundamentalmente, los equipos que tienen asignados.
Procesos de Onboarding/Offboarding:
Alta (Onboarding): Al dar de alta a un nuevo empleado (ya sea desde el formulario detallado o el básico en configuración), se puede preparar y registrar todo el equipamiento y accesos que necesita.
Baja (Offboarding): Al dar de baja a un empleado, se tiene una lista clara de los equipos que debe devolver. Los formularios imprimibles (/users/[userId]/print-return-form) ayudan a documentar este proceso.
Gestión de Roles: Aunque la autorización detallada aún no está implementada, la estructura permite definir roles (Administrador, Técnico, Usuario) que en un futuro controlarían el acceso a diferentes partes de la aplicación.
Gestión de Licencias (/licencias):

Control de Software: Permite registrar todas las licencias de software, su tipo (OEM, suscripción, perpetua), cantidad de puestos, fechas de compra y caducidad.
Cumplimiento y Costos: Ayuda a asegurar que la empresa cumple con los términos de las licencias y a planificar renovaciones, evitando gastos innecesarios o multas.
Gestión de Pedidos (/pedidos):

Seguimiento de Compras: La empresa puede registrar y seguir el estado de los pedidos de nuevo material (desde "Solicitado" hasta "Recibido").
Presupuesto y Planificación: Facilita la gestión de presupuestos de TI y la planificación de la llegada de nuevo equipamiento.
Gestión de Entregas (/entregas):

Registro de Entregas: Documenta formalmente qué equipos se han entregado a qué usuarios, cuándo y en qué estado. Esto complementa la asignación de inventario.
Gestión de Líneas Móviles (/mobile-lines):

Control de Líneas Corporativas: Permite llevar un registro de los números de teléfono, operadores, planes, SIMs y a quién están asignadas las líneas móviles de la empresa.
Beneficios para la Empresa:

Visibilidad y Control: Tener una vista unificada de todos los activos de TI.
Reducción de Pérdidas: Saber quién tiene qué reduce la pérdida de equipos.
Eficiencia Operativa: Agiliza los procesos de alta y baja de empleados, así como el soporte técnico.
Cumplimiento Normativo: Ayuda a gestionar las licencias de software correctamente.
Optimización de Costos: Permite tomar decisiones informadas sobre compras, renovaciones y reutilización de equipos.
Seguridad Mejorada: Documentar configuraciones clave y accesos ayuda a mantener la seguridad de los sistemas.
  
### Contribuciones
Las contribuciones son bienvenidas. Si deseas contribuir hablame. 

### Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.
