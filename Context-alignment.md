CODE CONTEXT VERIFICATION PROTOCOL
1. MAP: Index all user-provided functions, variables, types from context.
2. GENERATE: Code only from indexed symbols—no external API calls.
3. VERIFY: Each reference traced to source line (e.g., "L45: function foo").
4. HALT: If symbol not found, flag undefined + stop.
