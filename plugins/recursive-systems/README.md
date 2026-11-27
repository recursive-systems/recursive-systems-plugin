# Recursive Systems

For HVAC companies. Ask Claude how often your shop shows up when people nearby search, and who shows up instead.
It's free.

## Get started

Add Recursive Systems in Claude and connect: sign in with your email. We email you a code; there is no password.
Then:

1. **Say "Find my shop: Northwind Heating, Fairview"** (your shop's name and town). Claude finds it, or shows a
   short list to pick from.
2. **Say yes to add it.** Nothing is added until you do.
3. **Say "Show me my report."** A first report takes a few minutes.

Every button, step by step: [Connect Claude](https://recursivesystems.dev/docs/claude/). Already a Recursive
Systems client? Your business is already there: skip to step 3.

## Ask what you want to know

- "Who shows up instead of us on Google Maps, and why?"
- "How do our reviews compare?"
- "Which towns and services does our website show up for on Google?"
- "Which companies do AI tools like ChatGPT mention?"
- "What should I do first?"
- "Is my business still being monitored?"

Answers are short. Ask for more detail whenever you want it.

## One business per account

An account covers one business that you add, at a time. Your first one can be added any time. To follow a
different one, the first is removed; you can switch to a different business once a calendar month, and go back to
one you had before any time. Each location is its own business. Adding and removing happen only when you say yes.

## What's in your report

- **Google Maps:** how often you're in the top 3 at the places we checked around your shop, and who else is.
- **Google reviews:** your reviews beside what is typical for the shops that show up most.
- **Google search:** how often your website is in Google's first 10 results.
- **AI answers:** how often AI tools mention you, and who they mention instead.

Each part shows what changed since last month. You can also turn on **monitoring** (more Google Maps checks at
other times of day, up to 8 checks or 7 days) and a **monthly report**. Both are off until you say so.

## What isn't

- **A rank.** Google shows different results depending on where the person searching is, so your report counts how
  often you show up. It never says "you're #3".
- **Calls, clicks, website visits, leads or jobs.** Your report is what the public can see; your own Google
  Business Profile numbers aren't in it.

## Email

You may get an email when your first report is ready and, if you turned them on, when monitoring ends or a monthly
report is available. Once you have added a business, we may send you marketing email about our services; the
unsubscribe link in it turns that off and nothing else.

## Your data

The plugin runs no code of its own and stores nothing. It connects Claude to Recursive Systems as the person who
signed in, and you see only your own businesses. Your report is public data that Recursive Systems checks.

What leaves Claude: the shop name and town you type, your email when you sign in, and Claude's requests for your
report. If something in your report looks wrong and you say yes, Claude can also send us a short note about it, with
no names or numbers in it.

What we keep, who we share it with and how to have it deleted is in the
[Privacy Notice](https://recursivesystems.dev/privacy/#privacy-notice). Adding a business means you agree to the
[Terms of Service](https://recursivesystems.dev/terms/).

## Help

- **Claude stops answering or asks you to sign in again:** open your connectors in Claude
  (https://claude.ai/customize/connectors/yours) and select Connect or Reconnect on Recursive Systems. In Claude
  Code, run `/mcp`, choose Recursive Systems and select Authenticate.
- **You see the wrong businesses, or none:** you may be signed in with another email. Connect again with the email
  you use with Recursive Systems.
- **Anything else** about your account, your report or your data, or to delete your account or ask what we hold
  about you: https://recursivesystems.dev/support/ or bradley@recursivesystems.dev.
- **A security concern:** email bradley@recursivesystems.dev. See
  [SECURITY.md](https://github.com/recursive-systems/recursive-systems-plugin/blob/main/SECURITY.md).

Recursive Systems LLC, PO Box 35, Highwood, IL 60040

## In Claude Code

```
/plugin marketplace add recursive-systems/recursive-systems-plugin
/plugin install recursive-systems@recursive-systems
```

Then run `/mcp`, choose `plugin:recursive-systems:recursive-systems` and select **Authenticate**.

The plugin is one skill, `report`, and a connection to Recursive Systems (`https://app.recursivesystems.dev/mcp`).

## License

MIT. See [LICENSE](LICENSE).
