# Contributing to Claude Finance Subagents

Thank you for your interest in contributing to this finance-focused subagent collection!

## 🤝 How to Contribute

### Adding a New Subagent

1. **Choose the right category** — Place your subagent in the most appropriate category folder
2. **Follow the template** — Use the standardized YAML frontmatter format
3. **Test your subagent** — Ensure it works with Claude Code
4. **Update required files** — When adding a new agent, you must update:
   - **Main README.md**: Add your agent to the appropriate category section in alphabetical order
   - **Category README.md**: Add detailed description, update Quick Selection Guide table
   - **Your agent .md file**: Create the actual agent definition following the template
5. **Submit a PR** — Include a clear description of the subagent's purpose

### Subagent Requirements

Each subagent should include:
- Clear role definition with financial domain expertise
- List of expertise areas (indicators, models, strategies)
- Tool permissions appropriate to the role
- Communication protocol examples
- Development workflow with systematic phases
- Integration points with other finance subagents
- Best practices and risk considerations

### Required Updates When Adding a New Agent

When you add a new agent, you MUST update these files:

1. **Main README.md**
   - Add your agent link in the appropriate category section
   - Maintain alphabetical order
   - Format: `- [**agent-name**](path/to/agent.md) - Brief description`

2. **Category README.md** (e.g., `categories/01-technical-indicators/README.md`)
   - Add detailed agent description in the "Available Subagents" section
   - Update the "Quick Selection Guide" table

3. **Your Agent File** (e.g., `categories/01-technical-indicators/your-agent.md`)
   - Follow the standard template structure
   - Include all required sections

### Code of Conduct

- Be respectful and inclusive
- Provide constructive feedback
- Test contributions before submitting
- Follow the existing format and structure
- Ensure financial accuracy in agent definitions

### Pull Request Process

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-subagent`)
3. Add your subagent following the template
4. Update ALL required locations:
   - Main README.md (add to category section in alphabetical order)
   - Category-specific README.md (add description, update tables)
5. Verify all links work correctly
6. Submit a pull request with a clear description

### Quality Guidelines

- Subagents should be well-structured and tested
- Include clear documentation with financial domain context
- Provide practical examples relevant to trading/analysis
- Ensure compatibility with Claude Code
- Use accurate financial terminology and methodologies

## 📝 License

By contributing, you agree that your contributions will be licensed under the MIT License.

All subagents in this repository are provided "as is" without warranty. They are educational tools and should not be considered financial advice. The maintainers do not audit or guarantee the accuracy of any contribution and accept no liability for any issues arising from their use.
