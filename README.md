# Creating an Organizational Password Policy

An organizational password policy enforces consistent password complexity, length, and rotation requirements across all domain users. This reduces the risk of unauthorized access caused by weak or reused passwords and helps ensure compliance with baseline security best practices.

---

## Prerequisite: Group Policy Management

Before a domain-wide password policy can be created, **Group Policy Management (GPMC)** must be available within an Active Directory domain.

<img src="https://github.com/user-attachments/assets/491bda20-5e95-445d-9082-231f658d5ccf" alt="Install AD DS" width="900">

---

When this lab environment was initially deployed, the server was installed as a standalone system. As a result, authentication was limited to local user accounts.

Domain Group Policy Objects are stored in and applied through **Active Directory**, meaning Group Policy Management cannot function without a domain context.

To enable centralized authentication and policy enforcement, the **Active Directory Domain Services (AD DS)** role must be installed and the server promoted to a **Domain Controller**.

---

## Domain Controller Deployment Overview

This is a three-step process:

1. Install Active Directory Domain Services (AD DS)  
2. Promote the server to a Domain Controller  
3. Log in using the correct domain account  


<img src="https://github.com/user-attachments/assets/36055359-2cc9-400c-8335-822e9d55fd80" alt="Install AD DS" width="900">



*(The GIF quality is not ideal but demonstrates the process flow.)*

---

## Password Policy Configuration

Once logged in with a **domain administrator account**, the organizational password policy is configured using **Group Policy Management**.

Password policies configured at the domain level apply uniformly to all domain users unless **fine-grained password policies** are explicitly created.

At this stage, the domain password policy is created and implemented.

<img src="https://github.com/user-attachments/assets/6177e6bc-6226-4652-a3d0-4afbdc469a3f" alt="Install AD DS" width="900">

---

## Result

This configuration ensures that all domain users follow consistent password security standards.

Centralizing password policy enforcement through Active Directory reduces the risk of weak credentials and simplifies administrative control across the organization.







