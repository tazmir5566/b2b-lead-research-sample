# Data Dictionary

Columns in [`../data/sample-prospect-list.csv`](../data/sample-prospect-list.csv). All values are synthetic.

| Column | Description | Format / example |
| --- | --- | --- |
| `record_id` | Unique ID for each row | `LR-001` |
| `company_name` | Company's trading name | `Harborline Freight Systems` |
| `website` | Company domain, without `https://` or `www.` | `harborline.example` |
| `industry` | Industry label matched to the brief | `Logistics Software` |
| `city` | Headquarters city | `Chicago` |
| `state` | Two-letter US state code | `IL` |
| `country` | Country name, written in full | `United States` |
| `employee_range` | Headcount band | `100-249` |
| `contact_first_name` | Decision-maker's first name | `Dana` |
| `contact_last_name` | Decision-maker's last name | `Whitfield` |
| `job_title` | Current title as found at the source | `VP of Operations` |
| `business_email` | Work email address | `dana.whitfield@harborline.example` |
| `email_status` | Verification result and date in real work; demo label here | `Demo — not verified` |
| `source_reference` | Where the contact details were found in real work; demo label here | `Synthetic record — no real source` |
| `research_notes` | Short context useful for outreach or follow-up | `DEMO DATA. Fleet visibility platform…` |

## Status labels used in real deliveries

| Label | Meaning |
| --- | --- |
| Valid | Passed an email verification check on the stated date |
| Catch-all / Risky | The mail server accepts all addresses, so the result is uncertain |
| Invalid | Failed verification; not recommended for sending |
| Not checked | Sourced but not yet verified |

Phone numbers, when included in real work, are marked as *sourced* unless they have been checked separately. A sourced number is not confirmed as active.
