# How We Enabled PSReadLine for Screen Reader Accessibility

## Abstract

Follow along a deep dive into our design, prototype, iteration, and development process for enabling PSReadLine to be used with screen readers. While we always want to make our software as accessible as possible, we had an open issue with PSReadLine's renderer causing many common screen reader programs to be unusable with it. The problem was so complex that the initial workaround was simply to fallback to PowerShell's builtin prompt instead. Hear about how we came back with some fresh ideas (some of which didn't work) to solve this problem once and for all, and see new VS Code Terminal Shell Integration accessibility features this work unblocked.

Includes an inside look at our early design document, how we tested and scoped the project, code review of the first prototype, the iteration phase after a fundamental flaw was uncovered, and a walkthrough of the code change for the final implementation. You'll see (and hear) actual testing, debugging, and demonstrations.
