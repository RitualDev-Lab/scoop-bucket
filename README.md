# 🍨 RitualDev Lab Official Scoop Bucket

Official Windows package repository for the RitualDev-Lab AI agent defense, kernel sandboxing, and database guardrails suite via [Scoop](https://scoop.sh/).

## 🚀 Installation on Windows

### 1. Add the Ritual bucket:
```powershell
scoop bucket add ritual https://github.com/RitualDev-Lab/scoop-bucket
```

### 2. Install Tools:
```powershell
# AI Agent Runtime Defense & Kernel Sandbox (Windows AppContainer)
scoop install agentshield

# Database Guardrail, Sandboxing Wire Proxy & PII Masking
scoop install dbshield

# Context Window Optimizer & Tool Router
scoop install skillprism

# DAST, SAST, SCA & AI Secret Hunter
scoop install web-sec-auditor
```

### 3. Update Tools:
```powershell
scoop update
scoop update agentshield dbshield
```

## 📄 License
MIT © [RitualDev Lab](https://github.com/RitualDev-Lab)
