# Política de Privacidad y Uso de Datos — TasaVzla

**Última actualización:** 6/11/2026  
**Versión:** 1.0.0  
**Aplicación:** TasaVzla  
**Plataformas:** Android (Expo / React Native)

## 1. Introducción

TasaVzla es una aplicación móvil que permite consultar la tasa oficial de cambio del Banco Central de Venezuela (BCV) entre el bolívar (VES) y el dólar (USD) o el euro (EUR), y realizar conversiones monetarias rápidas.

Esta política explica qué información recopilamos, cómo la usamos, compartimos y protegemos, y cuáles son tus derechos como usuario.

## 2. Responsable del tratamiento

TasaVzla es un proyecto independiente. Si tienes dudas sobre esta política, puedes contactarnos a través de los canales indicados al final de este documento.

## 3. Información que recopilamos

### 3.1 Datos que NO recopilamos
TasaVzla **no requiere registro**, ni solicita tu nombre, correo electrónico, número de teléfono, dirección ni ningún otro dato de identificación personal. No creamos cuentas de usuario.

### 3.2 Datos técnicos y de uso (anónimos)
Para que la aplicación funcione, podemos recopilar automáticamente:
- **Información del dispositivo:** modelo, sistema operativo, versión de la app y identificadores anónimos del dispositivo (vía `expo-device` y `expo-constants`), únicamente para fines de compatibilidad y mejora del rendimiento.
- **Datos de conexión:** dirección IP anónima y datos de red necesarios para comunicarse con la API del BCV y obtener las tasas de cambio.
- **Preferencias dentro de la app:** moneda seleccionada (USD o EUR), última tasa consultada y configuración local, almacenada exclusivamente en tu dispositivo.

### 3.3 Datos proporcionados voluntariamente por el usuario
- **Portapapeles:** cuando usas la función "Copiar", la aplicación lee y escribe temporalmente en el portapapeles de tu dispositivo (vía `expo-clipboard`). No almacenamos este contenido en servidores propios.
- **Compartir:** si eliges compartir la tasa o un resultado de conversión (vía `expo-sharing`), la información se envía directamente a la aplicación de terceros que elijas (WhatsApp, redes sociales, etc.). TasaVzla no interviene en esa transmisión.

## 4. Cómo usamos la información

Usamos los datos únicamente para:
- Mostrarte la tasa oficial del BCV actualizada.
- Ejecutar la calculadora de conversión entre VES, USD y EUR.
- Guardar en caché local (en tu dispositivo) las tasas consultadas para que la app funcione más rápido y pueda usarse parcialmente sin conexión.
- Mejorar la estabilidad y el rendimiento de la aplicación.

No usamos tus datos para publicidad personalizada, ni los vendemos a terceros.

## 5. Almacenamiento y seguridad

- **Almacenamiento local:** Los datos de caché y preferencias se guardan en el almacenamiento local de tu dispositivo (vía `@react-native-async-storage/async-storage`). No se envían a nuestros servidores.
- **Servidores propios:** TasaVzla no opera servidores que almacenen datos personales de usuarios.
- **Seguridad:** Nos esforzamos por proteger la información, pero ninguna transmisión por Internet es totalmente segura. No podemos garantizar la seguridad absoluta de los datos transmitidos.

## 6. Compartición de información

TasaVzla **no comparte, vende ni alquila** tu información personal a terceros, porque no recopilamos datos personales identificables.

Los únicos destinos de información son:
- **El Banco Central de Venezuela (BCV):** para obtener las tasas oficiales. Ese organismo tiene sus propias políticas de privacidad.
- **Aplicaciones de terceros:** solo si tú decides compartir contenido desde la app (por ejemplo, por WhatsApp o correo). En ese caso, rigen las políticas de esas aplicaciones.

## 7. Derechos del usuario

Dado que no recopilamos datos personales identificables, no tenemos forma de vincular información contigo de forma individual. No obstante, tú puedes:

- **Eliminar datos locales:** desinstalando la aplicación se borra el caché y las preferencias guardadas en tu dispositivo.
- **Elegir no compartir:** no estás obligado a usar la función de compartir ni copiar al portapapeles.
- **Contactarnos:** si tienes dudas sobre esta política, escríbenos al correo indicado al final.

## 8. Enlaces y servicios de terceros

La aplicación puede interactuar con:
- API del Banco Central de Venezuela (BCV).
- Servicios de sistema de Expo y React Native (notificaciones, dispositivo, portapapeles, compartir).

Cada uno de estos servicios tiene sus propias políticas de privacidad. Te recomendamos revisarlas si usas esas funciones.

## 9. Menores de edad

TasaVzla no está dirigida a menores de 13 años y no recopila intencionalmente información de menores. Si eres padre o tutor y crees que tu hijo nos ha proporcionado datos personales, contáctanos.

## 10. Cambios a esta política

Podemos actualizar esta política de privacidad de vez en cuando. La versión más reciente estará siempre disponible dentro de la aplicación o en nuestra landing. Te recomendamos revisarla periódicamente.

## 11. Contacto

Si tienes preguntas, inquietudes o solicitudes sobre esta política de privacidad, puedes escribirnos a:

**appykz.dev@gmail.com**  
**TasaVzla — Soporte**
