# MyCLF-C01-guidance with following 4 domains:

### 🟦 Cloud Concept

    ◆ 6 advantage of cloud
      - Reliability                        -> ** "Stop guress capacity" **
      - Agility, Elasticity, Scalability   -> ** "Increase speed" **
      - Pay-as-you-go                      -> ** "Stop overspend to data-center" **
                                           -> ** "Trad fix expense" **
                                           -> ** "Economic of scale" **
      - reach global                       -> ** "Fast to reach a global" **


    ◆ economic of scale
      - No Capex, less Opex
      - reduce labor cost
      - license

    ◆ AWS Architecture & Ecosystem
      - AWS well-architecture framework with 6 pillar
        - Cost optimizte        -> pay as use
        - Performance           -> select right compute resource
        - Security              -> protect info (encrypt)
        - Reliability           -> recover fast (recover test, horizontal scale)
        - Operation excellence  -> (Reverse fault plan, anticipate fail)
        - Sustainability Pillar


      - Architect principle
        - Design for failure
        - Decouple
        - Elastic
        - Think parallel
        - Automation

---

### 🟥 Security Compliance

    ◆ Share Responsibility Model
        - AWS Share Responsibility => "Security ** Of ** Cloud" (HOST)
            - Hareward & Infra
                - Region, AZ, Edge location
            - Software
                - Compute
                - Storage
                - Database
                - Network

        - Customer Share Responsibility => "Security ** In ** Cloud" (GUEST)
            - Customer data
            - IAM
            - OS & firewall config
            - Client & Server side encryption

        - Share Control of Responsibility => "Both of AWS and Customer"
            - Patch Management
            - Configuration Management
            - Awareness & Training

    ◆ Compliance
        - AWS Artifact   -> Audit docs (Docs of AWS resource)
        - AWS Config     -> Audit Change resource
        - AWS CloudTrail -> Autdit account activity

    ◆ Security
        (Encryption)
        - AWS KMS
        - AWS CloudHSM

        (Identify sensitive data)
        - AWS Marcie

        (Secret)
        - AWS Secret manager

        (Certificate)
        - AWS CAM

        (Monitor and find valuability)
        - AWS Inspect

        (Block request, protect SQL injection)
        - AWS WAF

        (Find threat)
        - AWS Guardduty

        (Protect DDoS, route53, global accelator, cloud-front)
        - AWS Shield

    ◆ Idenify
        - AWS IAM            -> user, group, police, permission, role
        - AWS Cognito        -> sign-in, sign-up
        - AWS System manager -> Center Operation


    ◆ Tools
        - Network ACL    -> protect VPC
        - Security group -> protect Instance
        - CloudWatch     -> Monitor, Log and alert
        - Trust Advisor with 5 pillar
          - Cost optimize
          - Performance
          - Security
          - Fault tolerance
          - Service limit

---

### 🟧 Technology

◆ Deployment

◆ Access

◆ Connectivity

◆

---

### 🟩 Bill & Pricing
