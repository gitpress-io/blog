---
title: Using Message Blocks
date: 2019-04-09
---

GitPress implement some Markdown extension from [Open Publishing Service](https://docs.microsoft.com/en-us/contribute/how-to-write-use-markdown#ops-custom-markdown-extensions), such as Message Blocks.

You can choose from several types of message blocks to draw attention to specific content:

## Builtin Message Blocks

There are 5 builtin message blocks:

- NOTE
- WARNING
- ERROR
- TIP
- IMPORTANT

Examples:

```markdown
> [!NOTE]
> This is a NOTE

> [!WARNING]
> This is a WARNING

> [!ERROR]
> This is a ERROR

> [!TIP]
> This is a TIP

> [!IMPORTANT]
> This is IMPORTANT
```

These render as follows:

> [!NOTE]
> This is a NOTE

> [!WARNING]
> This is a WARNING

> [!ERROR]
> This is a ERROR

> [!TIP]
> This is a TIP

> [!IMPORTANT]
> This is IMPORTANT

## Custom Message Block

You can also use custom message block with default style:

```markdown
> [!Hello]
> This is a Greeting.
```

This render as follows:

> [!Hello]
> This is a Greeting.