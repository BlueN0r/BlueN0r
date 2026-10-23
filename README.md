<!-- ╔══════════════════════════════════════════════════════════════╗ -->
<!-- ║  BlueN0r · Offensive Security Researcher — GitHub Profile      ║ -->
<!-- ║  NOTE: dynamic widgets below use the handle `BlueN0r`.         ║ -->
<!-- ║  If your GitHub username differs, find/replace it once.        ║ -->
<!-- ╚══════════════════════════════════════════════════════════════╝ -->

<!-- ===================== HERO BANNER ===================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A0E27,50:1B2A4A,100:0A66C2&height=220&section=header&text=BlueN0r&fontSize=72&fontColor=ffffff&fontAlignY=38&desc=Find%20it.%20Prove%20it.%20Get%20it%20fixed.&descAlignY=60&descSize=20&animation=fadeIn" alt="BlueN0r banner">
</p>

<!-- ===================== TYPING SUBTITLE ===================== -->
<p align="center">
  <a href="https://bluen0r.com">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=2DA44E&center=true&vCenter=true&width=720&lines=Offensive+Security+Researcher+%2F+Penetration+Tester;Web+%C2%B7+Active+Directory+%C2%B7+Mobile+%C2%B7+Reverse+Engineering;Open-Source+Vulnerability+Research+%26+Coordinated+Disclosure" alt="roles">
  </a>
</p>

<!-- ===================== TOP BADGES ===================== -->
<p align="center">
  <a href="https://bluen0r.com"><img src="https://img.shields.io/badge/Blog-bluen0r.com-0A66C2?style=for-the-badge&logo=rss&logoColor=white" alt="Blog"></a>
  <a href="https://github.com/advisories?query=credit%3ABlueN0r"><img src="https://img.shields.io/badge/Security_Advisories-Credited-2DA44E?style=for-the-badge&logo=github&logoColor=white" alt="Advisories"></a>
  <img src="https://img.shields.io/badge/Based_in-Busan,_Korea-555555?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location">
  <img src="https://komarev.com/ghpvc/?username=BlueN0r&style=for-the-badge&color=0A66C2&label=PROFILE+VIEWS" alt="Profile views">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CPTS-Certified-9146FF?style=flat-square&logo=hackthebox&logoColor=white" alt="CPTS">
  <img src="https://img.shields.io/badge/CWES-Certified-9146FF?style=flat-square&logo=hackthebox&logoColor=white" alt="CWES">
  <img src="https://img.shields.io/badge/CVE-Credited-E00000?style=flat-square&logo=cve&logoColor=white" alt="CVE">
</p>

<div align="center">

```diff
+ "I break things to make them safer."
! From finding the bug → writing a clean PoC → shipping a fix & advisory with maintainers.
```

</div>

---

## 🧑‍💻 `whoami`

```yaml
name:      BlueN0r
role:      Offensive Security Researcher / Penetration Tester
location:  Busan, South Korea
focus:
  - Web application & API penetration testing
  - Active Directory & Windows infrastructure attacks
  - Android application security & dynamic instrumentation
  - Reverse engineering & binary analysis
  - Open-source vulnerability research & coordinated disclosure
certs:     [HTB CPTS, HTB CWES]
blog:      https://bluen0r.com
motto:     "Find it, prove it, get it fixed."
```

My work spans hands-on penetration testing of real-world services and independent
vulnerability research in open-source software — turning an interesting anomaly into a
reproducible PoC, and a PoC into a shipped fix.

---

## 🎓 Certifications

<p align="center">
  <a href="https://academy.hackthebox.com/preview/certifications/htb-certified-penetration-testing-specialist">
    <img src="https://static.hackthebox.com/academy/badges/htb-certified-penetration-testing-specialist.png" alt="HTB CPTS" width="150">
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://academy.hackthebox.com/preview/certifications/htb-certified-web-exploitation-specialist">
    <img src="https://static.hackthebox.com/academy/badges/ae46a491c837f0765dc1972f7d61e9ca/logo.png" alt="HTB CWES" width="150">
  </a>
</p>

