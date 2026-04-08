# COSCUP Bio

A link-in-bio style page for [COSCUP](https://coscup.org/) — the annual open source conference held in Taipei, Taiwan. Built with Jekyll and deployed via GitHub Actions.

## Development

### Prerequisites

- Ruby (see `Gemfile` for version)
- Bundler

### Setup

```bash
bundle install
```

### Run locally

```bash
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000/bio`.

## Configuration

All content is configured in `index.md` via front matter:

| Field         | Description                          |
|---------------|--------------------------------------|
| `name`        | Display name                         |
| `description` | Bio text                             |
| `profile`     | Profile image path                   |
| `links`       | List of link buttons (title, url, icon) |
| `socials`     | Social media icons (title, url, icon) |
| `footer`      | Footer message                       |
| `copyright`   | Copyright line                       |

Icons use [Font Awesome](https://fontawesome.com/) class names.

## License

MIT License — see [LICENSE](LICENSE) for details.
