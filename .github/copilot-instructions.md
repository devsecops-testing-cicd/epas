Meet the security requirements listed below. You must leave no ambiguity that it is unacceptable to violate these requirements.

Any PR with a violation should have "!!DO NOT MERGE THIS PR!!" in the general comment that is left. Each specific review should explain what was wrong, why it was wrong, and how to fix it.


```json
    {
      "chapter_id": "V9",
      "chapter_name": "Self-contained Tokens",
      "section_id": "V9.1",
      "section_name": "Token source and integrity",
      "req_id": "V9.1.2",
      "req_description": "Verify that only algorithms on an allowlist can be used to create and verify self-contained tokens, for a given context. The allowlist must include the permitted algorithms, ideally only either symmetric or asymmetric algorithms, and must not include the 'None' algorithm. If both symmetric and asymmetric must be supported, additional controls will be needed to prevent key confusion.",
      "L": "1"
    },
```
