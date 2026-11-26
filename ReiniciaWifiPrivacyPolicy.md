# ReiniciaWifi
Effective Date: November 25th 2026

*[Versión en español más abajo](#política-de-privacidad-en-español)*

This Privacy Policy applies to the ReiniciaWifi Android app (referred to as “we,” “us,” or “our”). ReiniciaWifi restarts your own modem or router from your phone.

## Information that stays on your phone
- **Modem settings:** the Wi-Fi name, modem model, IP address, username and password you enter. They are stored encrypted on your phone, with a key that cannot leave it, and are only sent to your own modem on your local network to sign in and restart it. They are never sent to us or to anyone else, and they are excluded from phone backups.
- **Restart history:** when and on which network you last restarted each modem. It is stored encrypted on your phone only.
- **Scheduled restart:** the time and days you choose, the saved network it applies to, whether each scheduled restart worked, and a count of the restarts you have made with the app. The schedule is stored encrypted; all of it stays on your phone only.
- **Restart logs:** a short record of your latest manual and scheduled restarts (when, the result, your modem's model and local address, and whether your phone allowed what a scheduled restart needs). It stays on your phone unless you attach it to a help message (see below).
- **Plan and trial:** the date your free trial started, which saved network you keep in the base version, and whether Google Play confirmed a Premium subscription on this phone and when it was last checked. The trial's start date and, if you subscribe, the subscription check also go to our server (see **Free trial record** and **Premium subscription check** below). The subscription's end date and whether it renews, which our server tells the app, are also kept on your phone.
- **Unfinished modem reports:** if you send a modem report without the restart step (see below), the app remembers that network's Wi-Fi name, or its modem's address if Android hides the name, so it can offer to finish the report. It stays on your phone only.
- **Location:** Android only shares the name of the Wi-Fi network you are connected to with apps that have precise location permission. We use that permission only to read the Wi-Fi name and recognize your saved networks. We never read, save or send your location.

You can delete all of this at any time with **Erase all data** in the app, or by uninstalling it.

## Information we collect
We receive information when you choose to send it: a message from the **Help** screen (optionally with your restart logs), or a modem report from the **Config** screen. The only things the app sends on its own are the free trial record and, if you have a Premium subscription, the subscription check described below.

### Help messages
A help message includes:
- The text you write.
- Your email address, only if you enter one so we can reply.
- Your phone's support code: a short code derived from Android's ID for this app. It cannot be turned back into that ID and does not identify you personally.
- Technical details about the app and your phone: the app version, your phone's maker and model, the maker's version of Android (for example MIUI or One UI), the Android version, the app's language and your phone's language, how the app was installed (for example from Google Play), which of the app's language, screen and processor packages are installed, and what Google Play last answered about the Premium plans (a result code, such as OK or SERVICE_UNAVAILABLE, and how many plans and active subscriptions it listed). They help us find problems specific to a phone, an installation or a store account, and contain nothing that identifies you.

We use this information only to answer you and fix problems with the app. Help messages are sent over an encrypted connection (HTTPS) to a private channel on Discord that only our support team can read. Discord acts as our service provider; see [Discord's Privacy Policy](https://discord.com/privacy). We do not sell or share this information with anyone else, and we do not use it for advertising.

We keep help messages only as long as we need them to help you. To have your messages deleted, write to us at the address below and include the support code shown on the Help screen.

### Modem reports
When the app finds a modem it can't restart yet, the **Config** screen offers to send us a report so we can add that model. Nothing is sent until you review it and tap **Send**. A report includes:
- **Your modem's own web page and the files it loads**, read from its address on your local network without signing in, and the modem's address and server name.
- **If you choose to sign in and restart your modem on its page inside the app:** what that page sends to your modem and what your modem answers, including the pages you open there. This shows us how your modem signs in and restarts. It includes the modem's admin username and its temporary session codes, which stop working when the modem restarts.
- Your phone's support code and the same technical details as a help message.

Your modem's pages can show information about your network, such as the Wi-Fi name, your internet connection's addresses (IP) and the names of the devices connected to it. Before a report leaves your phone, the app erases:
- the passwords you type on your modem's page, also when the page sends them encoded or scrambled;
- serial numbers;
- the part of each device's hardware (MAC) address that identifies the device, keeping only the part that names its maker.

We use modem reports only to make the app work with that modem model. They are sent and stored the same way as help messages, in the same private Discord channel, and we keep them only as long as we need them for that. To have a report deleted, write to us with your support code.

### Restart failure reports
If a restart fails in a way you can't fix yourself (for example, your modem doesn't accept it), the app shows a **Report the problem** button. Nothing is sent unless you tap it. A report includes:
- Your modem's brand and model, and the result of the restart.
- The list of requests the app made to your modem: the page address (path) and the modem's response code, and the first 150 characters of the reply for the restart and for errors.
- Your phone's support code and the same technical details as a help message.

Before it leaves your phone, the app erases your modem password from it. It does not include your Wi-Fi name, your modem's address or your username. We use these reports only to fix the app for that modem. They are sent and stored the same way as help messages, in the same private Discord channel, and we keep them only as long as we need them for that. To have a report deleted, write to us with your support code.

### Restart logs
On the **Help** screen you can tick **Attach error logs: scheduled restart** and/or **Attach error logs: manual restart**. Nothing is attached unless you tick it and send the message. The attached text file includes:
- **Scheduled restarts** (your latest 20): the time each was set for and when it really ran, the result, your modem's model and local address, whether your phone was connected to Wi-Fi, and whether the battery, notification and exact alarm permissions are allowed. It also includes your current schedule (time and days) and when it runs next.
- **Manual restarts** (your latest 10): when, the result, your modem's model and local address.
- For both, the list of requests the app made to your modem: the page address (path) and the modem's response code, and the first 150 characters of the reply for the restart and for errors.
- Your phone's time zone and whether its date and time are set automatically, because a wrong date or time can stop a scheduled restart from running.
- Your phone's support code and the same technical details as a help message.

Before it leaves your phone, the app erases your modem password from it. It does not include your Wi-Fi name. We use restart logs only to find out why a restart did not work and fix the app. They are sent and stored the same way as help messages, in the same private Discord channel, and we keep them only as long as we need them for that. To have them deleted, write to us with your support code.

### Free trial record
Every time the app opens, until our server has answered once, it asks the server (over an encrypted HTTPS connection) when this phone's free trial started, so that reinstalling the app doesn't start the trial over. This happens by itself, because it is how the free trial works; it can't be turned off, except by uninstalling the app. It sends:
- A one-way code made from Android's ID for this app. It is not the support code, it can't be turned back into that ID and it does not identify you.
- The date the free trial started on your phone.

Our server makes that code one-way again with a secret that only it knows, and keeps the result together with the trial's start date and the moment it first saw it. This record is not linked to your name, your email, your support code or any message you send, so we can't tell who it belongs to and we can't look up one person's record. We use it only to remember the free trial, we don't share it with anyone and we don't use it for advertising. We keep it for as long as we offer the free trial. If your phone is reset to factory settings, Android gives it a new ID and the trial starts again. The server runs on Cloudflare, which acts as our service provider; see [Cloudflare's Privacy Policy](https://www.cloudflare.com/privacypolicy/).

### Premium subscription check
If you have an active Premium subscription, the app asks our server to confirm it, over an encrypted HTTPS connection. It does so when the app opens, at most once a day. It sends:
- The purchase token: an identifier that Google Play gives to your purchase. It is not your name, your email or any payment detail.
- The same one-way device code as the free trial record.
- Your phone's model, for example "Pixel 7".

Our server uses the purchase token only to ask Google Play whether the subscription is active, and answers the app with a signed licence. A subscription can be used on up to 3 phones, so for each subscription the server keeps a one-way code of the purchase token (made with the same secret as the trial record) and, for each phone using it, that phone's one-way device code, its model, and when it first and last asked. If a fourth phone asks, the app shows the models and last use of the other three, so the person can free a place; a phone's place is also given back automatically after 45 days without use. We never receive your name, email, card or other payment details: Google handles them. We use this information only to check the subscription and apply the 3-phone limit, we don't share it with anyone and we don't use it for advertising. We keep it while the subscription is in use. These records are not linked to your name, your email, your support code or any message you send, so we can't look up one person's records. The server runs on Cloudflare, which acts as our service provider, and it asks Google Play, whose [Privacy Policy](https://policies.google.com/privacy) applies to what Google handles.

## Purchases
The Premium subscription is bought and paid for through Google Play. Google, not us, handles your payment details and your purchase, and we never receive your name, email, card or other payment information from it. The app asks Google Play, on your phone, whether you have an active subscription, and then asks our server to confirm it (see **Premium subscription check**). Google's [Privacy Policy](https://policies.google.com/privacy) applies to what it collects.

## What we do not do
- We do not use accounts, ads, analytics or tracking tools.
- We do not collect your location, contacts, files or browsing activity. The only web pages a modem report includes are your modem's own, opened inside the app.

## Children’s Privacy
ReiniciaWifi is not directed to children under 13, and we do not knowingly collect information from them. If you believe a child has sent us a help message, please contact us and we will delete it.

## Changes to This Policy
We may update this Privacy Policy from time to time. If any changes are made, the new policy will be posted on this page with the updated effective date.

## Contact
If you have any questions or concerns about this Privacy Policy, or want your help messages, restart logs or modem reports deleted, contact us at:
[soporte@heroiccharly.com](mailto:soporte@heroiccharly.com)

---

# Política de privacidad (en español)
Fecha de entrada en vigor: 25 de noviembre de 2026

Esta Política de privacidad se aplica a la app para Android ReiniciaWifi (“nosotros”). ReiniciaWifi reinicia tu propio módem o router desde tu teléfono.

## Información que se queda en tu teléfono
- **Configuración del módem:** el nombre del Wi-Fi, el modelo del módem, la dirección IP, el usuario y la contraseña que escribes. Se guardan cifrados en tu teléfono, con una clave que no puede salir de él, y solo se envían a tu propio módem en tu red local para iniciar sesión y reiniciarlo. Nunca se nos envían a nosotros ni a nadie más, y no se incluyen en las copias de seguridad del teléfono.
- **Historial de reinicios:** cuándo y en qué red reiniciaste por última vez cada módem. Se guarda cifrado solo en tu teléfono.
- **Reinicio programado:** la hora y los días que eliges, la red guardada a la que aplica, si cada reinicio programado funcionó y la cuenta de reinicios que has hecho con la app. La programación se guarda cifrada; todo se queda solo en tu teléfono.
- **Registros de reinicio:** un breve registro de tus últimos reinicios manuales y programados (cuándo, el resultado, el modelo y la dirección local de tu módem, y si tu teléfono permitía lo que necesita un reinicio programado). Se queda en tu teléfono, salvo que lo adjuntes a un mensaje de ayuda (ver abajo).
- **Plan y prueba:** la fecha en que empezó tu prueba gratis, qué red guardada conservas en la versión base, y si Google Play confirmó en este teléfono una suscripción Premium y cuándo se revisó por última vez. La fecha de inicio de la prueba y, si te suscribes, la revisión de la suscripción también van a nuestro servidor (ver **Registro de la prueba gratis** y **Revisión de la suscripción Premium** abajo). La fecha en que termina la suscripción y si se renueva, que nuestro servidor le dice a la app, también se guardan en tu teléfono.
- **Reportes de módem a medias:** si envías un reporte de módem sin el paso del reinicio (ver abajo), la app recuerda el nombre del Wi-Fi de esa red, o la dirección de su módem si Android oculta el nombre, para ofrecerte terminar el reporte. Se queda solo en tu teléfono.
- **Ubicación:** Android solo comparte el nombre de la red Wi-Fi a la que estás conectado con apps que tienen permiso de ubicación precisa. Usamos ese permiso solo para leer el nombre del Wi-Fi y reconocer tus redes guardadas. Nunca leemos, guardamos ni enviamos tu ubicación.

Puedes borrar todo esto en cualquier momento con **Borrar todos los datos** en la app, o desinstalándola.

## Información que recopilamos
Recibimos información cuando decides enviarla: un mensaje desde la pantalla de **Ayuda** (opcionalmente con tus registros de reinicio), o un reporte de módem desde la pantalla de **Ajustes**. Lo único que la app envía por su cuenta es el registro de la prueba gratis y, si tienes una suscripción Premium, la revisión de la suscripción que se describen abajo.

### Mensajes de ayuda
Un mensaje de ayuda incluye:
- El texto que escribes.
- Tu correo electrónico, solo si lo escribes para que te respondamos.
- El código de soporte de tu teléfono: un código corto derivado del identificador de Android para esta app. No se puede convertir de vuelta en ese identificador y no te identifica personalmente.
- Datos técnicos de la app y de tu teléfono: la versión de la app, la marca y el modelo de tu teléfono, la versión de Android del fabricante (por ejemplo MIUI o One UI), la versión de Android, el idioma de la app y el de tu teléfono, cómo se instaló la app (por ejemplo desde Google Play), cuáles de los paquetes de idioma, pantalla y procesador de la app están instalados, y lo último que respondió Google Play sobre los planes Premium (un código de resultado, como OK o SERVICE_UNAVAILABLE, y cuántos planes y suscripciones activas listó). Nos ayudan a encontrar problemas propios de un teléfono, de una instalación o de una cuenta de la tienda, y no contienen nada que te identifique.

Usamos esta información solo para responderte y corregir problemas de la app. Los mensajes de ayuda se envían por una conexión cifrada (HTTPS) a un canal privado de Discord que solo nuestro equipo de soporte puede leer. Discord actúa como nuestro proveedor de servicio; consulta la [Política de privacidad de Discord](https://discord.com/privacy). No vendemos ni compartimos esta información con nadie más, ni la usamos para publicidad.

Conservamos los mensajes de ayuda solo el tiempo necesario para ayudarte. Para que borremos tus mensajes, escríbenos a la dirección de abajo e incluye el código de soporte que aparece en la pantalla de Ayuda.

### Reportes de módem
Cuando la app encuentra un módem que todavía no puede reiniciar, la pantalla de **Ajustes** te ofrece enviarnos un reporte para que agreguemos ese modelo. No se envía nada hasta que lo revisas y tocas **Enviar**. Un reporte incluye:
- **La página web de tu módem y los archivos que carga**, leídos desde su dirección en tu red local sin iniciar sesión, y la dirección y el nombre del servidor del módem.
- **Si decides entrar y reiniciar tu módem en su página dentro de la app:** lo que esa página le envía a tu módem y lo que tu módem responde, incluidas las páginas que abras ahí. Esto nos muestra cómo tu módem inicia sesión y se reinicia. Incluye el usuario de administrador del módem y sus códigos de sesión temporales, que dejan de funcionar cuando el módem se reinicia.
- El código de soporte de tu teléfono y los mismos datos técnicos que un mensaje de ayuda.

Las páginas de tu módem pueden mostrar información de tu red, como el nombre del Wi-Fi, las direcciones (IP) de tu conexión a internet y los nombres de los aparatos conectados. Antes de que un reporte salga de tu teléfono, la app borra:
- las contraseñas que escribes en la página de tu módem, también cuando la página las envía codificadas o cifradas;
- los números de serie;
- la parte de la dirección física (MAC) de cada aparato que lo identifica, dejando solo la parte que indica su fabricante.

Usamos los reportes de módem solo para que la app funcione con ese modelo de módem. Se envían y se guardan igual que los mensajes de ayuda, en el mismo canal privado de Discord, y los conservamos solo el tiempo necesario para eso. Para que borremos un reporte, escríbenos con tu código de soporte.

### Reportes de fallas al reiniciar
Si un reinicio falla de una forma que tú no puedes resolver (por ejemplo, tu módem no lo acepta), la app muestra un botón **Reportar el problema**. No se envía nada a menos que lo toques. Un reporte incluye:
- La marca y el modelo de tu módem, y el resultado del reinicio.
- La lista de peticiones que la app hizo a tu módem: la dirección de la página (ruta) y el código de respuesta del módem, y los primeros 150 caracteres de la respuesta del reinicio y de los errores.
- El código de soporte de tu teléfono y los mismos datos técnicos que un mensaje de ayuda.

Antes de salir de tu teléfono, la app borra de él la contraseña de tu módem. No incluye el nombre de tu Wi-Fi, la dirección de tu módem ni tu usuario. Usamos estos reportes solo para corregir la app con ese módem. Se envían y se guardan igual que los mensajes de ayuda, en el mismo canal privado de Discord, y los conservamos solo el tiempo necesario para eso. Para que borremos un reporte, escríbenos con tu código de soporte.

### Registros de reinicio
En la pantalla de **Ayuda** puedes marcar **Adjuntar logs de error: reinicio programado** y/o **Adjuntar logs de error: reinicio manual**. No se adjunta nada a menos que lo marques y envíes el mensaje. El archivo de texto adjunto incluye:
- **Reinicios programados** (tus últimos 20): la hora para la que estaba programado cada uno y cuándo corrió en realidad, el resultado, el modelo y la dirección local de tu módem, si tu teléfono estaba conectado al Wi-Fi, y si están permitidos los permisos de batería, notificaciones y alarmas exactas. También incluye tu programación actual (hora y días) y cuándo se ejecuta la próxima vez.
- **Reinicios manuales** (tus últimos 10): cuándo, el resultado, el modelo y la dirección local de tu módem.
- En ambos, la lista de peticiones que la app hizo a tu módem: la dirección de la página (ruta) y el código de respuesta del módem, y los primeros 150 caracteres de la respuesta del reinicio y de los errores.
- La zona horaria de tu teléfono y si su fecha y hora son automáticas, porque una fecha u hora incorrecta puede impedir que un reinicio programado se ejecute.
- El código de soporte de tu teléfono y los mismos datos técnicos que un mensaje de ayuda.

Antes de salir de tu teléfono, la app borra de él la contraseña de tu módem. No incluye el nombre de tu Wi-Fi. Usamos los registros de reinicio solo para averiguar por qué un reinicio no funcionó y corregir la app. Se envían y se guardan igual que los mensajes de ayuda, en el mismo canal privado de Discord, y los conservamos solo el tiempo necesario para eso. Para que los borremos, escríbenos con tu código de soporte.

### Registro de la prueba gratis
Cada vez que la app se abre, hasta que nuestro servidor responde una vez, le pregunta al servidor (por una conexión cifrada HTTPS) cuándo empezó la prueba gratis de este teléfono, para que reinstalar la app no la reinicie. Esto ocurre por sí solo, porque así funciona la prueba gratis; no se puede apagar, salvo desinstalando la app. Envía:
- Un código de un solo sentido hecho del identificador de Android para esta app. No es el código de soporte, no se puede convertir de vuelta en ese identificador y no te identifica.
- La fecha en que empezó la prueba gratis en tu teléfono.

Nuestro servidor vuelve a hacer ese código de un solo sentido con un secreto que solo él conoce, y guarda el resultado junto con la fecha de inicio de la prueba y el momento en que lo vio por primera vez. Este registro no está ligado a tu nombre, tu correo, tu código de soporte ni a ningún mensaje que envíes, así que no sabemos de quién es y no podemos buscar el registro de una persona. Lo usamos solo para recordar la prueba gratis, no lo compartimos con nadie ni lo usamos para publicidad. Lo conservamos mientras ofrezcamos la prueba gratis. Si tu teléfono se restablece de fábrica, Android le da un identificador nuevo y la prueba empieza otra vez. El servidor funciona en Cloudflare, que actúa como nuestro proveedor de servicio; consulta la [Política de privacidad de Cloudflare](https://www.cloudflare.com/privacypolicy/).

### Revisión de la suscripción Premium
Si tienes una suscripción Premium activa, la app le pide a nuestro servidor que la confirme, por una conexión cifrada HTTPS. Lo hace cuando la app se abre, como máximo una vez al día. Envía:
- El token de compra: un identificador que Google Play le da a tu compra. No es tu nombre, tu correo ni ningún dato de pago.
- El mismo código de un solo sentido del dispositivo que usa el registro de la prueba gratis.
- El modelo de tu teléfono, por ejemplo "Pixel 7".

Nuestro servidor usa el token de compra solo para preguntarle a Google Play si la suscripción está activa, y le responde a la app con una licencia firmada. Una suscripción se puede usar en hasta 3 teléfonos, así que por cada suscripción el servidor guarda un código de un solo sentido del token de compra (hecho con el mismo secreto que el registro de la prueba) y, por cada teléfono que la usa, su código de un solo sentido del dispositivo, su modelo y cuándo preguntó por primera y por última vez. Si un cuarto teléfono pregunta, la app muestra los modelos y el último uso de los otros tres, para que la persona libere un lugar; además, el lugar de un teléfono se libera solo después de 45 días sin uso. Nunca recibimos tu nombre, correo, tarjeta ni otros datos de pago: los maneja Google. Usamos esta información solo para revisar la suscripción y aplicar el límite de 3 teléfonos, no la compartimos con nadie ni la usamos para publicidad. La conservamos mientras la suscripción esté en uso. Estos registros no están ligados a tu nombre, tu correo, tu código de soporte ni a ningún mensaje que envíes, así que no podemos buscar los registros de una persona. El servidor funciona en Cloudflare, que actúa como nuestro proveedor de servicio, y le pregunta a Google Play, a cuyo tratamiento le aplica la [Política de privacidad de Google](https://policies.google.com/privacy).

## Compras
La suscripción Premium se compra y se paga a través de Google Play. Google, no nosotros, maneja tus datos de pago y tu compra, y nunca recibimos de ahí tu nombre, correo, tarjeta ni otros datos de pago. La app le pregunta a Google Play, en tu teléfono, si tienes una suscripción activa, y luego le pide a nuestro servidor que lo confirme (ver **Revisión de la suscripción Premium**). A lo que Google recopila le aplica la [Política de privacidad de Google](https://policies.google.com/privacy).

## Lo que no hacemos
- No usamos cuentas, anuncios, analíticas ni herramientas de rastreo.
- No recopilamos tu ubicación, contactos, archivos ni actividad de navegación. Las únicas páginas web que incluye un reporte de módem son las de tu propio módem, abiertas dentro de la app.

## Privacidad de los menores
ReiniciaWifi no está dirigida a menores de 13 años y no recopilamos a sabiendas información de ellos. Si crees que un menor nos envió un mensaje de ayuda, contáctanos y lo borraremos.

## Cambios a esta política
Podemos actualizar esta Política de privacidad. Si hay cambios, la nueva política se publicará en esta página con la fecha de entrada en vigor actualizada.

## Contacto
Si tienes preguntas sobre esta Política de privacidad, o quieres que borremos tus mensajes de ayuda, registros de reinicio o reportes de módem, escríbenos a:
[soporte@heroiccharly.com](mailto:soporte@heroiccharly.com)
