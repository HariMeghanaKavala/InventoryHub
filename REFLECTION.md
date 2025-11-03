# REFLECTION: InventoryHub Full-Stack Project with Microsoft Copilot

## Overview
This project, **InventoryHub**, is a full-stack application built using a Blazor front-end and a .NET Minimal API back-end. Throughout the project, I used **Microsoft Copilot** to generate, debug, and optimize code efficiently.

---

## Activity 1: Integration Code Generation
Copilot assisted in generating the initial integration between the Blazor front-end and the back-end API.  
It suggested code for fetching product data and setting up HttpClient communication, which saved time and reduced manual setup errors.

---

## Activity 2: Debugging Integration Issues
When errors occurred, such as incorrect API routes, CORS restrictions, and malformed JSON, Copilot provided step-by-step suggestions to fix them.  
It helped me:
- Update API routes from `/api/products` to `/api/productlist`
- Configure CORS policies in `Program.cs`
- Add error handling for JSON deserialization in Blazor.

These improvements made the app more stable and prevented runtime errors.

---

## Activity 3: JSON Structuring
Copilot generated well-structured JSON responses for the back-end API.  
It helped create nested objects like:
```json
{
  "Id": 1,
  "Name": "Laptop",
  "Price": 1200.50,
  "Stock": 25,
  "Category": {
    "Id": 101,
    "Name": "Electronics"
  }
}
