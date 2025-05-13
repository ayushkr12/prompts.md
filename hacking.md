### **JavaScript Reverse Engineering:**

*"Help me deobfuscate and reverse engineer JavaScript. Start by identifying the obfuscation technique, then walk me through the logic and purpose of the code step-by-step. Explain evals, dynamic functions, string decodes, and any weird control flow. Output cleaned-up code alongside explanations, and point out any interesting endpoints, tokens, or behaviors that might be exploitable."*

---

### **Payload Crafting:**

*"Generate payloads for the given context. Think like an attacker — give me minimal but effective payloads for things like XSS, SSTI, SQLi, etc., depending on what I ask. Always explain why it would work, and how it's bypassing filters or protections. Prioritize obfuscation, evasion, and functionality."*

---

### **Bypass Guidance:**

*"Give me ideas to bypass common protections like WAFs, client-side validations, CSP, input filters, regex blacklists, etc. Based on the context I give, suggest payload tricks, encodings, header manipulations, or protocol abuse. Think like someone actively trying to break through with clever workarounds."*

---

### **Recon Exploiter:**

*"Act like an OSINT bloodhound. If I give you a domain, suggest all the recon techniques I should run — subdomain hunting, endpoint discovery, parameter fuzzing, third-party assets, archived files, Git leaks, etc. Help me expand the attack surface like a professional recon artist."*

---

### **Binary Exploitation Trainer:**

*"Explain binary exploitation techniques like buffer overflows, format string bugs, or ROP chains in a step-by-step way based on a given binary challenge or concept. Break down what’s happening at the assembly level, memory layout, and what the exploit is achieving at each step."*

---

### **CVE Analyzer:**

*"Given a CVE ID or description, break down how the vulnerability works technically. Include affected components, root cause, potential exploitability, and how a proof-of-concept might look. If available, include real exploit code snippets and walk me through them."*

---

### **Hack the Flow:**

*"When I give you a web app flow or API interaction, break it down from a hacker’s perspective. Identify potential vulnerabilities at each step — auth flaws, IDOR, replay attacks, CSRF, race conditions, etc. Give brief, pointed exploitation ideas for each weak spot."*

---

### **Endpoint Decoder:**

*"If I paste a blob of JavaScript, network logs, or request data, analyze it like a black-box pen tester. Pull out any useful endpoints, secrets, tokens, or IDs. Try to infer the app's internal API structure and suggest next steps for fuzzing or exploiting them."*

---

### **Scope Validator:**

*"If I paste a scope or program brief, help me break down what parts are actually in scope for testing. Identify hidden or ambiguous areas that are often overlooked (like forgotten subdomains, mobile APIs, staging environments). Help me read between the lines to find gray areas worth testing."*

---

### **Obfuscation Identifier:**

*"When I give you obfuscated JavaScript or weird-looking code, identify the type of obfuscation (like string splitting, Base64 wrapping, control flow flattening). Then walk me through decoding or rewriting it into readable form. Assume I want to understand what it does and why it’s structured that way."*

---

### **Auth Flow Breaker:**

*"Break down the authentication flow I describe and find weak spots. Look for token leakage, insecure storage, logic flaws, weak 2FA implementation, or refresh token issues. Tell me how you’d try to hijack or bypass auth step-by-step."*

---

### **Bug Chain Builder:**

*"If I describe multiple low or medium-severity bugs, help me think creatively about chaining them into a high or critical impact. Give ideas for privilege escalation, data exfiltration, or persistence by combining multiple flaws in the flow."*

---
