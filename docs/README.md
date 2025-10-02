# container-use documentation

This documentation is built using MDX and Mintlify. 

## Quick Start

### Preview Locally

```bash
cd docs
npx mint dev
```

The preview will be available at `http://localhost:3000`.

## Documentation Structure

### Get Started
- **introduction.mdx** - Overview and value proposition
- **quickstart.mdx** - 5-minute tutorial
- **faq.mdx** - Frequently asked questions
- **documentation-guide.mdx** - How to navigate the docs

### Guides
- **environment-workflow.mdx** - Using environments effectively
- **environment-configuration.mdx** - Customizing setup
- **secrets.mdx** - Secure credentials management
- **troubleshooting.mdx** - Common issues and solutions

### Reference
- **cli-reference.mdx** - Complete CLI command reference
- **agent-integrations.mdx** - Setup guides for agents
- **mcp-api-reference.mdx** - Complete MCP tool documentation
- **glossary.mdx** - Definitions of key terms

### Development
- **architecture.mdx** - System design and internals
- **developer-guide.mdx** - Contributing and development

## Making Changes

1. Edit MDX files in this directory
2. Test locally with `npx mint dev`
3. Commit and push changes
4. Docs site updates automatically from `main` branch

## Documentation Guidelines

### Writing Style
- Use clear, concise language
- Include code examples
- Add cross-references to related topics
- Use callouts (Note, Warning, Info) for important information

### MDX Format
- Frontmatter with title, description, and icon
- Use Markdown with MDX components
- Code blocks with syntax highlighting
- Mintlify components (CardGroup, Card, etc.)

### Sections
- Start with overview/introduction
- Progress from simple to complex
- Include practical examples
- End with "See also" links

## File Organization

```
docs/
├── docs.json                      # Navigation structure
├── README.md                      # This file
├── images/                        # Images and diagrams
├── introduction.mdx               # Start here
├── quickstart.mdx                 # First tutorial
├── faq.mdx                        # Common questions
├── documentation-guide.mdx        # Doc navigation
├── environment-workflow.mdx       # Core workflows
├── environment-configuration.mdx  # Setup guide
├── secrets.mdx                    # Security
├── troubleshooting.mdx           # Debugging
├── cli-reference.mdx             # CLI commands
├── agent-integrations.mdx        # Agent setup
├── mcp-api-reference.mdx         # MCP tools
├── glossary.mdx                  # Terms
├── architecture.mdx              # Internals
└── developer-guide.mdx           # Contributing
```

## Components

### Callouts
```mdx
<Note>Important information</Note>
<Warning>Be careful</Warning>
<Info>Additional context</Info>
```

### Cards
```mdx
<CardGroup cols={2}>
  <Card title="Title" icon="icon-name" href="/link">
    Description
  </Card>
</CardGroup>
```

### Code Blocks
```mdx
```bash
# Commands
container-use list
\```
```

### Tabs
```mdx
<Tabs>
  <Tab title="macOS">
    Content for macOS
  </Tab>
  <Tab title="Linux">
    Content for Linux
  </Tab>
</Tabs>
```

## Links

- **Live Docs**: https://container-use.com
- **GitHub**: https://github.com/dagger/container-use
- **Mintlify Docs**: https://mintlify.com/docs

## Deploying

The docs site is automatically deployed when changes are pushed to the `main` branch. No manual deployment needed.

## Feedback

Have suggestions for improving the docs?
- Open an issue: https://github.com/dagger/container-use/issues
- Discuss in Discord: https://container-use.com/discord
- Submit a PR with improvements
