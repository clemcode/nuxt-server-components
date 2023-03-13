# nuxt-server-components

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/nuxt-starter-xqpqje)

[Server components](https://nuxt.com/docs/guide/directory-structure/components#server-components)

## Description

Sur la page `/`, le composant utilisant la librairie `date-fns` est uniquement rendu côté serveur. La librairie `date-fns` n'est donc pas chargée côté client.

Sur la page `/client`, le composant utilisé suit le comportement classique des composants Nuxt, et la librairie est donc importée côté client.
