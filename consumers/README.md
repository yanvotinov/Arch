```plantuml
!include https://raw.githubusercontent.com/plantuml-stdlib/C4-PlantUML/master/C4_Container.puml
' Подключаем наши компоненты для работы 
!define consumers https://gitlab.com/-/ide/project/test15310820/microarch/edit/main/-/systemdesign/containers/consumers/ 

!include consumers/ADMINISTRATOR.puml

!include consumers/BUHGALTER.puml

!include consumers/PROGRAMMIST.puml

!include consumers/MANAGER.puml

!include consumers/USER.puml
```