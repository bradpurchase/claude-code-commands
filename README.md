# claude-code-commands
Custom commands I've written for Claude Code.

## Usage

These commands are not project-specific, you could add them as [personal commands](https://code.claude.com/docs/en/slash-commands#personal-commands) and have them available across all your projects:

```sh
mkdir -p ~/.claude/commands
cp -r claude-code-commands/.claude/commands ~/.claude/commands
```

However if you wanted to share them with your team and/or scope them to your project, copy them to the `.claude/commands` directory in your project:

```sh
mkdir -p .claude/commands
cp -r claude-code-commands/.claude/commands .claude/commands
```

Read more about command types in the Claude Code docs [here](https://code.claude.com/docs/en/slash-commands#command-types).