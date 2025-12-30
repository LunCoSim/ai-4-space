# Using n8n: Think in Data, Automate Everything

## What is n8n?

**n8n** is a workflow automation tool that connects different services together. Think of it as a **visual programming tool** where you connect blocks (called "nodes") instead of writing code.

You can automate tasks like:
- Posting to social media on a schedule
- Saving meeting notes to GitHub
- Sending notifications when something happens
- Moving data between different tools

## The Core Concept: Think in Data Flow

Every automation follows the same pattern:

1. **Trigger** (Where does data come from?)
   - A schedule (every day at 9 AM)
   - A webhook (when something happens)
   - A new file, message, or event

2. **Process** (What happens to the data?)
   - Filter, transform, or combine it
   - Extract specific information
   - Make decisions based on conditions

3. **Action** (Where does it go?)
   - Send to Discord, Twitter, email
   - Save to database or file
   - Trigger another system

## Quick Example

**Automate daily social media posts:**
1. **Trigger**: Schedule (10 AM daily)
2. **Process**: Get content from Google Sheet
3. **Action**: Post to Twitter

That's it. No coding required.

## Getting Started

**Cloud (Easiest):**
- Sign up at [n8n.cloud](https://n8n.cloud)

**Self-Hosted (Free):**
```bash
docker run -it --rm --name n8n -p 5678:5678 n8nio/n8n
```
Open `http://localhost:5678`

## Your First Workflow

1. Create new workflow
2. Add a "Schedule Trigger" node
3. Add an action node (e.g., "HTTP Request" or "Discord")
4. Connect them
5. Click "Execute Workflow" to test
6. Toggle "Active" to run automatically

## Common Use Cases

- **Social media automation**: Schedule posts across platforms
- **Meeting notes**: Auto-save Fathom transcripts to GitHub
- **Monitoring**: Get alerts when simulation data shows anomalies
- **Data sync**: Keep Google Sheets, Notion, Discord in sync
- **Backups**: Automatically backup important data

## Key Tips

- **Start simple**: One trigger, one action. Build from there.
- **Use expressions**: `{{ $json.fieldName }}` to reference data from previous nodes
- **Test often**: Use "Execute Node" to test each step
- **Handle errors**: Add error handling so workflows don't silently fail

## Learn More

- **Documentation**: [docs.n8n.io](https://docs.n8n.io)
- **Templates**: [n8n.io/workflows](https://n8n.io/workflows) - Browse pre-built workflows
- **Community**: [community.n8n.io](https://community.n8n.io)

---

**The mindset shift**: Instead of doing repetitive tasks manually, ask yourself:
- "Where is this data coming from?"
- "What do I need to do with it?"
- "Where should it end up?"

Then build a workflow. n8n handles the rest.
