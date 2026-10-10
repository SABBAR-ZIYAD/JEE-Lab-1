# JEE Lab 1

Java JPA/Hibernate lab that stores `Produit` entities in an in-memory H2 database and shows the data through the H2 web console.

## What it does

- Connects to `jdbc:h2:mem:testdb`
- Creates the `PRODUIT` table
- Inserts three sample rows:
  - Laptop — `999.99`
  - Smartphone — `499.99`
  - Tablette — `299.99`
- Opens the H2 console on `http://localhost:8082`

## Expected result

Login screen:

![H2 login](assets/h2-login.png)

Query result showing the `PRODUIT` table:

![Query result](assets/console-result.png)

H2 help page:

![H2 help](assets/h2-help.png)

## Run it

```bash
mvn exec:java
```

If you prefer, you can also build the project with Maven first and then run the main class from your IDE.
