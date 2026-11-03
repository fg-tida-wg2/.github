# FG-TIDA WG2: Identity, Behaviour and Enforcement for AI Agents (IBEA)

The working group addresses the mismatch between an AI agent's identity, its unpredictable behaviour and the enforcement of the authority it acts under. We observe a direct contradiction between a stable, verifiable identity on the one hand and an intrinsically probabilistic and radically changing behavior of an AI agent on the other hand. Therefore, differently from classical software, we need to accept that a typical, flat identity (e.g., derived from a public key) of an AI agent can say nothing about how the Agent will behave for a given request/task; similarly, the fact that an Agent misbehaved might not be a sufficient reason for action. Overall, it emerges that using a stable identity as a basis for AI Agent authorizations or revocations is not really sound.

In this theme, differently from the state of the art, we suggest studying new ways how a metamorphing entity such as an AI Agent can be represented and handled in the scope of (classical) security policies and security policy enforcement.

## Charter
📄 [Web](https://fg-tida-wg2.github.io/wg2-ibea-charter/) · 📑 [PDF](https://fg-tida-wg2.github.io/wg2-ibea-charter/wg-charter.pdf)
Source: [`wg2-ibea-charter`](https://github.com/fg-tida-wg2/wg2-ibea-charter)

## Specifications
| Deliverable | Description | Published | Source |
|---|---|---|---|
| IBEA-Problem | WG problem statement, terminology, use and threat cases. <Spec ibea-problem> | [web](#) · [PDF](#) | [`wg2-ibea-problem`](#) |
| IBEA-REQ | Requirements for enforcing security policy on agent actions, common to all solution branches: policy expression for enforceability, decision outcomes and their meaning, decisions under policy collision, escalation, and the statement that no decision was taken. <Spec ibea-req> | [web](#) · [PDF](#) | [`wg2-ibea-req`](#) |
| IBEA-TR 1.1 | Study on AI Agent internal design and its internal dependencies, formalization of relationships typically encountered in the popular agents, assurances that can be produced in this regard, and the corresponding trust models. <Spec ibea-tr11> | [web](#) · [PDF](#) | [`wg2-ibea-tr11`](#) |
| IBEA-TR 1.2 | Requirements and solution candidates for a naming scheme for AI Agent along with details of corresponding mechanisms capable of formally and deterministically packaging these assurances into an identity string to be used for granting and revoking access rights. <Spec name> | [web](#) · [PDF](#) | [`wg2-ibea-tr12`](#) |
| IBEA-TR 2.1 | Study of possibilities how a security policy could be expressed as "an intent" regardless of the involved actors and agents. Understanding of features and limits of such policies. <Spec ibea-tr21> | [web](#) · [PDF](#) | [`wg2-ibea-tr21`](#) |
| IBEA-TR 2.2 | Requirements and solution candidates for Security Policy as an intent, requirements on agents capable to enforce it, coexistence with legacy security policies. <Spec ibea-tr22> | [web](#) · [PDF](#) | [`wg2-ibea-tr22`](#) |
| IBEA-FX | Shared evaluation fixtures: versioned cases with expected outcomes and negative controls, used to assess and compare all solution branches against IBEA-REQ. <Spec ibea-fx> | [web](#) · [PDF](#) | [`wg2-ibea-fx`](#) |

## Working group
- **Chairs:** Artur Hecker (Huawei Technologies); Cyril Gorlla (CTGT)
- **Mailing list:** <list / link> TBD
- **Meetings:** <cadence / calendar link> TBD

## Contributing
See `CONTRIBUTING.md` in each repository — open an issue or a pull request; do not push directly to `main`.

## Parent
Operates under [FG-TIDA](https://github.com/FG-TIDA), an ITU-T Focus Group (parent Study Group: SG17).
