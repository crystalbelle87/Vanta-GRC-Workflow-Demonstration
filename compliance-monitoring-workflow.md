# Compliance Monitoring Workflow

## 1. Purpose

This document demonstrates a simulated compliance monitoring workflow based on GRC automation concepts used by platforms such as Vanta.

The workflow illustrates how an organization can identify control failures, review supporting evidence, assign remediation responsibilities, and document resolution.

## 2. Scenario

**Organization:** Example Technology Company

**Compliance Program:** SOC 2

**Control Area:** Access Control

**Control ID:** AC-01

**Control Requirement:** User accounts must have multi-factor authentication (MFA) enabled.

**Monitoring Result:** Failed

**Finding:** A user account was identified without MFA enabled.

## 3. Monitoring and Detection

In a compliance automation platform such as Vanta, a monitoring check may evaluate whether user accounts meet an established security requirement.

For this simulation:

- The monitoring check identifies an account without MFA.
- The control is marked as requiring attention.
- The finding is documented for review.
- Supporting evidence is requested or collected.

## 4. Evidence Review

The GRC analyst reviews the available evidence to determine whether the finding is valid.

**Evidence Reviewed:**
- Simulated monitoring alert
- User account MFA configuration status
- Access control documentation

**Review Outcome:** The finding is confirmed for this scenario.

**Note:** No actual system integrations, user accounts, or production evidence were accessed.

## 5. Remediation Assignment

**Finding ID:** F-001

**Remediation Action:** Enable MFA for the affected account and verify the configuration.

**Responsible Role:** IT Administrator

**Oversight Role:** GRC Analyst

**Priority:** High

**Status:** Open

## 6. Remediation Verification

After the IT Administrator completes the corrective action, the GRC analyst would:

1. Review updated configuration evidence.
2. Confirm MFA is enabled.
3. Recheck the monitoring result.
4. Document the verification outcome.
5. Update the finding status.

**Simulated Final Result:** MFA enabled; monitoring check passes.

**Finding Status:** Closed — Remediation Verified (Simulated).

## 7. GRC Analyst Responsibilities

The GRC analyst supports this workflow by:

- Reviewing monitoring alerts.
- Validating potential control failures.
- Requesting and organizing evidence.
- Coordinating remediation with responsible teams.
- Tracking findings through resolution.
- Maintaining documentation for audit readiness.

## 8. Vanta Concepts Demonstrated

| GRC Activity | Vanta-Related Concept |
|---|---|
| Compliance monitoring | Automated control monitoring |
| Finding identification | Failed monitoring check |
| Evidence review | Evidence collection and review |
| Remediation assignment | Task and issue tracking |
| Verification | Monitoring status reassessment |
| Documentation | Audit readiness |

## 9. Simulation Disclaimer

This is an illustrative workflow based on GRC and compliance automation concepts. It does not demonstrate an actual Vanta integration, live monitoring, production control testing, or real-world remediation.
