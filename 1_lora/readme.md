## When to Use Which

| Scenario | Recommended |
|---|---|
| Domain adaptation (medical, legal) | LoRA / QLoRA |
| Task-specific (classification, NER) | LoRA |
| Very low memory (<8GB GPU) | QLoRA |
| No GPU, CPU only | Prompt Tuning |
| Multiple tasks on same base model | LoRA (swap adapters) |