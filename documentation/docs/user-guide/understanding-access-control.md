---
slug: /understanding-access-control
sidebar_label: "Understanding access control"
sidebar_position: 3
---

# Understanding access control

Learn how the GDI Portal manages your access to datasets using industry-standard security protocols.

## How access control works

The GDI Portal uses the **GA4GH Passport and Visa** system to securely manage access to genomic datasets. This system ensures that:

- Your access credentials are verified cryptographically
- Dataset access is granted by authorised data access committees
- Your permissions are automatically synchronised across the network
- All access is auditable and compliant with data governance policies

:::info What is GA4GH?

The Global Alliance for Genomics and Health (GA4GH) is an international standards organization that develops frameworks for responsible genomic data sharing. The Passport and Visa system is their standard for secure authentication and authorization.

:::

## What are Passports and Visas?

Think of GA4GH credentials like international travel documents:

- **Passport**: Your authenticated identity provided by LS-AAI when you sign in
- **Visas**: Digital certificates proving you have permission to access specific datasets, issued by data access committees

When you sign in to the GDI Portal, your Passport may contain one or more Visas granting you access to datasets across the European genomic data network.

### Security and privacy

The GA4GH Passport and Visa system ensures:

- **Cryptographic verification**: All Visas are digitally signed and verified
- **Time-limited access**: Grants have expiration dates that are automatically enforced
- **Transparent auditing**: All access is logged for compliance
- **Revocable permissions**: Authorities can revoke access instantly across the network


## Where your access grants come from

Your dataset access grants (Visas) are issued by:

- **Data Access Committees (DACs)**: Organisations that review and approve access requests
- **Research Ethics Committees**: Bodies that verify ethical compliance
- **Institutional Authorities**: Your home institution or research organization

These authorities issue Visas after you've completed their approval processes, which are then automatically recognized by the GDI Portal.

:::tip Keep your access current

With a GA4GH Passport, you can view your approved datasets through the [Entitlements tab](/view-entitlements). If your access is approaching expiration, you may need to renew your application or request an extension from the granting authority.
If you see a message that your "GA4GH Passport is unavailable," sign in again to refresh your credentials or contact support.

:::
