# Contributing to ScamShield 🛡️

Thank you for helping protect families from online scams! Every contribution makes the internet safer.

## 🎯 **Ways to Contribute**

### 🔍 **Improve Scam Detection**
- **Add new scam patterns** you've encountered
- **Submit real scam examples** (anonymized)
- **Improve detection algorithms**
- **Expand threat databases**

### 🎨 **Enhance User Experience**
- **Mobile optimization**
- **Accessibility improvements** 
- **Multi-language support**
- **Better visual design**

### 📚 **Educational Content**
- **Safety tips and guides**
- **Real-world scam examples**
- **Training materials for families**
- **Age-appropriate content for children**

## 🚀 **Quick Start**

1. **Fork** the repository
2. **Create** your feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

## 🔒 **Adding Scam Patterns**

When submitting new scam patterns, please:

1. **Anonymize** any personal information
2. **Include context** about where/how the scam appears
3. **Explain the tactic** used by scammers
4. **Test** your patterns don't create false positives

Example:
```javascript
// New urgency pattern for fake delivery scams
const newPattern = {
    keywords: ['package undelivered', 'delivery failed', 'parcel waiting'],
    context: 'Fake shipping notifications',
    severity: 'high',
    explanation: 'Scammers impersonate delivery companies to steal personal info'
};
