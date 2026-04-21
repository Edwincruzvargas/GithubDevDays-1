---
name: SocOps Blazor Development
description: Workspace instructions for the SocOps social bingo game built with Blazor and C#
---

# SocOps Development Guide

**SocOps**: A Blazor social bingo game for in-person mixers. **Stack**: .NET 10, Blazor Components, Bootstrap 5.

## ✅ Mandatory Checklist
- [ ] **Lint** - `dotnet format --verify-no-changes` (or fix with `dotnet format`)
- [ ] **Build** - `dotnet build` (verify compilation succeeds)
- [ ] **Test** - `dotnet test` (all tests passing)

## 🚀 Quick Start

```bash
cd SocOps
dotnet build
dotnet run      # http://localhost:5000
```

Run `/setup` before diving in.

## 📂 Project Structure

- **Components/** - BingoBoard, GameScreen, StartScreen, etc.
- **Pages/** - Home, Counter, Weather, NotFound
- **Models/** - GameState, BingoSquareData, BingoLine
- **Services/** - BingoGameService, BingoLogicService
- **Data/** - Questions.cs
- **Layout/** - MainLayout, NavMenu
- **wwwroot/** - Static assets (CSS, Bootstrap)

## 🎨 Design & Styling

Use `/frontend-design` for UI work. Use `/css-utilities` for consistent styling.

## 🧪 Testing (TDD)

Use `/tdd` to orchestrate the full TDD cycle. Individual agents: `/tdd-red`, `/tdd-green`, `/tdd-refactor`.

```bash
dotnet test
```

## 🤖 Available Agents

| Agent | Purpose |
|-------|---------|
| `/tdd` | Full TDD cycle orchestration |
| `/ui-review` | UI quality review |
| `/quiz-master` | Quest/game logic management |
| `/pixel-jam` | Fast prototyping & visual polish |
| `/cloud-explore` | Cloud deployment |
