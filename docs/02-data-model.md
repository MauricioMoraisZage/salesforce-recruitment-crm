# Data Model

## Standard Objects

### Account

Represents a company or organization.

Examples:

- Microsoft Portugal
- Google Portugal
- Unitel

### Contact

Represents a person related to an Account.

Examples:

- João Silva
- Ana Costa

### Opportunity

Represents a business opportunity.

Example:

- Backend Recruitment Project

## Relationships

Account (1)
|
+---- Contact (N)

Account (1)
|
+---- Opportunity (N)


# Future Custom Objects

## Candidate

Represents a job candidate.

Fields:

- Full Name
- Email
- Phone
- Skills
- Years of Experience
- Status

Example Status:

- Applied
- Screening
- Technical Interview
- Approved
- Rejected
