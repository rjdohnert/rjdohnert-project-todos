## July 13, 2026

## Todo

1. Replace placeholder command substitution behavior with real subprocess capture for $(...).
2. Ensure shell status variable $? always reflects real child process exit code.
3. Implement standard input/output/error redirection operators.
4. Add support for command pipelines using | between commands.
5. Improve tokenization to correctly handle quoted text and escapes.
6. Implement deterministic expansion order for variables, arithmetic, and command substitution.
7. Add common parameter expansion forms needed by many shell scripts.
8. Improve conditional parsing and evaluation for [[ ... ]].
9. Implement core conditional control flow for script execution.
10. Add elif support
11. Implement loop constructs required for script portability.
12. Expand array handling and typeset behavior closer to expected ksh semantics.
13. Implement function definitions and invocation with scoped variable behavior.
14. Stabilize job lifecycle and command semantics for background control.
15. Improve quoting and command construction to prevent splitting/injection mistakes.
16. Reduce completion latency and improve result relevance.
17. Add configurable history management options.
18. Support startup profile script execution for customization.
19. Add repeatable automated validation for shell behavior.
20. Document supported and unsupported behavior clearly.

## Estimated Time Of Completion

2 months estimated, it truly will depend on how much time I have to dedicate to the shell

