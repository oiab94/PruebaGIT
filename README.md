# Tutorial GIT
- [Acerca de GIT](https://git-scm.com/book/es/v2/Inicio---Sobre-el-Control-de-Versiones-Acerca-del-Control-de-Versiones)
- [Configuración de GIT](https://git-scm.com/book/es/v2/Personalizaci%C3%B3n-de-Git-Configuraci%C3%B3n-de-Git)
- [Eliminar un commit](https://www.youtube.com/watch?v=h-xN14zPgsQ&list=PLTd5ehIj0goMCnj6V5NdzSIHBgrIXckGU&index=6)
- [Revertir un commit](https://www.youtube.com/watch?v=4SwaV29SpIc&list=PLTd5ehIj0goMCnj6V5NdzSIHBgrIXckGU&index=7) -> Utilizar mayormente este
- [Crear, modificar, eliminar branches](https://www.youtube.com/watch?v=j0U9jBmP3LM&list=PLTd5ehIj0goMCnj6V5NdzSIHBgrIXckGU&index=9)

# Comandos 

| Comandos  | Para que sirve |
|---------- |----------------|
| git diff  | Permite ver las diferencias entre dos conjuntos de archivos o commits |

| | DESHACER O ELIMINAR COMMITS|
| -- | ---------------- |
| git reset | Permite eliminar un commit de forma soft, es decir no borra las modificaciones |
| git reset --hard | Permite eliminar un commit de forma hard, es decir esto borra todas las modificaciones realizadas sin posibilidad de recuperar |
| git revert | Permite revertir un commit sin necesidad de borrar los commit anterior, esta operación es más segura que reset. |
| git revert --no-commit | Permite revertir varios commmits hasta que le demos la opcion de continue |