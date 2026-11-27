# Recursive Systems plugin for Claude

For HVAC companies. See how visible your shop is to homeowners nearby, next to the companies that show up instead:
how often you're in the Google Maps top 3 around your shop, how your reviews compare, and which companies Google
and AI tools mention. Then work out with Claude what to do about it. It's free.

Start with "Find my shop: <name>, <town>": Claude finds it, or shows a short list to pick from, and you say yes
before anything is added. Then
"Show me my report" or "Who shows up instead of us on Google Maps, and why?"

The plugin runs no code of its own. It connects Claude to the Recursive Systems connector
(`https://app.recursivesystems.dev/mcp`) and adds one skill, `report`, that helps Claude use it. What leaves Claude:
the shop name and town you type, your email when you sign in, and Claude's requests for your report.

## Install

In Claude Code:

```
/plugin marketplace add recursive-systems/recursive-systems-plugin
/plugin install recursive-systems@recursive-systems
```

Then run `/mcp`, choose `plugin:recursive-systems:recursive-systems` and select **Authenticate**. Sign in with the
email you use with Recursive Systems. You see only your own businesses: the ones you're on the team of and the one
you added.

In a browser or the desktop app, follow [Connect Claude](https://recursivesystems.dev/docs/claude/).

## More

- What you get, the tools and the data: [plugins/recursive-systems/README.md](plugins/recursive-systems/README.md)
- Changes: [CHANGELOG.md](CHANGELOG.md)
- Support: https://recursivesystems.dev/support/
- Security: [SECURITY.md](SECURITY.md)
- Privacy: https://recursivesystems.dev/privacy/#privacy-notice
- Terms: https://recursivesystems.dev/terms/

## License

MIT. See [LICENSE](LICENSE).
