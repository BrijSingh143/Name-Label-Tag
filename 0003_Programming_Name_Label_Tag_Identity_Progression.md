## Programming Domain

 The same **Name → Label → Tag → Identity → Role → State → Relationship** progression maps nicely to programming concepts:

 | Level | Programming concept | Human analogy | Question answered |
| --- | --- | --- | --- |
| **Name** | Variable / Function / Class name | Rahul | **What do we call it?** |
| **Label** | Type / Class / Interface | Manager | **What kind of thing is it?** |
| **Tag** | Annotation / Attribute / Metadata | Skills / interests | **What properties are attached to it?** |
| **Identity** | Object identity / Reference | Unique person | **Which exact instance is it?** |
| **Role** | Interface / Responsibility | Job/function | **What is it supposed to do?** |
| **State** | Object / Variable state | Current condition | **What is its current condition?** |
| **Relationship** | Reference / Dependency / Association | Connection with others | **How is it connected?** |
| **Scope** | Local / Global / Module / Class scope | Social context | **Where does it exist?** |
| **Behavior** | Method / Function implementation | How a person acts | **How does it behave?** |
| **Contract** | Interface / API / Type contract | Expected responsibilities | **What does it promise?** |
| **Configuration** | Parameters / Environment / Settings | Personal preferences | **How is its behavior controlled?** |
| **Execution** | Call stack / Runtime / Process | Person actively performing | **What is happening now?** |
| **Dependency** | Library / Module / Service dependency | Reliance on another person | **What does it depend on?** |
| **Structure** | AST / Object graph / Module graph | Organization | **How is the program constructed?** |
| **System Model** | Architecture / Runtime system | Complete social ecosystem | **How does everything work together?** |

### Example

 For a programming object:

```
Name         → User
Label        → Class / Entity
Tags         → Serializable, Persistent, Auditable
Identity     → Object reference / ID
Role         → Represents an application user
State        → active = true
Scope        → User module
Behavior     → login(), logout(), changePassword()
Contract     → IUser
Relationships
             → belongs to Organization
             → has Roles
             → depends on AuthService
Dependencies → Database, AuthService
Configuration→ Environment / constructor parameters
Execution    → Currently processing login()
```

 ### Conceptual progression

 The progression becomes:

 **Name → Type → Metadata → Identity → Role → State → Scope → Behavior → Contract → Relationship → Dependency → Execution → Structure → Architecture**

 Or at a higher conceptual level:

 > **Name → Classify → Describe → Identify → Assign responsibility → Track state → Define behavior → Define contracts → Connect → Depend → Execute → Compose → Architect**

 ### Across the three domains

 You now have a useful common abstraction:

 | Human | Networking / Infrastructure | Programming |
| --- | --- | --- |
| Name | Hostname | Variable / Function / Class name |
| Label | Device type | Type / Class |
| Tag | Metadata tag | Annotation / Attribute |
| Identity | Device ID / UUID | Object identity / Reference |
| Role | Server / Router / Firewall role | Interface / Responsibility |
| State | Up / Down | Object / Variable state |
| Relationship | Network connection | Reference / Dependency |
| Location | Rack / DC / Region | Scope / Module |
| Behavior | Traffic / telemetry | Function / Method |
| Structure | Network topology | Object / Module graph |
| System | Infrastructure architecture | Software architecture |

**Core idea:**

 > **Name tells you what to call it. Label tells you what kind of thing it is. Tag tells you what attributes are attached to it. Identity tells you which exact instance it is. Role tells you what it does. State tells you what condition it is in. Relationship tells you how it connects to other things.**

 ### Recommended file name

 `Programming_Name_Label_Tag_Identity_Progression.md`

 Other options:

 - `Programming_Conceptual_Progression.md`
- `Programming_Identity_Role_State_Relationship.md`
- `Programming_Name_Type_Metadata_Progression.md`
- `Programming_Object_Identity_And_Metadata.md`
