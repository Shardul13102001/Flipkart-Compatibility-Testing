# Flipkart Compatibility Testing Report 📋  

**📅 Test Date:** 22/02/2025  
**👤 Tested By:** Shardul  
**🔍 Testing Type:** Compatibility Testing  
**🛠 Objective:** Ensure Flipkart operates smoothly across different browsers & OS.  

## 🖥️ Test Environment:
| OS           | Browser          | Device        | Status |
|-------------|----------------|--------------|--------|
| Windows 11  | Google Chrome   | Desktop      | ✅ Pass |
| Windows 11  | Microsoft Edge  | Desktop      | ✅ Pass |
| macOS       | Google Chrome   | MacBook      | ✅ Pass |
| macOS       | Firefox         | MacBook      | ✅ Pass |
| iOS         | Google Chrome   | POCO X5 Pro  | ✅ Pass |

## 📌 Test Scenarios:
| Test Scenario          | Expected Result                     | Actual Result            | Status |
|------------------------|-----------------------------------|-------------------------|--------|
| Website loads          | Page loads without errors         | Page loads fine         | ✅ Pass |
| Navigation Menu        | Works smoothly                    | Works as expected       | ✅ Pass |
| Forms (Login, Signup)  | Submit without UI issues         | Works as expected       | ✅ Pass |
| Add-to-cart Function   | User can add 20 items            | Works as expected       | ✅ Pass |
| Pop-ups and Alerts     | Appear correctly                 | ❌ Issue found          | ❌ Fail |

## 🛠 Issues Found:
| Issue ID | OS  | Browser | Description | Severity | Status |
|---------|----|---------|-------------|---------|--------|
| 001     | iOS | Chrome  | Pop-ups appear off-screen or fail to close. | 🔴 High | 🟡 Open |

## 📌 Conclusion:
The Flipkart web app performs well on most platforms. However, a **critical pop-up issue on iOS Chrome** affects usability and needs a fix.

