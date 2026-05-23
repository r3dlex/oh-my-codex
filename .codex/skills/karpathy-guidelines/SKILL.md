# karpathy-guidelines

Behavioral guidelines to reduce common LLM coding mistakes. Use when writing, reviewing, or refactoring code to avoid overcomplication, make surgical changes, surface assumptions, and define verifiable success criteria.

**License:** MIT

## Trigger Patterns

Apply these guidelines when:
- Writing new code
- Reviewing code
- Refactoring code

## Core Guidelines

**1. Think Before Coding**
- State assumptions explicitly; ask if uncertain
- Present multiple interpretations rather than choosing silently
- Push back when simpler approaches exist
- Stop and ask if something is unclear

**2. Simplicity First**
- Minimum code that solves the problem
- No speculative features or abstractions
- Rewrite if 200 lines could be 50

**3. Surgical Changes**
- Touch only what must be changed
- Match existing style, even if you'd do it differently
- Remove only what your changes made unused
- Don't improve unrelated code

**4. Goal-Driven Execution**
- Transform tasks into verifiable goals
- Write tests that reproduce issues before fixing
- State multi-step plans with verification checkpoints
