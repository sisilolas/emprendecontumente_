# Emprende con Tu Mente - Landing

Web estática de una sola página. Todo el contenido está en `index.html`.

## 1. Cambiar datos importantes (sin tocar el diseño)
Abre `index.html` y busca el bloque `CONFIG` al inicio del `<script>`:
- `whatsapp`: número sin el signo +  (ej: 56963070425)
- `paymentLink`: link de pago (Mercado Pago, Flow, Stripe). Mientras diga REEMPLAZAR, el botón abre WhatsApp.
- `calendarLink`: link de Calendly o Cal.com (opcional).

## 2. Editar textos
Los textos están escritos directamente en el HTML. Busca la frase que quieres cambiar (Ctrl+F) y reemplázala.

## 3. Publicar en Vercel (gratis)
1. Crea una cuenta gratis en github.com y un repositorio nuevo, por ejemplo `emprende-con-tu-mente`.
2. Sube estos archivos (`index.html` y `vercel.json`). En GitHub puedes arrastrarlos a la página del repositorio y pulsar "Commit changes".
3. Entra a vercel.com, inicia sesión con GitHub, pulsa "Add New > Project", elige el repositorio y pulsa "Deploy". No hace falta configurar nada.
4. Vercel te dará un link público (ej: emprende-con-tu-mente.vercel.app).

## 4. Editar después
- Opción fácil: en GitHub, abre `index.html`, pulsa el ícono del lápiz, edita y pulsa "Commit changes". Vercel se actualiza solo en 1 minuto.
- Para dominio propio (ej: emprendecontumente.cl): en Vercel, ve a Settings > Domains y sigue las instrucciones.
