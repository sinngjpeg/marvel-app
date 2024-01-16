


# Marvel Heroes 

Aplicativo desenvolvido para desenvolver habilidades tecnicas. 

---

#### O que foi utilizado no projeto:

 -  [Detekt](https://detekt.dev/docs/gettingstarted/gradle) 
 - SOLID
 - Clean Architecture
 - [App Android Architecture](https://developer.android.com/topic/architecture?hl=pt-br) 
 - Navigation
 - [DI](https://developer.android.com/training/dependency-injection?hl=pt-br)
 - [Dagger Hilt](https://dagger.dev/hilt/)
 - [Editor Markdown](https://stackedit.io)
 - 

----------

#### Modulos:

**:app** - contem componentes do framework do android (view, database, context, navigation, framework) 

 - presentation - Activity, Fragment, Adapters, View Components 
 - framework - ViewModel, Navigation, Room Database, Retrofit, Dependency Injection

**:core** - contem regras de negocio, casos de uso e repositorios (nada relacionado com o framework Android).

 - use cases - interfaces e implementaçoes de todos os casos de uso da aplicacao.
 -  repository - repositorios de acesso aos dados e implementaçao de fontes de dados diversas domain - classes de dominio da aplicaçao.
