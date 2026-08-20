---
slug: /view-entitlements
sidebar_label: "View your entitlements"
sidebar_position: 4
---

# View your entitlements

**View datasets you have access to** through approved applications or external grants. Your entitlements are automatically retrieved from your credentials when you sign in.

## What are entitlements?

Entitlements are dataset access grants you've received through:

- **Approved applications** submitted through the GDI Portal
- **External grants** issued by partner institutions or data access committees
- **Institutional agreements** between your organization and data providers

The GDI Portal automatically recognizes these grants via the GA4GH Passport and Visa system. Learn more: [Understanding access control](/understanding-access-control)

## View your approved datasets

To view your entitlements:

1. Select the **folder icon** (<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" className="size-5" style={{display: 'inline', width: '1em', height: '1em', verticalAlign: 'text-bottom'}}><path d="M4.75 3A1.75 1.75 0 0 0 3 4.75v2.752l.104-.002h13.792c.035 0 .07 0 .104.002V6.75A1.75 1.75 0 0 0 15.25 5h-3.836a.25.25 0 0 1-.177-.073L9.823 3.513A1.75 1.75 0 0 0 8.586 3H4.75ZM3.104 9a1.75 1.75 0 0 0-1.673 2.265l1.385 4.5A1.75 1.75 0 0 0 4.488 17h11.023a1.75 1.75 0 0 0 1.673-1.235l1.386-4.5A1.75 1.75 0 0 0 16.896 9H3.104Z"/></svg>) on your dashboard.

2. Select the **Entitlements** tab to see the list of your approved datasets.

<figure>
<img src="img/download-datasets/view-approved-datasets.png" alt="Screenshot of the Entitlements tab showing approved datasets" width="900" />
<figcaption></figcaption>
</figure>

3. Each entitlement card shows:
   - **Dataset name and description**
   - **Access period**: Start and end dates of your access grant
   - **Granted by**: The authority that issued your access permission
   - **Source**: The system or institution managing the grant

4. Select a dataset to view its full metadata and details.

## Understanding entitlement information

### Access period

Each grant has a validity period:

- **Start date**: When your access became active
- **End date**: When your access expires (if applicable)

:::tip Expiring access

If your access is approaching expiration, you may need to renew your application or request an extension from the granting authority.

:::

### Grant source and authority

Entitlements show who granted your access:

- **Granted by**: The specific data access committee or organization
- **Source**: The source system (e.g., REMS, institutional systems)

This information helps you:

- Understand who to contact for questions
- Track where your permissions come from
- Comply with specific terms from each authority

## What if I don't see any entitlements?

If the Entitlements tab is empty, you may see one of these messages:

### "No access grants found"

Your credentials were successfully retrieved, but you don't have any active access grants. This could mean:

- Your applications are still under review
- Your previous grants have expired
- You haven't applied for any datasets yet

**Next steps**: [Apply for access](/apply-for-access) to datasets you need.

### "GA4GH Passport unavailable"

The system couldn't retrieve your access credentials. This may happen if:

- Your sign-in session has expired
- There's a temporary issue with the authentication service

**Next steps**: Sign out and sign in again to refresh your credentials. If the issue persists, contact support.

### Entitlement shows "Dataset details unavailable"

Sometimes dataset metadata may be temporarily unavailable, but your entitlement information (dataset ID, granting authority, source) is still shown.

**Next steps**: Try again later or contact support if the issue persists.

## Access your datasets

Viewing entitlements in the portal shows you **metadata only**. To download and work with your approved datasets:

1. Check your email for instructions from the data provider
2. Follow the link to the **Secure Processing Environment (SPE)**
3. Access your datasets within the SPE

For detailed instructions, see: [Download datasets](/download-datasets)

:::info Stay compliant

Remember to **use data responsibly** according to the terms and agreements you signed during the application process. Your access is audited for compliance.

:::
