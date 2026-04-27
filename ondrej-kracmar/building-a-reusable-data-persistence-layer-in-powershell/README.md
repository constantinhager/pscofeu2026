# Building a reusable data persistence layer in PowerShell

## Abstract

PowerShell scripts often handle data in inconsistent ways – JSON files, CSV exports, temporary storage, or direct API calls. Over time, this leads to duplicated logic, hard-to-maintain scripts, and a lack of standardization.

In this short Open Stage session, I’ll present a simple approach to standardize data persistence in PowerShell using a repository-style abstraction.

Instead of each script implementing its own way of storing and retrieving data, this pattern introduces a consistent interface and separates data handling from business logic.

The session includes a short live demo showing how to:
- store and retrieve data in a consistent way
- switch between different backends (FileSystem, Azure Blob)
- simplify automation workflows

If you’ve ever struggled with maintaining scripts that pass data around in different formats, this session will give you a practical pattern you can start using immediately.
