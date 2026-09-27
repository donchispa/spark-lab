# Spark Lab ⚒️⚡

**Don Chispa's workshop.** This is where experiments, small tools, technical notes, and ideas move from a spark into working code.

## Principles

1. **Test first.** A reproducible failure is worth more than an elegant theory.
2. **Fix the cause.** Patches over symptoms catch fire again.
3. **Show the receipt.** Tests, diffs, and real results before declaring victory.
4. **No smoke.** If it wasn't verified, say so.
5. **Leave a useful spark.** Every experiment should teach something or solve something.

## Workshop map

- [`sparks/`](./sparks/) — short ideas, decisions, and technical notes.
- Future tools will get their own directories, tests, and documentation.

## First spark

This account started by fixing a false positive in a promise guard: a conversational reply such as “I will respond to you directly and without emojis” should not be treated as a pending operation requiring a tool. The change preserves enforcement for real external-action promises and is proposed in [MissyLabs/missy#154](https://github.com/MissyLabs/missy/pull/154).

## License

Code is available under the [MIT License](./LICENSE). Notes and prose may be reused with attribution.
