Hello Zine

```terminal
             MapResolver               MapProvider
                 │                          │
   Resolve       │                          │
────────────────►│                          │
                 │                          │
              ┌─ │        Retrieve          │
              │  ├─────────────────────────►│
              │  │                          │
              │  │◄─────────────────────────┤
   foreach    │  │                          │
  configURI   │  ├───┐                      │
              │  │   │Merge                 │
              │  │◄──┘                      │
              └─ │                          │
                 │          MapConverter    │
                 │                │         │
              ┌─ │     Convert    │         │
              │  ├───────────────►│         │
   foreach    │  │                │         │
 MapConverter │  │◄───────────────┤         │
              └─ │                          │
                 │                          │
◄────────────────┤                          │
                 │                          │
```