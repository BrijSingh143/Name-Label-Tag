Here is a concise, reusable README designed as a **cross-domain naming guide**.

 Name, Label & Tag — Cross-Domain Guide✓

# Name, Label & Tag

 A simple cross-domain framework for identifying and organizing IT entities.

 ## Core Rule

 > **Name identifies. Label classifies. Tag describes.**

 | Concept | Purpose | Question | Example |
| --- | --- | --- | --- |
| **Name** | Identity in human-readable form | **What do we call it?** | `web-prod-01` |
| **Label** | Classification / type | **What kind of thing is it?** | `Web Server` |
| **Tag** | Flexible metadata / attributes | **What describes it?** | `prod`, `frontend`, `critical` |

## Cross-Domain Examples

 | Domain | Name | Label | Tags |
| --- | --- | --- | --- |
| Computer | `DEV-LAPTOP-01` | Laptop | `developer`, `mobile` |
| Networking | `core-sw-01` | Switch | `core`, `datacenter` |
| Software | `PaymentService` | Backend Service | `payments`, `critical` |
| Programming | `UserService` | Class / Service | `auth`, `api` |
| Cloud | `prod-web-01` | Compute Instance | `prod`, `web` |
| Security | `alice@example.com` | User Identity | `privileged`, `engineering` |
| AI | `SupportAgent` | AI Agent | `support`, `production` |

## Naming Rules

 ### Name

 Use a **stable, unique, human-readable identifier**.

```
<domain>-<purpose>-<environment>-<sequence>
```

 Example:

```
web-prod-01
```

 ### Label

 Use a **controlled vocabulary** representing the entity's type or classification.

```
Web Server
Database
AI Agent
Developer
Network Switch
```

 ### Tag

 Use **short, reusable metadata** for filtering, grouping, search, and automation.

```
environment=production
team=platform
location=mumbai
criticality=high
```

 ## Decision Rule

 When creating new metadata, ask:

 1. **Is this the entity's primary identifier?** → **Name**
2. **Is this its type or classification?** → **Label**
3. **Is this additional descriptive metadata?** → **Tag**

 ## Principle

 Keep the three separate:

```
Name  → Identity
Label → Classification
Tag   → Metadata
```

 This framework can be applied consistently across **Computer, Programming, Software, Networking, Cloud, Security, AI, DevOps, and other IT domains**.