| Certification | Issuer | Scope |
|---|---|---|
| **CPTS** — Certified Penetration Testing Specialist | Hack The Box | Full-scope internal/external pentest, Active Directory attack chains, pivoting, privilege escalation, professional reporting |
| **CWES** — Certified Web Exploitation Specialist | Hack The Box | Web application exploitation, authn/authz bypass, injection classes, business-logic flaws, bug bounty–style reporting |

---

## 🎯 What I Do

<table>
<tr>
<td width="50%" valign="top">

### 🌐 Web & API Security
- Authn / authz & access-control testing (IDOR, privesc, multi-tenant isolation)
- OAuth 2.0 / OIDC / SSO flows, session & JWT handling
- Injection, SSRF, XSS, deserialization, business-logic flaws
- Manual testing with Burp Suite + custom Python tooling

</td>
<td width="50%" valign="top">

### 🏢 Active Directory & Infrastructure
- AD enumeration & attack paths (Kerberoasting, AS-REP roasting, ACL abuse, delegation)
- Lateral movement, pivoting & privesc on Windows Server
- Network traffic analysis with Wireshark
- Kali Linux–based offensive workflow

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📱 Mobile Security
- Android app assessment via ADB
- Runtime instrumentation & hooking with Frida
- SSL pinning / root detection bypass
- Local storage & IPC review

</td>
<td width="50%" valign="top">

### 🔬 Reverse Engineering & Research
- Static analysis with IDA & Ghidra
- Open-source library auditing (npm, Go, Python)
- PoC development & coordinated disclosure via GHSA / CVE

</td>
</tr>
</table>

---

## 🛡️ Security Advisories

<div align="center">

| CVE | Advisory | Package | Severity | Summary |
|---|---|---|---|---|
| `CVE-2026-107719` | [GHSA-x937-hj6v-793p](https://github.com/advisories/GHSA-x937-hj6v-793p) | [fast-jwt](https://github.com/nearform/fast-jwt) (npm) ≤ 6.3.3 | ![Moderate](https://img.shields.io/badge/Moderate-4.2-FB8C00?style=flat-square) | JWT expiration bypass via verifier cache (CWE-613) |

</div>

<p align="center"><sub>Credited as reporter · <a href="https://github.com/advisories?query=credit%3ABlueN0r">All credited advisories →</a></sub></p>

---

## 🧰 Arsenal

<p align="center">
  <img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white" alt="Burp Suite">
  <img src="https://img.shields.io/badge/Frida-EF6456?style=for-the-badge&logoColor=white" alt="Frida">
  <img src="https://img.shields.io/badge/ADB-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="ADB">
  <img src="https://img.shields.io/badge/Ghidra-2B2B2B?style=for-the-badge&logoColor=white" alt="Ghidra">
  <img src="https://img.shields.io/badge/IDA_Pro-1B1B1B?style=for-the-badge&logoColor=white" alt="IDA Pro">
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" alt="Wireshark">
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white" alt="Kali Linux">
  <img src="https://img.shields.io/badge/Windows_Server-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows Server">
  <img src="https://img.shields.io/badge/Active_Directory-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" alt="Active Directory">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
</p>

---

## 📊 GitHub Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=BlueN0r&show_icons=true&count_private=true&hide_border=true&title_color=2DA44E&icon_color=0A66C2&text_color=c9d1d9&bg_color=0D1117" alt="stats">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=BlueN0r&layout=compact&hide_border=true&title_color=2DA44E&text_color=c9d1d9&bg_color=0D1117" alt="top langs">
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=BlueN0r&hide_border=true&background=0D1117&stroke=2DA44E&ring=0A66C2&fire=E00000&currStreakLabel=2DA44E&sideLabels=c9d1d9&dates=8b949e" alt="streak">
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=BlueN0r&theme=darkhub&no-frame=true&column=7&margin-w=8" alt="trophies">
</p>

---

## 📝 Writing

Write-ups, research notes and disclosure stories live on **[bluen0r.com](https://bluen0r.com)**.

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A66C2,100:0A0E27&height=120&section=footer&text=Want%20to%20talk%20security%3F&fontSize=20&fontColor=ffffff&fontAlignY=70&desc=reach%20out%20via%20bluen0r.com&descAlignY=90&descSize=14" alt="footer">
</p>
