# Welcome

Here's a quick guide to get you started.

## Dev Philosophy

- **Simple is better** - Do not add an abstraction or a library if you can do it in a simpler way.
- **Prefer great tests over great code**
- **Every feature should have an associated test**
- **Measure what matters** - Data allows us to make good decisions, give our team the power to do that by adding GA events.

## Contributing

We use [Shortcut](https://shortcut.com/) for task and project management (you can log in via SSO using your Wakelet email);
please make sure your branch is associated to a story by naming it: `sc-{storyId}`. We make a habit of pushing our work daily;
if it's still WIP, you can commit it as such (via a `wip:` prefix), and amend it via a rebase later.

We write [conventional commits](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716) and follow the
[7 rules of a great commit message](https://cbea.ms/git-commit/#seven-rules); these are used to generate release notes
in our Slack `#bot-releases` channel, so keep them concise and informative. If you're working on a feature branch, prefer
to include tests (and any fixes from code and/or design reviews) in the same commit as the feature itself, rather than
separately.

Even though branches are associated to Shortcut stories, we prefer to write meaningful PR titles so they are easy to navigate
and manage. If the repository you are working on has a PR checklist, please fill it (if applicable), as this will help speed
up the review process.
