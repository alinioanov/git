# git
```mermaid
gitGraph
    commit id:" "
    branch qa
    commit id:"  "
    checkout prod
    branch dev
    commit id:"   "
    checkout prod
    commit id:"..."
    checkout qa
    commit id:"... "
    checkout dev
    commit id:"...  "
    checkout prod
    commit id:"       "
    branch CDP-FINANCE-REL0
    checkout CDP-FINANCE-REL0
    commit id: "        "
    checkout CDP-FINANCE-REL0
    branch CDPOFT-1234
    checkout CDPOFT-1234
    commit id: "1. Create from CDP-FINANCE-REL0"
    checkout CDP-FINANCE-REL0
    commit id:"...     "
    checkout CDPOFT-1234
    commit id: "2. Make commit(s)"
    checkout CDP-FINANCE-REL0
    commit id:"          "
    checkout CDPOFT-1234
    merge CDP-FINANCE-REL0 id:"3. Merge CDP-FINANCE-REL0"
    checkout CDP-FINANCE-REL0
    merge CDPOFT-1234 id:"3. Merge to CDP-FINANCE-REL0"
    checkout prod
    commit id:"            "
    checkout prod
    commit id:"....     "
    checkout CDP-FINANCE-REL0
    merge prod
    checkout dev
    merge CDP-FINANCE-REL0
    checkout qa
    merge CDP-FINANCE-REL0
    checkout prod
    merge CDP-FINANCE-REL0
    commit id:"                "
    checkout qa
    commit id:"                 "
    checkout dev
    commit id:"                  "
```
