# Elixir Enum.each and throw

This example demonstrates a potential issue when using `Enum.each` in Elixir with `throw`.  While `throw` can halt execution within the function and bubble up the exception, it is crucial to understand how it interacts with `Enum.each` to prevent unintended side-effects.  The included solution handles the exception to prevent unexpected termination and instead handles it gracefully.