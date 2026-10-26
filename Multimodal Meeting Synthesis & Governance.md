𝐄𝐧𝐠𝐢𝐧𝐞𝐞𝐫𝐞𝐝 𝐒𝐩𝐞𝐜𝐢𝐟𝐢𝐜𝐚𝐭𝐢𝐨𝐧:Multimodal Meeting Synthesis & Governance

𝐓𝐚𝐬𝐤: Analyze the provided meeting transcript to generate an authoritative decision register, an auditable action matrix, and a log of unresolved debates.

𝐂𝐨𝐧𝐭𝐞𝐱𝐭 & 𝐏𝐚𝐫𝐚𝐦𝐞𝐭𝐞𝐫𝐬:
• 𝐏𝐫𝐨𝐣𝐞𝐜𝐭/𝐈𝐧𝐢𝐭𝐢𝐚𝐭𝐢𝐯𝐞: [Insert Project Name]
• 𝐊𝐞𝐲 𝐃𝐞𝐜𝐢𝐬𝐢𝐨𝐧-𝐌𝐚𝐤𝐞𝐫𝐬 𝐏𝐫𝐞𝐬𝐞𝐧𝐭: [Insert Names/Titles]
• 𝐌𝐞𝐞𝐭𝐢𝐧𝐠 𝐃𝐚𝐭𝐞:[Insert Date]

𝐀𝐧𝐚𝐥𝐲𝐭𝐢𝐜𝐚𝐥 𝐑𝐮𝐥𝐞𝐬:
1. Distinguish explicit commitments from exploratory conversation. Tag only tasks with explicit verbal agreement as Action Items.
2. Where an action item lacks a stated deadline or single individual owner, flag it as "[NEEDS ASSIGNMENT]". Never assign joint ownership.
3. Explicitly capture dissent: Record where stakeholders disagreed on scope, technical feasibility, or resource allocation.
4. Suppress all conversational small talk, opening pleasantries, and logistical interruptions.

𝐈𝐧𝐩𝐮𝐭 𝐓𝐫𝐚𝐧𝐬𝐜𝐫𝐢𝐩𝐭:
"""
[Paste complete raw transcript text]
"""

𝐎𝐮𝐭𝐩𝐮𝐭 𝐀𝐫𝐜𝐡𝐢𝐭𝐞𝐜𝐭𝐮𝐫𝐞:
1. 𝐒𝐭𝐫𝐚𝐭𝐞𝐠𝐢𝐜 𝐃𝐞𝐜𝐢𝐬𝐢𝐨𝐧𝐬 𝐋𝐨𝐠: Markdown table with columns [Decision ID | Decision Description | Rationale | Reversibility (High/Med/Low) | Approver].
2. 𝐎𝐩𝐞𝐫𝐚𝐭𝐢𝐨𝐧𝐚𝐥 𝐀𝐜𝐭𝐢𝐨𝐧 𝐌𝐚𝐭𝐫𝐢𝐱:Markdown table with columns [Action Item | Single Owner | Stated/Inferred Deadline | Upstream Dependency | Verification Artifact].
3. 𝐎𝐩𝐞𝐧 𝐈𝐬𝐬𝐮𝐞𝐬 & 𝐔𝐧𝐫𝐞𝐬𝐨𝐥𝐯𝐞𝐝 𝐓𝐞𝐧𝐬𝐢𝐨𝐧𝐬: Bulleted list outlining unresolved debate points, conflicting assumptions, and required next discussions.
