# From Scripts to System Calls with PowerShell

## Abstract

The Win32 API is one of the oldest yet most essential pillars of the Windows operating system. Written in C and predating PowerShell by decades, it often feels like the polar opposite of the scripting world we know. Fortunately, PowerShell’s foundation in C# provides a powerful bridge: P/Invoke. This compatibility layer allows PowerShell to call directly into native C APIs, opening the door to parts of Windows that most administrators rarely touch.

In this session, we’ll explore how to uncover and understand Win32 APIs, translate their interfaces into forms that P/Invoke can consume, and manage memory safely while interacting with them. Along the way, you’ll see how PowerShell can be extended far beyond its usual boundaries, enabling you to read, write, and manipulate the operating system at a deeper level. Expect practical demonstrations, insights from real-world use, and a new appreciation for how PowerShell and P/Invoke together can unlock hidden capabilities within Windows.
