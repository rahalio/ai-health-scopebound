# Scopebound — User stories

**Product:** [PRODUCT.md](./PRODUCT.md)


### Nurse care manager (monitoring panel)

- As a nurse care manager, I want to see which of my panel's tasks are running on machine teammates tonight and which need me, so that I work exceptions instead of watching an entire dashboard.
- As a nurse care manager, I want to delegate overnight vitals surveillance for a stable heart-failure patient to a monitoring agent with my supervision recorded and an expiry attached, so that I can carry a larger panel without pretending I was awake for it.
- As a nurse care manager, I want to pull a task back from an agent immediately when the patient's picture changes, so that I am never negotiating with a workflow during a deterioration.
- As a nurse care manager, I want the ambient capture of my patient calls to draft my documentation, so that adding a machine to the team gives me minutes back rather than a new form.

### Supervising physician

- As a supervising physician, I want to see the current scope of practice of every agent operating under my licence, so that I know precisely what I am accountable for before I sign the delegation.
- As a supervising physician, I want escalations to arrive with the triggering evidence, the agent's confidence and its documented failure modes, so that I can act on the case rather than re-derive it.
- As a supervising physician, I want to override a machine recommendation in one click with a reason code, so that disagreeing with the system costs me nothing and leaves a clean record.

### Patient and family caregiver

- As a patient, I want to choose which parts of my care a machine may handle and which I want a person for, so that I receive the care I actually agreed to.
- As a patient, I want a plain-language account of what the virtual nurse does, what it cannot do and who is responsible for it, so that not understanding how it works stops being my reason to refuse.
- As a family caregiver, I want to receive only the monitoring alerts I am authorised for, so that I can help without being handed the whole record.
- As a patient, I want to withdraw consent for machine monitoring in the middle of an episode and have a human take the task over the same day, so that changing my mind does not cost me my care. *(exception path)*

### Clinical AI governance chair

- As the governance chair, I want to run a candidate agent in shadow mode against our own population before granting any live scope, so that we credential on our data rather than on the vendor's marketing claims.
- As the governance chair, I want subgroup performance monitored continuously with automatic scope suspension on a floor breach, so that an equity failure stops the agent instead of waiting for the quarterly committee.
- As the governance chair, I want to author, version and revoke each agent's scope of practice as a governed document, so that what a machine may do is controlled by us and not by a vendor release note. *(governance path)*

### Risk and compliance officer

- As a risk officer, I want to reconstruct any task with its performer, supervisor, agent version, consent state and data access trail, so that we can defend or concede a claim on evidence instead of reconstruction from memory.
- As a compliance officer, I want adverse events involving a machine teammate routed into our safety reporting process inside the reporting window, so that post-market surveillance duties are discharged by the workflow rather than by somebody remembering.
