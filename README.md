### 🛠 Architecture Diagram

```mermaid
graph TD
  A[Client] -->|HTTP Request| B[Server]
  B -->|Fetch data| C[Database]
  C -->|Data| B
  B -->|HTTP Response| A
