# Creating an Organizational Password Policy

An organizational password policy enforces consistent password complexity, length, and rotation requirements across all domain users. This reduces the risk of unauthorized access caused by weak or reused passwords and helps ensure compliance with baseline security best practices.

---

## Prerequisite: Group Policy Management

Before a domain-wide password policy can be created, **Group Policy Management (GPMC)** must be available within an Active Directory domain.

![Install GPMC / AD DS](insert-gif-here)

When this lab environment was initially deployed, the server was installed as a standalone system. As a result, authentication was limited to local user accounts.

Domain Group Policy Objects are stored in and applied through **Active Directory**, meaning Group Policy Management cannot function without a domain context.

To enable centralized authentication and policy enforcement, the **Active Directory Domain Services (AD DS)** role must be installed and the server promoted to a **Domain Controller**.

---

## Domain Controller Deployment Overview

This is a three-step process:

1. Install Active Directory Domain Services (AD DS)  
2. Promote the server to a Domain Controller  
3. Log in using the correct domain account  

![AD DS Installation and Promotion](insert-gif-here)

*(The GIF quality is not ideal but demonstrates the process flow.)*

---

## Password Policy Configuration

Once logged in with a **domain administrator account**, the organizational password policy is configured using **Group Policy Management**.

Password policies configured at the domain level apply uniformly to all domain users unless **fine-grained password policies** are explicitly created.

At this stage, the domain password policy is created and implemented.

![Password Policy Configuration](insert-gif-here)

---

## Result

This configuration ensures that all domain users follow consistent password security standards.

Centralizing password policy enforcement through Active Directory reduces the risk of weak credentials and simplifies administrative control across the organization.
