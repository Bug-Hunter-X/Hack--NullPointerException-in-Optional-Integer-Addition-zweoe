# Hack: NullPointerException in Optional Integer Addition

This repository demonstrates a potential runtime error in Hack when dealing with optional integers and addition. The function `foo` adds 1 to its input `x`, which is an optional integer (`?int`). If `x` is `null`, the addition will result in a runtime error.  The Hack type system doesn't catch this because it's a runtime issue, not a compile-time issue. 

The `bug.hack` file contains the buggy code. The `bugSolution.hack` file provides a corrected version that handles the null case gracefully.