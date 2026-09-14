# Centralized AI administration — CEO demo guide

## Recommendation

Move AI administration into one dedicated **AI Settings** destination. Keep Company, Office, and Calling Group governance visible as three local views instead of making admins navigate the organization hierarchy one entity type at a time.

## The product story

Today, AI policy follows the Admin portal's entity structure. That is precise, but it makes company-wide governance fragmented and harder to operate at scale.

This concept changes the entry point, not the hierarchy:

- Company remains the global ceiling.
- Offices can narrow Company policy and delegate management safely.
- Calling Groups can manage Conversation AI within their Office policy.
- Parent restrictions stay visible, saved child intent is preserved, and Data sharing remains an independent decision.

## Five-minute walkthrough

1. **Company:** Show one global AI control, the two capability families, separate Data sharing, and Company Dictionary.
2. **Offices:** Show all Offices in one AI-focused table. Select several rows and open the bulk editor, then open one Office drawer.
3. **Governance:** Point out that AI Management is independent from AI availability and that disabled child controls remain visible with explanations.
4. **Calling Groups:** Show Departments, Contact Centers, and Coaching Teams together. Filter the table and open a Calling Group drawer.
5. **Safety:** Enable Conversation AI for a Calling Group to show the required recording and transcription acknowledgment.

## Decision to discuss

Is centralized AI administration the right primary model for enterprise admins, with entity-specific areas becoming secondary access points rather than the main way to govern AI?

## Scope boundary

This prototype tests information architecture and governance behavior. It does not propose changes to User AI settings, Agent Builder, routing, licensing, connectors, credentials, or RBAC.
