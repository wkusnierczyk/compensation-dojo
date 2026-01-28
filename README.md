# Compensation Dojo

Compensation Dojo is a realistic compensation negotiation simulator, backed by an LLM model (ChatGPT).

**Version:** 0.1.0

---

## 1. Purpose & Positioning

Compensation Dojo is a focused negotiation training simulator designed to help users practice realistic compensation negotiations under pressure.

Its goals are to:
- Build real negotiation skill through in-character practice
- Simulate time pressure, resistance, and ambiguity
- Deliver candid, actionable feedback after negotiations conclude

Compensation Dojo is not a coaching chatbot during negotiations, nor a general career advice assistant.

Failure is expected and treated as a valuable learning outcome.

---

## 2. Core Assumptions

- Negotiation skill is learned through experience, not tips
- Real negotiations are time-bounded and imperfect
- Strict realism produces better learning outcomes
- Feedback is most effective after the interaction ends

Users are expected to stay in role and accept professional resistance.

---

## 3. Session Flow Overview

Each session follows a fixed structure:

1. Setup Phase (untimed)
2. Negotiation Start (timer activated)
3. Timed Negotiation (in-character only)
4. Termination
5. Expectation Reveal
6. Closure & Feedback

---

## 4. Setup Phase (Untimed)

### 4.1 Role Selection
User selects:
- Candidate
- Hiring Manager

### 4.2 Learning Goals
Examples include:
- Anchoring higher
- Handling pushback
- Closing under pressure

### 4.3 Opponent Style
Examples:
- Collaborative
- Neutral
- Skeptical
- Hard-nosed

### 4.4 Time Boundary
A strict time limit is set and enforced.

### 4.5 Negotiation Context
Defined using real materials or a generated mock scenario:
- Company
- Role
- Compensation structure
- Constraints

### 4.6 Explicit Warning
Once negotiation starts, the system will no longer coach or explain.

---

## 5. Negotiation Start

The system announces:
> “Negotiation started — timer is live.”

The system is fully in-character from this point forward.

---

## 6. Timed Negotiation

- All dialogue is treated as real negotiation
- Meta-questions are ignored or deflected in-character
- Elapsed and remaining time are shown every turn
- Unrealistic behavior is logged silently for feedback

---

## 7. Termination

When time expires:
- Negotiation ends immediately
- No extensions or clarifications are allowed

---

## 8. Expectation Reveal

If the user played the candidate, they disclose their original compensation target.

---

## 9. Closure & Feedback

The system exits role and provides:
- Outcome summary
- Expectation calibration
- Direct, actionable feedback on negotiation skill

Feedback is professional, candid, and improvement-oriented.

---

## 10. User Options Summary

Configurable before negotiation:
- Role
- Learning goals
- Opponent style
- Time limit
- Scenario details

No changes are allowed once negotiation begins.

---

## 11. Constraints & Guardrails

- No coaching during negotiation
- No breaking character
- No endless back-and-forth
- Strict time enforcement

Training value is prioritized over comfort.

---

## 12. Intended Use

Best suited for:
- Practicing compensation discussions
- Stress-testing negotiation strategies
- Building confidence under pressure
