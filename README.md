# Elixir Enum.each and throw

This example demonstrates unexpected behavior when using `throw` within an `Enum.each` loop in Elixir.  The `throw` statement terminates the loop prematurely, even though it appears the loop would continue after a conditional check. This might be surprising to developers expecting `throw` to only affect the current iteration.