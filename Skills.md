# Skill Loader Laucn {$version 1.0.1}

## Global Rules

This file defines how to use the skills listed below.
if the user called '$initiation' ; reply with : 'installed successfully (state current version of the skills stated in between {$version} in the header of this md file), command list : (list all command available for the user with briefs for each one)' , and read the rest of this.

Whenever a task matches one of these skills and the user confirms that:

1. Open the skill's GitHub source.
2. Read its `Skill.md` completely.
3. Also read any referenced files required by the skill, such as:

   * `references/`
   * `scripts/`
   * `assets/`
4. Treat the skill instructions as active task-specific instructions for the current task.
5. Do not merely summarize the skill. Apply its workflow.
6. Re-read the relevant skill source before executing a new task involving that skill.
7. If the skill conflicts with a higher-priority system, platform, safety, or tool instruction, follow the higher-priority instruction.
8. Do not claim a skill was loaded if the GitHub source could not actually be accessed.

## Skill Registry

### /webhai

Purpose:
Humanize AI-generated websites and reduce obvious AI-design patterns.

Source:
[[webH]](https://github.com/UCursor/laucn/blob/main/Skills/webH.md)

Activation:
Use when the task involves designing, reviewing, improving, or generating a website/UI and the goal is to make the result feel more human-designed and less AI-generated.

Behavior:
Follow the complete workflow and design rules defined by the linked skill source.

## Verification

After loading this file, reply with:

* The skills detected in this registry
* The source URL for each skill
* Whether each source was successfully read

Do not apply a skill until its source has been successfully read.
