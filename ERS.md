# Especificación de Requerimientos de Software (ERS)
**Proyecto:** App de Mensajería Instantánea | **Estándar:** IEEE 830-1998
**Autor:** Kevin Orellana

## 1. Introdución
El presente documento define los requerimientos para el desarrollo de la aplicación.

## 2. Glosario de Términos
* **Cifrado punto a punto: ** Método de seguridad que evita la lectura de mensajes por terceros.
* **Notificación Push:** Mensaje de alerta enviado al dispositivo del usuario.

## 3. Requerimientos Funcionales (EL QUÉ)
* **RF01:** El sistema debe permitir registrar usuarios mediante número telefónico.
* **RF02:** El sistema debe permitir enviar mensajes de texto en chats individuales.
* **RF03:** El sistema debe permitir eliminar mensajes previamente enviados.
* **RF04:** El sistema debe permitir editar los mensajes enviados.
* **RF05:** El sistema debe permitir reenviar mensajes a diferentes chats.
* **RF06:** El sistema debe tener un limite de 100 caracteres por mensaje.

## 4. Requerimientos No funcionales (EL CÓMO)
* **RNF01: (Seguridad):** Los mensajes deben almacenarse encriptados en la base de datos.
* **RNF02: (Rendimiento):** El tiempo de envio de mensajes debe ser menor a 2 segundos.
* **RNF03: (Disponibilidad)**: La App debe estar funcionando el 99.9% durante el año.
* **RNF04: (Compatibilidad):** La App debe ser compatible para dispositivos Android que tengan android 10 en adelante.


## 5. Requerimiento de Dominio
* **RD01:** El servicio web debe configurarse bajo la extension de dominio '.ar.'

