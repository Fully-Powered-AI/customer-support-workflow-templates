# Help centre gap review

See what your help centre is missing from a period's tickets and search log, with one ranked gap list. Your support lead decides what is written.

> [!TIP]
> **Missing a template that is not listed here, or want these customized for your organization? Reach out to us.** This is a template, made to be customized and deployed. FullyPowered AI customizes and builds AI workflows, connects them to your business systems, installs them in your agents and puts them in the hands of the people who own the work. [See Help centre gap review on our website](https://fullypowered.ai/workflows/help-centre-gap-review/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=customer-support-help-centre-gap-review&from=gh-help-centre-gap-review). Not sure where to start? Email hello@fullypowered.ai and a person will answer.

**Quick start**

1. Read EXAMPLE.md to see what a good result looks like.
2. Copy all of TEMPLATE.md into your assistant, then give it your own inputs, or the sample ones from EXAMPLE.md.
3. Read what comes back. It marks what it checked and what is left for you.

*Workflow template · Customer support and service · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflows/help-centre-gap-review/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=customer-support-help-centre-gap-review&from=gh-help-centre-gap-review)*

## The outcome

The next article your team writes is the one last month's tickets asked for. Every ticket a customer could have settled alone is sorted by what it took: an agent writing the answer by hand because no article holds it, an agent sending a link to an article that already had the answer, or an agent sending a link and then correcting what the article said. The help centre's searches that returned nothing add the words customers typed and did not find.

Each common question gets a plain verdict with its facts: missing, falls short, not found by search, or no gap shown. Questions only your staff can resolve, such as refunds, are set apart, because no article will stop them arriving. Everything ends in one gap list, ranked by the tickets an article could have saved. Nothing is written, published or assigned until the lead says so.

## Who starts the work, and when

The support lead, or a support specialist preparing it for the lead, once a period after the tickets are tagged: monthly for most teams, quarterly for a small one. It is also worth running when ticket volume climbs and nobody can say which questions the help centre leaves unanswered.

The lead reads the review, settles the decisions at the end, confirms the gap list and names who writes each item before anyone starts.

## What they supply

- **The period's ticket export:** each ticket's topic, its subject line, the article the agent sent, if any, and a short line on what resolved it.
- **The help centre's search log** for the same period: each search term, how often it was searched and how many articles it returned.
- **The article list** from your help centre: IDs, titles and tags.
- **Your settings:** how many tickets make a topic common, and who receives security and escalation matters.

## What comes out

One review in a fixed order. A line for every common topic, with its count, how its tickets were answered and its verdict. The missing articles, with what agents told customers and the words customers used. The articles that fell short, with what the tickets say was wrong. The articles search could not find, with the exact words missing from their titles and tags. Searches that found nothing and match no ticket topic. The topics no article will help. Then the ranked gap list, and the decisions only the lead can make.

A check line at the top shows every ticket in the period counted exactly once. Customer names and company names in the subject lines stay out of the review.

See the worked example in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Customer support and service](https://fullypowered.ai/functions/customer-support-and-service/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=customer-support-help-centre-gap-review&from=gh-help-centre-gap-review), which owns the help centre and answers every question it leaves open.
- [Software technology](https://fullypowered.ai/industries/software-technology/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=customer-support-help-centre-gap-review&from=gh-help-centre-gap-review), where every new screen brings questions the help centre has not met yet.
- [E-commerce and retail](https://fullypowered.ai/industries/ecommerce-and-retail/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=customer-support-help-centre-gap-review&from=gh-help-centre-gap-review), where orders, deliveries and accounts generate the same questions week after week.
- [Professional services](https://fullypowered.ai/industries/professional-services/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=customer-support-help-centre-gap-review&from=gh-help-centre-gap-review), where client portals and billing questions repeat across every client.
- [Established businesses](https://fullypowered.ai/situations/established-businesses/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=customer-support-help-centre-gap-review&from=gh-help-centre-gap-review), where the help centre has grown for years and nobody has read it against the tickets.
- [Growth & scaling](https://fullypowered.ai/situations/growth-and-scaling/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=customer-support-help-centre-gap-review&from=gh-help-centre-gap-review), when ticket volume rises faster than the support team can.

## What has to change for your company

Agree your ticket topics and tag consistently; the review counts your tags and never invents its own. Agree a habit for the resolution line, because the review reads it: say when a linked article worked, when it was wrong or out of date, and when staff did the work. Export with the column headers the template expects, or tell it yours; when a header does not match, it stops and asks. Export the help centre's search log for the same period. Set how many tickets make a topic common, and name who receives security matters, which never become help-centre work. It runs in ChatGPT, Claude, Copilot or Gemini from files you export; it needs no connection to your helpdesk.

## What has been checked

FullyPowered AI wrote this workflow template as its own method. It was editorially reviewed on 10 November 2026. It was tried on its example in Claude on 10 November 2026, by the session that wrote it rather than an independent one; the record is published with it and says so. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on a past month your support lead remembers well, with hard cases written in advance: a topic only staff can resolve, an article an agent had to correct, a search term that matches no ticket, an export with different column headers, two tags that mean the same thing, a ticket about a compromised account. The lead checks every count against the export before anyone relies on the list. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=customer-support-help-centre-gap-review&from=gh-help-centre-gap-review) sets those cases up, and [what we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=customer-support-help-centre-gap-review&from=gh-help-centre-gap-review) describes the record we keep.

- Written by FullyPowered AI.
- Sources and rights reviewed.
- Editorially reviewed on 10 November 2026.
- Package format checked by script on every release.
- Tried once on its example in Claude on 10 November 2026. The record is in [TRIAL.md](TRIAL.md).
- Not yet tested in a client environment.

## What is in this folder

- [TEMPLATE.md](TEMPLATE.md): the complete workflow template. Roles, inputs, the procedure, exceptions and stop conditions, the output format, a reviewer checklist, acceptance tests, the instructions for an AI assistant and what to customize.
- [EXAMPLE.md](EXAMPLE.md): a worked example.
- [TRIAL.md](TRIAL.md): what came out when the template was tried on its example.
- [SKILL.md](SKILL.md): the technical file, for AI products that load packaged instructions from a folder.
- [SOURCES.md](SOURCES.md): what the workflow template drew on, with licences.
- [LICENSE](LICENSE): MIT. Use it, change it, make it yours.

## Start using it

1. Read [EXAMPLE.md](EXAMPLE.md) to see what a good result looks like.
2. Open [TEMPLATE.md](TEMPLATE.md) and set every item under "What to customize" to your own rules, roles and limits.
3. Give your AI assistant the instruction block and the output format from the template, with your own limits in place of the ones the instructions leave open in square brackets. Paste them in as custom instructions in ChatGPT, Claude, Copilot or Gemini, or copy this whole folder into a product that loads `SKILL.md` packages. This folder stands alone; you do not need the rest of the repository.
4. Run it on past work first, using the reviewer checklist and acceptance tests in the template, before anyone relies on it.

## Related workflow templates

- [Help article from a resolved issue](../help-article-from-a-resolved-issue/)
- [Customer feedback themes](../customer-feedback-themes/)
- [Support ticket triage](../support-ticket-triage/)

## Make it yours

This workflow template is an example and a starting point. FullyPowered AI adapts it to how your company works, proves it on real work and rolls it out to the roles that use it. We can also build any other workflow for your company, including one that runs several steps, in a Workflow Sprint or a scoped implementation. [Talk with us](https://fullypowered.ai/contact/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=customer-support-help-centre-gap-review&from=gh-help-centre-gap-review).
