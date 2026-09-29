# Maya Asset Validation & Pipeline Tool

A Maya pipeline tool designed to reduce human error during asset preparation and handoff.

The tool focuses on validating common production requirements before assets are exported or passed further down the pipeline.

## Overview

During production, repetitive asset checks can easily lead to human error, especially when artists need to verify naming conventions, scene cleanliness, transformations, and asset preparation manually.

This tool was created to automate part of that process and provide clear feedback before export or engine integration.

## Features

- Asset naming validation
- Duplicate name detection
- Freeze transformation checks
- Construction history checks
- Scene cleanup validation
- Unused material / shading node checks
- Automatic asset renaming
- Clear warnings and status feedback
- Pre-export asset verification

## Workflow

1. Select or prepare assets in Maya
2. Run the validation tool
3. Review detected issues
4. Fix issues manually or use supported automated actions
5. Re-run validation
6. Export assets once all required checks are complete

## Goal

The main goal of this tool is to:

- Reduce repetitive manual QA
- Minimize avoidable human error
- Improve naming and asset consistency
- Help artists identify issues earlier
- Prevent downstream integration problems

## Technical Notes

- Built for Autodesk Maya
- Developed using Maya Python
- Designed around artist-friendly workflow and production usability
- Python scripting level: basic, with a focus on workflow automation and practical tool development

## Screenshots

<img width="425" height="585" alt="image" src="https://github.com/user-attachments/assets/3994b6a7-d24c-4014-a6aa-a0182d182b4b" />


```md
<img width="426" height="240" alt="0929(1)" src="https://github.com/user-attachments/assets/a14227db-6313-4f44-af49-3b2ec7a09abd" />


