# Further Documentation
## User Stories
<!-- As a **user/role**, I want to **goal** so I can **rationale** -->
- As a **Anonymous User**, I want to **signup for a mailing list** so I can **recieve a newsletter**
  - Set up a Form and attach it to Webpage.
- As a **Public Relations Specialist**, I want to **send a newsletter** so I can **create engagement**
    - Set up Email Automation Platform
- As a **FOTP Member**, I want to **view a calendar** so I can **find events near me**
   - Setup CalDav server using Radicale, and configure access per member.
- As a **FOTP Member**, I want to **see other FotP ** so I can **contact them**
   - Setup CardDav server using Radicale, and configure access per member.
- As an **Administrator**, I want to **View, Manage, and Monitor User Access** so I can **follow The principle of least privilege (PoLP)**
  - Enable logging when and remember to check logs at a determined interval for Risk tolerance.
## Mis-User Stories
<!-- In addition to the user stories identify the ways in which users might be able to mis-use your app. Mis-user stories are just like user stories except the user, goal, and rationale are malicious. -->
- As a **Spammer**, I want to **download the Subscriber email list** so I can send **Spam**
  - ATT&K Tactics: Initial Access (TA0001), Collection (TA0009)
  - Risk Reduction 
    - (Implemented) Newsletter email list hosted via an industry trusted Email Automation Platform
- As a **Hacker**, I want to **steal Member Credentials** so I can **utilize Member services**
  - ATT&K Tactic: Credential Access (TA0006)
  - Risk Reduction

- As a **nefarious FOTP Member**, I want to **bypass Authorization controls** so I can **control various backend systems**
    - ATT&K Tactic: Privilege Escalation (TA0004)
    -  Risk Reduction

[To ReadMe](../README.md)
