```plantuml
!include https://raw.githubusercontent.com/plantuml-stdlib/C4-PlantUML/master/C4_Container.puml
' Подключаем наши компоненты для работы 
!define servers https://gitlab.com/-/ide/project/test15310820/microarch/edit/main/-/systemdesign/containers/servers/ 

!include servers/DBS01.puml

!include servers/DBS03.puml

!include servers/DBS05.puml

!include servers/DBS06.puml

!include servers/ERP01.puml

!include servers/ERP02.puml

!include servers/SQL07.puml
```