# Method to the Madness - How PowerShell Invokes .NET Methods

## Abstract

Ever wondered why PowerShell picked that overload when you called a .NET method? This session demystifies PowerShell's method resolution engine, revealing how it selects between overloads, casts your script values to .NET types, and handles generic methods. We'll explore the ranking algorithm that picks "the best" match, uncover how PowerShell's flexible type system can lead to surprising conversions, and tackle the special challenges of generic method invocation. You'll also learn how PowerShell handles ref and out parameters and how to use them. Along the way, we'll hit the common gotchas that trip up even experienced PowerShell developers - from ambiguous overloads to unexpected null handling and array wrapping surprises. By the end, you'll understand exactly what happens when PowerShell translates your script calls into .NET method invocations, and how to write code that behaves predictably.

Key Takeaways:

+ Understand PowerShell's method overload resolution and ranking algorithm
+ Learn how PowerShell casts script values to match .NET parameter types
+ Master generic method invocation patterns and workarounds
+ Handle ref and out parameters correctly in PowerShell method calls
+ Avoid common pitfalls with nulls, arrays, and ambiguous overloads
