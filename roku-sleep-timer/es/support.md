---
layout: default
lang: es
title: Soporte
alternates:
  en: /roku-sleep-timer/en/support.html
  pt: /roku-sleep-timer/pt/support.html
  es: /roku-sleep-timer/es/support.html
---

# Soporte

## Primeros pasos

1. Conecta el teléfono a la misma red Wi-Fi que el Roku.
2. En el Roku, abre **Configuración > Sistema > Configuración avanzada del sistema > Control por apps móviles** y ajusta **Acceso a la red** en **Permisivo**.
3. Abre la app y elige tu Roku en la lista o escribe su IP (en el Roku: **Configuración > Red > Acerca de**).
4. Elige una duración y toca **Iniciar temporizador**. Después mira YouTube o cualquier otra app en la TV.

No hace falta el modo desarrollador del Roku.

## Preguntas frecuentes

**La app dice que el Roku rechazó el comando.** El Acceso a la red en **Control por apps móviles** está en **Limitado** o **Desactivado**. Cámbialo a **Permisivo**.

**Mi Roku no aparece en la lista.** Algunos routers y iPhones bloquean el descubrimiento de dispositivos. Escribe la IP del Roku.

**El Roku se apagó, pero la TV siguió encendida.** Activa HDMI-CEC en la TV. Cada marca lo llama distinto, por ejemplo Anynet+ (Samsung), SimpLink (LG), Bravia Sync (Sony) o CEC (otras).

**En iPhone el temporizador no apagó el Roku.** iOS no deja que las apps envíen comandos en segundo plano. Deja la app abierta: mantiene la pantalla encendida mientras corre el temporizador. Si sales, una notificación te recuerda volver.

**En Android el temporizador no se activó.** Revisa que la app tenga permiso de **Alarmas y recordatorios** en los ajustes del sistema y que la optimización de batería no la restrinja.

## Contacto

{% if site.contact_email != "" %}Escribe a [{{ site.contact_email }}](mailto:{{ site.contact_email }}) o abre{% else %}Abre{% endif %} un issue en [{{ site.issues_url }}]({{ site.issues_url }}).

[Política de privacidad](privacy.html) · [Términos de uso](terms.html)
