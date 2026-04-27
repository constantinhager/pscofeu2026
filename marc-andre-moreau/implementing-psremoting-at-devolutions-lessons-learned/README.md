# Implementing PSRemoting at Devolutions: Lessons Learned

## Abstract

Implementing PSRemoting inside real products exposes a surprising number of practical challenges. From PowerShell SDK limitations and assembly load conflicts to WinRM configuration quirks, TrustedHosts behavior, and the realities of NTLM and Kerberos authentication, integrating PowerShell remoting into production systems quickly becomes more complicated than the documentation suggests.

In this session, we’ll walk through the lessons learned while building PSRemoting integrations in C#, exploring different transports such as WinRM, SSH, and stdin/stdout subprocess communication. Along the way we’ll look at the tradeoffs behind these approaches and the techniques used to work around platform limitations to deliver reliable remoting features in real-world software.
