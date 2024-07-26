---
permalink: /beta
nav_order: 1
---

# Versión de prueba

¡Letro ya está disponible para pruebas beta en Android! 🎉

<span class="fs-7 d-block text-center mx-auto">
[Instalar Letro](https://play.google.com/store/apps/details?id=tech.relaycorp.letro){: .btn }
</span>

## Consideraciones importantes

Debes estar al tanto de los riesgos de usar Letro en este momento:

- **Es muy probable que haya fallos**. Estamos seguros de que Letro es lo suficientemente estable para el uso diario, pero estamos seguros de que descubrirás problemas que el equipo aún no había encontrado.
- **Puedes perder tus datos en cualquier momento**, ya sea debido a un error o a un cambio importante en una versión más nueva de la aplicación. Si compartes algo importante, haz una copia fuera de Letro.
- **Hemos solicitado una auditoría de seguridad independiente a un equipo de confianza**. Hemos tomado todas las medidas razonables para asegurar que Letro sea seguro, pero no deberías confiar solo en nuestra palabra hasta que se publique el informe. Por lo tanto, por favor no uses Letro para nada sensible todavía.

## Limitaciones importantes

A excepción de algunos metadatos mínimos y no delicados almacenados en [nuestro servidor](https://docs.relaycorp.tech/letro-server/),
todos tus datos se almacenan en tus propios dispositivos.
Esto significa que:

- Los identificadores de cuentas gratuitas bajo nombres de dominio gestionados por Relaycorp (por ejemplo, `applepie.rocks`, `cuppa.fans`) no se pueden migrar a otros dispositivos ni restaurar si desinstalas Letro. Esta limitación no se aplica a ningún nombre de dominio bajo tu control.
- _No deberías_ usar el mismo identificador en dispositivos distintos. Si haces esto, cada dispositivo tendría un conjunto diferente de contactos, y no podrás comunicarte con un contacto que tengas en otro teléfono, incluso si tu identificación es la misma.
- Las conversaciones y los contactos no se pueden migrar a otros teléfonos ni restaurar si vuelves a instalar Letro.

Tenemos planes para abordar estas limitaciones de una manera que respete la privacidad.

## Problemas conocidos

### Retrasos y duplicados de datos entrantes

Hay dos fallos independientes en Awala que afectan a Letro y a cualquier otra aplicación compatible **cuando Internet está disponible**:

- Los datos entrantes pueden experimentar retrasos cuando ni Awala ni Letro están en ejecución. Como solución temporal, cuando esperes datos entrantes, mantén Letro abierto.
- Los mensajes entrantes pueden recibirse dos veces. Esto puede manifestarse como una respuesta recibida dos veces, o tu nombre de usuario elegido teniendo un sufijo aleatorio añadido, por ejemplo. No hay una solución temporal para esto.

Estamos trabajando en solucionar estos problemas en Awala.

### Reinstalar Awala requiere reinstalar Letro

Si reinstalas Awala o borras sus datos, también deberás reinstalar Letro o borrar sus datos. Esta es una limitación en Awala.

## Ayuda y comentarios

Para reportar problemas, obtener ayuda o proporcionar comentarios, por favor usa [el subreddit r/Letro](https://www.reddit.com/r/Letro/).
