# AI Plan Generation

## Overview

Lyra can automatically generate a first draft of a project plan based on existing project documentation.

## Process

1. **User uploads** existing project documentation:
   - SOWs (Statements of Work)
   - Meeting minutes
   - Contracts
   - Mandates
   - Other relevant documents

2. **Lyra analyses** the documents and populates the eight default attributes:

   | Attribute | Type |
   |-----------|------|
   | Portfolio | Free text |
   | Programme | Free text |
   | Project | Free text |
   | Task name | Free text |
   | Start Date | Date |
   | Finish Date | Date |
   | Status | Choice |
   | % Complete | % |

3. **Structure estimation**: The hierarchy (Portfolio > Programme > Project > Workstream) is estimated by Lyra and presented to the user to review, edit, and confirm

4. **User confirms** the proposed structure

5. **Lyra drafts a full plan** for the user to edit

## Proven Concept

> This worked when we used Claude at Trimstone — we had loads of docs for it to base the data on and it produced something really helpful.

The assumption is that the data in the uploaded documents will cover enough information for Lyra to populate the eight default attributes.
