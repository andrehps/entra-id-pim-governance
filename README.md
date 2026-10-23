## 📸 Proof of Concept & Live Evidence

### 1. Governance Policy: Just-In-Time Eligibility
The image below confirms the architecture deployment within the "Blue Safe" tenant scope. The administrative identity (`Alice Correa / alice@...`) holds no standing permanent access and is strictly bound to the **Eligible assignments** pipeline:

![Microsoft Entra PIM Eligible Assignment](./configuracao-pim.png)

### 2. Operational Workflow: Group-Based Approval & Auditing Pipeline
When an activation request is triggered, the platform successfully intercepts it. The request remains sandboxed under **Requests for role activations** awaiting official approval. Note the mandatory integration of compliance ticketing trackers under the **Reason** auditing metadata (e.g., `Tickets SB0956`):

![PIM Activation Pending Approval](./fluxo-aprovacao.png)
