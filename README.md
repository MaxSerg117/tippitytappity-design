classDiagram
  User "1" --> "many" TypingTest

  class User {
    - id: int
    - username: string
    - password: string
    + login(user: string, pass: string) boolean
  }

  class TypingTest {
    - id: int
    - userId: int
    - wpm: float
    - accuracy: float
    - date: datetime
  }
