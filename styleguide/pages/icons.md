Иконки хранятся отдельно в пакете `@vkontakte/icons`. Вот [тут](https://vkcom.github.io/icons/) есть документация 
о том, как их использовать. Сама библиотека использует `@vkontakte/icons`, вынося зависимости оттуда в webpack 
`externals`. 

Так же следует отметить, что иконки находятся в `peerDependencies` библиотеки. Это означает, что в вашем
проекте пакет нужно явно указать в `package.json`.