# 🛡️ TryHackMe - Module 1

## 🧠 Task 1: Think Like a Hacker

### Key Concept
**Offensive Security** focuses on thinking like an attacker to identify vulnerabilities before malicious hackers can exploit them.

It is a fundamental concept in **ethical hacking**, where security professionals simulate real-world attacks in a legal and controlled environment.

### What I Learned
- The importance of adopting an attacker’s mindset
- The role of offensive security in protecting systems
- Ethical hacking must always be authorized and legal

---

## 🛡️ Task 2: Starting the Lab

### Environment
- A **virtual desktop** is used to simulate a real system
- Interaction with a web application: **FakeBank**

### What I Learned
- How cybersecurity labs simulate real-world environments
- Basic interaction with a web-based system
- The importance of exploring applications to understand their structure

---

## 🔎 Task 3: Find Hidden Pages

### Key Concept
Web applications may contain **hidden or unlinked pages**, which can represent security vulnerabilities if exposed.

### Tool Used
- **dirb**: a directory brute-forcing tool used to discover hidden web pages

### Command
```bash
dirb http://fakebank.thm
```

### What I Learned
- How attackers discover hidden endpoints in web applications
- The role of brute-force tools in reconnaissance
- Why improperly secured directories can lead to vulnerabilities

---

## 💣 Task 4: Attack the Admin Page

### Key Concept
Hidden administrative panels can allow unauthorized users to perform critical actions if not properly secured.

### What I Learned
- How access to hidden pages can lead to privilege abuse
- The risks of insecure web application design
- How small vulnerabilities can escalate into serious security issues

---

## 🧠 Module Summary

- Offensive Security involves simulating attacks to identify weaknesses
- Web applications often expose vulnerabilities through:
  - hidden directories
  - poor access controls
- Tools like **dirb** are used during the reconnaissance phase
- Gaining unauthorized access can compromise critical system functions

---

## 🚀 Key Takeaways

- Thinking like an attacker is essential in cybersecurity
- Reconnaissance is a crucial step in any attack
- Misconfigured systems are a common source of vulnerabilities
- Practical labs are key to understanding real-world security concepts







# 🛡️ Think Like a Defender

## 📌 ¿Qué es la seguridad defensiva?

La **seguridad defensiva (Defensive Security)** es el proceso de **proteger y asegurar dispositivos y sistemas** frente a ataques.

Antes de poder defender un sistema, es necesario entender las responsabilidades de un defensor:

- 🔍 Detectar actividad sospechosa  
- 🧪 Investigar posibles ataques  
- 🚨 Responder antes de que ocurra daño  

👉 A diferencia de la seguridad ofensiva:
- ❌ No atacas sistemas  
- ✅ Monitorizas y proteges  

---

## 🧠 Mentalidad de un Defensor

Un defensor debe:

- Diferenciar entre actividad normal y maliciosa  
- Analizar alertas de seguridad  
- Actuar rápidamente ante incidentes  

---

## 👨‍💻 Caso práctico: Joe (SOC Analyst)

Joe es un analista SOC en su primer turno en solitario.  
Su dashboard de monitorización muestra una alerta sospechosa.

👉 Tu misión es ayudarle a investigar antes de que se convierta en un incidente grave.

---

# 🔍 Fase 1: Detectar Actividad Sospechosa

### 🎯 Objetivo:
Identificar la IP sospechosa

### 🛠️ Pasos:

1. Abrir el dashboard de monitorización  
2. Revisar alertas recientes  
3. Identificar la **IP sospechosa**

---

# 🕵️ Fase 2: Identificar el Ataque

Detectar algo raro no es suficiente — hay que entender **qué está haciendo el atacante**.

### 🎯 Objetivo:
Determinar el tipo de ataque

### 🛠️ Pasos:

1. Investigar la actividad registrada  
2. Revisar la sección **"URL Discovery Attempts"**  
3. Analizar la entrada más reciente  

👉 Aquí encontrarás pistas sobre el comportamiento del atacante

---

# 🚫 Fase 3: Detener el Ataque

Una vez identificado el atacante y su objetivo:

👉 La prioridad es **contener el ataque**

### 🎯 Objetivo:
Bloquear al atacante

### 🛠️ Pasos:

1. Revisar las acciones de seguridad (Joe ya completó algunas)  
2. Bloquear la IP del atacante en el firewall  
