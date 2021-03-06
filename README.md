# La consulta del Dentista
Video descriptivo: https://www.youtube.com/watch?v=BNF6GiIbhbA

La Consulta del Dentista es un ejercicio de CRUD de la asignatura de Programación que maneja una pequeña consulta de varios dentistas. En ellas solo existe un administrador aparte del gestor de bases de datos, el cual gestiona y crea otros usuarios con menor privilegio (dentistas y no necesariamente dentistas), además de eliminarlos.

Este CRUD respeta fielmente la importancia que tiene la autenticación en una aplicación web, por lo que no usa "Magic Strings" ni deja acceder a modificar datos de la tabla "usuarios" a quien no sepa la contraseña del administrador, ni acceder a tablas a quien no sepa la contraseña de ninguna de las cuentas creadas (siempre que estas personas mantengan vigilado su ordenador en todo momento, pues la aplicación no está preparada para ataques "Evil Maiden" en todos sus casos). Tampoco se comprueba la integridad de los datos (si han sido modificados por quien se cree que han sido modificados), por lo que no es una aplicación web preparada para salir a producción, sino una prueba de concepto que cumple con los requisitos de un CRUD (Create, Read, Delete, Update) para todas las tablas.

El diseño está realizado con el framework Bootstrap 4 principalmente.

# Páginas

Estas incluyen un Login, una "landing page" para usuarios autentificados y una página por cada elemento del CRUD, una especializada a la tabla 'usuarios' y otra genérica, en está última no deberían haber problemas añadiendo nuevas tablas, debería adaptarse a ellas.

Login:
![Login](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/login.png)
Landing page:
![Front](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/Frontpage.png)
![Front2](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/FrontPage2.png)
Menus de Landing page:
![FrontMenu1](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/FrontPageMenu1.png)
![FrontMenu2](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/FrontPageMenu2.png)
![FrontMenu3](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/FrontPageMenu3.png)
Create:
![Add](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/AddMenu.png)
Create (Interactuando):
![Adding](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/AddingMenu.png)
![Added](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/Added.png)
Create especializado:
![Loggin](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/LoginPrompt.png)
![LoggingIn](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/LoggingMenu.png)
Create especializado (autentificado):
![Logged](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/LoggedInMenu.png)
![AddingUser](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/AddingUsuario.png)
Create especializado (autentificado y interactuado):
![AddedUser](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/AddedUsuario.png)
Update:
![Modify](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/ModifyMenu.png)
Update (Interactuando):
![Modifying](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/ModifyMenuModifying.png)
![Modified](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/ModifiedMenu.png)
Update especializado:
![Loggin](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/LoginPrompt.png)
![LoggingIn](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/LoggingMenu.png)
Update especializado (autentificado):
![ModMenu](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/ModifyUsuario.png)
![Modifing](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/ModifyingUsuario.png)
Update especializado (autentificado y interactuado):
![Modified](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/ModifiedUsuario.png)
Delete:
![Delete](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/DeleteMenu.png)
Delete (Interactuando):
![Deleting](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/DeletingMenu.png)
![Deleted](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/DeletedMenu.png)
Delete especializado:
![Loggin](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/LoginPrompt.png)
![LoggingIn](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/LoggingMenu.png)
Delete especializado (autentificado):
![DeleteMenu](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/ModifyingUsuario.png)
![Deletin](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/DeletingUsuario.png)
Delete especializado (autentificado y interactuado):
![DeletedUser](https://github.com/PabloLuisMolinaBlanes/LaConsultaDelDentista/blob/master/FotosCRUD/DeletedUsuario.png)
