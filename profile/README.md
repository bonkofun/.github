<h1 align="center">Bonko</h1>
<p align="center"><strong>Small link. Big smile.</strong></p>
<p align="center">Personal moments, made interactive.</p>

<p align="center">
  <a href="https://github.com/bonkofun/bonko-cli">Bonko CLI</a> ·
  <a href="https://github.com/bonkofun/template-sdk">Template SDK</a> ·
  <a href="https://github.com/bonkofun/bonko-cli#readme">Get started</a>
</p>

Bonko turns birthdays, anniversaries, pet moments, achievements, and everyday appreciation into private, interactive links. Start with a template, add a photo and a few words, then share a little surprise with someone you care about.

**Pick → Personalize → Create a link → Share → Open → Reveal**

## Build something personal

Our public tools help developers create reusable interactive templates, preview them locally, and package them for review.

| Project                                                      | What it does                                                                                          |
| ------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------- |
| [**Bonko CLI**](https://github.com/bonkofun/bonko-cli)       | Create, preview, build, verify, and package templates with a Node.js CLI and local Studio.            |
| [**Template SDK**](https://github.com/bonkofun/template-sdk) | Shared TypeScript contracts, package validation, and an isolated browser runtime for Bonko templates. |

## Create your first template

Install the CLI on macOS or Linux with Node.js **22.12 or later** and npm available:

```sh
curl -fsSL https://github.com/bonkofun/bonko-cli/releases/latest/download/install.sh | sh
```

Follow the installer's PATH instructions, then start creating:

```sh
bonko new birthday-card
cd birthday-card
bonko dev
```

Studio provides a phone-frame preview for trying your content, photo crop, and interactions. When your template is ready:

```sh
bonko check
bonko pack
```

Read the [CLI guide](https://github.com/bonkofun/bonko-cli#readme) and [template protocol](https://github.com/bonkofun/bonko-cli/blob/main/docs/PROTOCOL.md) for supported components, runtime behavior, and delivery requirements. Packaged templates still require platform review before publication.

## What we care about

- **Personal by design.** One photo, a name, and a short message give each template its meaning.
- **Accessible interactions.** Keyboard access, reduced motion, and readable static states are part of the template contract.
- **Clear boundaries.** Local authoring tools use a shared, versioned SDK and an isolated runtime.
- **Tools you can inspect.** Explore the source, report issues, and help improve the developer experience.

## Contribute

Start with the [contributing guide](https://github.com/bonkofun/bonko-cli/blob/main/CONTRIBUTING.md), or [open an issue](https://github.com/bonkofun/bonko-cli/issues) with a reproducible bug or a focused suggestion. For security concerns, follow the repository's [security reporting guidance](https://github.com/bonkofun/bonko-cli/blob/main/SECURITY.md).

<p align="center"><strong>Make an ordinary day a little more memorable.</strong></p>
