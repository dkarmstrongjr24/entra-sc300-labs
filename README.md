# Entra ID SC-300 Labs

Hands-on Microsoft Entra ID labs, built while studying for **SC-300: Microsoft Identity and Access Administrator**. Everything runs from a Linux terminal with the Azure CLI, with Terraform for repeatable setups.

## Labs

| # | Lab | What it covers | Status |
|---|---|---|---|
| 01 | [Users and groups](labs/01-users-and-groups/) | Create and manage users and groups from the Azure CLI | Not started |
| 02 | [SAML single sign-on](labs/02-saml-sso/) | Connect a SaaS app to Entra ID with SAML SSO | Not started |
| 03 | [OIDC app registration](labs/03-oidc-app/) | Register an app and sign in with OpenID Connect | Not started |
| 04 | [Sign-in and audit logs](labs/04-sign-in-and-audit-logs/) | Read and query sign-in and audit logs | Not started |
| 05 | [Conditional Access](labs/05-conditional-access/) | Require MFA and block risky access with policies | Not started |
| 06 | [Dynamic groups](labs/06-dynamic-groups/) | Auto-assign membership from user attributes | Not started |
| 07 | [Privileged Identity Management](labs/07-pim/) | Just-in-time admin roles with approval | Not started |
| 08 | [Access reviews](labs/08-access-reviews/) | Recurring reviews of group and app access | Not started |
| 09 | [Identity Protection](labs/09-identity-protection/) | User and sign-in risk policies | Not started |
| 10 | [Joiner, mover, leaver](labs/10-joiner-mover-leaver/) | Lifecycle automation for hires, moves and exits | Not started |

## Setup

- Free Entra ID test tenant (Phase 2 labs use an Entra ID P2 trial)
- [Azure CLI](https://learn.microsoft.com/cli/azure/install-azure-cli)
- [Terraform](https://developer.hashicorp.com/terraform/install) with the `azuread` provider

## Repo layout

```
labs/
  01-users-and-groups/
    README.md       lab notes: goal, steps, verify, lessons
    screenshots/
  ...
terraform/          reusable Terraform as labs get automated
```

No real names, secrets or tenant IDs are committed. Test users only.
