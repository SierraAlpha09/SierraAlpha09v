# Tekmirio
**Civic information with traceable document evidence**

[Public app](https://tekmirio.lovable.app) · [Portfolio overview](../../README.md)

## The problem
Official documents contain numbers and statements whose meaning depends on context. An extracted amount may be a net value, a tax component or a total. A useful civic-information product needs to preserve that context and distinguish draft extraction from reviewed information.

## My role
I own the product direction and direct development with AI assistance. My contribution includes defining evidence requirements, reviewing interpretation problems, setting acceptance criteria and guiding validation and publication behaviour.

## Selected decisions
- Connect candidate facts to source evidence and explicit verification status.
- Separate review and publication, with distinct role permissions.
- Preserve the meaning of net, tax and total values to avoid double counting.
- Leave ambiguous information pending review rather than publishing an unsupported conclusion.

## A concrete example
Consider a synthetic source containing a net amount of EUR 100 and tax of EUR 24. The calculated total is EUR 124, not EUR 248 of independent expenditure. The total must also be labelled as derived rather than quoted from the source.

This example illustrates the requirement without reproducing a real record or the private implementation.

## Validation approach
The project includes amount-interpretation logic and regression cases for publication readiness. Review focuses on the relationship between a candidate fact, its source evidence and whether it is suitable for publication.

## Relevant capabilities
Requirements analysis · structured data · evidence traceability · data validation · regression criteria · human review · AI-assisted development.

## Explore
The public app demonstrates the product experience. This is an active independent project; internal review records and application source remain private.
