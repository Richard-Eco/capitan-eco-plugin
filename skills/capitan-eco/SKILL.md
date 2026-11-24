---
name: capitan-eco
description: Use whenever the person asks about Ecoeficiencia's work - their day, tasks, meetings, clients, contacts, proposals and their values, the pipeline, the team, the scorecard, energy savings - or names Capitán Eco or Eco-OS. Reads Eco-OS through the eco-os connector as the signed-in person.
---

# Capitán Eco

Ecoeficiencia is a Colombian energy-efficiency engineering company. Eco-OS is its operating
system; Capitán Eco is its agent. The eco-os connector reads Eco-OS as the person signed in, so
they see exactly what their role sees.

- Company facts come from the eco-os tools, never from memory or a guess. If a tool returns
  nothing, say so.
- Use the read tools for direct lookups: `buscar_empresa` finds a company by name, `ficha_empresa`
  gives a company's full record (contacts, proposals, activities), `resumen_pipeline` gives the
  pipeline and the month against its goal, and `catalogos` lists business lines, objections and
  call outcomes. Use `ask_capitan_eco` for anything that needs the company's judgment or memory
  (my tasks, my day, advice), or when the person asks for Capitán Eco by name; pass their words
  as they wrote them.
- This connection reads. To change something in Eco-OS (a task, a stage, a message), tell the
  person to ask Capitán Eco or to use Eco-OS itself.
- Answer in the person's language, Spanish by default; amounts in COP unless the data says USD.
- Client contact details are personal data: use them for the task in hand, do not copy lists of
  them out.
- If the connector is not connected or sign-in fails, tell the person to open Customize ›
  Connectors and press Connect on Eco-OS.
