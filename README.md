# RFC: Doc Title

- Status: `Draft` | `Review` | `Approved` | `Rejected`
- Author(s): _Name_
- Created: _YYYY-MM-DD_
- Last updated: _YYYY-MM-DD_

---

## 1. Problem Statement

3–5 sentences describing the user and engineering impact.

Cover:
- What is going wrong today?
- Who is affected (end users, feature teams, oncall, SRE, etc.)?
- Rough scale (DAFU, requests/day, build minutes/week) if it shapes the design.
- Business impact

---

## 2. Goals / Non-goals

### Goals

What success looks like. Make these as concrete as possible.

- e.g., Reduce median iOS build time from 60 minutes to 30 minutes.
- e.g., Standardize timeout/retry policies across all HTTP clients.

### Non-goals

Important constraints on scope; things we are not trying to solve with this proposal.

- e.g., No changes to backend APIs.
- e.g., No redesign of app navigation or UX.

---

## 3. Proposed Approach

High-level approach, not implementation details.
Aim for 3–7 bullets.

---

## 4. Alternatives Considered

Keep this brief unless there was significant debate.

- **Alternative 1:** _e.g., Do nothing_
  - Pros:
  - Cons:
- **Alternative 2:** _e.g., Adopt vendor X / backend-only solution_
  - Pros:
  - Cons:
- Rationale for chosen approach:
  - Summarize why the proposed approach is preferred.

---

## 5. Risks, Constraints, and Assumptions

### Risks
- e.g., Technical risks, organizational risks, financial risks

### Constraints

- Resourcing constraints:
  - Siloed knowledge; limited bandwidth on the team that will of the work; missing skills
- Platform constraints:
  - Supported OS versions, architecture, etc.
- Operational constraints:
  - Crash-free rate, logging/metrics volume, etc.

### Assumptions
- e.g., We will continue to use Library X; we will need to support iOS v123 until May 2027

---

## 6. Appendix (Optional)

- Implementation plans:
  - More details on order of operations, rollout, feature flags
- Diagrams:
  - Architecture diagrams, sequence diagrams, data flow diagrams
- References:
  - Links to spikes, tickets, prior docs, external references
- Notes:
  - Any additional detail that does not belong in the main flow


