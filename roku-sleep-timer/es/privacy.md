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

- No tenemos servidores ni cuentas de usuario, y nunca recibimos tu información personal.
- Los datos de tu Roku y tu configuración se quedan en tu teléfono.
- La app muestra anuncios de Google AdMob. Google puede recopilar identificadores del dispositivo y datos de uso para mostrar y medir anuncios, como se describe abajo.
- La app usa Google Firebase Analytics y Crashlytics para entender cómo se usa la app y corregir fallos. Esos servicios pueden recopilar datos del dispositivo y de uso, como se describe abajo.

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


## Análisis e informes de fallos (Google Firebase)

La app usa Google Firebase Analytics y Firebase Crashlytics para ver qué funciones se usan, dónde falla la configuración y cuándo se cierra la app. Firebase puede recopilar y tratar:

- eventos de la app, como abrir pantallas, conectar un Roku, iniciar o cancelar un temporizador, y si el apagado funcionó;
- datos de fallos y diagnóstico, como stack traces, versión de la app y modelo del dispositivo;
- identificadores de dispositivo usados por Google Analytics for Firebase (por ejemplo el app-instance id).

Estos informes no incluyen el nombre, la IP ni el número de serie de tu Roku. Los usamos solo para mejorar la app y corregir errores. Más información en la [Política de Privacidad de Google](https://policies.google.com/privacy?hl=es) y en la [información de privacidad de Firebase](https://firebase.google.com/support/privacy?hl=es).

## Notificaciones

En iOS, la app puede programar una notificación local para recordarte cuándo termina un temporizador. Se crea en el propio teléfono y no pasa por ningún servidor.

## Lo que no hacemos

- No vendemos tu información personal.
- No recopilamos contactos, fotos, ubicación precisa ni archivos.
- No vendemos datos de análisis. Los informes de uso y fallos van solo a Google Firebase para los fines anteriores.

## Menores

La app no está dirigida a menores de 13 años y no recopilamos su información de forma intencionada.

## Tus derechos

Según dónde vivas (por ejemplo, por la LGPD de Brasil, el RGPD de la Unión Europea o la CCPA de California), puedes tener derecho a acceder, corregir o eliminar datos personales y a oponerte a su tratamiento. No guardamos datos personales sobre ti en servidores propios. Para los datos que Google trata para anuncios, análisis o informes de fallos, usa los controles anteriores o las [herramientas de privacidad de Google](https://myaccount.google.com/data-and-privacy?hl=es).

## Cambios

Si esta política cambia, actualizaremos la fecha de vigencia anterior y publicaremos la nueva versión en esta página.

## Contacto

{% if site.contact_email != "" %}Escribe a [{{ site.contact_email }}](mailto:{{ site.contact_email }}) o abre{% else %}Abre{% endif %} un issue en [{{ site.issues_url }}]({{ site.issues_url }}).
