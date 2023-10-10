# MyCLF-C01-guidance with following 4 domains:

### 🟦 Cloud Concept

    ◆ What is cloud Computing
      - 6 advantage of cloud
      - economic of scale

    ◆ AWS Architecture & Ecosystem
      - AWS well-architecture framework with 6 pillar
      - AWS Cloud Adoption framework
      - Ecosystem
        - AWS support plan
        - AWS Market place
        - AWS professional service & APN

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

---

### 🟩 Bill & Pricing
