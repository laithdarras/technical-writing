# Using Graphical Elements in Technical Writing

## Breaking Up the Monotony

- Dull writing can lose your reader. Using humor is fine, but only in limited circumstances.
- A better way to hold your reader’s attention is by using **graphical elements** such as:
  - Figures
  - Equations
  - Photographs
  - Tables
  - Flowcharts
- These elements add life to your writing and prevent dry, text-only passages.
- Bulleted lists (like this!) also help improve pace and readability.

---

## Modeling Ideas with Graphics

- The challenge is to **find the right type of graphic** to match the idea you’re explaining.
- Experiment with different **layouts, font sizes, and non-text elements** to keep the reader engaged.
- Use graphics to:
  - **Guide** the reader visually
  - **Clarify** complex logic
  - **Balance** text-heavy sections
- But beware: too many graphics can distract, while too few can lead to fatigue and confusion.

### Simple Example: Troubleshooting a Broken Lamp

Instead of writing:
> "If the lamp doesn’t work, check if it’s plugged in. If it isn’t, plug it in. If it is, check the bulb. If the bulb’s burned out, replace it. Otherwise, repair the lamp."

...just use a **flowchart**.

![Flowchart: Troubleshooting a Broken Lamp]([../assets/graphics/LampFlowchart.svg.png](https://www.google.com/url?sa=i&url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FFlowchart&psig=AOvVaw1zAxlOY_hMbpkQAIVXuF4s&ust=1743547373159000&source=images&cd=vfe&opi=89978449&ved=0CBMQjRxqFwoTCODN96CytYwDFQAAAAAdAAAAABAE))  
*Figure 1: A visual model showing the decision flow for troubleshooting a broken lamp.*

---

## 📅 Example Gantt Chart (Markdown)

Here is a **text-based Gantt chart** using markdown syntax. You can convert this to a proper visual version with tools like [Mermaid](https://mermaid.js.org/) or GanttProject.

```markdown
| Task                     | Start Date | Duration | Dependencies |
|--------------------------|------------|----------|---------------|
| Proposal Drafting        | Mar 25     | 5 days   | -             |
| Peer Review              | Mar 30     | 2 days   | Proposal      |
| Revisions & Edits        | Apr 1      | 3 days   | Peer Review   |
| Final Formatting         | Apr 4      | 1 day    | Revisions     |
| Submission               | Apr 5      | -        | Formatting    |
