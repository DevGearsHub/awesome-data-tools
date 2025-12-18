# Contributing to Awesome Data Tools

Thank you for your interest in contributing! This guide will help you add new tools or improve existing entries.

## How to Contribute

### 1. Fork and Clone

1. Fork this repository
2. Clone your fork locally
3. Create a new branch: `git checkout -b add-new-tool`

### 2. Make Your Changes

#### Adding a New Tool

When adding a new tool, please follow this format:

```markdown
- **[Tool Name](url)** — Brief description. Free tier details: X GB storage, Y operations per month. Additional info if needed.
```

**Example:**
```markdown
- **[ClickHouse Cloud](https://clickhouse.com/)** — Real-time analytics database. Free tier: 100GB storage, limited compute hours per month.
```

#### Categories for Tags (Optional)

You can add tags to help categorize tools:
- `Open Source` — Tool is open source
- `Self-Hosted` — Can be self-hosted
- `Cloud` — Cloud-based service
- `Always Free` — Free tier is permanent
- `Limited Trial` — Free tier is time-limited

### 3. Inclusion Criteria

Before submitting, ensure the tool meets these requirements:

✅ **Must Have:**
- Genuine free tier (not just a trial) OR trial period of at least 30 days
- Cloud-based or SaaS offering
- Relevant to data engineering, analytics, ML, or data science
- Active and maintained (updated within last 12 months)
- Clear documentation

❌ **Not Eligible:**
- Services with only paid tiers
- Free trials less than 30 days (unless "always free" tier exists)
- Self-hosted-only tools (unless also offering cloud version)
- Discontinued or abandoned services
- Services that restrict essential features (like TLS/SSL) to paid tiers only

### 4. Free Tier Requirements

Be specific about **permanent** free tier limits, but avoid promotional credit amounts:

**Good Examples:**
- "1GB storage, 1000 API requests per month (always free)"
- "Free trial available for new users"
- "100GB data processing per month (always free)"
- "5 users, unlimited projects, 1GB storage"
- "Free tier for first 12 months (new accounts): 20GB storage"

**Bad Examples:**
- "Limited free tier available" (too vague)
- "$300 in credits for 90 days" (promotional amounts change frequently)
- "Generous free tier" (not specific)
- "$50/month in free credits" (dollar amounts are unstable)

**Why avoid specific promotional dollar amounts?**
- Credit amounts change frequently and make the list outdated
- Instead use: "Free trial available" or "New user trial credits available"
- Focus on **permanent free tiers** whenever possible

### 5. Adding to the Right Category

Place your tool in the most appropriate category:

- **Major Cloud Providers** — AWS, GCP, Azure, Oracle, IBM services
- **Cloud Data Warehouses** — Snowflake, BigQuery, Redshift, etc.
- **Cloud Databases** — Managed database services
- **Cloud Storage** — Object storage, data lakes
- **Cloud Analytics & BI** — Business intelligence and visualization
- **Cloud ETL & Data Integration** — Data pipeline tools
- **Cloud Data Streaming** — Kafka, Kinesis, event streaming
- **Cloud ML & AI** — Machine learning platforms and APIs
- **Cloud Data Orchestration** — Airflow, workflow management
- **Cloud Notebooks & IDEs** — Jupyter, collaborative notebooks
- **Cloud APIs & Serverless** — Lambda, Cloud Functions
- **Cloud Monitoring & Logging** — Observability tools

If unsure, suggest a new category in your pull request.

### 6. Commit Messages

Use clear, descriptive commit messages:

**Good:**
- `Add ClickHouse Cloud to data warehouses section`
- `Update BigQuery free tier limits`
- `Fix broken link for Snowflake`

**Bad:**
- `Update`
- `Add stuff`
- `Changes`

### 7. Pull Request Guidelines

When submitting your PR:

1. **Title Format:** `Add [Tool Name]` or `Update [Tool Name] free tier info`
2. **Description:** Briefly explain what you're adding/changing and why
3. **Checklist:** Complete this checklist in your PR:

```markdown
- [ ] Tool meets inclusion criteria
- [ ] Free tier details are specific and accurate
- [ ] Link is working and goes to official website
- [ ] Tool is in the correct category
- [ ] Description is clear and concise (under 150 characters)
- [ ] Alphabetically ordered within category (if applicable)
- [ ] No affiliate links
```

### 8. Quality Standards

- **Links:** Always link to the official website or product page
- **Description:** Keep it under 150 characters, focus on what it does
- **Free Tier:** Be specific about limits, duration, and restrictions
- **Grammar:** Use proper grammar and spelling
- **Neutrality:** Avoid promotional language ("amazing," "best," etc.)
- **Accuracy:** Verify free tier details before submitting

### 9. Updating Existing Entries

If you're updating an existing tool:

- Clearly explain what changed in the PR description
- Update the free tier limits if they changed
- Fix broken links
- Improve unclear descriptions
- Add missing information

### 10. What NOT to Submit

❌ Don't submit:
- Affiliate links
- Referral codes
- Self-promotion without meeting criteria
- Duplicate entries
- Paid-only services
- Outdated or discontinued tools
- Non-English services (unless they have English documentation)
- Tools with security concerns or poor reputation

## Code of Conduct

- Be respectful and constructive
- Focus on the content, not the person
- Accept feedback gracefully
- Help maintain a welcoming community

## Questions?

If you're unsure about anything:

1. Check existing entries for examples
2. Open an issue to discuss before submitting a PR
3. Ask in your PR description

## Review Process

- PRs are typically reviewed within 7 days
- Maintainers may request changes or clarifications
- Once approved, your contribution will be merged

## Thank You!

Your contributions help developers worldwide discover useful data tools. We appreciate your time and effort! 🙏

---

## Quick Checklist for Submissions

Before submitting, verify:

- [ ] Free tier is genuine and well-documented
- [ ] Tool is actively maintained
- [ ] Link is working and official
- [ ] Description is clear and concise
- [ ] Free tier limits are specific
- [ ] Correct category
- [ ] No promotional language
- [ ] No affiliate links
- [ ] Proper formatting
- [ ] Commit message is descriptive

