# Fragile Cooperation: Climate Treaty Participation with LLM-Driven Regional Agents

This project studies why world regions join, leave, or rejoin a climate agreement, and how those choices change global emissions, carbon prices, and warming. The focus is on mechanisms: how cooperation erodes and recovers under different information and interaction rules. The project couples two models in a closed loop:

- **DICE-2023**, the integrated climate-economy model of Barrage and Nordhaus (2024), handles the global economy, emissions, temperature, carbon price, and the social cost of carbon (SCC).
- **An agent-based model (ABM)** with 12 regional agents, one for each RICE-2010 region. A large language model (LLM) drives each agent through Google DeepMind's Concordia framework.

> **Status:** in progress (2026). The source code is in a private repository and is available on request.

## Research Questions

| | Question |
|---|---|
| RQ1 | Do agent decisions and stated reasons respond to regional characteristics and to the information they receive? |
| RQ2 | How do exit, rejoining, erosion, and recovery of cooperation change emissions, carbon prices, the SCC, and warming? |
| RQ3 | How do roundtable discussion, public commitments, and small-group negotiation change participation, compared with independent decisions? |

## Tools

Python · DICE-2023 (Python) · Google DeepMind Concordia · LLM APIs (DeepSeek, Gemini, OpenAI) · NumPy / SciPy

## References

- Barrage, L., and Nordhaus, W. (2024). Policies, projections, and the social cost of carbon: Results from the DICE-2023 model. *PNAS*, 121. https://doi.org/10.1073/pnas.2312030121
- Millar, R. J., et al. (2017). A modified impulse-response representation of the global near-surface air temperature and atmospheric concentration response to carbon dioxide emissions. *Atmospheric Chemistry and Physics*, 17. https://doi.org/10.5194/acp-17-7213-2017
- Vezhnevets, A. S., et al. (2023). Generative agent-based modeling with actions grounded in physical, social, or digital space using Concordia. arXiv:2312.03664.
