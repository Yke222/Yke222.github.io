---
layout: default
lang: es
title: Política de privacidad
alternates:
  en: /roku-sleep-timer/en/privacy.html
  pt: /roku-sleep-timer/pt/privacy.html
  es: /roku-sleep-timer/es/privacy.html
---

# Política de privacidad

Vigente desde: {{ site.policy_effective_date }}

Esta política explica qué información trata la app Roku Sleep Timer ("la app") en Android e iOS. La app la desarrolla un desarrollador independiente ("nosotros") y no está afiliada a Roku, Inc.

## Resumen

- No tenemos servidores ni cuentas de usuario.
- Los datos de tu Roku y tu configuración se quedan en tu teléfono.
- La app envía estadísticas de uso e informes de fallos a Google Firebase, vinculados solo a un identificador aleatorio, para corregir problemas y mejorar la app.
- La app muestra anuncios de Google AdMob. Google puede recopilar identificadores del dispositivo y datos de uso para mostrar y medir anuncios, como se describe abajo.

## Información guardada en tu teléfono

Para apagar tu Roku, la app guarda en tu teléfono:

- la dirección IP, el nombre, el modelo y el número de serie del Roku conectado;
- el idioma elegido;
- la hora de fin de un temporizador en curso.

Esta información se queda solo en tu teléfono. Se envía únicamente a tu Roku, por tu red local, y nunca a nosotros. Al tocar **Cambiar** en los ajustes de la app se olvida el Roku, y al desinstalar la app se borra todo.

## Comunicación con tu Roku

La app encuentra dispositivos Roku en tu red Wi-Fi y les envía comandos como "apagar" con el External Control Protocol de Roku (red local, puerto 8060). Este tráfico no sale de tu red local y, por definición de Roku, no está cifrado.

## Anuncios (Google AdMob)

La app muestra un anuncio a pantalla completa al abrirse. Los anuncios los proporciona Google AdMob, que puede recopilar y tratar:

- identificadores del dispositivo, como el ID de publicidad de Android o el identificador de publicidad de iOS (IDFA, solo si permites el seguimiento);
- tu dirección IP y la ubicación aproximada que se deriva de ella;
- información del dispositivo y de la app, como modelo, sistema operativo y versión de la app;
- interacciones con anuncios, como vistas y toques, además de datos de diagnóstico.

Google usa estos datos para mostrar anuncios, medir su rendimiento, limitar la frecuencia con que los ves y prevenir fraudes. Donde la ley lo exige (por ejemplo, en el Espacio Económico Europeo, el Reino Unido y Suiza), la app pide tu consentimiento antes de mostrar anuncios con la herramienta de consentimiento de Google. En esos casos, puedes cambiar tu elección en cualquier momento en la app en **Ajustes > Privacidad y anuncios**. En iOS, los anuncios solo se personalizan si permites el seguimiento. También puedes restablecer o eliminar tu ID de publicidad en la configuración del teléfono.

Más información en [Cómo utiliza Google la información de sitios web o aplicaciones que utilizan sus servicios](https://policies.google.com/technologies/partner-sites?hl=es) y en la [Política de Privacidad de Google](https://policies.google.com/privacy?hl=es).

## Estadísticas de uso e informes de fallos (Google Firebase)

La app usa Google Analytics para Firebase y Firebase Crashlytics, proporcionados por Google. Recopilan:

- cómo se usa la app, por ejemplo las pantallas abiertas, los temporizadores iniciados o cancelados, si la conexión con el Roku o el apagado funcionó y si se mostró el anuncio de apertura;
- información del dispositivo y de la app, como modelo, sistema operativo, idioma, versión de la app y un identificador aleatorio de esta instalación;
- informes de fallos con el estado técnico de la app en el momento del error;
- la ubicación aproximada (país o región) obtenida a partir de tu dirección IP.

Estas estadísticas nunca incluyen la dirección IP, el nombre ni el número de serie de tu Roku. Usamos estos datos solo para entender cómo se usa la app, corregir errores y mejorarla, y no los usamos para identificarte ni para mostrarte anuncios. Google conserva los datos de análisis hasta 14 meses y los informes de fallos hasta 90 días. Más información en [Privacidad y seguridad en Firebase](https://firebase.google.com/support/privacy?hl=es).

## Notificaciones

En iOS, la app puede programar una notificación local para recordarte cuándo termina un temporizador. Se crea en el propio teléfono y no pasa por ningún servidor.

## Lo que no hacemos

- No vendemos tu información personal.
- No recopilamos contactos, fotos, ubicación precisa ni archivos.
- No combinamos las estadísticas de uso con otros datos para identificarte.

## Menores

La app no está dirigida a menores de 13 años y no recopilamos su información de forma intencionada.

## Tus derechos

Según dónde vivas (por ejemplo, por la LGPD de Brasil, el RGPD de la Unión Europea o la CCPA de California), puedes tener derecho a acceder, corregir o eliminar datos personales y a oponerte a su tratamiento. No guardamos datos que te identifiquen: las estadísticas de uso solo se vinculan a un identificador aleatorio, que se borra al desinstalar la app. Para los datos que Google trata para anuncios, usa los controles anteriores o las [herramientas de privacidad de Google](https://myaccount.google.com/data-and-privacy?hl=es).

## Cambios

Si esta política cambia, actualizaremos la fecha de vigencia anterior y publicaremos la nueva versión en esta página.

## Contacto

{% if site.contact_email != "" %}Escribe a [{{ site.contact_email }}](mailto:{{ site.contact_email }}) o abre{% else %}Abre{% endif %} un issue en [{{ site.issues_url }}]({{ site.issues_url }}).
