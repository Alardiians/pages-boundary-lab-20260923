# Owned Mermaid callback probe

```mermaid
flowchart LR
 A[CLICK_OWNED_CANARY] --> B[SAFE]
 click A call eval("window.__ownedMermaidCallback=1") "Inert callback"
```
