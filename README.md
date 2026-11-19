# Votaciones Jóvenes que Inspiran

**Quinta Edición de la Gala de la Juventud · Villa Rica, Cauca**

Plataforma web de votación pública de los premios **Jóvenes que Inspiran**, desarrollada para el **Consejo Municipal de Juventud (CMJ) de Villa Rica, Cauca**.

**Página:** https://cmjvillarica01.github.io/votacion/

---

## ¿Qué es?

Una página web para que la comunidad elija a los jóvenes destacados de cada categoría de los premios. Cada persona inicia sesión con su cuenta de Google y puede votar **una sola vez por categoría**, desde el celular o el computador.

**Periodo de votación:** del 17 al 20 de noviembre de 2026 (hora de Colombia), con cuenta regresiva en la página.

## Características

- **Un voto por cuenta de Google en cada categoría**, con confirmación antes de votar.
- **Voto en blanco** en cada categoría.
- **Cuenta regresiva** de apertura y cierre. El horario lo controla el servidor, no el dispositivo del votante.
- **Fotos de los nominados**, con vista ampliada al tocarlas.
- **Conteo de votos en tiempo real**, con barras, podio de los tres primeros por categoría e indicador de quién va a la cabeza. Se puede ocultar mientras la votación está abierta.
- **Progreso personal:** "Has votado en X de N categorías".
- **Buscador** de nominados y filtro por categoría.
- **Compartir** por WhatsApp o copiando el enlace.
- **Diseño adaptado a celulares**, con los colores institucionales del CMJ.
- Animaciones y confeti al votar.

## Cómo votar

1. Abre el enlace de la página.
2. Pulsa **Iniciar sesión con Google** y elige tu cuenta.
3. Escoge a tu nominado en cada categoría y pulsa **Votar**.
4. Confirma tu voto. **No se puede cambiar.**

## Cómo funciona

La página está hecha en HTML, CSS y JavaScript, y se aloja en GitHub Pages. Se conecta a un servicio de Google que recibe y registra los votos. Todo el proyecto usa servicios gratuitos.

## Seguridad

La validación de los votos se realiza en el servidor y cada persona debe iniciar sesión con una cuenta de Google. Las claves privadas no forman parte de este repositorio.

## Estructura del repositorio

```
votacion/
├── index.html   # Página de votación
└── README.md    # Este archivo
```



## Administración

Los nominados y sus fotos se gestionan desde un archivo privado del Consejo Municipal de Juventud. Los cambios se ven en la página sin necesidad de volver a publicarla.

## Privacidad

La página usa el correo de la cuenta de Google únicamente para verificar que cada persona vote una sola vez por categoría. Los datos se guardan en un Google Sheet privado y no se comparten con terceros.

## Créditos

Desarrollado para el **Consejo Municipal de Juventud de Villa Rica, Cauca**.

Quinta Edición de la Gala de la Juventud · *Jóvenes que Inspiran*.
