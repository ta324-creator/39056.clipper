# CLIPPER BARBER STUDIO — PROYECTO Y VISIÓN GENERAL

> Documento maestro para el desarrollo del sitio web.

## INFORMACIÓN DEL NEGOCIO
- Nombre: Clipper Barber Studio
- Dirección: Av. Delante 479 – Local 1, Cuauhtemoc, 22890, Ensenada, Baja California, México
- Teléfono: 646 534 3804
- Instagram: https://www.instagram.com/clipper_barberstudio
- Contacto actual: Teléfono y WhatsApp

## OBJETIVO
El sitio debe convertirse en la forma principal de reservar citas.

Flujo deseado:
Cliente entra → selecciona fecha → horario → servicio → nombre y teléfono → paga en línea → la cita se crea automáticamente en Google Calendar → recibe confirmación.

Actualmente el negocio administra todas las citas mediante Google Calendar y desea conservarlo como sistema principal.

## HORARIOS
Lunes a Sábado: 9:00 AM–7:00 PM
Domingo: 10:00 AM–5:00 PM

## PRECIOS
- Corte — $220 MXN
- Barba — $180 MXN
- Corte y Barba — $350 MXN
- Facial — $300 MXN
- Servicio Clipper — $580 MXN

Lema: 'Precisión • Estilo • Confianza'

## MENSAJE DE MARCA
No comunicar la barbería como un negocio nuevo o una mudanza. La percepción debe ser de un negocio establecido con un equipo consolidado y continuidad en la calidad.

## RESEÑAS
- 'La mejor barbería de Ensenada... excelente servicio.'
- 'Excelente recomendación para un corte de barba.'
- 'Cada uno de sus barberos han demostrado su habilidad...'

## CONTEXTO DEL CLIENTE
El sitio debe sentirse primero como una plataforma de reservas y después como un sitio informativo.
La mayoría de los usuarios ya decidió reservar.
La primera pregunta que debe responder el sitio es: '¿Cuándo puedo reservar?'

Se prefiere un calendario visible tipo caja como interacción principal (no scroll selector). En móvil puede adaptarse a un selector compacto.

## VISIÓN DEL SISTEMA
Google Calendar debe ser la única fuente de verdad.
El sitio nunca debe mantener un calendario separado.

Cada barbero administrará únicamente su propio Google Calendar.
El sitio consultará todos los calendarios y mostrará únicamente horarios realmente disponibles.
No permitir dobles reservas.

No crear cuentas de clientes.
No login.
No dashboard.

## PAGOS
Integrar Stripe.
Reserva → Pago exitoso → Crear evento en Google Calendar → Confirmación.

## ESCALABILIDAD
Diseñar la arquitectura para soportar páginas individuales de barberos en el futuro (/barbers/nombre), con portafolio, servicios, disponibilidad y reserva directa, además de permitir elegir un barbero específico o 'sin preferencia'.

## ENLACES
Instagram: https://www.instagram.com/clipper_barberstudio
Google: https://share.google/PzkHDY4pV1tRNR8oF
