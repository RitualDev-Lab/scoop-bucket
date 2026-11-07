# 🍨 RitualDev Lab Official Scoop Bucket

Official Windows package repository for the RitualDev-Lab AI agent defense, kernel sandboxing, and database guardrails suite via [Scoop](https://scoop.sh/).

## 🚀 Installation on Windows

### 1. Add the Ritual bucket:
```powershell
scoop bucket add ritual https://github.com/RitualDev-Lab/scoop-bucket
```

### 2. Install Tools:
```powershell
# Enterprise AI DLP & Secret Firewall CLI
scoop install promptshield

# Safety-first Database Guardrail, Sandboxing Wire Proxy & Virtual Schema RBAC
scoop install dbshield

# Intelligent Relational Mock DB & Synthetic Test Data Engine
scoop install mockforge

# In-Memory Contract, Lease & NDA Scanner
scoop install fineprint

# AI Agent Runtime Defense & Kernel Sandbox (Windows AppContainer)
scoop install agentshield

# Context Window Optimizer & Tool Router
scoop install skillprism

# DAST, SAST, SCA & AI Secret Hunter
scoop install web-sec-auditor
```

### Install All Suite Tools:
```powershell
scoop install promptshield dbshield mockforge fineprint agentshield skillprism web-sec-auditor
```

### 3. Update Tools:
```powershell
scoop update
scoop update *
```

## 📄 License
MIT © [RitualDev Lab](https://github.com/RitualDev-Lab)
