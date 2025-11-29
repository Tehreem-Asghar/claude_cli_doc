# Lesson 2 Documentation: Installing & Authenticating Claude Code

## 1. Introduction
Is lesson ka maqsad hai Claude Code ko apki machine par install, setup, aur authenticate karna. Install ke baad Claude Code apki project files, terminal commands, aur development workflow ko directly assist karega.

---

## 2. Installation Paths
Claude Code ko do professional paths se install kiya ja sakta hai:

| Path | Cost | Features |
|------|------|----------|
| **Official Claude (Pro/Max)** | Pro $20/month, Max $200/month | Official models, direct integration, support |
| **Free Path (Lesson 3)** | Free | Claude Code architecture any LLM (Gemini, GPT, Local) ke sath |

---

## 3. Why Terminal Integration Matters
Terminal-based AI integration se Claude Code:
- Aapki real project files access karta hai
- Code propose karta hai
- Commands run karta hai
- Testing, refactoring, git workflow manage kar sakta hai

Ye workflow AI ko consultant se pair programmer bana deta hai.

---

## 4. Prerequisites
Installation se pehle yeh cheezein honi chahiye:

### 4.1 Terminal Access
- Windows: PowerShell / CMD
- macOS: Terminal
- Linux: Koi bhi terminal

### 4.2 Claude Account
- **A)** Claude.ai subscription (Pro/Max)
- **B)** Console API account

---

## 5. Installation Methods
Claude Code ko 4 methods se install kiya ja sakta hai:

### 5.1 macOS/Linux (Recommended)
```
curl -fsSL https://claude.ai/install.sh | bash
```

### 5.2 Homebrew (macOS)
```
brew install --cask claude-code
```

### 5.3 Windows (PowerShell)
```
irm https://claude.ai/install.ps1 | iex
```

### 5.4 npm (Cross Platform)
```
npm install -g @anthropic-ai/claude-code
```

---

## 6. Verify Installation
Installation check karne ke liye:
```
claude --version
```
Agar version number show ho jaye → installation successful.

---

## 7. Authentication
Claude Code use karne ke liye login karna zaroori hai.

### 7.1 Start Login
```
claude
```

Aapko 2 login methods milenge:

### Method A: Claude.ai Login (Recommended)
- Option 1 select karo
- Browser open hoga → login
- Terminal par message: **Login successful**

Test command:
```
claude "Hello! Confirm you're working."
```

### Method B: Console API Login
1. Go to: https://console.anthropic.com/settings/keys
2. API key copy karo
3. Terminal mein paste karo
4. "API key validated" message aayega

---

## 8. Security Best Practices
Claude Code ko file access aur command permission hoti hai, isliye:

### 8.1 Avoid Running in Directories:
- C:\
- Windows\
- System32\
- Program Files\

### 8.2 Commands Kabhi Approve Na Kare:
- sudo
- rm -rf
- format
- destructive commands

---

## 9. Safe Test Commands
### 9.1 Version Test
```
claude --version
```

### 9.2 Simple Greeting
```
claude "Hello Claude!"
```

### 9.3 Safe File Read Test
```
echo "Hello Test File" > test.txt
claude "Read test.txt"
```

### 9.4 Directory Check
```
claude "Check my current directory."
```

---

## 10. First Exercise (Beginner Friendly)
```
claude "Create a new file test.js and write console.log('Hello Claude Code!') in it."
```

Claude:
- File banayega
- Diff show karega
- Approval maangega

---

## Document Complete

