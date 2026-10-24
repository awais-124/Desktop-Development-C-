# Agent Rules & Workflow Guidelines

## Core Directives for this Project

1. **Documentation-First Approach**:
   - Whenever explaining how anything works in code or introducing new concepts/features, always create or update markdown documentation in the `docs/` directory at the project root.
   - For every new feature or piece of code written, document how it works, why it is structured that way, and how the parts connect.

2. **Target Audience & Mental Model**:
   - **Target Level**: Beginner in C#, WPF (Windows Presentation Foundation), and XAML.
   - **Background Knowledge**: Proficient in JavaScript, React Native (RN), and the MERN stack (MongoDB, Express, React, Node.js).
   - **Explanation Strategy**:
     - Bridge new concepts by mapping them to familiar JS / React Native / MERN equivalents (e.g., JSX vs XAML, State/Props vs DependencyProperties/DataBinding, `package.json` vs `.csproj`, npm vs NuGet, React Native styling vs WPF Styles/Templates, `App.js` vs `App.xaml`).
     - Avoid unexplained .NET jargon. Break down behind-the-scenes (BTS) mechanics like the MSBuild compiler, partial classes, BAML compilation, and WPF event routing.

3. **Code Style & Explanations**:
   - Keep C# and XAML clean, modern, and idiomatic.
   - Include meaningful comments explaining non-trivial syntax or framework quirks.
   - Point the user to the corresponding `.md` guide in `docs/` whenever introducing changes.
