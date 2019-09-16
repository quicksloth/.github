---
title: '[Tech Debt] TD Title'
labels: tech-debt
---
<!-- Just for template purpose /\ -->

# Tech Debt Title

## Summary

> TL;DR: A simple summary about the tech debt
**Age:** { LEGACY | NEW_TECH_DEBT_INTRODUCED }

<!-- 
  Age labels:
  - LEGACY: found in the codebase and being document right now.
  - NEW_TECH_DEBT_INTRODUCED: we consciously added a new tech debt in our code base right now and we're document it.
-->

**Estimated cost:** { SIMPLE | COMPLEX | INVESTIGATION_NEEDED }
<!-- going to transform also in a label -->

<!-- 
  Estimated cost labels:
  - SIMPLE: It's simple to identify the solution and clearly simple to solve and test.
  - COMPLEX: It's not so simple to understand and fix it. it also may require big refactorings.
  - INVESTIGATION_NEEDED: There's a lot of unknowns related that it's impossible to say until it's prioritized, invetigated and have proposed solutions.
-->

### Description :clipboard:

A clear and concise description of what the tech debt is and the reason of being created

### Impact :bomb:

Description of the current or possible impact of this tech debt.

<!-- estimated -->
**Critical in**: { N MONTHS | N YEARS | UNKOWN }

### Proposed solutions :squirrel:

_How would you fix it?_

<!-- 
Here you should add only hints, context, and opinions and 
but let the solution proposal in a PR for ADR.
-->

> (if don't you have any solution in mind, write it)
This Tech debts still don't have any proposed issue.

> (if you have solutions in mind, describe it below)
**Solution 1.**

- How

- Pros :green_heart:

- Cons :broken_heart:

## Observations :thinking:

### Files related

[files related](files_related_link.file)

### Other evidences

#### Depends on issue X
