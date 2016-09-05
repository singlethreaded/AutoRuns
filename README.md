AutoRuns PowerShell Module
==========================

This is basically the Powershell version of SysIntenal's Autoruns.  Forked to add backwards compatibility with Powershell 2.0 and CLR 2.0 for inclusion in the PSHunt Project.

Known problems: Uses schedule.service com object to access scheduled tasks.  This com object doesn't exist on Win2k3.  Still works but Scheduled tasks will be missed.