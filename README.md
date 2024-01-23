# Project Integration Documentation

## Step 1: Create a New Web Project

### 1.1 Project Structure

- **wwwroot:** Contains static assets such as CSS, JS, fonts, and images.
- **Controllers:** Lists APIs, each function redirects to a view mapped in the corresponding folder.
- **Views:** Each folder (e.g., Home) corresponds to a controller.
- **Shared:** Contains reference pages that are extended by other views; all should start with '_'.
- **program.cs:** Contains middleware configuration.

### 1.2 Project Appearance

![image](https://github.com/Amir0055/IntegrationTemplate_ASP.NET-Core--MVC/assets/93008466/e7a25b01-1683-4b64-9ee6-5a3220825590)

## Step 2: Download Template

### 2.1 Template Selection

- Download a free template from [w3layouts](https://w3layouts.com/?s=website&post_type=product).
- Example: [Dentition Template](https://w3layouts.com/template/dentition-a-dental-clinic-website-template/).

## Step 3: Add Functions for Each Page

### 3.1 Define Functions

- Identify pages in the template (e.g., Services, Home, About, Contact).
- Link each page with a corresponding function in the controller.

   ![image](https://github.com/Amir0055/IntegrationTemplate_ASP.NET-Core--MVC/assets/93008466/1ff64567-53df-4638-92fd-883c7f0137a6)

- Example:

   ```csharp
   public IActionResult Services()
   {
       // Function logic
       return View();
   }
# Result

![Project 23](https://github.com/Amir0055/IntegrationTemplate_ASP.NET-Core--MVC/assets/93008466/0ddb973e-1646-4be1-8922-12ee5107539e)

>For more details step by step 
[lien. ](https://github.com/Amir0055/IntegrationTemplate_ASP.NET-Core--MVC/edit/main/README.md)

