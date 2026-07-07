---
title: PM Tool Project
date: "2026-07-06T23:30:00.000Z"
description: "The project management tool I've been working on"
---

I started working on a project management tool with Claude's help, and now Codex's, several months ago. The [front end](https://github.com/ericadev/pm_tool_frontend) is built using React, TypeScript, Shadcn, and TailwindCSS. The [back end](https://github.com/ericadev/pm_tool_fastapi) was originally started in TypeScript but I moved it to Python and FastAPI.

This past week I've added features to create and update tasks, and updated the code to correct an issue whereby any user could update or delete any task. Now only the owner of the project can update or delete a given task. 

From here, I'm not sure whether to build out more project management features such as a task board and member management, or move on to adding an AI integration to take meeting notes and generate a task list from them.

It certainly has been exciting to see how AI can help me quickly generate code, even though sometimes things need to be corrected or tweaked. For example, as mentioned, the code written by the AI allowed the user to update or delete any task instead of just their own. A small tweak in this case to filter only down to tasks with the same creator as the project owner was necessary. I think I prefer Claude Code's planning mode, but I'll have to try Codex more to compare fairly.