# AWS Cloud SOC Pipeline – CloudTrail & CloudWatch Integration  

This project demonstrates how to build a lightweight **Security Operations Center (SOC) pipeline** on AWS using **CloudTrail, CloudWatch, and SNS**.  
The goal was to enable logging, detect critical security events, and alert the SOC team in real time.  

---

## ⚙️ Stages  

### **Stage 1 & 2: CloudTrail Setup**  
- Enabled **CloudTrail** across all AWS regions.  
- Stored logs securely in an **S3 bucket**.  
- Integrated CloudTrail with **CloudWatch Logs** for monitoring.  

📄 *Screenshots:* (stage1.png)(stage2.png)

---

### **Stage 3 & 4: Alerts & Notifications**  
- Created **CloudWatch rules** for critical security events:  
  - Root account logins.  
  - IAM policy/role changes.  
  - S3 bucket configuration changes.  
- Configured **SNS topics** to send real-time alerts via email.  

📄 *Screenshots:* (stage3.png) (stage4.png)) 

---

### **Stage 5: Testing**  
- Simulated suspicious events (e.g., S3 policy change, IAM update).  
- Verified that CloudWatch triggered SNS alerts and delivered them via email.  

📄 *Screenshots:* (stage5.png)

---

## ✅ Outcomes  
- Developed hands-on **cloud security monitoring skills**.  
- Built a real-time **alerting pipeline** for AWS account security.  
- Demonstrated how SOC teams can leverage AWS native tools for **cloud defense**.  

---

## 📂 Repository Structure  
