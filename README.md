# Paquetes-RPM

# Paquete RPM

Los paquetes RPM (Red Hat Package Manager) son un formato de archivo utilizado en sistemas operativos Linux para distribuir software y sus dependencias. Fueron creados por Red Hat, pero son compatibles con varias distribuciones de Linux, como CentOS y Fedora.

## Contenido de un paquete RPM
Un paquete RPM contiene:
- Archivos binarios del software.
- Scripts de instalación/desinstalación.
- Información sobre las dependencias necesarias.
- Información de versión y metadatos.

La principal ventaja de los paquetes RPM es que facilitan la instalación, actualización y eliminación de software, manejando automáticamente las dependencias entre diferentes aplicaciones. Esto ayuda a mantener un sistema organizado y evita conflictos entre diferentes versiones de bibliotecas o programas.

---

# Rocky Linux

Rocky Linux es una distribución de Linux basada en Red Hat Enterprise Linux (RHEL) y se considera el sucesor no oficial de CentOS. Aquí tienes algunas de sus características más destacadas:

## Características de Rocky Linux

1. **Compatibilidad Binaria**: Rocky Linux es compatible a nivel binario con RHEL, lo que significa que los paquetes diseñados para RHEL también funcionan en Rocky Linux.
2. **Estabilidad y Fiabilidad**: Está diseñado para ser un sistema operativo estable y fiable, ideal para servidores y aplicaciones empresariales.
3. **Soporte a Largo Plazo**: Ofrece diez años de soporte con actualizaciones periódicas, proporcionado por la Rocky Enterprise Software Foundation (RESF).
4. **Licencia Gratuita**: Es una versión gratuita de RHEL, lo que lo hace accesible sin costo adicional.
5. **Repositorios**: Incluye varios repositorios base y aprobados por la comunidad para facilitar la instalación de software.
6. **Seguridad**: Aunque no incluye algunas funciones avanzadas de RHEL, como el parcheo en vivo del núcleo, sigue siendo una opción segura para muchas aplicaciones.
7. **Uso en HPC**: Es especialmente adecuado para aplicaciones de alto rendimiento (HPC) y servidores.

---

## Configuración de Repositorios en Rocky Linux

En Rocky Linux, los archivos de configuración de los repositorios se encuentran en el directorio `/etc/yum.repos.d/`. Cada archivo dentro de este directorio corresponde a un repositorio específico y tiene la extensión `.repo`.

Por ejemplo, un archivo típico de repositorio podría ser `rocky.repo` y su contenido incluiría información como la URL del repositorio, las opciones de habilitación y deshabilitación, y otras configuraciones relevantes.

Si deseas agregar o modificar repositorios en Rocky Linux, puedes editar estos archivos o agregar nuevos archivos `.repo` dentro del directorio `/etc/yum.repos.d/`.
