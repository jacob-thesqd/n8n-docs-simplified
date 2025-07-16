# n8n Documentation - Simplified

A clean, user-friendly documentation site for n8n built with Mintlify.

## 🚀 What's Different?

This is a **simplified version** of n8n documentation that focuses on:

- **Clean structure** - Easy to navigate and understand
- **User-focused content** - Practical guides and examples
- **Simple maintenance** - No complex auto-generation or multiple API specs
- **Modern design** - Clean, responsive interface

## 📁 Structure

```
├── docs.json                 # Main configuration
├── index.mdx                 # Homepage
├── installation.mdx          # Installation guide
├── quickstart.mdx           # Quick start tutorial
├── troubleshooting.mdx      # Common issues and solutions
├── concepts/                # Core concepts
│   ├── workflows.mdx        # Understanding workflows
│   ├── nodes.mdx           # Node fundamentals
│   ├── expressions.mdx     # Data expressions
│   └── credentials.mdx     # Authentication
├── nodes/                   # Node documentation
│   ├── overview.mdx        # Node library overview
│   ├── core-nodes.mdx      # Essential nodes
│   ├── trigger-nodes.mdx   # Trigger nodes
│   ├── regular-nodes.mdx   # Regular nodes
│   └── custom-nodes.mdx    # Custom node development
├── workflows/               # Workflow guides
│   ├── creating.mdx        # Creating workflows
│   ├── testing.mdx         # Testing workflows
│   ├── debugging.mdx       # Debugging workflows
│   └── examples.mdx        # Real-world examples
├── api/                     # API documentation
│   ├── introduction.mdx    # API overview
│   ├── authentication.mdx  # Auth methods
│   ├── workflows.mdx       # Workflows API
│   └── executions.mdx      # Executions API
├── hosting/                 # Self-hosting
│   ├── overview.mdx        # Hosting overview
│   ├── docker.mdx          # Docker deployment
│   ├── npm.mdx             # npm installation
│   └── configuration.mdx   # Configuration options
└── community.mdx            # Community resources
```

## 🔧 Development

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

```bash
# Install Mintlify CLI
npm i -g mint

# Clone this repository
git clone https://github.com/jacob-thesqd/n8n-docs-simplified.git
cd n8n-docs-simplified

# Start development server
mint dev
```

### Building

```bash
# Build for production
mint build
```

## 🎨 Customization

### Themes & Colors

The documentation uses n8n's brand colors:

```json
{
  "colors": {
    "primary": "#FF6D5A",
    "light": "#FF8A75", 
    "dark": "#E55A47"
  }
}
```

### Navigation

All navigation is configured in `docs.json`. The structure is:

1. **Getting Started** - Installation and quick start
2. **Core Concepts** - Understanding n8n fundamentals
3. **Nodes** - Node documentation and guides
4. **Building Workflows** - Workflow creation and management
5. **API Reference** - REST API documentation
6. **Self-Hosting** - Deployment and configuration
7. **Help & Support** - Troubleshooting and community

## 📝 Content Guidelines

### Writing Style

- **Clear and concise** - Use simple language
- **Action-oriented** - Focus on what users can do
- **Example-driven** - Include practical examples
- **Progressive** - Start simple, build complexity

### File Structure

- Use `.mdx` files for all content
- Include frontmatter with `title` and `description`
- Use descriptive filenames
- Organize content logically

### Components

Common Mintlify components used:

- `<Card>` - Feature cards and links
- `<CardGroup>` - Group related cards
- `<Steps>` - Step-by-step instructions
- `<Warning>` - Important warnings
- `<Tip>` - Helpful tips
- `<Note>` - Additional information

## 🆚 Comparison with Original

### Original n8n-docs Issues:
- ❌ 6 different API specs auto-generated
- ❌ Complex navigation with multiple tabs
- ❌ Cryptic auto-generated filenames
- ❌ Over-engineered for simple documentation needs
- ❌ Hard to maintain and update

### This Simplified Version:
- ✅ Single, clean documentation structure
- ✅ Human-readable file names
- ✅ Easy to navigate and search
- ✅ Simple to maintain and update
- ✅ User-focused content organization
- ✅ No auto-generation complexity

## 🚀 Deployment

### Mintlify Hosting

1. Connect your GitHub repository to Mintlify
2. Configure the deployment settings
3. Push changes to automatically deploy

### Self-Hosting

1. Build the static site: `mint build`
2. Deploy the `build` folder to your hosting provider
3. Configure your web server to serve the files

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally with `mint dev`
5. Submit a pull request

### Content Contributions

- **New pages** - Add to appropriate directory
- **Updates** - Edit existing `.mdx` files
- **Examples** - Add practical examples
- **Fixes** - Correct errors and typos

## 📖 Resources

- [Mintlify Documentation](https://mintlify.com/docs)
- [n8n Official Site](https://n8n.io)
- [n8n GitHub Repository](https://github.com/n8n-io/n8n)
- [n8n Community](https://community.n8n.io)

## 📜 License

This documentation is open source and available under the [MIT License](LICENSE).

---

**Made with ❤️ for the n8n community**

*This simplified documentation focuses on what users actually need rather than complex auto-generated API specs. It's designed to be maintainable, searchable, and user-friendly.*