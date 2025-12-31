Hi please create prompt that user can provide code (paste or upload) and provide instructions for creating SKILL.md, then agent will create SKILL.md with 31 skills based on user's instructions.


You will be creating a SKILL.md file based on code provided by a user. Your task is to analyze the code and identify exactly 31 distinct skills, techniques, or competencies demonstrated in the code, then document them in a well-structured SKILL.md file.

Here is the code to analyze:
<code>
{{CODE}}
</code>

Here are the user's specific instructions for what to include or focus on when creating the SKILL.md:
<user_instructions>
{{INSTRUCTIONS}}
</user_instructions>

Your task is to:
1. Carefully analyze the provided code to identify skills, techniques, patterns, and competencies demonstrated
2. Follow any specific guidance provided in the user's instructions
3. Create a SKILL.md file that lists exactly 31 skills

Guidelines for identifying skills:
- Skills can include: programming concepts used, design patterns, algorithms, data structures, API usage, architectural decisions, best practices, testing approaches, optimization techniques, security measures, error handling methods, etc.
- Each skill should be distinct and specific
- Skills should be actually demonstrated in the code, not just theoretical possibilities
- Consider both technical skills (e.g., "implements binary search algorithm") and software engineering practices (e.g., "uses descriptive variable naming")
- Look at different levels: language features, code organization, problem-solving approaches, and domain-specific techniques

Format requirements for SKILL.md:
- Use markdown formatting
- Include a title: "# Skills Demonstrated"
- Number each skill from 1 to 31
- For each skill, provide:
  - A clear, concise skill name or title
  - A brief description (1-3 sentences) explaining how this skill is demonstrated in the code
- Organize skills logically (you may group related skills together with subheadings if appropriate)
- Ensure the document is well-formatted and easy to read

Important rules:
- You must identify exactly 31 skills, no more and no fewer
- Each skill must be genuinely present in the provided code
- Pay close attention to the user's instructions and prioritize the aspects they want emphasized
- If the user's instructions conflict with finding 31 skills, still aim for 31 but weight your analysis according to their guidance
- Be specific rather than generic (e.g., "implements OAuth 2.0 authentication" rather than "uses authentication")

Write your complete SKILL.md file inside <skill_md> tags. Do not include any preamble or explanation outside these tags.
