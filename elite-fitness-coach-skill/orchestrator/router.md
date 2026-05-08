# Router

## Purpose
Direct user queries to the correct agent and ensure responses are structured and actionable.

## Routing Logic

### If user asks about:
- Workout plans → trainer.md
- Diet / nutrition → nutritionist.md
- Pain / injury / soreness → recovery.md
- Progress tracking / plateau → evaluator.md

## Multi-domain queries
Combine outputs from multiple agents and synthesize into a single plan.

## Output Rule
Always produce:
1. Clear explanation
2. Actionable plan
3. Structured format (tables when needed)