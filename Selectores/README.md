### Ejercicio de Selectores Prioridades:
_ _ _

>¿Cuál es el peso de los siguientes selectores de CSS? ¿Cuál pesa más? ¿Cuál pesa menos?
(Ordenados de más a menos)

`!important > #titulo > .container href > .container > h1 > *`

- **.container** contiene una clase, por lo tanto tiene prioridad media.

- **.container href** contiene una clase y un elemento, por lo tanto tiene prioridad media. Al contener una clase y un elemento tiene más prioridad que una clase solo y menos prioridad que un IDs.

- **h1** contiene un elemento, por lo tanto tiene prioridad baja.

- **#titulo** contiene un IDs, por lo tanto tiene prioridad alta.

- El **!important** es una excepción, tiene la prioridad más alta.

- El **asterisco** no tiene ningúna prioridad.
