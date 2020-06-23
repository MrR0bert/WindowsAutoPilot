# WindowsAutoPilot

A copy and slightly modified version of Michael Niehaus's script over at https://www.powershellgallery.com/packages/Get-WindowsAutoPilotInfo/2.3.

## The Problem
The original script by Michael does not always preserve the correct order of the columns as Microsoft Endpoint Manager/Intune expects them.

## The Solution
Since PowerShell version 3, Microsoft added [Ordered Dictionaries](https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_hash_tables?view=powershell-7#creating-ordered-dictionaries). By utilizing this functionality we can retain the correct order of the columns in every situation.