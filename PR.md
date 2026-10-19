# PR Title

feat/FEAPP-420: Allow customer notification via WhatsApp

## PR Description

### WHAT

Implemented support for WhatsApp as an additional notification channel for product listing updates.

Customers can now optionally provide their WhatsApp number along with their existing email notification preference. When a valid WhatsApp number is provided, product update notifications will be delivered through both email and WhatsApp.

The existing email notification flow has been retained to ensure that current customers who do not opt for WhatsApp notifications continue to receive updates without any changes to their existing experience.

### WHY

Customers have requested the ability to receive product listing updates through WhatsApp in addition to email. Adding WhatsApp as an optional notification channel provides customers with greater flexibility in how they receive important product updates.

This change also helps improve notification reach while maintaining the existing email-based notification behavior for customers who do not provide a WhatsApp number.

### Notes

- WhatsApp notification is an optional feature.
- Customers can continue using email notifications without providing a WhatsApp number.
- Customers who provide a valid WhatsApp number will receive notifications through both email and WhatsApp.
- Existing email notification functionality remains unchanged.
- The WhatsApp notification option should not affect customers who have not opted into it.
- QA validation should cover both email-only and email-plus-WhatsApp notification scenarios.

### PR Reviewers

The following teams and stakeholders are requested to review this change:

- **Frontend Development Team** : Review the customer-facing changes and ensure they follow existing frontend standards and patterns.
- **QA Team** : Validate the WhatsApp notification flow and confirm that existing email notification functionality continues to work as expected.
- **Project Lead** : Verify that the implementation satisfies the requirements outlined in FEAPP-420.
- **Engineering Lead** : Review the overall implementation for maintainability, consistency, and adherence to engineering standards.
