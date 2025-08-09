# TASK-2-Elevatelabs-
# Phishing Email Analysis — Citibank Suspicious Activity Scam

##  Objective
Analyze a phishing email claiming to be from Citibank and identify red flags using email header analysis and visual inspection.

##  Tools Used
- [MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- Web browser (hover link inspection)
- WHOIS Lookup (domain verification)

##  Steps Taken
1. **Obtained phishing email sample** — Fake Citibank "Suspicious Activity" alert.
2. **Checked sender address** — Found spoofed domain: `citibanksecuremygateway.com`.
3. **Analyzed email header** using MXToolbox:
   - SPF: FAIL
   - DKIM: FAIL
   - DMARC: FAIL
   - Sender IP traced to non-Citibank server.
4. **Checked language** — Urgent and fear-based wording.
5. **Checked branding** — Missing personalization and legal disclaimers.


### Phishing Email Example
![Citibank Phishing Email](citibank-phishing-email.png)

### Email Header Analysis (MXToolbox)
![Header Analysis Results](header-analysis.png)

##  Key Phishing Indicators
- Spoofed sender domain.
- Mismatched URL in link.
- Failed SPF/DKIM/DMARC authentication.
- Urgent security alert to provoke quick action.
- No customer name or proper Citibank signature.

##  Conclusion
The email is a clear phishing attempt aimed at stealing Citibank user credentials.  
By analyzing both the content and the header, we confirmed multiple security red flags.

---

