Auditoria del informe de Análisis Estático

* App Name: EvalucionMAPAS-SR
* Android versión Name: 1.0
  
* File Name: app-debug.apk
* Package Name: com.zimmer.evaluacionmapas_sr
* Scan Date: Oct. 22, 2024, 8:44 p.m.
* App Security Score: 36/100 (HIGH RISK)
* Grade: C

_Compatibilidad
* Descripción: la aplicación puede instalarse en versiones anteriores de Android (minSdk=24)
* Severidad: Alta
* Acción Correctiva: Establecer como objetivo una versión más reciente (API 29 o superior)

_Modo Debug Habilitado
* Descripción: El modo debug está habilitado, facilitando la ingeniería inversa.
* Severidad: Alta
* Acción Correctiva: Deshabilitar el modo debug en la configuración de la aplicación.
 
_Respaldo de datos en la aplicación
* Descripción: Opción "android:allowBackup=true", permitiendo el respaldo de datos.
* Severidad: Advertencia
* Acción Correctiva: Cambiar esta opción a "false".

_Permisos Peligrosos
* Descripción: Usó de permisos de ubicación " ACCESS_FINE_LOCATION", "ACCESS_COARSE_LOCATION"
* Severidad: Alta
* Acción Correctiva: Justificar la necesidad de estos permisos y considerar consentimientos más estrictos.

_Receptor de Broadcast Exportado
* Descripción: Receptor compartido sin una protección de permiso adecuada.
* Severidad: Advertencia
* Acción Correctiva: Revisar el nivel de protección del permiso y restringir el acceso si es necesario
 
_Recomendaciones Generales

* Revisar la lógica de seguridad: considerar el uso de checks de sistema para prevenir el análisis no autorizado.
* Análisis Dinámico: Realizar pruebas adicionales en un entorno controlado para indicar vulnerabilidades en caso de que el análisis estático no las haya detectado.


// Esta aplicacion fue realizada por Sergio Rojas //
