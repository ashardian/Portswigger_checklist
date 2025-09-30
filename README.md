# PortSwigger / Web Security Academy — Personal Study Checklist

> Curated learning progression (Beginner → Practitioner → Professional).  
> Each item links to PortSwigger's Web Security Academy pages or representative labs. Follow the recommended lab order inside each topic (PortSwigger orders labs easy → hard).

---

## Quick resources
- Web Security Academy home: https://portswigger.net/web-security.  
- Learning paths index: https://portswigger.net/web-security/learning-paths.  
- All labs: https://portswigger.net/web-security/all-labs.

---

# Beginner (Foundations)
Do these first to build a strong base.

1. **Getting started / Essential skills**
   - PortSwigger Web Security Academy (home): https://portswigger.net/web-security
   - Recommended practice: Burp basics, intercept & repeater, encodings, simple labs.

2. **Cross-Site Scripting (XSS)**
   - Topic index: https://portswigger.net/web-security/cross-site-scripting
   - Lab order: Reflected XSS → Stored XSS → DOM XSS → Filter bypasses.

3. **SQL Injection (SQLi)**
   - Learning path / example lab: https://portswigger.net/web-security/sql-injection/lab-login-bypass
   - Lab order: Basic error-based → UNION extraction → Blind/timing.

4. **Cross-Site Request Forgery (CSRF)**
   - Topic index: https://portswigger.net/web-security/csrf
   - Lab order: Token omission → CSRF with forged forms → SameSite testing.

5. **Authentication vulnerabilities (basics)**
   - Authentication path: https://portswigger.net/web-security/authentication
   - Labs: session fixation, weak tokens, login-bypass exercises.

6. **Access control (basic)**
   - Access control: https://portswigger.net/web-security/access-control
   - Labs: IDORs, horizontal/vertical privilege escalation.

---

# Practitioner (Intermediate)
Chain vulnerabilities and perform effective recon.

1. **Path traversal**
   - Topic/index: https://portswigger.net/web-security/path-traversal
   - Labs: relative traversal, filter bypasses.

2. **File upload vulnerabilities**
   - Topic/index: https://portswigger.net/web-security/file-upload
   - Labs: bypass content-type checks → upload web shell.

3. **NoSQL injection**
   - Topic/index: https://portswigger.net/web-security/no-sql-injection
   - Labs: operator injection, JSON payload manipulation.

4. **Server-Side Request Forgery (SSRF)**
   - Learning path: https://portswigger.net/web-security/ssrf
   - Example lab: Basic SSRF against local server — https://portswigger.net/web-security/ssrf/lab-basic-ssrf-against-localhost
   - Lab order: Basic SSRF → Blind SSRF → SSRF to metadata/internal services.

5. **XML External Entity (XXE)**
   - Topic/index: https://portswigger.net/web-security/xml-external-entity
   - Labs: XXE file read → blind XXE.

6. **Command injection / OS command injection**
   - Topic index: https://portswigger.net/web-security/command-injection
   - Labs: input to OS exec → escalate to RCE.

7. **WebSockets vulnerabilities**
   - Topic: https://portswigger.net/web-security/websockets
   - Labs: Manipulating messages — https://portswigger.net/web-security/websockets/lab-manipulating-messages-to-exploit-vulnerabilities
   - Labs: Handshake manipulation — https://portswigger.net/web-security/websockets/lab-manipulating-handshake-to-exploit-vulnerabilities

8. **CORS misconfigurations**
   - Topic/index: https://portswigger.net/web-security/cors
   - Labs: permissive wildcard origins, reflected origin attacks.

9. **Clickjacking (UI redressing)**
   - Topic/index: https://portswigger.net/web-security/clickjacking

10. **API testing**
    - Learning path: https://portswigger.net/web-security/learning-paths
    - Labs: discover hidden endpoints, parameter pollution.

---

# Professional (Advanced)
Research-level topics that require strong background and careful tooling.

1. **Race conditions**
   - Topic/index: https://portswigger.net/web-security/race-conditions

2. **Prototype pollution**
   - Learning path: https://portswigger.net/web-security/learning-paths/prototype-pollution
   - Notes: advanced JS-based vulnerability with client & server impacts.

3. **Server-side template injection (SSTI)**
   - Topic/index: https://portswigger.net/web-security/server-side-template-injection

4. **HTTP request smuggling**
   - Topic/index / reading: https://portswigger.net/web-security/request-smuggling
   - Notes: requires deep HTTP/proxy behavior knowledge.

5. **Web cache deception / cache poisoning**
   - Topic: https://portswigger.net/web-security/web-cache-deception
   - Additional reading: https://portswigger.net/web-security/web-cache-poisoning

6. **GraphQL API vulnerabilities**
   - Topic/index: https://portswigger.net/web-security/graphql

7. **Web LLM attacks (emerging)**
   - Learning path: https://portswigger.net/web-security/learning-paths/web-llm-attacks

8. **Advanced SQLi / blind / second-order**
   - Deep labs and timing attacks: explore advanced SQLi labs in the SQLi section.

---

# Recommended lab-by-lab order (compact 12-week plan)
- Weeks 1–2: Getting started → Burp basics → Reflected XSS → Simple SQLi.  
- Weeks 3–4: Auth basics → CSRF → Access control labs → Stored XSS.  
- Weeks 5–6: Path traversal → File upload → Command injection → NoSQL.  
- Weeks 7–8: SSRF → API testing → CORS → WebSockets.  
- Weeks 9–10: Prototype pollution → SSTI → Race conditions.  
- Weeks 11–12: Request smuggling → Web cache deception → Web LLM / GraphQL.

---

## How to use this file
1. Open each link and complete labs in PortSwigger's suggested order (they go easy → hard).  
2. For each lab, document: objective, payloads tried, exact request/response, and mitigation notes.  
3. Keep a single notes file where you paste working payloads and bypass tricks for quick reference.

---

*File generated for you by Ashar Dian — happy hacking (ethically & on authorised targets only).*
