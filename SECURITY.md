<div align="center">

# 🔐 Security Policy — Name Days

</div>

---

## Supported Versions

| Version | Supported |
|---|:---:|
| Latest (Google Play) | ✅ Active |
| Previous versions | ❌ No support |

Always use the latest version of Name Days available on Google Play to
ensure you have the most recent security fixes and improvements.

---

## Reporting a Vulnerability

If you discover a security vulnerability in Name Days, please report it
**responsibly** and **privately:**

> ⚠️ **Do not open a public GitHub issue for security vulnerabilities.**
> This could expose users before a fix is available.

### How to Report

1. Send an email to **[support@rdcapps.com](mailto:support@rdcapps.com)**
   with the subject line: `[SECURITY] Name Days Vulnerability Report`
2. Include in your report:
   - A clear description of the vulnerability
   - Steps to reproduce the issue
   - Potential impact assessment
   - Your suggested fix (if any)
   - Your Android version and Name Days version

### Response Timeline

| Step | Timeline |
|---|---|
| Acknowledgement | Within 72 hours |
| Assessment | Within 7 days |
| Fix release | Depends on severity |

We appreciate responsible disclosure and will credit researchers who help
keep Name Days secure (with their permission).

---

## Scope

| In Scope ✅ | Out of Scope ❌ |
|---|---|
| Name Days Android app | Google's advertising services |
| In-app purchase flows | Third-party service infrastructure |
| Widget security | Google Play / RevenueCat |
| Notification handling | Physical device attacks |

---

## Known Security Practices

- ✅ All network requests use **HTTPS** encryption
- ✅ No plaintext credentials stored
- ✅ Google AdMob advertising with UMP privacy checks; no ad requests for recognized ad-removal entitlements
- ✅ All preferences stored locally using Android SharedPreferences
- ✅ Purchase verification handled by RevenueCat (server-side)

---

*Thank you for helping keep Name Days and its users safe. 📅*
