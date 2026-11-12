# prompts
Custom VS Code Copilot plugin instructions

## Installation

### Windows

```pwsh
New-Item -ItemType Junction `
    -Path "$env:USERPROFILE\.copilot\instructions" `
    -Target "D:\git\rafalpotempa\prompts\instructions"

New-Item -ItemType Junction `
    -Path "$env:USERPROFILE\.copilot\skills" `
    -Target "D:\git\rafalpotempa\prompts\skills"
```
