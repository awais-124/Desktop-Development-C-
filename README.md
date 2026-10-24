# Test-App: WPF & C# Desktop Development Practice

A hands-on repository dedicated to learning and practicing Windows desktop application development using **C#**, **WPF** (Windows Presentation Foundation), and **XAML**.

This project bridges modern web and mobile concepts (JavaScript, React Native, MERN stack) to desktop .NET architecture.

---

## 🛠️ Tech Stack

- **Framework**: [.NET 9 (Windows)](https://learn.microsoft.com/en-us/dotnet/core/whats-new/dotnet-9/overview)
- **UI Platform**: WPF (Windows Presentation Foundation)
- **Language**: C# 13
- **Markup**: XAML (Extensible Application Markup Language)

---

## 📁 Repository Structure

```text
├── docs/                   # Beginner-friendly guides & architectural breakdowns
│   └── 01-wpf-architecture-and-flow.md
├── agent.md                # Agent guidelines, rules, and learning conventions
├── App.xaml                # Application startup definition & global resources
├── App.xaml.cs             # Application-level logic & lifecycle handlers
├── MainWindow.xaml         # Main window UI layout (XAML)
├── MainWindow.xaml.cs      # Main window code-behind (C#)
├── AssemblyInfo.cs         # Assembly-level metadata and theme resources
└── Test-App.csproj         # Project configuration & SDK settings
```

---

## 🚀 Getting Started

### Prerequisites
- [.NET 9 SDK](https://dotnet.microsoft.com/download/dotnet/9.0) installed on Windows.

### Build and Run

Run from terminal:

```bash
# Restore dependencies and build the project
dotnet build

# Launch the desktop application
dotnet run
```

---

## 📚 Documentation & Learning Notes

All architectural explanations, concept breakdowns, and deep dives are documented in the [`docs/`](./docs) folder:

- [01. WPF Architecture, Execution Flow & Boilerplate Explained](./docs/01-wpf-architecture-and-flow.md)
- [Agent & Contributor Rules](./agent.md)
