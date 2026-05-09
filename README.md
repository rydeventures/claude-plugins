# Ryde Ventures Claude Plugins

Claude Code plugins we build and use at Ryde Ventures.

## Installation

```bash
/plugin marketplace add rydeventures/claude-plugins
```

## Available Plugins

### Advisory

#### personas

Session-aware persona advisors with project-scoped threads and memory. Bundled pack of public-figure personas (Steve Jobs, Taylor Otwell, Raymond Hettinger, David Tolnay); pluggable for third-party personas via git repos. Replaces the standalone `*-says` plugins.

```bash
/plugin install personas@rydeventures-claude-plugins
```

[View documentation →](https://github.com/mischasigtermans/claude-personas)

### Automation

#### ralph

An opinionated take on the Ralph autonomous loop for Claude Code. Define user stories, run the loop, check back when it's done.

```bash
/plugin install ralph@rydeventures-claude-plugins
```

[View documentation →](https://github.com/mischasigtermans/claude-ralph)

### Productivity

#### parley

Cross-session peer agents for Claude Code. Ask one project what another knows, with full context and memory across turns. Three-tier routing: live-attached when a peer window is in listen mode, headless-resumed when a cached session exists, headless-fresh otherwise.

```bash
/plugin install parley@rydeventures-claude-plugins
```

[View documentation →](https://github.com/mischasigtermans/claude-parley)

## License

MIT
