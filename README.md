## Welcome to Kotlin Last Crusade – A Shared Guide for Learning Architecture and Coding in Kotlin!

## Projects

Explore a collection of projects that showcase various architectural patterns and coding practices in Kotlin. Each link below provides in-depth details on implementation and best practices to enhance your development skills.

### 1. [KotlinLastCrusade1](https://github.com/Crusade4Code/kotlinlastcrusade1-xml-koin-mapper-usecase)
- **Description**: This project uses Github API to get information from Users and Repos in a user-details screen. The proposal is to use Clean Architecture concepts inside Repositories, through Repository Interfaces, Mappers and UseCases. Also to use Koin as Dependency Injection. Unit Tests. And some important concepts to a better use of Dispatchers according to  which teaches about change the Dispatchers inside repositories, since it does the true work. (i).
- **Technologies:**
  - **Retrofit**, **Koin**, **Unit Tests**, **Navigation**, **XML**
  - **Clean Architecture**
    - **Repository/RepositoryImpl**
    - **Mapper**
    - **Use-case**

(i) "This pattern makes your app more scalable, as classes calling suspend functions don't have to worry about what Dispatcher to use for what type of work. This responsibility lies in the class that does the work." (https://developer.android.com/kotlin/coroutines/coroutines-best-practices)

## How to Use

Explore the repositories above to compare different architectural approaches. Each project includes detailed setup and usage instructions.
