# ✍️ GitHub Copilot Custom Instructions

# C# Style Guide (Telerik-inspired)

## 🔠 Naming Conventions

- Use **PascalCase** for classes, methods, and properties  
  `public class UserManager { }`
- Use **camelCase** for private fields and method parameters  
  `private int userId;`
- Prefix private backing fields with `_`  
  `private string _emailAddress;`

## 🧼 Formatting & Layout

- Allman-style braces (open on a new line)
  ```csharp
  public void Initialize()
  {
      // logic here
  }
