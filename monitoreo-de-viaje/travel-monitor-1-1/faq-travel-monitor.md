---
description: PREGUNTAS SOBRE LAS ALERTAS
---

# Alerta

## ¿Qué diferencia hay entre una alerta y una alerta especial?

**Alerta**: Una alerta es un correo electrónico sobre un incidente que tiene posibles efectos sobre los viajeros, los lugares o la actividad comercial. Las alertas están relacionadas con un viajero específico o la ubicación de una empresa. Para cada incidente que activa una alerta, el sistema envía varios correos electrónicos: uno está redactado para el viajero, y el otro para el gestor.

**Alerta especial**: En caso que haya una alerta especial, no se puede descartar que haya un viajero directamente afectado por un incidente de seguridad que pueda ser una amenaza para su vida y salud. La plataforma contacta directamente con los viajeros afectados por llamada telefónica para saber su estado. Además, el viajero recibe la información del incidente por correo electrónico, junto con pautas de comportamiento para reducir el riesgo en los alrededores del evento. Para cada incidente que activa una alerta especial, el sistema envía varios correos electrónicos: uno está redactado para el viajero, y el otro para el gestor y contiene actualizaciones de estado continuas.

## ¿Por qué el viajero A recibe una llamada de estado por alerta especial, mientras que el viajero B que está junto con él sólo recibe un correo electrónico de alerta?

Puede haber varias razones para una situación así, por ejemplo:

**Situación**: Suponiendo que los viajeros A y B estén juntos en una conferencia, pero su confianza de ubicación es distinta. Mientras que la plataforma sólo ha recibido los datos PNR con la llegada al aeropuerto del viajero A, el viajero B ha usado la función de seguimiento de calendario y ha añadido la ubicación exacta de la conferencia. Es por eso que la plataforma tiene datos de viaje más precisos para el viajero B que para el A, y de ahí que haya determinado un radio de incidente más grande para el viajero A. Mientras que el sistema puede descartar que el viajero B esté dentro del radio de impacto del incidente que activó la alerta, la información que posee sobre el viajero A no es tan precisa, y por esto, para saber si necesita ayuda, se activa la llamada de estado automatizada

Esta situación debería explicar que hay varios parámetros que determinan el radio del incidente. Algunos de los parámetros más importantes que definen la alerta y la alerta especial son el impacto del incidente, la categoría del incidente y la confianza de ubicación del viajero. Si no está seguro de su configuración o solamente siente curiosidad para saber cómo funciona la plataforma, puede comprobarlo y verlo en la sección llamada «vista previa del radio de incidente» en la configuración de las alertas del monitoreo de viaje.

## ¿Cómo puedo ver las alertas y las alertas especiales en el monitoreo de viaje?

Las alertas especiales son iconos con un marco rojo. Las alertas son iconos con un marco amarillo. También puede usar el filtro para encontrar una alerta o alerta especial específica.

## Tengo 200 viajeros en Shanghái. Si ocurre un incidente crítico de seguridad, ¿cuánto tardaría en saber el estado de mis viajeros?

En cuanto la plataforma detecta un incidente y el analista lo ha confirmado \(normalmente, la confirmación dura 1-2 minutos\), la plataforma llamará inmediatamente a sus viajeros. Si en la configuración de llamada ha indicado que sólo se llame UNA VEZ a sus viajeros, usted recibiría el estado final de los 200 viajeros en 1-2 minutos. No obstante, se recomienda intentar la llamada más de una vez, porque, en la mayoría de los casos, sus viajeros no responderán a la primera llamada.

{% hint style="info" %}
Para más información, consulte la sección de configuración de alertas.
{% endhint %}

