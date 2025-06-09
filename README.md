
#  Case 3: Automated Dunning Agent

##  Goal

You are tasked with designing a lightweight automation system that monitors unpaid invoices and triggers a smart, multi-step dunning (payment reminder) process.

This challenge is designed to test how you think, structure systems, and prioritize pragmatically – not how flashy your code is. We value clarity, creativity and reasoning.

---

##  Provided Files

- `invoice_data.csv` – Sample invoice records in tabular format
- `invoice_data.json` – Same data in JSON format

Each record includes:
- Customer name
- Invoice number
- Amount
- Due date
- Payment status

---

##  Scenario

The company sends out invoices regularly. Some customers do not pay on time. Your job is to design an agent that tracks these cases and reacts accordingly:

### Dunning escalation logic:

- **+3 days after due date** → Friendly reminder
- **+7 days** → Formal reminder with deadline
- **+14 days** → Final notice with legal warning
- **+21+ days** → Escalate to legal/collections process

---

##  Optional Features

- Slack alert to finance team when escalation occurs
- Integration with CRM (e.g., tagging the customer with dunning level)
- Log file or dashboard to monitor status per customer

---

##  Your Task

> Please focus on structure, reasoning, and pragmatism. Code is optional but welcome.

1. **How would you structure and build this dunning agent?**
2. **Which tools would you use and why?**
3. **What would you automate, and what would you keep manual?**
4. **How would you prevent duplicate messages or missed reminders?**
5. **What would your MVP look like after one day of work?**

You can use bullet points, diagrams, or pseudocode. A working CLI prototype is a bonus but not required.

---

##  Time Recommendation

Please spend no more than **90 minutes** on this case.

---

##  Submission

- Create a public GitHub repo or share a zipped folder
- Include your answers and any relevant scripts or diagrams
- Add a short README explaining what you built

We’re excited to see how you approach this!
