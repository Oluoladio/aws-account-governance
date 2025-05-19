# AWS Account Governance 

Securing AWS account is crucial to prevent breaches, unauthorized access, and compliance failures. Insecure AWS account configurations, such as overly permissive IAM policies and unmonitored root logins, are common causes of cloud security breaches. This lab documents building a secure AWS account governance strategy to enforce identity controls, centralize monitoring, automate compliance checks, and manage costs effectively.

---
# Why this Project
I chose this project to build hands-on expertise in services I was not really familiar with, especially CloudTrail, CloudWatch metric filters, Config rules via CloudFormation, and Security Hub. Each step taught me something valuable, from filtering raw log data to interpreting compliance findings. These challenges not only reinforced my cloud security knowledge but also improved my ability to troubleshoot and problem solving skills.

---

## 🎯 What I Learned

1. **Identity & Access**  
   - Enforced MFA and a strict password policy  
   - Learned how IAM Identity Center permission sets simplify multi-account access

2. **Logging & Monitoring**  
   - Deployed CloudTrail multi-region trails, integrated with CloudWatch Logs  
   - Wrote custom metric filters (e.g. root logins, policy changes) and wired them to alarms

3. **Compliance Automation**  
   - Used CloudFormation to deploy AWS Config managed rules  
   - Enabled Security Hub standards and interpreted findings to prioritize remediations

4. **Cost Management**  
   - Created AWS Budgets with email alerts  
   - Saved Cost Explorer reports to track service spend over time

---

## 🛠 Tools & AWS Services

- **IAM & Identity**: IAM Password Policy, MFA, IAM Identity Center  
- **Auditing & Alerts**: CloudTrail, CloudWatch Logs, Metric Filters, Alarms, SNS  
- **Compliance & Posture**: AWS Config (Recorder & Rules), Security Hub, Access Analyzer  
- **Cost Controls**: AWS Budgets, AWS Cost Explorer  
- **IaC**: CloudFormation templates for Config rules

---

## 🔗 Assessment & Reflection

As part of documenting my work and supporting my GRC portfolio, I completed an **[Assessment Worksheet](./docs/Assessment-Worksheet.pdf)**. This worksheet:

- **Verifies core controls**: Shows which security measures are in place and provides evidence  
- **Tracks compliance**: Lists AWS Config rule status and noncompliant resources for remediation planning  
- **Summarizes Security Hub posture**: Captures scores for Foundational and CIS standards  
- **Reflects on learnings**: Encourages me to analyze what went well, what gaps remain, and how these insights map to industry frameworks


---

## 🔗 Quick Links
- 📝 [Implementation Walkthrough](https://medium.com/@olaaoluwase/building-a-secure-aws-account-governance-baseline-f415dac01355)

---

Questions or Suggestions? 

If you found this helpful, consider sharing it with your network to spread awareness about the importance of secure AWS account governance. 

Thank you!

---
