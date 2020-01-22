```mermaid
sequenceDiagram
  Alice->Bob: Authentication Request
  note right of Bob: Bob thinks about it
  Bob->Alice: Authentication Response

  alt text1
      A->B: text
  else text2
      A->B: text
  end
```