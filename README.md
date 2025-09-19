# Ivy HelloWorld (C#)

A minimal **Ivy** application scaffolded with the Ivy CLI, intended as a quick-start and as the Step-1 qualification artifact for the Ivy Upwork job post.

> Ivy is a new open-source framework for building interactive internal web apps using **pure C#** (inspired by React/Streamlit).

---

## ✨ What’s inside

- Minimal Ivy app created via `ivy init --hello`
- Hot-reload with `dotnet watch`
- Runs locally on `http://localhost:5010` (or the port shown in the console)

---

## 🧱 Prerequisites

- **.NET 9 SDK**
- **Visual Studio 2022** (17.12+) *or* VS Code (optional)
- **Ivy CLI** (installed as a global .NET tool)

Install Ivy CLI once:
```powershell
dotnet tool install -g Ivy.Console
```

## 🚀 Run locally

From the project folder:
```powershell
dotnet watch
```

Then open:
```powershell
http://localhost:5010
```

If a different port is used, the console will print the exact URL.

## 🧭 Visual Studio workflow

Open Visual Studio 2022

File → Open → Folder… → select this repo folder

Press F5 (Debug) or Ctrl+F5 (Run)

You can also use Visual Studio’s Git Changes panel to commit and Push to GitHub without any command-line steps.

## 🛠️ How this project was created
```powershell
mkdir ivy-helloworld
cd ivy-helloworld
ivy init --hello
# (Accepted default namespace when prompted)
```

## 📂 Project structure (minimal)
```powershell
ivy-helloworld/
├─ IvyHelloWorld.csproj
├─ Program.cs
├─ appsettings.json
└─ (Ivy-generated files for the Hello page/components)
```

Exact filenames can vary slightly as Ivy evolves, but this is the minimal layout after scaffolding with ivy init --hello.

## 🧪 Useful commands
```powershell
# run with hot reload
dotnet watch

# restore & build
dotnet restore
dotnet build

# open Ivy docs & samples (from anywhere once Ivy CLI is installed)
ivy docs
ivy samples
```

## 🆘 Troubleshooting

ivy is not recognized
Open a new terminal, or ensure %USERPROFILE%\.dotnet\tools is on your PATH.

.NET 9 not found in Visual Studio
Update Visual Studio to 17.12+ via the VS Installer (and install the .NET 9 SDK).

Port already in use
Stop the other process using the port, or let Ivy pick another port (check the console output for the actual URL).

Firewall prompt on first run
Allow access so the local server can bind to the port.

## 🔗 Helpful links

Ivy website: https://ivy.app

Framework repo: https://github.com/Ivy-Interactive/Ivy-Framework

Docs: https://docs.ivy.app

Samples: https://samples.ivy.app

## 📄 License

This repository is shared under the MIT License (or choose your preferred license).

## 🙌 Notes for reviewers

This repo demonstrates the Step-1 requirement (HelloWorld Ivy app).
I’ve also starred the Ivy framework repository as requested.
