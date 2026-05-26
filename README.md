# Ryzen AI Software Documentation (Mintlify)

Mintlify port of the [AMD Ryzen AI Software documentation](https://ryzenai.docs.amd.com/en/latest/).

Source content was migrated from the Sphinx/RST site at [bconsolvo/ryzen-ai-documentation](https://github.com/bconsolvo/ryzen-ai-documentation).

## Local preview

```bash
npx mint dev
```

Then open <http://localhost:3000>.

## Structure

- `docs.json` - Mintlify site configuration (navigation, theme, branding)
- `index.mdx` - Landing page
- `*.mdx` - Top-level pages
- `llm/`, `gpu/`, `winml/` - Subsection pages
- `images/` - Inline diagrams referenced from pages
- `assets/` - Site assets (favicon, logo)

## Editing

Each page is plain MDX. Standard Markdown plus Mintlify components such as `<Note>`, `<Warning>`, `<CardGroup>`, and `<Card>`. See <https://mintlify.com/docs> for the full component reference.

## License

Ryzen AI is licensed under the [MIT License](https://github.com/amd/RyzenAI-SW/blob/main/LICENSE).
