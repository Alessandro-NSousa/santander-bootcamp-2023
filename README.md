# santander Bootcamp 2023 Java Backend
Java RESTful API criada para o Bootcamp Back-end Java 2023.

## Diagrama de classes

```mermaid
classDiagram
  class User {
    - name: String
    - account: Account
    - feature: Feature[]
    - card: Card
    - news: News[]
  }

  class Account {
    - number: String
    - agency: String
    - balance: Float
    - limit: Float
  }

  class Feature {
    - icon: String
    - description: String
  }

  class Card {
    - number: String
    - limit: Float
  }

  class News {
    - icon: String
    - description: String
  }

  User --> Account
  User --> Feature
  User --> Card
  User --> News

```
