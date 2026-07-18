# Network Design

```
                    corp.local

                  +-----------+
                  |   DC01    |
                  | Server2022|
                  | AD DS/DNS |
                  +-----------+
                      |
        -----------------------------
        |                           |
+----------------+          +----------------+
|   CLIENT01     |          |   CLIENT02     |
|   Windows 10   |          |   Windows 11   |
| Domain Joined  |          | Domain Joined  |
+----------------+          +----------------+
```

Current Components

- Active Directory Domain Services
- DNS
- Two domain-joined Windows workstations
