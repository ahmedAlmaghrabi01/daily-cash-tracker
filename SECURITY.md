# Security

Do not include credentials, financial data, or personal information in a public GitHub issue. Report sensitive findings privately to the repository owner.

## Credential handling

- Firebase Admin and Google credentials must remain in server-side environment variables.
- Never commit `.env` files or downloaded service-account JSON files.
- Use a separate Firebase project and Google Sheet for testing.
- Rotate a credential immediately if it is accidentally published.

## Portfolio data

This public repository uses placeholder configuration and fictional driver names. It does not contain the production database, spreadsheet, user accounts, or organization-specific records.
