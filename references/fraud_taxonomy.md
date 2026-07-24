# NRF Retail Fraud Taxonomy

**Version 2.0 | July 14, 2026**

Prepared by the National Retail Federation

---

## Table of Contents

- [Executive Summary](#executive-summary)
- [Introduction](#introduction)
- [The Retail Fraud Lifecycle](#the-retail-fraud-lifecycle)
- [Using the Taxonomy](#using-the-taxonomy)
- [Future Vision](#future-vision)
- [Taxonomy Elements](#taxonomy-elements)
  - [Schemes](#schemes)
  - [Tactics](#tactics)
  - [Channels](#channels)
  - [Techniques](#techniques)
- [Technique Details](#technique-details)
- [Mitigations](#mitigations)
- [Detection Sources](#detection-sources)
- [References](#references)

---

## Executive Summary

Retail fraud has evolved into a highly organized, adaptive, and technology-driven threat. What was once mostly opportunistic theft or isolated policy abuse has become coordinated organized criminal activity involving cyber intrusions, social engineering, account compromise, supply chain abuse, marketplace exploitation, and crowdsourced retail crime.

Today's fraud actors operate across both physical and digital environments. They exploit gaps between ecommerce platforms, stores, fulfillment systems, customer service operations, payment systems, and third-party marketplaces. These groups quickly adapt tactics, share knowledge online, use automation and anonymity tools, and often specialize in different stages of fraud operations. The growing overlap between cybercrime, financial fraud, and organized retail crime has created a complex threat landscape that is difficult to track and defend against using traditional methods alone.

At the same time, fraud is often defined and categorized differently across retailers, fraud teams, cybersecurity teams, investigators, vendors, and law enforcement. Similar schemes may be labeled inconsistently, creating operational inefficiencies, limiting intelligence sharing, complicating trend analysis, and slowing response efforts.

The retail industry needs a common operational framework and shared language to consistently identify, analyze, detect, and mitigate fraud activity.

---

## Introduction

Inspired by proven cybersecurity intelligence frameworks, the Taxonomy represents more than a catalog of fraud techniques. It is designed to serve as a foundational framework for the retail fraud ecosystem — enabling a more structured, intelligence-driven approach to fraud prevention and collaboration across the industry. It provides defenders with a repeatable methodology for describing fraud behaviors, identifying operational trends, evaluating security controls, improving detection capabilities, prioritizing investments, and strengthening cross-industry collaboration.

---

## The Retail Fraud Lifecycle

Retail fraud is rarely a single isolated action — most modern fraud operations involve a sequence of coordinated activities to achieve a financial objective. Fraud techniques are evolving faster than traditional defensive models can adapt. Automation tools, anonymization services, breached credential databases, proxy infrastructure, AI-generated content, and fraud-as-a-service communities have lowered the barrier and enabled sophisticated fraud activity.

Techniques that were once limited to highly capable actors are now widely accessible, repeatable, and rapidly shared across online criminal ecosystems. This evolution has created several critical challenges for the retail industry:

1. Fraud activity spans multiple business units and operational domains
2. Threats increasingly blend physical and digital channels
3. Traditional reactive methods are insufficient against coordinated, automated schemes

The Taxonomy models fraud activity across a typical fraud attack lifecycle of tactics. This lifecycle-oriented approach enables organizations to better understand:

- How fraud schemes develop
- How individual techniques connect together
- Where defensive controls are most effective
- How operational telemetry can be used to identify malicious behavior earlier in the fraud chain

By mapping fraud techniques to tactics, mitigations, and detection sources, organizations can move beyond reactive investigations toward more proactive and intelligence-driven fraud defense strategies.

---

## Using the Taxonomy

This framework is designed to support a broad range of stakeholders across the retail fraud ecosystem. While each group approaches fraud from a different operational perspective, a shared framework and common terminology help improve coordination, streamline investigations, strengthen detection capabilities, and support more effective risk management.

By aligning fraud operations, cybersecurity, engineering, retail operations, vendors, and law enforcement around a common structure, organizations can improve intelligence sharing, accelerate response efforts, and create more consistent fraud mitigation strategies across both physical and digital environments.

### Additional Use Cases

- **Support Threat Modeling and Exercises:** Simulate realistic fraud scenarios and operational workflows to improve preparedness and incident response coordination.
- **Prioritize Security Investments:** Evaluate defensive coverage against known fraud techniques to better allocate resources toward the highest-risk threats and operational gaps.
- **Enhance Information Sharing:** Enable more effective collaboration between retailers, fraud teams, cybersecurity professionals, solution providers, and law enforcement through structured intelligence sharing.
- **Evaluate Technologies and Vendors:** Assess products, detection platforms, and fraud prevention capabilities against a standardized set of observed fraud techniques and operational behaviors.
- **Testing:** Simulate fraud scenarios to test detection and response capabilities.

---

## Future Vision

The long-term vision is to establish a scalable industry framework that not only supports fraud investigations and intelligence sharing today, but also enables future operational capabilities such as:

- Structured threat intelligence exchange
- Analytical mapping
- Detection engineering
- Fraud simulation and testing
- Cross-industry fraud trend analysis

Through continued collaboration, the NRF Retail Fraud Taxonomy aims to strengthen the retail industry's collective ability to identify, disrupt, and defend against increasingly sophisticated fraud operations.

For questions or comments, please contact:
- Caroline Reppert, National Retail Federation: reppertc@nrf.com
- Jon Tran, Chertoff Group: jon.tran@chertoffgroup.com

---

## Taxonomy Elements

The Retail Fraud Taxonomy is built around a structured set of core elements that help organizations consistently classify, analyze, and communicate fraud activity.

| Term | Description |
|------|-------------|
| **Schemes** | The overarching fraud objective or operation, typically composed of multiple tactics and techniques working together to achieve monetization or exploitation goals. |
| **Tactics** | The high-level objectives or goals adversaries aim to achieve during a stage of a fraud scheme or operation. |
| **Channels** | The operational or transactional environments through which fraud activity is conducted, exploited, or targeted. |
| **Techniques** | The specific methods, actions, or behaviors used by adversaries to execute a tactic or advance a fraud scheme. |
| **Mitigations** | Security controls, operational processes, or technologies designed to prevent, disrupt, or reduce the effectiveness of fraud techniques. |
| **Detection Sources** | Telemetry, logs, behavioral indicators, or data sources that can be used to identify, investigate, or monitor fraud activity. |

---

### Schemes

The overarching fraud objective or operation, typically composed of multiple tactics and techniques working together to achieve monetization or exploitation goals.

| Scheme | Description |
|--------|-------------|
| **Gift Card Fraud** | Tampering, generating, stealing, or otherwise using a gift card in an unauthorized manner to extract resources. |
| **Account Takeover** | Gaining unauthorized access to a victim's account. |
| **Return Fraud** | Deliberate exploitation of return and refund policies to gain monetary value, store credit, gift cards, or replacement merchandise. |

---

### Tactics

The high-level objectives or goals adversaries aim to achieve during a stage of a fraud scheme or operation. Not all tactic phases are required for a scheme — actors may specialize in each phase.

| Tactic | Description |
|--------|-------------|
| **Pre-Compromise** | Operations that occur prior to compromise. |
| **Initial Access** | Stealing, generating, confirming, or otherwise obtaining a legitimate gift card, account, or other resource. |
| **Defense Evasion** | Techniques that are used to bypass security measures and fraud controls. |
| **Control** | Physically or digitally gaining control of a resource from a customer or retailer. |
| **Monetization** | Converting illicitly gathered resources into liquid funds or an item that can be converted into liquid funds. |

---

### Channels

The operational or transactional environments through which fraud activity is conducted, exploited, or targeted.

#### Analog (Physical) Channels

Techniques conducted outside of computer networks that rely on physical actions, in-person interaction, or tangible objects. These techniques often involve manipulating or exploiting physical items rather than digital systems, and typically include direct physical interaction, including handling physical objects, creating fraudulent materials, or requiring physical proximity to execute the activity.

**Analog Techniques:** Reconnaissance · Third Party Supplier Manipulation · Fake Receipt Generation · Shoplifting · Gift Card Extortion · Check Gift Card Balance · Check Gift Card Balance: Phone Verification · Check Gift Card Balance: In Store Gift Card Verification · Digital Wallet Apps · Item Manipulation · Gift Card Return · Gift Card Merge · Gift Card Tampering · Gift Card Redemption · Wardrobing · Item Manipulation: Harvesting · Item Manipulation: Switch Merchandise · Returns Process Exploitation · Returns Process Exploitation: Shipping Manipulation · Returns Process Exploitation: Damaged Shipment · Resale · Resale: Drop Shipping · Resale: Unwitting Buyer · Marketplace Exploitation · Marketplace Exploitation: Fraudulent Delivery · Marketplace Exploitation: Fraudulent Seller · Checkout · Checkout: Point of Sale · Checkout: Guest Services · Fraudulent Refund · Gift Cards as Defense Evasion

#### Digital Channels

Techniques executed through digital systems or networks that do not require physical interaction or direct human contact. These techniques rely on remote access, code execution, system manipulation, or network exploitation to facilitate fraud activity.

**Digital Techniques:** Reconnaissance · Third Party Supplier Manipulation · Acquire Database · Gift Card Number Generation · Password Reset · Proxy Abuse · VOIP Abuse · Digital Wallet Apps · Cryptocurrency · Gift Cards as Defense Evasion · Gift Card Extortion · Check Gift Card Balance · Check Gift Card Balance: Application · Check Gift Card Balance: Phone Verification · Fake Pages · Valid Accounts · Valid Accounts: Fraudulent Account · Valid Accounts: Fraudulent Account Update · Valid Accounts: Authorized Account Abuse · Credential Stuffing · Gift Card Return · Gift Card Merge · Gift Card Redemption · Loyalty Points Abuse · Wardrobing · Item Manipulation · Item Manipulation: Harvesting · Item Manipulation: Switch Merchandise · Returns Process Exploitation · Returns Process Exploitation: Shipping Manipulation · Returns Process Exploitation: Damaged Shipment · Resale · Resale: Drop Shipping · Resale: Unwitting Buyer · Marketplace Exploitation · Marketplace Exploitation: Fraudulent Delivery · Marketplace Exploitation: Fraudulent Seller · Checkout · Checkout: Online/Web Mobile · Fraudulent Refund · Refund: Refund to Gift Card · Refund: Double Refund · Refund: Non-Receipted Returns · Fake Receipt Generation

#### Social Engineering

Techniques that exploit human behavior, trust, or social expectations to gain access, information, or assets. These techniques can occur through digital or physical channels and rely on deception, manipulation, coercion, or persuasion to facilitate fraud activity.

**Social Engineering Techniques:** Reconnaissance · Fake Receipt Generation · Insider Recruitment · Impersonation of Retail Employee · Gift Card Extortion · Check Gift Card Balance · Check Gift Card Balance: Phone Verification · Check Gift Card Balance: In Store Gift Card Verification · Gift Card Return · Gift Card Redemption · Item Manipulation · Item Manipulation: Harvesting · Item Manipulation: Switch Merchandise · Returns Process Exploitation · Returns Process Exploitation: Shipping Manipulation · Returns Process Exploitation: Damaged Shipment · Resale · Resale: Drop Shipping · Resale: Unwitting Buyer · Checkout · Checkout: Point of Sale · Checkout: Guest Services · Fraudulent Refund · Refund: Refund to Gift Card · Refund: Double Refund · Refund: Non-Receipted Returns

---

### Techniques

The specific methods, actions, or behaviors used by adversaries to execute a tactic or advance a fraud scheme.

| Pre-Compromise | Initial Access | Defense Evasion | Control | Monetization |
|---|---|---|---|---|
| Reconnaissance | Gift Card Extortion | Gift Card Extortion | Valid Accounts | Resale |
| Fake Pages | Valid Accounts | VOIP Abuse | Authorized Account Abuse | Drop Shipping |
| Acquire Database | Check Gift Card Balance | Digital Wallet Apps | Fraudulent Account | Unwitting Buyer |
| Gift Card Number Generation | Application | Cryptocurrency | Fraudulent Account Update | Checkout |
| Password Reset | Phone Verification | Gift Cards as Defense Evasion | Gift Card Return | Point of Sale |
| Proxy Abuse | In Store Gift Card Verification | — | Gift Card Merge | Guest Services |
| Third Party Supplier Manipulation | Valid Accounts | — | Gift Card Tampering | Online/Web Mobile |
| Fake Receipt Generation | Fraudulent Account | — | Gift Card Redemption | Fraudulent Refund |
| Insider Recruitment | Fraudulent Account Update | — | Wardrobing | Refund to Gift Card |
| Impersonation of Retail Employee | Credential Stuffing | — | Loyalty Points Abuse | Double Refund |
| — | Insider Recruitment | — | Item Manipulation | Non-Receipted Returns |
| — | Impersonation of Retail Employee | — | Harvesting | Cryptocurrency |
| — | Shoplifting | — | Switch Merchandise | — |
| — | — | — | Returns Process Exploitation | — |
| — | — | — | Damaged Shipment | — |
| — | — | — | Shipping Manipulation | — |
| — | — | — | Marketplace Exploitation | — |
| — | — | — | Fraudulent Delivery | — |
| — | — | — | Fraudulent Seller | — |

---

## Technique Details

### Reconnaissance | FT1001

**Tactic:** Pre-Compromise  
**Channels:** Analog · Digital · Social Engineering  
**Schemes:** Gift Card Fraud · Account Takeover

**Description**

Fraudsters actively or passively gather information that can be used to support operations. Information may include details of the victim organization, infrastructure, or staff/personnel. This information can be leveraged by the fraudster to aid in other phases of the adversary lifecycle, such as using gathered information to plan and execute future operations. Threat actors will attempt to create accounts, wish lists, and other related assets using lists of usernames and credentials from breached databases. If the attempt fails, it signals to the actor that the account already exists and is a good candidate for credential stuffing.

**Mitigations**

- **FM1006 — Training and Awareness:** At physical locations, train employees to identify and report suspicious individuals to security.
- **FM1016 — Security Guards:** At physical locations, use a security guard to identify and deter reconnaissance attempts.
- **FM1018 — Software Configuration:** Fully decommission obsolete login software that may not be protected by current security protocols. Redirect login requests to obsolete software to follow the approved login flow.

**Detection Opportunities**

- **FD1007 — Network Traffic Attributes:** Automated network reconnaissance will scan internet resources in a manner that a normal user typically will not. Monitor for connections to suspicious ports and traversal to suspicious directories such as www.mywebsite.com/admin or www.mywebsite.com/phpadmin.
- **FD1009 — Online Identities:** When account creation has limited restrictions, fraudsters often create test accounts to develop automation, test fraud techniques, or validate stolen credentials. These accounts frequently use fake identity information and can provide insight into an actor's methods and intent. Organizations should monitor account creation activity for abnormal behavior, as fraudsters may also use registration flows to determine whether accounts already exist before attempting credential-based attacks.
- **FD1002 — Video Surveillance Systems:** At physical locations, use video surveillance to identify and report suspicious individuals to security.

**References:** MITRE ATT&CK

---

### Fake Pages | FT1003

**Tactic:** Pre-Compromise  
**Channels:** Digital  
**Schemes:** Gift Card Fraud · Account Takeover

**Description**

The fraudster creates a web page that may mimic a legitimate website to fool victims into divulging information. This website may visually appear to be legitimate or have a URL that is similar to the legitimate website. One example is to register a domain that looks or sounds like a legitimate website — if www.legitimatewebsite.com was the target, the fraudster may register www.legitimatewebsite.io or www.legitwebsite.com. Using this along with similar visual elements, the fraudster can fool victims into divulging information such as account name and password.

**Mitigations**

- **FM1007 — Website Takedown Requests:** When a fake page is identified, file a takedown request with the Website Host and DNS Registrar.
- **FM1013 — DNS Registration:** Identify potential URLs that may be mistaken for the legitimate website and register them so they cannot be used by fraudsters.

**Detection Opportunities**

- **FD1007 — Network Traffic Attributes:** Monitor domain registration, certificate transparency logs, and phishing sites to identify sites established with your branding but designed to fool your customers into divulging information.

**References:** Industry Partner Collaboration

---

### Acquire Database | FT1004

**Tactic:** Pre-Compromise  
**Channels:** Digital  
**Schemes:** Gift Card Fraud · Account Takeover

**Description**

Fraudster will, through legitimate or illegal means, acquire databases that may be used for future operations. These databases may range from legitimate marketing information sold by reputable companies to data stolen from victims. Examples of databases that can be acquired include account databases, marketing information, gift card numbers, and personally identifiable information (PII).

**Mitigations**

- **FM1014 — Password Policy:** Encourage using strong passwords with sufficient length and complexity. Discourage reusing passwords.

**Detection Opportunities**

- **FD1009 — Online Identities:** Subscribe to breach databases and monitor logins for usage of known or publicly compromised credentials.

**References**
- MITRE ATT&CK: https://attack.mitre.org/techniques/T1650/
- Top 10 Digital Commerce Account Risks & How to Mitigate Them: https://www.forter.com/blog/rh-isac-account-risk-mitigation/
- Authentication and Access to Financial Institution Services and Systems: https://www.ffiec.gov/guidance/Authentication-and-Access-to-Financial-Institution-Services-and-Systems.pdf

---

### Gift Card Number Generation | FT1005

**Tactic:** Pre-Compromise  
**Channels:** Digital  
**Schemes:** Gift Card Fraud

**Description**

Fraudster uses an algorithm or brute force to generate gift card numbers that can potentially be legitimate. This can be conducted by predicting or acquiring the algorithm used to generate gift card numbers and creating them. This can be used with Check Gift Card Balance to identify legitimate gift cards with funds for future use.

**Mitigations**

- **FM1011 — Brute Force Resistant Gift Card Numbers:** Generate long and complicated gift card numbers that are resistant to prediction.

**Detection Opportunities**

This technique cannot be easily detected by organizational controls due to it occurring outside of the organization's scope.

**References:** Industry Partner Collaboration

---

### Password Reset | FT1006

**Tactic:** Pre-Compromise · Initial Access  
**Channels:** Digital  
**Schemes:** Account Takeover

**Description**

Actors abuse the password reset functionality to verify whether an account exists on a website. If the website provides feedback that indicates the account does exist, the actor then proceeds to attempt a login using exposed credentials. Actors may also compromise the victim's email account and submit a password reset request to the targeted site, allowing access to the victim's account.

**Mitigations**

- **FM1019 — Neutral Feedback:** Do not provide feedback that notifies an actor if the account exists or does not exist on the website.
- **FM1020 — Customer Notification:** Notify all available contacts on the account when a password is reset.

**Detection Opportunities**

- **FD1003 — Behavioral Attributes:** Monitor password reset endpoints for abnormal behavior.
- **FD1006 — Velocity Attributes:** Identify automated attempts to validate a credential list by volume of attempts.

**References:** Industry Partner Collaboration

---

### Proxy Abuse | FT1007

**Tactic:** Pre-Compromise  
**Channels:** Digital  
**Schemes:** Account Takeover

**Description**

Actors abuse legitimate or illegal proxy services that act as an intermediary for requests from clients seeking resources from other servers, effectively masking the fraudster's IP address or other network attributes. Examples include commercial VPN services, proxies through hosting providers, residential proxies, compromised machines such as botnets and malware infected hosts, and TOR services.

**Mitigations**

- **FM1008 — Behavior Prevention:** Block traffic from known proxies, TOR exit nodes and infected machines.

**Detection Opportunities**

- **FD1007 — Network Traffic Attributes:** Aggregate IP addresses to identify the common carriers / autonomous system numbers. Establish normal and abnormal behavior for traffic originating from those networks.

**References:** MITRE ATT&CK: https://attack.mitre.org/techniques/T1090/

---

### Third Party Supplier Manipulation | FT1008

**Tactic:** Pre-Compromise  
**Channels:** Analog · Digital  
**Schemes:** Return Fraud

**Description**

A supplier or manufacturer knowingly produces and distributes nongenuine goods with the intent (or willful disregard of the likelihood) that these items will be returned to legitimate retailers for refunds, store credit, or replacements, thereby monetizing counterfeits via the retailer's returns channel and shifting losses to the merchant. This scheme often leverages high demand SKUs and categories with permissive return policies to maximize refund yield and minimize detection.

**Mitigations**

- **FM1208 — Law Enforcement:** Report known counterfeiters or other confirmed illegal activity to Law Enforcement for action.

**Detection Opportunities**

- **FD1012 — Controlled Purchase:** Purchase items from Third Party Supplier to identify indicators of fraud.
- **FD1010 — Transaction Data:** Identify indicators of counterfeit or fake items such as poor packaging or labeling with incorrect or repeating serial numbers.
- **FD1004 — Time-Based Attributes:** Identify returns that happen quickly, ranging from a few minutes from purchase to a day depending on fraudster behavior.
- **FD1006 — Velocity Attributes:** Fraudsters will attempt a high number of returns at once.

**References:** Industry Partner Collaboration

---

### Fake Receipt Generation | FT1009

**Tactic:** Pre-Compromise  
**Channels:** Analog · Digital  
**Schemes:** Return Fraud

**Description**

A fraudulent receipt created by a fraudster that appears legitimate. The primary purpose is to fabricate proof of purchase or transaction to deceive systems, individuals, or institutions and often to claim refunds, reimbursements, or validate false returns.

**Mitigations**

- **FM1008 — Behavior Prevention:** Validate the receipt with store records (preferably by electronic scan). Do not permit use of receipts without validation of store-controlled records.
- **FM1006 — Training and Awareness:** Identify fake receipts, which may appear visually different.

**Detection Opportunities**

- **FD1010 — Transaction Data:** Identify refunds that do not have proper proof of purchase.
- **FD1006 — Velocity Attributes:** A large volume of receipts may obscure or overlap with a genuine receipt. A large number of items on the receipt.

**References:** Industry Partner Collaboration

---

### Insider Recruitment | FT1010

**Tactic:** Pre-Compromise · Initial Access  
**Channels:** Social Engineering  
**Schemes:** Return Fraud

**Description**

A form of social engineering, this technique involves fraudsters enlisting employees, typically in customer service, logistics, or returns processing, to help execute fraudulent return schemes from within the organization. These insiders are incentivized with payments or a share of the refund value to manipulate internal systems, such as marking items as undelivered, falsifying damage claims, or overriding verification protocols. Recruitment often begins on social platforms like Telegram, LinkedIn, or even customer service contact channels with communication quickly shifting to encrypted channels to avoid detection.

**Mitigations**

- **FM1006 — Training and Awareness:** Train employees to recognize recruitment attempts and remind them of their role, ethical agreements, and consequences.
- **FM1022 — Escalation:** Require secondary approvals for sensitive actions that can be taken on behalf of customers to limit damage an insider could perform.

**Detection Opportunities**

- **FD1003 — Behavioral Attributes:** Monitor employees' interactions with other employees and discussions regarding potential payment or other ways to receive value for fraudulent activity. Insiders may attempt to hire employees to support their activity. For call center or chat-based customer service operations, identify customer attempts to offer money, jobs, or other reimbursement for actions taken at the retail store.
- **FD1002 — Video Surveillance Systems:** Use video surveillance system to identify and record suspicious activity for correlation as fraudsters may commit actions over a long period.

**References:** Industry Partner Collaboration

---

### Impersonation Of Retail Employee | FT1011

**Tactic:** Pre-Compromise · Initial Access  
**Channels:** Social Engineering  
**Schemes:** Return Fraud

**Description**

A form of social engineering in returns fraud involving fraudsters posing as store staff, either physically, over the phone, or online, to manipulate return processes and bypass verification protocols. They may dress like employees, use fake IDs, or spoof contact details to gain trust and access, often requesting unauthorized refunds or overrides. In more advanced schemes, real employees are recruited to impersonate others or approve fraudulent returns.

**Mitigations**

- **FM1021 — Identity Verification:** Establish identification and authentication procedures to prove someone is an employee in person or remotely.
- **FM1006 — Training and Awareness:** Train employees in stores to recognize impersonation attempts, posing as an employee, someone from headquarters, or a legitimate third party such as contractors.
- **FM1022 — Escalation:** Require secondary approvals for sensitive actions that the fraudster may ask employees to perform.

**Detection Opportunities**

- **FD1003 — Behavioral Attributes:** Monitor employees' interactions with other employees and discussions regarding potential payment or other ways to receive value for fraudulent activity. For call center or chat-based customer service operations, identify customer attempts to offer money, jobs, or other reimbursements for actions taken at the retail store.
- **FD1002 — Video Surveillance Systems:** Use video surveillance systems to identify and record suspicious activity for correlation. Correlate suspicious individuals across multiple stores to identify fraudsters.

**References:** Industry Partner Collaboration

---

### Shoplifting | FT1101

**Tactic:** Initial Access  
**Channels:** Analog  
**Schemes:** Gift Card Fraud

**Description**

Taking items from a store without paying for them. Shoplifting can range from concealing items in personal clothing or bags to swapping price tags to make items appear cheaper. Items shoplifted to support fraud are typically high value, small in size and easy to resell. Examples of commonly stolen items to support fraud are Gift Cards, Electronics, and Luxury Goods.

**Mitigations**

- **FM1017 — Satchel Control:** Control the size and type of satchels that are permitted inside the store.
- **FM1005 — Anti-theft Prevention:** Additional physical protection of products from theft such as locked shelving, containers, and vending machines, and storing items behind checkout counter.
- **FM1016 — Security Guards:** At physical locations, use security guards to identify and deter shoplifting.

**Detection Opportunities**

- **FD1001 — Anti-theft security tags:** Attach a device to items that will cause an alarm if removed from the store without authorization.
- **FD1002 — Video Surveillance Systems:** Monitor video feeds for suspicious activity around high value items.

**References:** Detecting and Reporting the Illicit Financial Flows Tied to Organized Theft Groups (OTG) and Organized Retail Crime (ORC): https://www.acams.org/en/media/document/29436

---

### Gift Card Extortion | FT1102

**Tactic:** Initial Access · Control  
**Channels:** Analog · Digital · Social Engineering  
**Schemes:** Gift Card Fraud

**Description**

The fraudster obtains gift cards through coercion of a victim. This can involve threats of violence, property damage, harm to reputation, or unwarranted government action. A fraudster may pretend to be a representative of the government to coerce a victim through a fear response, convincing them to purchase gift cards with their own funds. Another common scam involves a fraudster pretending to be a relative being held against their will, convincing the victim to purchase gift cards as restitution or a bribe.

**Mitigations**

- **FM1001 — Primary Gift Card Lock In:** When a gift card is purchased, lock the gift card into the identity of the purchaser. Do not allow another person to use the gift card without identity verification or authentication.
- **FM1002 — Login Required:** Require an account before permitting purchase of or transfer of a gift card.
- **FM1012 — Gift Card Purchase Limit:** Enforce limits of quantity and/or the value that may be purchased by an interaction or person.
- **FM1006 — Training and Awareness:** Consumer fraud awareness and education campaigns, signage, pop-ups, and other forms of communication.

**Detection Opportunities**

- **FD1006 — Velocity Attributes:** Monitor the purchase of gift cards by value and quantity from an individual by a predetermined value and/or time frame.
- **FD1003 — Behavioral Attributes:** Monitor for out-of-character purchases of an individual and their lifestyle.

**References**
- Detecting and Reporting the Illicit Financial Flows Tied to Organized Theft Groups (OTG) and Organized Retail Crime (ORC): https://www.acams.org/en/media/document/29436
- Avoiding and Reporting Gift Card Scams: https://consumer.ftc.gov/articles/avoiding-and-reporting-gift-card-scams#commonscams

---

### Check Gift Card Balance | FT1103

**Tactic:** Initial Access  
**Channels:** Analog · Digital · Social Engineering  
**Schemes:** Gift Card Fraud

**Description**

The fraudster may abuse legitimate functions to confirm a gift card is active and has funds. To reduce overhead, retailers may have autonomous systems for gift card owners and recipients to check if their gift card is usable and has value.

**Sub-Techniques:** Application (FT1103.001), Phone Verification (FT1103.002), In Store Gift Card Verification (FT1103.003)

**Mitigations**

- **FM1002 — Login Required:** Require authentication before displaying gift card status or value.
- **FM1003 — Access Code Required:** Require an access code that is separate from the gift card number before revealing the status and funds on the gift cards.
- **FM1209 — Online Location Data:** Some physical locations should not be able to check gift card balance. Prevent the ability to check gift card status and funds based on locations.
- **FM1210 — Phone Number:** Automatically block phone numbers related to VOIP services and phone numbers that have been known to be used to perpetrate fraud.

**Detection Opportunities**

- **FD1007 — Network Traffic Attributes:** Monitor for Network Traffic Attributes such as IP Address, DNS Name, ASN, and other digital location attributes especially if some of these sources have known fraud activity or have a high risk of fraud activity.
- **FD1004 — Time-Based Attributes:** Based on the location of your operations, monitor for activities that occur during off hours.
- **FD1005 — Device Attributes:** Monitor device factors such as device type, user agent string, operating system, cookies.
- **FD1006 — Velocity Attributes:** Monitor for number of requests based on a predetermined number of requests over a set amount of time.
- **FD1008 — VOIP Attribute:** Monitor for use of VOIP numbers that are not tied to a physical landline or mobile phone.

**References:** Industry Partner Collaboration

---

#### Check Gift Card Balance: Application | FT1103.001

**Tactic:** Initial Access  
**Channels:** Digital  
**Schemes:** Gift Card Fraud

**Description**

The fraudster may iteratively probe Web Applications using built-in functions to confirm the gift card is active and has funds. The fraudster may use gift card numbers that are generated by brute force guessing, purchased from a source, or gathered from victims.

**Mitigations**

- **FM1002 — Login Required:** Require authentication before displaying gift card status or value.
- **FM1003 — Access Code Required:** Require an access code that is separate from the gift card number before revealing the status and funds on the gift cards.
- **FM1209 — Online Location Data:** Some physical locations should not be able to check gift card balance. Prevent the ability to check gift card status and funds based on locations.

**Detection Opportunities**

- **FD1007 — Network Traffic Attributes:** Monitor for Network Traffic Attributes such as IP Address, DNS Name, ASN, and other digital location attributes.
- **FD1004 — Time-Based Attributes:** Based on the location of your operations, monitor for activities that occur during off hours.
- **FD1005 — Device Attributes:** Monitor device factors such as device type, user agent string, operating system, cookies.
- **FD1006 — Velocity Attributes:** Monitor for number of requests based on a predetermined number of requests over a set amount of time.

**References:** Industry Partner Collaboration

---

#### Check Gift Card Balance: Phone Verification | FT1103.002

**Tactic:** Initial Access  
**Channels:** Analog · Digital · Social Engineering  
**Schemes:** Gift Card Fraud

**Description**

The fraudster may use a retailer-provided phone service to confirm a gift card is active and has funds. The fraudster may use gift card numbers that are generated by brute force guessing, purchased from a source, or gathered from victims.

**Mitigations**

- **FM1003 — Access Code Required:** Require an access code that is separate from the gift card number before revealing the status and funds on the gift cards.
- **FM1008 — Behavior Prevention:** Automatically block phone numbers related to VOIP services and phone numbers that have been known to be used to perpetrate fraud.

**Detection Opportunities**

- **FD1004 — Time-Based Attributes:** Based on the location of your operations, monitor for activities that occur during off hours.
- **FD1008 — VOIP Attribute:** Monitor for use of VOIP numbers that are not tied to a physical landline or mobile phone.

**References:** Industry Partner Collaboration

---

#### Verification | FT1103.003

**Tactic:** Initial Access  
**Channels:** Analog  
**Schemes:** Gift Card Fraud

**Description**

The fraudster uses legitimate functions inside a bricks-and-mortar store to verify status of gift cards. The fraudster may use Kiosks, Checkout, or Customer service to verify legitimacy of a gift card.

**Mitigations**

- **FM1003 — Access Code Required:** Require an access code that is separate from the gift card number before revealing the status and funds on the gift cards.

**Detection Opportunities**

- **FD1006 — Velocity Attributes:** Monitor for gift cards a person is attempting to verify.

**References:** Industry Partner Collaboration

---

### Valid Accounts | FT1104

**Tactic:** Initial Access · Defense Evasion · Control  
**Channels:** Digital  
**Schemes:** Gift Card Fraud · Account Takeover · Return Fraud

**Description**

The fraudster may obtain, create and abuse accounts to gain access, elevate access, or control a resource. Since these credentials are generally legitimate, they may be used to bypass access controls in place to protect resources. This can also be used to achieve persistence in a system. For example, if a fraudster gains control over a loyalty account, the fraudster can control the spending of loyalty points to buy items or use gift cards tied to the accounts.

**Sub-Techniques:** Fraudulent Account (FT1104.001), Fraudulent Account Update (FT1104.002), Authorized Account Abuse (FT1104.003)

**Mitigations**

- **FM1004 — Multi-Factor Authentication:** Use multiple forms of authentication such as username and password paired with a One-time Passcode before permitting access. Use passkeys linked to a known physical device as authentication factor. Require identity verification upon detection of access requests that are significantly different than what is expected for the individual.
- **FM1014 — Password Policy:** Encourage using strong passwords with sufficient length and complexity. Discourage reusing passwords.

**Detection Opportunities**

- **FD1007 — Network Traffic Attributes:** Monitor for Network Traffic Attributes such as IP Address, DNS Name, ASN, and other digital location attributes.
- **FD1004 — Time-Based Attributes:** Based on the location of your operations, monitor for activities that occur during off hours.
- **FD1005 — Device Attributes:** Monitor device factors such as device type, user agent string, operating system, cookies.
- **FD1003 — Behavioral Attributes:** Monitor for access attempts and purchases that are significantly different from known good behavior for each customer.

**References**
- MITRE ATT&CK: https://attack.mitre.org/techniques/T1078/
- Top 10 Digital Commerce Account Risks & How to Mitigate Them: https://www.forter.com/blog/rh-isac-account-risk-mitigation/
- NIST Digital Identity Guidelines 800-63: https://pages.nist.gov/800-63-3

---

#### Valid Accounts: Fraudulent Account | FT1104.001

**Tactic:** Pre-Compromise · Initial Access · Control  
**Channels:** Digital  
**Schemes:** Gift Card Fraud · Account Takeover · Return Fraud

**Description**

The fraudster uses a legitimate resource to create an account for malicious usage. These accounts may be used for reconnaissance and to probe the defenses of the victim's applications. Using this as a foothold the fraudster may gather information on the application itself such as naming convention, loyalty points, and other information that may be used to monetize the account.

**Mitigations**

- **FM1004 — Multi-Factor Authentication:** Before permitting account changes, use multiple forms of authentication. If relevant, send confirmatory message to the original contact fields.

**Detection Opportunities**

- **FD1007 — Network Traffic Attributes:** Monitor for Network Traffic Attributes such as IP Address, DNS Name, ASN, and other digital location attributes.
- **FD1004 — Time-Based Attributes:** Based on the location of your operations, monitor for activities that occur during off hours.
- **FD1005 — Device Attributes:** Monitor device factors such as device type, user agent string, operating system, cookies.
- **FD1006 — Velocity Attributes:** Monitor for accounts that are created quickly in succession from the same location or with similar features.

**References:** Top 10 Digital Commerce Account Risks & How to Mitigate Them: https://www.forter.com/blog/rh-isac-account-risk-mitigation/

---

#### Valid Accounts: Fraudulent Account Update | FT1104.002

**Tactic:** Pre-Compromise · Initial Access  
**Channels:** Digital  
**Schemes:** Gift Card Fraud · Account Takeover · Return Fraud

**Description**

The fraudster makes a change to an account without the knowledge of the account holder. For example, a fraudster convinces a helpdesk to update the phone number of a legitimate account to one they control, then uses this to reset the password and control the victim's account.

**Mitigations**

- **FM1004 — Multi-Factor Authentication:** Use multiple forms of authentication before permitting access. Require identity verification upon detection of access requests that are significantly different than what is expected. Send confirmatory message to the original contact fields.

**Detection Opportunities**

- **FD1007 — Network Traffic Attributes:** Monitor for Network Traffic Attributes such as IP Address, DNS Name, ASN, and other digital location attributes.
- **FD1004 — Time-Based Attributes:** Based on the location of your operations, monitor for activities that occur during off hours.
- **FD1005 — Device Attributes:** Monitor device factors such as device type, user agent string, operating system, cookies.
- **FD1006 — Velocity Attributes:** Monitor for accounts that are created quickly in succession from the same location or with similar features.
- **FD1009 — Online Identities:** Monitor for account creations with suspicious names that do not appear legitimate (e.g., ABCD, AAA, QAZ).

**References:** Top 10 Digital Commerce Account Risks & How to Mitigate Them: https://www.forter.com/blog/rh-isac-account-risk-mitigation/

---

#### Valid Accounts: Authorized Account Abuse | FT1104.003

**Tactic:** Defense Evasion  
**Channels:** Digital  
**Schemes:** Gift Card Fraud · Account Takeover

**Description**

The fraudster persuades a legitimate customer to grant access to their account, enabling the fraudster to leverage a seasoned profile with an established purchase history and associated metadata. This tactic helps bypass or weaken fraud detection controls.

**Mitigations**

- **FM1004 — Multi-Factor Authentication:** Before permitting account changes, use multiple forms of authentication. If relevant, send confirmatory message to the original contact fields.

**Detection Opportunities**

- **FD1007 — Network Traffic Attributes:** Monitor for Network Traffic Attributes such as IP Address, DNS Name, ASN, and other digital location attributes.
- **FD1004 — Time-Based Attributes:** Based on the location of your operations, monitor for activities that occur during off hours.
- **FD1005 — Device Attributes:** Monitor device factors such as device type, user agent string, operating system, cookies.
- **FD1006 — Velocity Attributes:** Monitor for accounts that are created quickly in succession from the same location or with similar features.

**References:** Top 10 Digital Commerce Account Risks & How to Mitigate Them: https://www.forter.com/blog/rh-isac-account-risk-mitigation/

---

### Credential Stuffing | FT1105

**Tactic:** Initial Access  
**Channels:** Digital  
**Schemes:** Account Takeover

**Description**

Fraudsters abuse a variety of web automation tools to automate login attempts using credential lists known as "combolists." Fraudsters develop custom credential stuffing tools to automate login attempts. These tools can be site-specific or configurable via files known as "configs" which are then either sold or shared in underground communities.

**Mitigations**

- **FM1008 — Behavior Prevention:** Many commercial services provide bot detection and mitigation, often incorporated into content delivery networks and other management packages. Commonly available tooling includes default technical indicators which should be mitigated at the edge and automatically denied.

**Detection Opportunities**

- **FD1006 — Velocity Attributes:** Monitor for surges in login attempts and other anomalous activity. Monitor the response to login attempts where a surge in attempts to access accounts that do not exist is a strong indicator of automated credential stuffing.
- **FD1003 — Behavioral Attributes:** Monitor for repeated patterns of activity post-login that is an indicator that the activity is automated.

**References**
- MITRE ATT&CK: https://attack.mitre.org/techniques/T1110/004/
- Top 10 Digital Commerce Account Risks & How to Mitigate Them: https://www.forter.com/blog/rh-isac-account-risk-mitigation/

---

### Gift Card Return | FT1201

**Tactic:** Control  
**Channels:** Analog · Digital · Social Engineering  
**Schemes:** Gift Card Fraud

**Description**

The fraudster converts an illicitly acquired or invalid gift card for a legitimate gift card. Through social engineering or taking advantage of a retailer's legitimate system, they transfer the value from the illicitly obtained gift card to a new gift card that the fraudster legitimately owns.

**Mitigations**

- **FM1015 — Return Limit:** Do not exchange gift cards over a pre-determined value.

**Detection Opportunities**

- **FD1010 — Transaction Data:** Identify suspicious purchases and returns by gift card numbers.

**References:** Detecting and Reporting the Illicit Financial Flows Tied to Organized Theft Groups (OTG) and Organized Retail Crime (ORC): https://www.acams.org/en/media/document/29436

---

### Gift Card Merge | FT1202

**Tactic:** Control  
**Channels:** Analog · Digital  
**Schemes:** Gift Card Fraud

**Description**

The fraudster obtains a gift card through legitimate means. Using a retailer-provided method they transfer value from illicitly obtained gift cards to the legitimate gift card. For example, a fraudster purchases a legitimate gift card with a value of $5, then illicitly obtains multiple gift cards with values of $100 and $150. Using a legitimate retailer feature they combine gift cards, adding $250 to their $5 gift card for a total of $255.

**Mitigations**

- **FM1008 — Behavior Prevention:** Do not permit merging of gift cards.
- **FM1002 — Login Required:** Require authentication before permitting transfer of gift card value.
- **FM1003 — Access Code Required:** Require an access code before permitting transfer of gift card value.

**Detection Opportunities**

- **FD1010 — Transaction Data:** Identify suspicious transfer of value from gift cards to other gift cards.
- **FD1006 — Velocity Attributes:** Identify suspicious transfers from many gift cards to one gift card (e.g., if 20 gift cards with value of $5 are added to a single gift card).

**References:** Industry Partner Collaboration

---

### Gift Card Tampering | FT1203

**Tactic:** Control  
**Channels:** Analog  
**Schemes:** Gift Card Fraud

**Description**

Fraudster takes physical possession of an unactivated gift card and takes the information that allows them to control the gift card when it is funded and activated. For example, a fraudster steals gift cards from a store, copies down the gift card number and security pin, then repackages the gift card and returns it to the store. When a victim purchases the gift card and loads value, the fraudster can spend the funds without the victim's awareness.

**Mitigations**

- **FM1001 — Primary Gift Card Lock in:** For gift cards, lock the Gift Card into the identity of the purchaser. Do not allow another person to use the gift card without identity verification or authentication.
- **FM1002 — Login Required:** For gift cards, require an account before permitting purchase of or transfer.
- **FM1005 — Anti-theft Prevention:** Store gift cards behind checkout counter to limit theft.
- **FM1016 — Security Guard:** At physical locations, use security guards to identify instances of fraudsters stealing gift cards and/or returning tampered gift cards.

**Detection Opportunities**

- **FD1002 — Video Surveillance Systems:** At physical locations, use video surveillance to identify instances of fraudsters stealing gift cards and/or returning tampered gift cards.

**References**
- Industry Partner Collaboration
- Detecting and Reporting the Illicit Financial Flows Tied to Organized Theft Groups (OTG) and Organized Retail Crime (ORC): https://www.acams.org/en/media/document/29436

---

### Gift Card Redemption | FT1204

**Tactic:** Control  
**Channels:** Analog · Digital · Social Engineering  
**Schemes:** Gift Card Fraud

**Description**

The fraudster obtains a gift card through legitimate or illicit means and purchases an item. For example, a fraudster uses a gift card to purchase a high-value easy-to-sell item such as jewelry or electronics, then monetizes these items through resale or drop shipping.

**Mitigations**

- **FM1001 — Primary Gift Card Lock in:** For gift cards, lock the gift card into the identity of the purchaser. Do not allow another person to use the gift card without identity verification or authentication.
- **FM1002 — Login Required:** For gift cards, require an account before permitting purchase of or transfer.

**Detection Opportunities**

- **FD1010 — Transaction Data:** Identify suspicious purchases of commonly resold items with potentially illicitly obtained gift cards.

**References:** Detecting and Reporting the Illicit Financial Flows Tied to Organized Theft Groups (OTG) and Organized Retail Crime (ORC): https://www.acams.org/en/media/document/29436

---

### Loyalty Points Abuse | FT1205

**Tactic:** Control  
**Channels:** Digital  
**Schemes:** Account Takeover

**Description**

The fraudster converts loyalty points into items or gift cards that can be used for monetization. For example, a fraudster successfully compromises a victim's account through social engineering, then converts the victim's loyalty points into a gift card that the fraudster controls for further monetization.

**Mitigations**

- **FM1004 — Multi-Factor Authentication:** Use multiple forms of authentication before permitting access. Require identity verification upon detection of access requests that are significantly different than what is expected.
- **FM1014 — Password Policy:** Encourage using strong passwords with sufficient length and complexity. Discourage reusing passwords.

**Detection Opportunities**

- **FD1007 — Network Traffic Attributes:** Monitor for Network Traffic Attributes such as IP Address, DNS Name, ASN, and other digital location attributes.
- **FD1004 — Time-Based Attributes:** Based on the location of your operations, monitor for activities that occur during off hours.
- **FD1005 — Device Attributes:** Monitor device factors such as device type, user agent string, operating system, cookies.
- **FD1003 — Behavioral Attributes:** Monitor for access attempts and purchases that are significantly different from known good behavior for each customer.

**References:** Industry Partner Collaboration

---

### Item Manipulation | FT1206

**Tactic:** Control  
**Channels:** Analog · Digital · Social Engineering  
**Schemes:** Return Fraud

**Description**

Fraudster returns merchandise to a retailer under deceptive circumstances to obtain monetary refunds, store credit, replacement goods, or has somehow extracted value from the merchandise. This technique involves presenting an item at the point of return (altered, incomplete, counterfeit, or previously used) while misrepresenting its condition or origin.

**Sub-Techniques:** Harvesting (FT1206.001), Switch Merchandise (FT1206.002)

**Mitigations**

- **FM1013 — Item Condition & Tag Checks:** Ensure item is returned with all its components such as packaging, accessories, and documentation in good condition. Verify additional attributes such as weight, general wear and tear, scuffs on screws, reapplied tape. Do not accept returns that are missing components or may be suspicious.
- **FM1005 — Anti-theft Prevention:** Use unique serial numbers or RFID tags tied to the original transaction record. Verify serial numbers/digital product IDs upon return. Apply tamper-proof seals or packaging that are difficult to replicate.
- **FM1015 — Return Limit:** Require original packaging in return policy for high-value items. Shorten return windows for high-risk categories (electronics, luxury goods). Deny returns to guests or tenders with a history of abuse or suspected abuse.
- **FM1203 — Proof of Purchase:** Require receipts and ID for high-value returns.
- **FM1009 — Restocking Fees:** Charge fees for high-risk categories.
- **FM1006 — Training and Awareness:** Train associates to identify mismatched logos, misspelled labels, or damaged packaging.
- **FM1022 — Escalation:** Implement escalation paths for suspicious returns.

**Detection Opportunities**

- **FD1010 — Transaction Data:** Match returned product identifiers (IMEI, serial, RFID) to the original purchase record.
- **FD1003 — Behavioral Attributes:** Profiles or tenders with high rates of returns in specific categories.
- **FD1005 — Device Attributes:** Use graph or link analysis to find connected devices, IPs, or payment tenders and label them as suspicious for future tracking.
- **FD1009 — Online Identities:** Use graph or link analysis to find connected accounts.

**References**
- Appriss: https://apprissretail.com/blog/8-common-types-of-return-fraud/
- Industry Partner Collaboration

---

#### Item Manipulation: Harvesting | FT1206.001

**Tactic:** Control  
**Channels:** Analog · Social Engineering · Digital  
**Schemes:** Return Fraud

**Description**

Fraudster harvests valuable components of an item and returns the merchandise for a full refund. For example, a fraudster purchases a computer, harvests valuable components such as the graphics processor and CPU, then returns the item to the store and receives full value of the purchase but has stolen the components. Another example: a fraudster purchases a console system that comes with redeemable points or single use credit, steals and redeems this credit, then returns the console for full value.

**Mitigations**

- **FM1013 — Item Condition & Tag Checks:** Ensure item is returned with all its components. Verify additional attributes such as weight, general wear and tear, scuffs on screws, reapplied tape. Do not accept returns that are missing components or may be suspicious.
- **FM1005 — Anti-theft Prevention:** Apply tamper-proof seals or packaging that are difficult to replicate.
- **FM1009 — Restocking Fees:** Charge fees for high-risk categories.

**Detection Opportunities**

- **FD1003 — Behavioral Attributes:** Profiles or tenders with high rates of returns in specific categories.

**References:** Industry Partner Collaboration

---

#### Item Manipulation: Switch Merchandise | FT1206.002

**Tactic:** Control  
**Channels:** Analog · Digital · Social Engineering  
**Schemes:** Return Fraud

**Description**

A fraudster returns a different item, a broken item, or a counterfeit item for resources such as gift cards, store credit, or cash. For example, a fraudster may purchase an item they already own that is broken, keep the new merchandise and put the broken item into the box of the new purchase, then return the broken item for full monetary value. Another example: a fraudster may purchase an item online, begin an online return and ship a different item or other material that is similar in weight or size, then keeps the purchased item and receives monetary value of the returned item.

**Mitigations**

- **FM1005 — Anti-theft Prevention:** Use unique serial numbers or RFID tags tied to the original transaction record. Verify serial numbers/digital product IDs upon return. Apply tamper-proof seals or packaging.
- **FM1015 — Return Limit:** Require original packaging for high-value items. Shorten return windows for high-risk categories. Deny returns to guests or tenders with a history of abuse.
- **FM1203 — Proof of Purchase:** Require receipts and ID for high-value returns.
- **FM1009 — Restocking Fees:** Charge fees for returning high-risk categories.
- **FM1006 — Training and Awareness:** Train associates to identify mismatched logos, misspelled labels or damaged packaging.
- **FM1022 — Escalation:** Implement escalation paths for suspicious returns.

**Detection Opportunities**

- **FD1010 — Transaction Data:** Match returned product identifiers (IMEI, serial, RFID) to the original purchase record.
- **FD1003 — Behavioral Attributes:** Identify accounts or tenders with repeated returns in high-counterfeit categories.
- **FD1005 — Device Attributes:** Use graph or link analysis to find connected devices, IP addresses, or payment tenders.
- **FD1009 — Online Identities:** Use graph or link analysis to find connected accounts.

**References:** Industry Partner Collaboration

---

### Returns Process Exploitation | FT1207

**Tactic:** Control  
**Channels:** Analog · Digital · Social Engineering  
**Schemes:** Return Fraud

**Description**

A fraudster abuses a retailer's returns system to receive the value of an item. They may claim an item is damaged or never arrived. For example, a fraudster purchases an item and has it delivered to their house, then fraudulently claims the item never arrived or was damaged in transit, and abuses the retailer's claims system to receive a refund while keeping the delivered item.

**Sub-Techniques:** Shipping Manipulation (FT1207.001), Damaged Shipment (FT1207.002)

**Mitigations**

- **FM1008 — Behavior Prevention:** Flag customers that make too many returns and delay or deny returns.
- **FM1009 — Restocking Fees:** Impose a fee for returns.
- **FM1010 — Delayed Reimbursement:** Delay reimbursement for a specific amount of time or until the return is verified.
- **FM1203 — Proof of Purchase:** Require proof of purchase such as a receipt before permitting return.

**Detection Opportunities**

- **FD1010 — Transaction Data:** Record serial numbers to make sure refunds match the product.
- **FD1003 — Behavioral Attributes:** Identify fraudsters that make repeat or frequent returns. Identify fraudsters attempting to refund online and in stores.
- **FD1005 — Device Attributes:** Identify devices such as a single phone or computer used for many return attempts.

**References:** Industry Partner Collaboration

---

#### Returns Process Exploitation: Shipping Manipulation | FT1207.001

**Tactic:** Control  
**Channels:** Analog · Digital · Social Engineering  
**Schemes:** Return Fraud

**Description**

Fraudster purchases an item with the intent to return the item. They request a return from the retailer and tamper with the return label, resulting in a lost package. The fraudster does not return the original item, but an item with similar weight and size. The retailer in good faith refunds the fraudster as soon as the return is initiated. The fraudster now possesses the merchandise as well as the value of the refund.

**Mitigations**

- **FM1204 — Delivery Confirmation:** Only refund after the item is received and verified.
- **FM1008 — Behavior Prevention:** Flag customers that make too many returns and delay or deny returns.
- **FM1015 — Return Limit:** Restrict fast refunds on high-risk items like electronics.
- **FM1010 — Delayed Reimbursement:** Delay reimbursement for a specific amount of time or until the return is verified.

**Detection Opportunities**

- **FD1003 — Behavioral Attributes:** Identify fraudsters that make repeat or frequent delivery-based returns.
- **FD1010 — Transaction Data:** Match refund claims with shipping records.
- **FD1005 — Device Attributes:** Identify devices such as a single phone or computer used for many return attempts.

**References**
- Appriss: https://apprissretail.com/blog/8-common-types-of-return-fraud/
- Industry Partner Collaboration

---

#### Returns Process Exploitation: Damaged Shipment | FT1207.002

**Tactic:** Control  
**Channels:** Analog · Digital · Social Engineering  
**Schemes:** Return Fraud

**Description**

A fraudster orders multiple items in one shipment and then falsely claims that damage to one item rendered the entire order unusable (e.g., leakage, shattered glass, food contamination). They request an order-level refund or reshipment rather than a partial remedy, exploiting lenient damage policies and limited evidence requirements. For example, a fraudster orders printer ink, toner and a laptop, then claims the toner exploded during shipping and damaged the laptop, requesting a refund for all items while keeping them.

**Mitigations**

- **FM1205 — Proof of Damage:** Require customers to submit photos or video evidence of damage. Require the physical return of damaged goods before issuing a refund.
- **FM1206 — Enhanced Packaging:** Isolate items that could leak or cause contamination into separate packages. Use waterproof packaging or tamper-proof seals.
- **FM1015 — Return Limit:** Limit the amount that can be refunded without requiring the item to be physically returned.

**Detection Opportunities**

- **FD1003 — Behavioral Attributes:** Flag customers with repeated claims tied to specific accounts, addresses, and/or payment identities. Monitor for claims made on first-time orders by new customers.
- **FD1006 — Velocity Attributes:** Monitor for frequent damage claims of specific items.

**References:** Industry Partner Collaboration

---

### Wardrobing | FT1209

**Tactic:** Control  
**Channels:** Analog · Digital  
**Schemes:** Return Fraud

**Description**

A fraudster buys merchandise (often apparel, footwear, or accessories) intending to temporarily use or wear the item for an event, photo shoot, or short-term need. After use, the fraudster returns the item, exploiting return policies. The retailer incurs losses through inventory depreciation, sanitation costs, and resale markdowns, as returned items often cannot be sold as new.

**Mitigations**

- **FM1015 — Return Limit:** Deny returns on worn, washed, or tag-removed items. Shorten return windows for seasonal/fashion merchandise.
- **FM1009 — Restocking Fees:** Apply Restocking Fees to high-value apparel items.
- **FM1005 — Anti-theft Prevention:** Use tamper-proof tagging that would leave a detectable residue that the item has been worn. RFID tagging to validate item being returned was purchased within the return window.

**Detection Opportunities**

- **FD1006 — Velocity Attributes:** Profiles or tenders with high rates of returns in specific categories.
- **FD1013 — Item Condition & Tag Checks:** Inspect the item being returned for missing original packaging, tags, or signs of use (stains, scuffs).

**References:** Industry Partner Collaboration

---

### Resale | FT1301

**Tactic:** Monetization  
**Channels:** Analog · Digital · Social Engineering  
**Schemes:** Gift Card Fraud

**Description**

The fraudster exchanges the illicitly obtained items or gift cards with another person or organization in exchange for liquid funds. For example, a fraudster may steal jewelry worth $100, then sell the illicitly obtained jewelry for $80 via a third party market such as Facebook Marketplace, converting the item to currency the fraudster controls.

**Sub-Techniques:** Drop Shipping (FT1301.001), Unwitting Buyer (FT1301.002)

**Mitigations**

- **FM1001 — Primary Gift Card Lock in:** For gift cards, lock the gift card into the identity of the purchaser. Do not allow another person to use the gift card without identity verification or authentication.
- **FM1002 — Login Required:** For gift cards, require an account before permitting purchase of or transfer.

**Detection Opportunities**

- **FD1010 — Transaction Data:** Monitor for anomalous purchases of easily monetized items such as Electronics and Luxury Goods.

**References:** Detecting and Reporting the Illicit Financial Flows Tied to Organized Theft Groups (OTG) and Organized Retail Crime (ORC): https://www.acams.org/en/media/document/29436

---

#### Resale: Drop Shipping | FT1301.001

**Tactic:** Monetization  
**Channels:** Analog · Digital · Social Engineering  
**Schemes:** Gift Card Fraud

**Description**

The fraudster will use a third party to ship directly to a customer. To obfuscate the legitimacy of the gift card, the fraudster will store gift cards with a third-party partner who will list and manage their gift cards. A buyer will purchase the gift card from the third party and receive illegally obtained gift cards.

**Mitigations**

- **FM1001 — Primary Gift Card Lock in:** For gift cards, lock the gift card into the identity of the purchaser. Do not allow another person to use the gift card without identity verification or authentication.
- **FM1002 — Login Required:** For gift cards, require an account before permitting purchase of or transfer.

**Detection Opportunities**

- **FD1010 — Transaction data:** Monitor for anomalous purchases of easily monetized items such as Electronics and Luxury Goods.

**References:** Detecting and Reporting the Illicit Financial Flows Tied to Organized Theft Groups (OTG) and Organized Retail Crime (ORC): https://www.acams.org/en/media/document/29436

---

#### Resale: Unwitting Buyer | FT1301.002

**Tactic:** Monetization  
**Channels:** Analog · Digital · Social Engineering  
**Schemes:** All

**Description**

The fraudster sells the illicitly obtained goods or resources to an unwitting buyer.

**Mitigations**

- **FM1001 — Primary Gift Card Lock in:** For gift cards, lock the gift card into the identity of the purchaser.
- **FM1002 — Login Required:** For gift cards, require an account before permitting purchase of or transfer.

**Detection Opportunities**

- **FD1011 — Market Resale Data:** Monitor for anomalous sales of serialized items and gift cards in third party locations and other repositories.

**References:** Detecting and Reporting the Illicit Financial Flows Tied to Organized Theft Groups (OTG) and Organized Retail Crime (ORC): https://www.acams.org/en/media/document/29436

---

### Marketplace Exploitation | FT1302

**Tactic:** Control  
**Channels:** Analog · Digital  
**Schemes:** Return Fraud

**Description**

Fraudulent sellers pose as legitimate marketplace accounts and exploit drop shipping to shift financial loss and reputational damage onto retailers. These sellers may deliver counterfeit, damaged, or no goods at all, causing customers to request refunds or initiate chargebacks, which the retailer absorbs. Fraudsters often use stolen payment methods, fake or nonexistent addresses, and may intercept packages or "double dip" by keeping goods while claiming non-delivery.

**Sub-Techniques:** Fraudulent Delivery (FT1302.001), Fraudulent Seller (FT1302.002)

**Mitigations**

- **FM1204 — Delivery Confirmation:** Only refund after the item is received and verified.
- **FM1008 — Behavior Prevention:** Validate address is legitimate and do not deliver to unlisted addresses.
- **FM1211 — Blacklist Known High-Risk Addresses:** Maintain a blacklist of shipping and billing addresses tied to prior fraud, freight forwarders, or reshipping operations, and block or hold orders directed to them.
- **FM1212 — Require Signature on Delivery:** Require signature confirmation at delivery for high-value or high-risk orders to establish proof of receipt and counter fraudulent non-delivery claims.

**Detection Opportunities**

- **FD1007 — Network Traffic Attributes:** Identify mismatch between Network Traffic Attributes such as IP geo location against the billing and shipping address.
- **FD1016 — Location Attributes:** Identify mismatch between billing and shipping address.
- **FD1003 — Behavioral Attributes:** Refund returns only to the method of purchase.

**References:** Industry Partner Collaboration

---

#### Marketplace Exploitation: Fraudulent Delivery | FT1302.001

**Tactic:** Control  
**Channels:** Analog · Digital  
**Schemes:** Return Fraud

**Description**

The fraudster places an order using a fraudulent, fake, incorrect, or nonexistent shipping address. This could include a fake street number, a real street but non-existent apartment number, an abandoned property, or a vacant lot. The fraudster may use stolen credit cards or other illicit resources to pay for the item. If the item is successfully delivered, the fraudster may steal the item from the real but fraudulent location or a consolidated mailroom. The fraudster may "double dip" and intercept the package to keep the goods and claim non-delivery.

**Mitigations**

- **FM1204 — Delivery Confirmation:** Only refund after the item is received and verified.
- **FM1008 — Behavior Prevention:** Validate address is legitimate and do not deliver to unlisted addresses.
- **FM1211 — Blacklist Known High-Risk Addresses:** Maintain a blacklist of shipping and billing addresses tied to prior fraud, freight forwarders, or reshipping operations.
- **FM1212 — Require Signature on Delivery:** Require signature confirmation at delivery for high-value or high-risk orders.

**Detection Opportunities**

- **FD1007 — Network Traffic Attributes:** Identify mismatch between Network Traffic Attributes such as IP geo location against the billing and shipping address.
- **FD1016 — Location Attributes:** Identify mismatch between billing and shipping address.
- **FD1003 — Behavioral Attributes:** Refund returns only to the method of purchase.

**References:** Industry Partner Collaboration

---

#### Marketplace Exploitation: Fraudulent Seller | FT1302.002

**Tactic:** Control  
**Channels:** Analog · Digital  
**Schemes:** Return Fraud

**Description**

A fraudulent seller is an account operating on (or connected to) your storefront/marketplace that appears legitimate but uses drop shipping to execute scams that shift loss, reputational damage, and chargebacks onto your retail brand. A legitimate customer may buy an item from the reseller that is counterfeit, damaged, or inferior, resulting in the customer returning the item for a full refund. A fraudster may work with the fraudulent seller to purchase the item with stolen funds or other illicit resources, resulting in a return or chargeback and enabling the seller to convert stolen funds into legitimate cash.

**Mitigations**

- **FM1204 — Delivery Confirmation:** Only refund after the item is received and verified.
- **FM1008 — Behavior Prevention:** Do not permit resellers to operate in your ecosystem without legitimate business credentials or sufficient time in market. Validate address is legitimate.
- **FM1211 — Blacklist Known High-Risk Addresses:** Maintain a blacklist of shipping and billing addresses tied to prior fraud.
- **FM1212 — Require Signature on Delivery:** Require signature confirmation at delivery for high-value or high-risk orders.

**Detection Opportunities**

- **FD1006 — Velocity Attributes:** Flag sellers with multiple returns or chargebacks.

**References:** Industry Partner Collaboration

---

### Checkout | FT1303

**Tactic:** Monetization  
**Channels:** Analog · Digital · Social Engineering  
**Schemes:** All

**Description**

The fraudster uses legitimate checkout to redeem or otherwise convert illicit resources into liquid funds.

**Sub-Techniques:** Point of Sale (FT1303.001), Guest Services (FT1303.002), Online/Web Mobile (FT1303.003)

**Mitigations**

- **FM1003 — Access Code Required:** Require an access code that is separate from the gift card before refunding gift card value.
- **FM1008 — Behavior Prevention:** Identify potentially fraudulent returns and do not refund money if fraud is detected.
- **FM1009 — Restocking Fees:** Require a fee for potentially fraudulent returns.
- **FM1010 — Delayed Reimbursement:** Postpone refund by a predetermined amount of time for items that are commonly related to fraud.

**Detection Opportunities**

- **FD1010 — Transaction Data:** Monitor for returns of items commonly related to fraud such as gift cards, Luxury Items, and Electronics for fraudulent activity.

**References:** Industry Partner Collaboration

---

#### Checkout: Point of Sale | FT1303.001

**Tactic:** Monetization  
**Channels:** Analog · Social Engineering  
**Schemes:** All

**Description**

The fraudster uses the checkout in store to convert illicit resources into liquid funds.

**Mitigations**

- **FM1003 — Access Code Required:** Require an access code that is separate from the gift card before refunding gift card value.
- **FM1008 — Behavior Prevention:** Identify potentially fraudulent returns and do not refund money if fraud is detected.
- **FM1009 — Restocking Fees:** Require a fee for potentially fraudulent returns.
- **FM1010 — Delayed Reimbursement:** Postpone refund by a predetermined amount of time for items that are commonly related to fraud.

**Detection Opportunities**

- **FD1010 — Transaction data:** Monitor and record product serial number of items that are commonly related to fraud.
- **FD1006 — Velocity Attributes:** Monitor returns for total amount and total value of items returned.

**References:** Industry Partner Collaboration

---

#### Checkout: Guest Services | FT1303.002

**Tactic:** Monetization  
**Channels:** Analog · Social Engineering  
**Schemes:** All

**Description**

The fraudster uses the guest services in store to convert illicit resources into liquid funds.

**Mitigations**

- **FM1003 — Access Code Required:** Require an access code that is separate from the gift card before refunding gift card value.
- **FM1008 — Behavior Prevention:** Identify potentially fraudulent returns and do not refund money if fraud is detected.
- **FM1009 — Restocking Fees:** Require a fee for potentially fraudulent returns.
- **FM1010 — Delayed Reimbursement:** Postpone refund by a predetermined amount of time for items that are commonly related to fraud.
- **FM1006 — Training and Awareness:** Train customer service representatives to identify potential fraud situations and deny refund.

**Detection Opportunities**

- **FD1010 — Transaction data:** Monitor and record product serial number of items that are commonly related to fraud.
- **FD1006 — Velocity Attributes:** Monitor returns for total amount and total value of items returned.

**References:** Industry Partner Collaboration

---

#### Checkout: Online/Web Mobile | FT1303.003

**Tactic:** Monetization  
**Channels:** Digital  
**Schemes:** All

**Description**

The fraudster uses digital resources to convert illicit resources into liquid funds.

**Mitigations**

- **FM1209 — Online Location Data:** Some physical locations should not be able to return items. Prevent the ability to return items for funds based on locations.

**Detection Opportunities**

- **FD1010 — Transaction data:** Monitor and record product serial number of items that are commonly related to fraud.
- **FD1007 — Network Traffic Attributes:** Monitor for Network Traffic Attributes such as IP Address, DNS Name, ASN, and other digital location attributes.
- **FD1004 — Time-Based Attributes:** Based on the location of your operations, monitor for activities that occur during off hours.
- **FD1005 — Device Attributes:** Monitor device factors such as device type, user agent string, operating system, cookies.
- **FD1006 — Velocity Attributes:** Monitor for number of requests based on a predetermined number of requests over a set amount of time.

**References:** Industry Partner Collaboration

---

### Fraudulent Refund | FT1304

**Tactic:** Monetization  
**Channels:** Analog · Digital · Social Engineering  
**Schemes:** Return Fraud

**Description**

Deliberate exploitation of a retailer's refund process to obtain financial gain or store credit without legitimate grounds. The fraudster initiates a return, often under false pretenses such as claiming damage, misrepresentation, or leveraging policy loopholes, and secures cash refunds, gift cards, or store credit.

**Sub-Techniques:** Refund to Gift Card (FT1304.001), Double Refund (FT1304.002), Non-Receipted Returns (FT1304.003)

**Mitigations**

- **FM1015 — Return Limit:** Link each order to an individual refund. Restrict how many times a refund can be requested per order. Limit the number and total amount of non-receipted returns per customer. Only allow in-store credit or gift cards as a refund tender.
- **FD1003 — Behavioral Attributes:** Stop refunds if the same order ID is already refunded.
- **FM1022 — Escalation:** Escalate suspicious repeat attempts to returns.
- **FM1021 — Identity Verification:** Require government-issued ID. Tie return transaction to customer profile for monitoring.
- **FM1009 — Restocking Fees:** Impose fees on items being returned.
- **FM1207 — Redemption Limits:** Limit the amount of store credit that can be used on a single transaction.

**Detection Opportunities**

- **FD1010 — Transaction Data:** Identify multiple refund requests for the same order. Check if item identifiers (IMEI, serial, RFID) can be associated with a prior purchase. Identify the same return in multiple stores and online. Compare items against inventory shortage reports.
- **FD1003 — Behavioral Attributes:** Flag accounts that are doing frequent gift card refunds. Identify in person or Online Identities attempting gift card refund. Flag accounts attempting frequent non-receipted returns. Monitor for invalid government ID usage. Track items frequently returned without receipts at locations associated with high rates of theft.
- **FD1005 — Device Attributes:** Detect repeat attempts from the same computer or phone submitting duplicate requests.
- **FD1006 — Velocity Attributes:** Identify accounts requesting several refunds in a short time.
- **FD1014 — Credit Redemption Behavior:** Monitor for the consolidation of in-store credit gift cards to purchase high-value items or issued to multiple identities.

**References:** Industry Partner Collaboration

---

#### Refund: Refund To Gift Card | FT1304.001

**Tactic:** Monetization  
**Channels:** Digital · Social Engineering  
**Schemes:** Return Fraud

**Description**

Exploiting a retailer's refund process by requesting that the refund value be issued as a gift card or store credit rather than returned to the original payment method. Fraudsters favor gift cards because they are highly liquid, easily transferable, and often lack the same fraud detection or traceability controls for credit or debit card refunds. Once obtained, these gift cards can be resold on secondary markets, exchanged for cash, or used to purchase high-value goods for sale, effectively converting fraudulent returns into fungible currency.

**Mitigations**

- **FM1003 — Access Code Required:** Require an access code before permitting access to resources.
- **FM1015 — Return Limit:** Limit the amount of money that can be refunded.
- **FM1022 — Escalation:** Based on value require Escalation to manager.

**Detection Opportunities**

- **FD1010 — Transaction Data:** Record serial numbers for refunded gift cards.
- **FD1003 — Behavioral Attributes:** Flag accounts doing frequent gift card refunds. Identify in person or Online Identities attempting gift card refund.
- **FD1005 — Device Attributes:** Detect repeat attempts from the same computer or phone.

**References:** Industry Partner Collaboration

---

#### Refund: Double Refund | FT1304.002

**Tactic:** Monetization  
**Channels:** Digital · Social Engineering  
**Schemes:** Return Fraud

**Description**

Fraudsters refund the same item multiple times either in multiple stores, online or some combination of both.

**Mitigations**

- **FM1015 — Return Limit:** Link each order to an individual refund. Restrict how many times a refund can be requested per order.
- **FM1022 — Escalation:** Escalate repeat attempts to return the same item to manager.
- **FM1008 — Behavior Prevention:** Stop refunds if the same order ID is already refunded.

**Detection Opportunities**

- **FD1010 — Transaction Data:** Identify multiple refund requests for the same order. Identify the same return in multiple stores and online.
- **FD1003 — Behavioral Attributes:** Flag accounts doing frequent gift card refunds. Identify in person or Online Identities attempting gift card refund.
- **FD1005 — Device Attributes:** Detect repeat attempts from the same computer or phone submitting duplicate requests.
- **FD1006 — Velocity Attributes:** Identify accounts requesting several refunds in a short time.

**References:** Industry Partner Collaboration

---

#### Refund: Non-Receipted Returns | FT1304.003

**Tactic:** Control  
**Channels:** Analog · Digital · Social Engineering  
**Schemes:** Return Fraud

**Description**

Fraudster intentionally misuses the returns process without a valid receipt (or other proof of purchase) to obtain cash refunds, store credit, gift cards, or replacements. The actor exploits no receipt allowances, low evidence thresholds, and minimal inspection.

**Mitigations**

- **FM1015 — Return Limit:** Limit the number and total amount of non-receipted returns per customer. Limit the types of items that can be returned without a receipt. Only allow in-store credit or gift cards as a refund tender.
- **FM1021 — Identity Verification:** Require government-issued ID. Tie return transaction to customer profile for monitoring.
- **FM1009 — Restocking Fees:** Impose fees on items being returned that have no proof of purchase.
- **FM1207 — Redemption Limits:** Limit the amount of store credit that can be used on a single transaction.

**Detection Opportunities**

- **FD1003 — Behavioral Attributes:** Flag accounts attempting frequent non-receipted returns. Monitor for invalid government ID usage. Track items frequently returned without receipts at locations associated with high rates of theft. Compare against inventory shortage reports.
- **FD1010 — Transaction Data:** Check if item identifiers (IMEI, serial, RFID) can be associated with a prior purchase.
- **FD1014 — Credit Redemption Behavior:** Monitor for the consolidation of in-store credit gift cards to purchase high value items or issued to multiple identities.

**References:** Industry Partner Collaboration

---

### VOIP Abuse | FT1401

**Tactic:** Defense Evasion  
**Channels:** Digital  
**Schemes:** Return Fraud · Gift Card Fraud · Account Takeover

**Description**

Fraudsters leverage Voice over Internet Protocol (VOIP) services to mask or manipulate their true geographic location and identity during fraudulent transactions. By using VOIP numbers, they can appear to originate from a trusted region or local area, even when operating from a completely different country or jurisdiction. This tactic is designed to evade fraud detection systems that rely on phone number validation, geolocation checks, or call-back verification. These numbers may also be used on seemingly normal account creations.

**Mitigations**

- **FM1008 — Behavior Prevention:** Do not permit registration of VOIP numbers on accounts or other customer resources.

**Detection Opportunities**

- **FD1008 — VOIP Attribute:** Identify VOIP phone usage and correlate against customer profile. Identify high-risk VOIP numbers or multiple accounts with the same VOIP number in your database.

**References:** Industry Partner Collaboration

---

### Digital Wallet Apps | FT1402

**Tactic:** Defense Evasion  
**Channels:** Analog · Digital  
**Schemes:** Return Fraud · Gift Card Fraud

**Description**

Digital wallet applications (such as Apple Pay, Google Pay, and PayPal) are mobile or web-based platforms that store payment credentials and enable electronic transactions without physical cards. Fraudsters exploit these wallets to evade detection by creating multiple accounts under different identities, masking the original payment source, and requesting refunds to wallet balances instead of the original payment method, making it easier to convert funds into cash, gift cards, or resale value. Fraudsters may also load stolen credit, debit and gift cards onto the wallet for reuse.

**Mitigations**

- **FM1021 — Identity Verification:** Verify the person's identity matches what is on the card in the wallet.
- **FM1008 — Behavior Prevention:** Do not permit multiple use of the same credit, debit, or gift cards within a defined period.

**Detection Opportunities**

- **FD1016 — Location Attributes:** Identify impossible travel transactions for the same credit, debit, or gift card.

**References:** Industry Partner Collaboration

---

### Cryptocurrency | FT1403

**Tactic:** Defense Evasion · Control · Monetization  
**Channels:** Digital  
**Schemes:** Return Fraud

**Description**

Fraudsters in retail exploit cryptocurrency as a tool to hide their tracks and bypass traditional fraud controls. After committing fraud or policy abuse, they often convert refunds or store credits into crypto through gift cards, prepaid instruments, or resale of goods on secondary markets. Crypto's anonymity, lack of centralized oversight, and irreversible transactions make it ideal for laundering value obtained from fraudulent returns. Fraudsters also use multiple wallets, peer-to-peer exchanges, and privacy coins to fragment and obscure transaction history.

**Mitigations**

- **FM1021 — Identity Verification:** Positively verify the identity of the customer.
- **FM1008 — Behavior Prevention:** Do not accept Cryptocurrency in your marketplace.

**Detection Opportunities**

- **FD1010 — Transaction data:** Use CTI to correlate and identify crypto wallets that are either suspicious or have been identified as supporting illegal activity or fraud.

**References:** Industry Partner Collaboration

---

### Gift Cards as Defense Evasion | FT1404

**Tactic:** Defense Evasion  
**Channels:** Analog · Digital  
**Schemes:** Return Fraud

**Description**

Gift cards are commonly exploited in fraud schemes due to their anonymity, liquidity, and ease of transfer. Fraudsters use them to bypass traditional detection systems by converting stolen funds or merchandise into gift card balances, which are harder to trace.

**Mitigations**

- **FM1001 — Primary Gift Card Lock in:** For gift cards, lock the gift card into the identity of the purchaser. Do not allow another person to use the gift card without identity verification or authentication.
- **FM1002 — Login Required:** For gift cards, require an account before permitting purchase of or transfer.

**Detection Opportunities**

- **FD1010 — Transaction Data:** Identify suspicious purchases of commonly resold items with potentially illicitly obtained gift cards.

**References**
- Detecting and Reporting the Illicit Financial Flows Tied to Organized Theft Groups (OTG) and Organized Retail Crime (ORC): https://www.acams.org/en/media/document/29436
- Industry Partner Collaboration

---

## Mitigations

Security concepts and technologies that can be used to prevent or disrupt a technique from being successfully executed.

### FM1001 — Primary Gift Card Lock In

**Description:** Ensure the purchaser is the only person that can monetize the gift card.

**Techniques Mitigated:** Gift Card Extortion (FT1102), Resale (FT1301), Resale: Drop Shipping (FT1301.001), Resale: Unwitting Buyer (FT1301.002), Gift Cards as Defense Evasion (FT1404), Gift Card Redemption (FT1204), Gift Card Tampering (FT1203)

---

### FM1002 — Login Required

**Description:** Ensure a resource is tied to an authentication source before allowing activation, use or transfer.

**Techniques Mitigated:** Gift Card Extortion (FT1102), Check Gift Card Balance (FT1103), Check Gift Card Balance: Application (FT1103.001), Gift Card Merge (FT1202), Resale (FT1301), Resale: Drop Shipping (FT1301.001), Gift Cards as Defense Evasion (FT1404), Gift Card Redemption (FT1204), Gift Card Tampering (FT1203), Resale: Unwitting Buyer (FT1301.002)

---

### FM1003 — Access Code Required

**Description:** Require an access code before permitting access to a resource.

**Techniques Mitigated:** Check Gift Card Balance (FT1103), Check Gift Card Balance: Application (FT1103.001), Check Gift Card Balance: Phone Verification (FT1103.002), Check Gift Card Balance: In Store Gift Card Verification (FT1103.003), Gift Card Merge (FT1202), Checkout (FT1303), Checkout: Point of Sale (FT1303.001), Checkout: Guest Services (FT1303.002), Refund: Refund to Gift Card (FT1304.001)

---

### FM1004 — Multi-Factor Authentication

**Description:** Requires two forms of identification, such as a password and a fingerprint or a password and a one-time code sent to a mobile device.

**Techniques Mitigated:** Valid Accounts (FT1104), Valid Accounts: Fraudulent Account (FT1104.001), Valid Accounts: Authorized Account Abuse (FT1104.003), Loyalty Points Abuse (FT1205), Valid Accounts: Fraudulent Account Update (FT1104.002)

---

### FM1005 — Anti-Theft Prevention

**Description:** Additional physical protection of products from theft (e.g. locked shelving, containers, vending machines, storing items behind checkout counter, etc.).

**Techniques Mitigated:** Shoplifting (FT1101), Gift Card Tampering (FT1203)

---

### FM1006 — Training and Awareness

**Description:** Employee training and consumer education to recognize and report fraud activity.

**Techniques Mitigated:** Reconnaissance (FT1001), Gift Card Extortion (FT1102), Checkout: Guest Services (FT1303.002), Fake Receipt Generation (FT1009), Item Manipulation (FT1206), Item Manipulation: Switch Merchandise (FT1206.002), Insider Recruitment (FT1010), Impersonation of Retail Employee (FT1011)

---

### FM1007 — Website Takedown Requests

**Description:** A formal request to a website owner, service provider, or domain registrar to remove an offending website.

**Techniques Mitigated:** Fake Pages (FT1003)

---

### FM1008 — Behavior Prevention

**Description:** Use capabilities to prevent suspicious behavior patterns from occurring on various systems.

**Techniques Mitigated:** Check Gift Card Balance: Phone Verification (FT1103.002), Gift Card Merge (FT1202), Checkout (FT1303), Checkout: Point of Sale (FT1303.001), Checkout: Guest Services (FT1303.002), Fake Receipt Generation (FT1009), Returns Process Exploitation (FT1207), Returns Process Exploitation: Shipping Manipulation (FT1207.001), Marketplace Exploitation: Fraudulent Delivery (FT1302.001), Marketplace Exploitation: Fraudulent Seller (FT1302.002), VOIP Abuse (FT1401), Digital Wallet Apps (FT1402), Cryptocurrency (FT1403), Marketplace Exploitation (FT1302), Refund: Double Refund (FT1304.002)

---

### FM1009 — Restocking Fees

**Description:** Impose a fee for product returns.

**Techniques Mitigated:** Checkout (FT1303), Checkout: Point of Sale (FT1303.001), Checkout: Guest Services (FT1303.002), Wardrobing (FT1209), Item Manipulation (FT1206), Item Manipulation: Harvesting (FT1206.001), Item Manipulation: Switch Merchandise (FT1206.002), Returns Process Exploitation (FT1207), Fraudulent Refund (FT1304), Refund: Non-Receipted Returns (FT1304.003)

---

### FM1010 — Delayed Reimbursement

**Description:** Delay return reimbursement for a predetermined amount of time.

**Techniques Mitigated:** Checkout (FT1303), Checkout: Point of Sale (FT1303.001), Checkout: Guest Services (FT1303.002), Returns Process Exploitation (FT1207), Returns Process Exploitation: Shipping Manipulation (FT1207.001)

---

### FM1011 — Brute Force Resistant Gift Card Numbers

**Description:** Using algorithms to generate long and complicated gift card numbers that are resistant to prediction.

**Techniques Mitigated:** Gift Card Number Generation (FT1005)

---

### FM1012 — Gift Card Purchase Limit

**Description:** Enforce limits of quantity and/or the value that may be purchased by an interaction or person.

**Techniques Mitigated:** Gift Card Extortion (FT1102)

---

### FM1013 — DNS Registration

**Description:** Identify potential URLs that may be used to fool individuals and register them to your organization.

**Techniques Mitigated:** Fake Pages (FT1003)

---

### FM1014 — Password Policy

**Description:** Enforce strong passwords with length and complexity requirements.

**Techniques Mitigated:** Acquire Database (FT1004), Valid Accounts (FT1104), Loyalty Points Abuse (FT1205)

---

### FM1015 — Return Limit

**Description:** Do not allow returns over a specified amount.

**Techniques Mitigated:** Gift Card Return (FT1201), Fraudulent Refund (FT1304), Item Manipulation (FT1206), Item Manipulation: Switch Merchandise (FT1206.002), Refund: Double Refund (FT1304.002), Refund: Non-Receipted Returns (FT1304.003), Refund: Refund to Gift Card (FT1304.001), Returns Process Exploitation: Damaged Shipment (FT1207.002), Returns Process Exploitation: Shipping Manipulation (FT1207.001), Wardrobing (FT1209)

---

### FM1016 — Security Guard

**Description:** A person charged with safeguarding the premises, protecting assets, preventing theft, and ensuring the safety of both customers and staff. Their duties typically include monitoring surveillance equipment, patrolling the retail space, managing access points, responding to emergencies, and sometimes assisting in loss prevention strategies.

**Techniques Mitigated:** Reconnaissance (FT1001), Shoplifting (FT1101), Gift Card Tampering (FT1203)

---

### FM1017 — Satchel Control

**Description:** Control the admittance or size of satchels allowed at the location.

**Techniques Mitigated:** Shoplifting (FT1101)

---

### FM1018 — Software Configuration

**Description:** Harden devices with configurations that can mitigate techniques or harden attack surface.

**Techniques Mitigated:** Reconnaissance (FT1001)

---

### FM1019 — Neutral Feedback

**Description:** When providing automatic feedback for failed requests such as accounts, gift cards, password resets, etc., provide an abstract response that does not confirm or deny that the resource exists. For example, instead of stating that the account exists and an email was sent, instead return "If the account exists, an email will be sent to the address on file."

**Techniques Mitigated:** Password Reset (FT1006)

---

### FM1020 — Customer Notification

**Description:** Send a notification to the original contacts listed on an account or resource when changes are made to the account or resources.

**Techniques Mitigated:** Password Reset (FT1006)

---

### FM1021 — Identity Verification

**Description:** Positively verify identity of customer with government or store credentials.

**Techniques Mitigated:** Fraudulent Refund (FT1304), Refund: Non-Receipted Returns (FT1304.003), Digital Wallet Apps (FT1402), Impersonation of Retail Employee (FT1011)

---

### FM1022 — Escalation

**Description:** Require additional Escalation to manager for suspicious cases or based on dollar amount.

**Techniques Mitigated:** Item Manipulation (FT1206), Item Manipulation: Switch Merchandise (FT1206.002), Fraudulent Refund (FT1304), Refund: Refund to Gift Card (FT1304.001), Refund: Double Refund (FT1304.002), Insider Recruitment (FT1010), Impersonation of Retail Employee (FT1011)

---

### FM1203 — Proof Of Purchase

**Description:** Require receipts and ID for high-value returns.

**Techniques Mitigated:** Item Manipulation (FT1206), Item Manipulation: Switch Merchandise (FT1206.002), Returns Process Exploitation (FT1207)

---

### FM1204 — Delivery Confirmation

**Description:** Only refund after the item is received and verified.

**Techniques Mitigated:** Returns Process Exploitation: Shipping Manipulation (FT1207.001), Marketplace Exploitation: Fraudulent Delivery (FT1302.001), Marketplace Exploitation: Fraudulent Seller (FT1302.002), Marketplace Exploitation (FT1302)

---

### FM1205 — Proof Of Damage

**Description:** Require customers to submit photos or video evidence of damage. Require the physical return of damaged goods before issuing a refund.

**Techniques Mitigated:** Returns Process Exploitation: Damaged Shipment (FT1207.002)

---

### FM1206 — Enhanced Packaging

**Description:** Isolate items that could leak or cause contamination into separate packages. Use waterproof packaging or tamper-proof seals.

**Techniques Mitigated:** Returns Process Exploitation: Damaged Shipment (FT1207.002)

---

### FM1207 — Redemption Limits

**Description:** Limit the amount of store credit that can be used on a single transaction.

**Techniques Mitigated:** Fraudulent Refund (FT1304), Refund: Non-Receipted Returns (FT1304.003)

---

### FM1208 — Law Enforcement

**Description:** Report known counterfeiters or other confirmed illegal activity to Law Enforcement for action.

**Techniques Mitigated:** Third Party Supplier Manipulation (FT1008)

---

### FM1209 — Online Location Data

**Description:** Restrict or block return, balance-check, and verification functions based on the originating location. Certain physical or digital locations should not have access to these functions, and locations associated with repeated fraud activity can be blocked.

**Techniques Mitigated:** Check Gift Card Balance (FT1103), Check Gift Card Balance: Application (FT1103.001), Checkout: Online/Web Mobile (FT1303.003)

---

### FM1210 — Phone Number

**Description:** Automatically block or flag phone numbers associated with VOIP services or with known fraud activity from accessing balance-check, verification, or account-recovery functions.

**Techniques Mitigated:** Check Gift Card Balance (FT1103)

---

### FM1211 — Blacklist Known High-Risk Addresses

**Description:** Maintain and enforce a blacklist of shipping and billing addresses associated with prior fraud, freight forwarders, or reshipping operations, and block, hold, or flag orders directed to them.

**Techniques Mitigated:** Marketplace Exploitation (FT1302), Marketplace Exploitation: Fraudulent Delivery (FT1302.001), Marketplace Exploitation: Fraudulent Seller (FT1302.002)

---

### FM1212 — Require Signature on Delivery

**Description:** Require signature confirmation at delivery for high-value or high-risk orders to establish proof of receipt and reduce fraudulent non-delivery and item-not-received claims.

**Techniques Mitigated:** Marketplace Exploitation (FT1302), Marketplace Exploitation: Fraudulent Delivery (FT1302.001), Marketplace Exploitation: Fraudulent Seller (FT1302.002)

---

## Detection Sources

Telemetry that can be collected to detect fraud that is in progress or has occurred in the past.

### FD1001 — Anti-Theft Security Tags

**Description:** A tag or similar device that is attached to an item that will cause an alarm or otherwise alert security personnel when it is removed without authorization.

**Techniques Detected:** Shoplifting (FT1101)

---

### FD1002 — Video Surveillance Systems

**Description:** Cameras and related equipment used for monitoring activities in various settings to enhance security, deter crime, and gather evidence when necessary.

**Techniques Detected:** Shoplifting (FT1101), Reconnaissance (FT1001), Insider Recruitment (FT1010), Gift Card Tampering (FT1203), Impersonation of Retail Employee (FT1011)

---

### FD1003 — Behavioral Attributes

**Description:** Information involving user's behavior and habits. For example, a system might use a user's typing pattern, mouse movements, preferred language, or how they navigate an application, to look for deviations from normal or compare similarity to known abuse or fraud patterns.

**Techniques Detected:** Gift Card Extortion (FT1102), Valid Accounts (FT1104), Credential Stuffing (FT1105), Password Reset (FT1006), Loyalty Points Abuse (FT1205), Item Manipulation (FT1206), Item Manipulation: Harvesting (FT1206.001), Item Manipulation: Switch Merchandise (FT1206.002), Returns Process Exploitation (FT1207), Returns Process Exploitation: Shipping Manipulation (FT1207.001), Returns Process Exploitation: Damaged Shipment (FT1207.002), Fraudulent Refund (FT1304), Refund: Refund to Gift Card (FT1304.001), Refund: Double Refund (FT1304.002), Refund: Non-Receipted Returns (FT1304.003), Impersonation of Retail Employee (FT1011), Insider Recruitment (FT1010), Marketplace Exploitation: Fraudulent Delivery (FT1302.001), Marketplace Exploitation (FT1302)

---

### FD1004 — Time-Based Attributes

**Description:** Time an action occurred that can be compared against a baseline of activity.

**Techniques Detected:** Check Gift Card Balance (FT1103), Check Gift Card Balance: Application (FT1103.001), Check Gift Card Balance: Phone Verification (FT1103.002), Valid Accounts (FT1104), Valid Accounts: Fraudulent Account (FT1104.001), Valid Accounts: Authorized Account Abuse (FT1104.003), Checkout: Online/Web Mobile (FT1303.003), Loyalty Points Abuse (FT1205), Third Party Supplier Manipulation (FT1008), Valid Accounts: Fraudulent Account Update (FT1104.002)

---

### FD1005 — Device Attributes

**Description:** Data related to a user's device, such as a smartphone or laptop, as indicators that identify what type of device and software they are using. For example, a system might require a specific cookie or device identifier, expect a consistent device profile to include screen resolution, memory, operating system, time zone, installed plug-ins or other data that may be used to measure device similarity.

**Techniques Detected:** Check Gift Card Balance (FT1103), Check Gift Card Balance: Application (FT1103.001), Valid Accounts (FT1104), Checkout: Online/Web Mobile (FT1303.003), Loyalty Points Abuse (FT1205), Fraudulent Refund (FT1304), Item Manipulation (FT1206), Item Manipulation: Switch Merchandise (FT1206.002), Refund: Double Refund (FT1304.002), Refund: Refund to Gift Card (FT1304.001), Returns Process Exploitation (FT1207), Returns Process Exploitation: Shipping Manipulation (FT1207.001), Valid Accounts: Authorized Account Abuse (FT1104.003), Valid Accounts: Fraudulent Account (FT1104.001), Valid Accounts: Fraudulent Account Update (FT1104.002)

---

### FD1006 — Velocity Attributes

**Description:** Frequency or unusual velocity of an action compared to baseline by some aggregation value. An action might be gift card balance checks. An aggregation value might be a device identifier, IP address, user account ID, or other value. A concrete example might be looking for a large volume of orders in a short period of time for an account.

**Techniques Detected:** Gift Card Extortion (FT1102), Check Gift Card Balance (FT1103), Check Gift Card Balance: Application (FT1103.001), Check Gift Card Balance: In Store Gift Card Verification (FT1103.003), Valid Accounts: Authorized Account Abuse (FT1104.003), Valid Accounts: Fraudulent Account (FT1104.001), Gift Card Merge (FT1202), Checkout: Online/Web Mobile (FT1303.003), Credential Stuffing (FT1105), Password Reset (FT1006), Checkout: Guest Services (FT1303.002), Checkout: Point of Sale (FT1303.001), Fake Receipt Generation (FT1009), Fraudulent Refund (FT1304), Marketplace Exploitation: Fraudulent Seller (FT1302.002), Refund: Double Refund (FT1304.002), Returns Process Exploitation: Damaged Shipment (FT1207.002), Third Party Supplier Manipulation (FT1008), Valid Accounts: Fraudulent Account Update (FT1104.002), Wardrobing (FT1209)

---

### FD1007 — Network Traffic Attributes

**Description:** Metadata about an IP address like whether it is a hosting provider, VPN or Proxy service, Residential network, cellular provider, or residential ISP. This information may also be associated with user accounts or devices to baseline them over time and look for deviations from the usual access patterns.

**Techniques Detected:** Fake Pages (FT1003), Check Gift Card Balance (FT1103), Check Gift Card Balance: Application (FT1103.001), Valid Accounts (FT1104), Valid Accounts: Fraudulent Account (FT1104.001), Valid Accounts: Authorized Account Abuse (FT1104.003), Checkout: Online/Web Mobile (FT1303.003), Loyalty Points Abuse (FT1205), Marketplace Exploitation: Fraudulent Delivery (FT1302.001), Marketplace Exploitation (FT1302), Reconnaissance (FT1001), Valid Accounts: Fraudulent Account Update (FT1104.002)

---

### FD1008 — VOIP Attribute

**Description:** A VOIP (Voice over Internet Protocol) number is a virtual phone number that is not tied to physical telephones or mobile phones. These numbers are highly portable and may be swapped and reused.

**Techniques Detected:** Check Gift Card Balance (FT1103), Check Gift Card Balance: Phone Verification (FT1103.002), VOIP Abuse (FT1401)

---

### FD1009 — Online Identities

**Description:** Email addresses, Telegram usernames, social media handles, accounts, etc., that have been the source of fraudulent activities.

**Techniques Detected:** Reconnaissance (FT1001), Acquire Database (FT1004), Item Manipulation (FT1206), Item Manipulation: Switch Merchandise (FT1206.002), Valid Accounts: Fraudulent Account Update (FT1104.002)

---

### FD1010 — Transaction Data

**Description:** Records that are related to transactions in-store or online.

**Techniques Detected:** Resale (FT1301), Gift Card Return (FT1201), Gift Card Merge (FT1202), Resale: Drop Shipping (FT1301.001), Checkout: Point of Sale (FT1303.001), Checkout: Guest Services (FT1303.002), Checkout: Online/Web Mobile (FT1303.003), Third Party Supplier Manipulation (FT1008), Fake Receipt Generation (FT1009), Item Manipulation (FT1206), Item Manipulation: Switch Merchandise (FT1206.002), Returns Process Exploitation (FT1207), Returns Process Exploitation: Shipping Manipulation (FT1207.001), Fraudulent Refund (FT1304), Refund: Refund to Gift Card (FT1304.001), Refund: Double Refund (FT1304.002), Refund: Non-Receipted Returns (FT1304.003), Cryptocurrency (FT1403), Gift Cards as Defense Evasion (FT1404), Checkout (FT1303), Gift Card Redemption (FT1204)

---

### FD1011 — Market Resale Data

**Description:** Monitor sales of items through third-party market monitoring and other resale data.

**Techniques Detected:** Resale: Unwitting Buyer (FT1301.002)

---

### FD1012 — Controlled Purchase

**Description:** Purchase items from Third Party Supplier to identify indicators of fraud.

**Techniques Detected:** Third Party Supplier Manipulation (FT1008)

---

### FD1013 — Item Condition & Tag Checks

**Description:** Ensure item is returned with all its components such as packaging, accessories, and documentation in good condition. Verify additional attributes such as weight, general wear and tear.

**Techniques Detected:** Wardrobing (FT1209)

---

### FD1014 — Credit Redemption Behavior

**Description:** Monitor for the consolidation of in-store credit gift cards to purchase high value items or issued to multiple identities (e.g. electronics).

**Techniques Detected:** Fraudulent Refund (FT1304), Refund: Non-Receipted Returns (FT1304.003)

---

### FD1016 — Location Attributes

**Description:** Identify mismatch between billing and shipping address. Identify illegitimate or fake addresses.

**Techniques Detected:** Marketplace Exploitation (FT1302), Marketplace Exploitation: Fraudulent Delivery (FT1302.001), Digital Wallet Apps (FT1402)

---

## References

- **Authentication and Access to Financial Institution Services and Systems**  
  https://www.ffiec.gov/guidance/Authentication-and-Access-to-Financial-Institution-Services-and-Systems.pdf

- **Authentication and Lifecycle Management SP 800-63B**  
  https://doi.org/10.6028/NIST.SP.800-63b

- **Detecting and Reporting the Illicit Financial Flows Tied to Organized Theft Groups (OTG) and Organized Retail Crime (ORC)**  
  https://www.acams.org/en/media/document/29436

- **MITRE ATT&CK**  
  https://attack.mitre.org/

- **Top 10 Digital Commerce Account Risks & How to Mitigate Them by Gunnar Peterson**  
  https://www.forter.com/blog/rh-isac-account-risk-mitigation/

- **Avoiding and Reporting Gift Card Scams**  
  https://consumer.ftc.gov/articles/avoiding-and-reporting-gift-card-scams#commonscams

- **Industry Partner Collaboration**  
  *(Source not listed to obfuscate partner defenses)*
