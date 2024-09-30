# NikeStore_ERD.md

```mermaid
erDiagram
    
    PRODUCT ||--|{CUSTOMER: delivered

    INVENTORY ||--|{SALES: records

    CUSTOMER ||..|{ SALES: generates
    SALES 

    INVENTORY ||--|| PRODUCT: Tracks


```

Inventory has to keep track of their product.
Product gets delivered to customers.
Customers in return generate sales for the company.
The sales made are recorded by the Inventory deparment which buys more products.