```plantuml
!include https://raw.githubusercontent.com/plantuml-stdlib/C4-PlantUML/master/C4_Container.puml
' Подключаем наши компоненты для работы 
!define systems https://gitlab.com/-/ide/project/test15310820/microarch/edit/main/-/systemdesign/containers/systems/ 

!include systems/AIKO.puml

!include systems/BUH.puml

!include systems/DOCMANAGER.puml

!include systems/ERP24.puml

!include systems/ERP25.puml

!include systems/HRM.puml

!include systems/HRMBIT.puml

!include systems/REDIRECT.puml
```