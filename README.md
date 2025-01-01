# Kotlin Map Function and Nullable Lists

This example demonstrates a common error when using the `map` function in Kotlin with nullable lists. If you don't handle the null case appropriately, a `NullPointerException` can occur.

The `BuggyMap.kt` file shows the problematic code, while `FixedMap.kt` presents the corrected version using safe-call and Elvis operators to gracefully handle null lists.

## How to Reproduce
1. Compile and run `BuggyMap.kt`.
2. Observe the `NullPointerException` when `nullableList` is null.
3. Compile and run `FixedMap.kt`. 
4. Observe the correct output, demonstrating that the null case is handled properly. 
