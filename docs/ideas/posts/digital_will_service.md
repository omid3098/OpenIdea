---
date: 2025-08-12
categories:
  - Digital Estate Planning
  - Legal Technology
  - Services
  - Will
---

# Digital Will Service: Automated Legacy Management for the Digital Age

An email-based digital will service that monitors user activity through familiar communication channels and automatically executes digital wills when users pass away, ensuring final messages and estate instructions reach loved ones without requiring separate app registration.

**Why (the problem)**

- People don't know when they will die, making traditional will execution uncertain and dependent on others finding and acting on documents
- Traditional wills require trusted intermediaries who may be unavailable, unwilling, or unaware of the will's existence
- Digital assets (social media, cryptocurrencies, online accounts) are often lost forever when someone dies
- Families struggle to access deceased loved ones' digital belongings and final messages
- Young, tech-savvy professionals avoid estate planning due to complexity and perceived irrelevance

**What (the idea)**

An email-based digital platform that monitors user activity through periodic check-ins via email and SMS, automatically executing personalized wills when users are confirmed deceased. Users interact through their existing email accounts with no separate registration required - bringing peace of mind to the digital generation through familiar communication channels.

**How (v0 / MVP)**

The smallest version that proves value in 2-4 weeks:
- Email-based interface: users send formatted emails to create/update wills
- Weekly email check-ins with SMS backup for non-responders
- Simple will templates sent via email with structured format
- Manual verification process using public obituary searches
- Email delivery system for final messages after 7-day verification delay
- Phone number collection for SMS fallback during onboarding
- Test with 10-20 beta users using their existing email accounts

**How (tech/ops)**

- **Primary Interface**: Email parsing system with structured commands and templates
- **Secondary Interface**: SMS for check-ins and critical notifications
- **Optional Interface**: Progressive Web App (PWA) for users preferring app-like experience
- **Backend**: Node.js API, PostgreSQL database, AWS hosting with email processing
- **Security**: Email encryption, secure token-based authentication, SOC 2 compliance
- **Death verification**: API integration with obituary databases, manual review process
- **Check-in system**: Automated email with SMS escalation (weekly → daily → emergency contacts)
- **Email parsing**: Natural language processing for will updates and commands
- **Legal**: Partner with estate planning lawyers for will validity consultation
- **Data retention**: Encrypted storage with multiple geographic backups

**Prior art & investigations**

- **Google Inactive Account Manager**: Basic account deletion, no custom messaging or legal documents
- **Facebook Legacy Contact**: Social media only, limited customization
- **Traditional estate planning**: Costly ($500-5000), complex, paper-based
- **Digital vault services**: Focus on password storage, not automated execution
- **Email-based services**: Limited to simple reminders, no comprehensive will execution
- **Life insurance**: Reactive, requires beneficiary action

**Risks & open questions**

- **Legal validity**: Will digital wills be legally binding across jurisdictions? (Partner with lawyers)
- **False death detection**: How to prevent accidental will execution? (Multi-step verification process)
- **Email security**: How to protect sensitive final messages in email format? (Encryption, secure tokens)
- **Spam/phishing**: How to prevent malicious emails from affecting wills? (Authentication, verification)
- **Email deliverability**: What if check-in emails go to spam? (SMS backup, multiple channels)
- **Business sustainability**: Will people pay for service they hope never to use? (Focus on peace of mind value)
- **Technical failure**: What if the platform goes down permanently? (Email backup systems, partner execution)

**Next step & call to action**

Build the MVP email processing system with will creation via structured email templates and check-in system within 4 weeks, then recruit 20 beta testers from personal network using their existing email addresses to validate the core value proposition and user experience without requiring any new registrations.
