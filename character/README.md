# Character Query – Rick and Morty GraphQL API

## 🧩 Overview
This project demonstrates how to use **GraphQL** to retrieve specific data from the [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql).  
The focus is on fetching detailed information for individual characters by their unique ID.

By constructing precise GraphQL queries, this project highlights how to interact with an API efficiently — requesting only the necessary fields for each character.

---

## 🚀 About the Project
The **Character Query** module is designed to explore how GraphQL queries work when fetching individual records using parameters.  
In this example, the query retrieves the details of specific Rick and Morty characters by their `id`, showcasing GraphQL’s ability to return structured and minimal data in a single request.

Each query returns key details including:
- **id** – Unique identifier of the character  
- **name** – Character’s full name  
- **status** – Indicates if the character is alive, dead, or unknown  
- **species** – The species classification of the character  
- **type** – Additional descriptor or subtype (if available)  
- **gender** – The gender identity of the character  

---

## 🧠 Key Concepts
- **GraphQL Queries:** Define exactly what data to fetch using flexible and strongly-typed queries.  
- **Arguments:** Use the `character(id: ID!)` argument to target a specific record.  
- **Selective Fetching:** Request only required fields (`id`, `name`, `status`, `species`, `type`, `gender`) to optimize performance.  
- **Structured Responses:** Receive predictable and typed JSON responses from the API.

