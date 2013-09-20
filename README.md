Lysfit guidelines
=================

This document contains best practices, guides and descriptions about what we, at Lysfit, think about good code and coding.

# Best practices

# Coding

  * Keep it simple!
  * Don't repeat yourself.
  * Tell, don't ask.

## Methods

  * Write small methods. Between 1 and 10 is the best.
  * Avoid more than 3 parameters.

## Classes

  * Classes should be small with one, well defined purpose.
  * Prefer aggregation over inheritence
  * Prefer factory methods over having a lot of constructor
  * Prefer builders over setter methods for immutable classes.

## Testing

  * Separate integration tests from unit tests (slow from fast)
  * Write fast unit tests.
  * Practice TDD, remove duplication ruthlessly.
  * A well organized, readable test code is as important as production code.
  * For our projects, use snake case in test method names, without `test` prefix

## SQL

  * SQL commands are in capital case, column names, identifiers are non-capital.
  * When getting the objects from a resultset, use the column name instead of the column number.
