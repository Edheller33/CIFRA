# CIFRA — Comunicación Soberana

Mensajería y llamadas de voz cifradas de extremo a extremo, sin número telefónico, sin correo, sin servidor propio. Tu identidad es un par de llaves que solo tú controlas.

🔗 **Prueba la app:** https://edheller33.github.io/CIFRA/

📖 **Manual de usuario:** [Leer en PDF](cifra_manual_de_usuario.pdf) — se abre directo en el navegador.

## ¿Qué protege?

El contenido de tus mensajes y llamadas viaja cifrado; solo tu contraparte puede leerlo. Los relays públicos usados para conectarse ven metadatos de enrutamiento, nunca el contenido.

## ¿Qué no cubre?

No protege un dispositivo ya comprometido, ni oculta que estás usando CIFRA frente a alguien con acceso físico al teléfono.

## Aviso técnico

La identidad y firma de mensajes (secp256k1/Schnorr) usan una implementación propia, verificada contra los vectores de prueba oficiales pero sin auditoría de terceros. El cifrado del contenido sí usa primitivas nativas del navegador (AES-256-GCM). Para uso cotidiano es razonable; para amenaza estatal de alto riesgo, ver la sección 8 del manual antes de depender de la app.

## Licencia

GPLv3 — ver [LICENSE](LICENSE). Cualquier versión modificada de CIFRA debe seguir siendo de código abierto.
