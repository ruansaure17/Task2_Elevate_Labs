# Phishing Email Analysis

**Sample analyzed:** Screenshot of an email impersonating PayPal
**Subject line:** "[PayPal]: Your account access has been limited"

---

## Phishing Indicators Found

### 1. Suspicious sender domain
The sender address is `services@paypal-accounts.com`, **not** the official PayPal domain (`paypal.com`). Adding words like "accounts" to a lookalike domain is a classic **domain spoofing / typosquatting** technique.

### 2. Generic, impersonal greeting
The email opens with **"Dear PayPal customer"** instead of using the recipient's actual registered name. Legitimate PayPal communications typically address account holders by name.

### 3. Urgency and fear tactics
- "You have **24 hours** to solve the problem or your account will be **permanetly disabled**."
This creates artificial time pressure, a common social engineering tactic used to prevent the victim from thinking critically before acting.

### 4. Threat of loss of service/funds
The email states the user will lose access to "purchasing, and sending and receiving money," reinforcing fear of financial loss to push the victim toward immediate action.

### 5. Vague, unverifiable justification
"We believe that your account is in danger from unauthorized users" gives no real details, evidence, or transaction reference — a generic excuse used broadly across phishing campaigns.

### 6. Call-to-action button leading to an external/unverified link
The **"Confirm Your Information"** button is designed to redirect the victim to a fake login page that harvests credentials. The displayed button text gives no indication of the real destination URL — legitimate services usually allow you to verify the target URL only by hovering, which this screenshot does not disclose, itself a red flag when combined with the sender mismatch.

### 7. Spelling and grammar errors
- **"permanetly"** → should be "permanently"
- "Your PayPal account is limited, You have 24 hours..." → incorrect capitalization after a comma (should be lowercase "you")
- "PayPal's advantages like purchasing, and sending and receiving money" → awkward, non-native phrasing
These inconsistencies are uncommon in official corporate communications and are strong phishing indicators.

### 8. Visual impersonation of a trusted brand
The email uses the official PayPal logo and color scheme to appear legitimate, a common tactic to lower the victim's guard and increase perceived trustworthiness.

### 9. Request for account verification via email link
Legitimate financial institutions like PayPal do not ask users to "confirm all account details" through an emailed link — this is a classic **credential harvesting** attempt.

---

## Summary

| Indicator | Present? |
|---|:---:|
| Spoofed / lookalike sender domain | ✅ |
| Generic greeting (no personalization) | ✅ |
| Urgency / threat language | ✅ |
| Vague security justification | ✅ |
| Suspicious call-to-action link/button | ✅ |
| Spelling/grammar errors | ✅ |
| Brand impersonation (logo/colors) | ✅ |
| Request for sensitive account verification | ✅ |

**Conclusion:** This email displays multiple classic phishing characteristics — spoofed sender domain, urgency-driven language, grammatical errors, brand impersonation, and a suspicious verification link — and should be treated as a **phishing / credential-harvesting attempt**, not a legitimate communication from PayPal.
