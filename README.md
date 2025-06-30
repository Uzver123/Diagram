graph TD
  A[Client] -->|HTTP Request| B[Server]
  B -->|Fetch data| C[Database]
  C -->|Data| B
  B -->|HTTP Response| A

  click A "https://example.com/client" "Go to Client page"
  click B "https://example.com/server" "Go to Server page"
  click C "https://example.com/database" "Go to Database docs"
