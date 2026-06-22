Author: Atishay Jain
Date: June 2026 (posted 2w ago)
Link: https://www.linkedin.com/posts/atishay-hyperke_if-you-want-to-use-claude-code-for-cold-email-activity-7468300616717516800-LIB0/

Content: 

f you want to use Claude Code for cold email without it breaking...

STOP building skills. 

Instead, build a system. 

CONTEXT: 

A skill is a text file telling Claude how to do a workflow. 

• You run it
• Claude re-reads the instructions
• It interprets them
• And then produces an output. 

Every run is a fresh interpretation, which means every run carries the chance the output is off and you're back to editing.

A SYSTEM is different.

For one client account, we have 5 subprograms that each handle one piece of the operation. 

• A monitor that runs nightly and kills any campaign whose PCPL goes above 1,700 after 3,000 sends. 
• A create module that spins up the next iteration when active campaigns drop below 2. 
• The watcher that polls Slack every 5 minutes for approvals. 
• Launch module that pushes approved campaigns into Smartlead. An upload module that adds leads in batches and skips bad inbox providers.

All 5 read from and write to one file. campaign_state.json.

It tracks which campaigns are running, how many leads were uploaded, which got skipped, every angle and script that's been tried, every piece of feedback the human gave. 

The system gets smarter every week because the state file keeps growing.

The difference is where the AI sits.

In a skill, the AI is the workflow re-interpreting itself every time.

In a system, the AI makes smart decisions inside deterministic rules. 

That way, the rules don't change, and the decisions just continue to get sharper.

Lesson: 

If you're trying to build a real outbound layer on top of Claude Code, build the SYSTEM. 

Skills are just the prototype.

Notes: 

- AI skills are useful for prototyping workflows, but production outbound systems require deterministic processes.

- Reliable outbound operations separate workflow logic from AI decision-making.

- Persistent state management enables systems to improve over time by tracking campaign history, feedback, experiments, and outcomes.

- Modular architectures allow different functions (monitoring, approvals, launching, lead uploads) to operate independently while sharing context.

- AI performs best when making decisions inside predefined rules rather than redefining the process on every execution.