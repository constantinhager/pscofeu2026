# Spawn of a Shell - Handling Sub Processes

## Abstract

Running external programs and managing child processes is a fundamental scripting task, yet it's often hard to understand what way it can be done in PowerShell. This session explores the various ways to invoke external executables, capture their output and errors, monitor exit codes, and handle long-running processes gracefully. We'll compare Start-Process with direct invocation, uncover the pitfalls of output redirection and encoding issues, and tackle challenges like handling errors, argument escaping. Learn how to properly parse and validate command output, handle credential scenarios, and coordinate multiple background processes. You'll also discover why sometimes PowerShell's approach differs from traditional shell scripting and how to work with the underlying process objects. By the end, you'll know how to reliably spawn and manage sub-processes in ways that are robust, maintainable, and integrate smoothly with PowerShell's pipeline.

Key Takeaways:

+ Invoke external processes and capture output correctly
+ Understand Start-Process and direct invocation trade-offs
+ Handle exit codes, errors, and process failures reliably
+ Manage encoding, newlines, argument escaping, and output parsing challenges
