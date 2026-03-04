```mermaid
classDiagram
  User "1" --> "many" TypingTest

  class User {
    id: int
    username: string
    password: string
  }

  class TypingTest {
    wpm: float
    accuracy: float
    date: datetime
  }
