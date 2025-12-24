# 🧪 UnitTests — Boris's C#/.NET Practice Repository

[![.NET](https://img.shields.io/badge/.NET-6.0%2B-blue?logo=.net)](https://dotnet.microsoft.com/)
[![C#](https://img.shields.io/badge/C%23-10%2B-239120?logo=csharp)](https://learn.microsoft.com/en-us/dotnet/csharp/)
[![NUnit](https://img.shields.io/badge/Testing-NUnit-4285F4?logo=nunit)](https://nunit.org/)
[![Student Project](https://img.shields.io/badge/Status-Learning%20%26%20Practicing-orange)]()

Hi 👋 I'm **Boris**, a first-year CS student passionate about mastering software development fundamentals — one unit test at a time!  
This repository contains *unit tests* I wrote for programming tasks from my coursework (control assignments), using **C#**, **.NET**, and **NUnit** — because great code deserves great tests. 🧪

---

## 🎯 Purpose
- ✅ Reinforce algorithmic thinking & problem-solving skills  
- ✅ Apply **NUnit** (with `Assert` and `[Test]`) for clean, expressive test cases  
- ✅ Practice writing *reliable*, *readable*, and *maintainable* tests  
- ✅ Build strong foundations for future projects and internships

---

## 🛠️ Tech Stack
| Technology | Purpose |
|------------|---------|
| **C#** | Modern, strongly-typed language for robust solutions |
| **.NET 8** | Fast, cross-platform runtime (LTS version) |
| **NUnit** | Elegant, battle-tested unit testing framework |
| **Visual Studio / VS Code + C# Dev Kit** | My daily drivers for coding & debugging |

> 💡 Tests use `[Test]`, `[TestCase]`, `Assert.That()`, and other NUnit features to cover normal paths, edge cases, and invalid inputs.


## 🚀 Getting Started

### Prerequisites
- [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0)

### Run Tests
```bash
# Clone & navigate
git clone https://github.com/boris-ec/UnitTests.git
cd UnitTests

# Restore dependencies
dotnet restore

# Run all tests
dotnet test

# Run tests for a specific task
dotnet test Task1_ArraySum/Task1_ArraySum.csproj