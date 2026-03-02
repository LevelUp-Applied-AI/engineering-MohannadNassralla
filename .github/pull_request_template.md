What? What changed? Summarize the major modifications — file-level or behavior-level — without requiring the reviewer to read the entire diff first.

Why? What problem does this solve? What context drove this decision? What alternatives were considered and rejected? This is the most important part of a description that engineers routinely skip.

How? What significant design decisions were made? If a recursive approach was used where a loop would also work, say why. If a third-party library was introduced, say why. The diff shows the code; the description explains the reasoning.

Test? How does the reviewer verify this works? What commands to run, what output to expect, what edge cases were covered. If tests are included, explain what they check. If they are not, say why.

- [ ] Tests added or updated
