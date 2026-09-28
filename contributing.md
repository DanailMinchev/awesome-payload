# Contribution Guidelines

Please note that this project is released with a [Contributor Code of Conduct](code-of-conduct.md).
By participating in this project you agree to its terms.

This list follows guidelines and rules from the [Awesome manifesto](https://github.com/sindresorhus/awesome/blob/main/awesome.md) and the [Awesome list guidelines](https://github.com/sindresorhus/awesome/blob/main/pull_request_template.md).
This is a curated list of the best Payload resources, not an index of everything that exists.

---

## What gets accepted

Make sure the project you are suggesting meets all of the following:

- **It is Payload specific.** Built for Payload or integrated with Payload, rather than a generic tool that works with it.
- **It is at least 30 days old.** That means 30 days from either the first real commit or when it was open-sourced. Whatever is most recent.
- **It is actively maintained.** Unmaintained, archived and deprecated projects are not accepted, and existing entries may be removed once they go stale.
- **It is documented.** A README or documentation which explains what the project does, how to install it and how to use it.
- **It has a license.** A `license` or `LICENSE` file in the repository root.
- **Not a duplicate.** If it is similar to something already on the list, explain in your pull request why it is worth adding alongside it.

Self-submissions are welcome - please mention in the pull request that you are the author.
Commercial projects and paid services are fine, as long as the pricing is disclosed in the project's own readme.

## AI-generated content

- **Fully AI-generated pull requests are not accepted.**
- You may use AI tools while preparing a contribution, but the entry text must be written and checked by you, and you are expected to have actually used the project you are suggesting.
- Descriptions generated from a model's summary of a readme, for a project you have not tried, will be rejected.

The Awesome guidelines additionally require that a list "is not AI-generated" and stays a "non-generated Markdown file", so this applies to the list itself as well as to individual contributions.

## Entry format

- When the entry is a link to a GitHub repository (or similar), use the format `[owner / repository](https://github.com/owner/repository) - Description.`
- When available, the source code should be linked instead of package manager links or marketing websites.
- Add your entry to the bottom of the relevant section.
- Start the description with a capital letter and end it with a period.
- Keep descriptions short, factual and objective - no marketing taglines, no title case, no superlatives.
- Do not repeat "Payload" in the description where it is already implied.

## New sections

New sections are welcome once there is enough to fill them or there is a reason to create them (there is a missing section).

## Pull requests

- Search previous suggestions, including closed pull requests, before making a new one, as yours may be a duplicate.
- Make an individual pull request for each suggestion.
- **The pull request title becomes the commit message.** Pull requests are squash-merged, so the title is what ends up in the repository history - please make it a good one and use [Conventional Commits](https://www.conventionalcommits.org/), for example: `feat: add payload-example plugin`.
- Check your spelling and grammar.
- Make sure your text editor is set to remove trailing whitespace.
- This project is using [Prettier](https://prettier.io/) and [awesome-lint](https://github.com/sindresorhus/awesome-lint) to format the source code. You can run the following commands to format and lint your changes:
  ```shell
  npm ci
  npm run format
  npm run lint
  ```

Thank you for your suggestions!

## Updating your PR

A lot of times, making a PR adhere to the standards above can be difficult.
If the maintainers notice anything that we'd like changed, we'll ask you to edit your PR before we merge it.
There's no need to open a new PR, just edit the existing one.
