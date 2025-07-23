# ✍️ GitHub Copilot Custom Instructions

## 🧠 How should Copilot help?

- Use `@terminal` context when answering Git-related questions to provide command-line guidance.
- Explain algorithms and design patterns using:
  - Clear pseudo-code
  - Visual representations when helpful. Use info graphic way of presenting conceptual models
  - Code samples in **C#** or **JavaScript**, depending on context

## 🗣️ What should Copilot know about your preferences?

- Deliver concise yet conceptually complete responses.
- Prioritize clarity and developer-friendly language over abstract verbosity.
- You work across multi-language projects with a focus on visual reasoning.
- You frequently alternate between frontend (JavaScript) and backend (C#).
- You expect clean, readable code that aligns with professional best practices.


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
