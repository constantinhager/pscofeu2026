# Watch Your Step! Building Long-Running Scripts That Don't Trip Over Themselves

## Abstract

We've all been there. It's 11pm, you're running a 45-minute deployment script, and it fails at step 37 of 42. Cool. Cool cool cool. Now you get to start over. Or worse, you're not sure where it failed, so you spend 20 minutes poking around before you dare re-run anything.

Long-running automation is fragile. Networks drop. Systems reboot. Someone presses Ctrl+C. Your toddler walks in and demands breakfast. Reality happens.

I got tired of this, so I built Stepper: a small PowerShell module that lets you break scripts into discrete steps that automatically save their progress. When something goes wrong (or life happens), just run it again. It picks up where it left off.

It's basically a really simple PowerShell Workflow that actually works in PS7+!

In this session, I'll show you how to structure scripts as resumable steps, persist state across interruptions, and build configuration-driven automation that doesn't make you want to mass-delete your repo. We'll live-code an example, kill it mid-run on purpose, and watch it recover like nothing happened.

You don't have to use Stepper to get something out of this talk. The patterns apply whether you're using my module or rolling your own. If you build deployments, migrations, health checks, or any multi-step automation, you'll leave with ideas you can use immediately. Stop restarting from scratch and start building scripts that remember where they were.
