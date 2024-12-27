# Elixir Enum.each Unexpected Behavior When Modifying List During Iteration

This example demonstrates an unexpected behavior when attempting to modify a list within an `Enum.each` loop in Elixir.  The `Enum.each` function is designed for side effects (like printing to the console), but it doesn't return a modified list. Attempting to modify the list directly within `Enum.each` will not produce the intended result and may lead to unexpected behavior. This example shows how to correctly modify the list using `Enum.reduce` or `Enum.filter` for a more robust solution.
