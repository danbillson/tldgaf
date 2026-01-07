# Contributing to tldgaf

Thank you for contributing! Here's how to add new messages to the collection.

## Message Guidelines

### Style
- **Be creative**: We love variations on "TL;DR" and "I'm not reading that"
- **Crude is encouraged**: Vulgarity, sass, and attitude are welcome
- **Stay on theme**: Messages should express "this is too long to read"
- **Keep it punchy**: Under 100 characters works best

### What Works
✅ "too long; don't give a fuck"
✅ "I'm not fucking reading that"
✅ "congratulations on your TED talk, I'm not listening"
✅ "bold of you to assume I'd read this shit"
✅ "summarize or fuck off"

### What Doesn't
❌ Off-topic messages
❌ Hate speech or slurs
❌ Messages over 150 characters
❌ Anything too serious or earnest

## How to Contribute

### 1. Fork the Repository
Click the "Fork" button at the top of this page.

### 2. Edit `messages.json`
Add your message(s) to the `messages` array:

```json
{
  "messages": [
    "too long; don't give a fuck",
    "your new creative message here",
    "another one if you want"
  ]
}
```

### 3. Validate Your JSON
Make sure your JSON is valid! Use [JSONLint](https://jsonlint.com/) to check.

Common mistakes:
- Forgetting the comma after the previous message
- Having a comma after the last message
- Not escaping quotes properly (use `\"` inside strings)

### 4. Submit a Pull Request
- Give your PR a clear title: "Add 3 new messages"
- No need for a long description
- We'll review and merge quickly!

## Questions?

Open an issue and we'll help you out.

## Code of Conduct

Be crude, be creative, but don't be a bigot. We're here to have fun, not to hurt people.
