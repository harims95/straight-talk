# Idea Sparring — A Claude Skill

A Claude Skill that turns Claude into a sparring partner instead of an agreement engine when you bring an idea, plan, or decision for evaluation.

## The problem this solves

LLMs are trained on human feedback. Humans rate "you make a good point" responses higher than "actually you're wrong because..." responses. Over time, this trains models toward agreeableness.

This creates a real and underappreciated harm: people bring ideas to Claude (or any LLM), get gentle validation, and walk away believing their idea is sound. Some percentage of them spend months or years building the wrong thing.

The cost of that, multiplied across the millions of people having idea conversations with LLMs daily, is enormous in aggregate. Wasted time. Wasted capital. Wasted ambition. And usually the user doesn't know it happened until much later.

## What this skill does

When activated, Claude stops being agreeable and starts being useful in a harder way. It:

- Refuses to evaluate ideas before understanding the situation neutrally
- Separates problem-validation from solution-validation (these are two different conversations)
- Generates the strongest counter-case before any endorsement
- Demands specifics and rejects generic advice
- Stress-tests with unit economics when relevant
- States what would change its mind, so the user knows what evidence to look for
- Resists sycophancy ("great question," "you're absolutely right")
- Pushes back when the user pushes back, instead of immediately capitulating
- Volunteers the uncomfortable observation before concluding

It does not become hostile, cold, or refuse engagement. It just stops protecting the user from sharp observations they would benefit from hearing.

## Installation

Copy the `SKILL.md` file into your Claude skills directory. Trigger it by bringing an idea, plan, or decision for evaluation. Phrases like "is this a good idea," "I'm considering building," "what do you think of this" will activate it.

To use the human-facing version directly (without installing the skill), see `RULEBOOK.md` — a guide on how to talk to any LLM productively, even without this skill installed.

## When NOT to use this skill

This skill is calibrated for idea evaluation. It is not appropriate for:

- Factual questions
- Coding tasks
- Writing assistance
- Emotional support
- Open brainstorming where you want expansion, not critique

Trying to use this skill for those contexts will produce annoying friction. The skill is designed to deactivate when the conversation is not about evaluation.

## Origin

This skill was extracted from a long conversation between a user and Claude where the user repeatedly pushed back on default agreeable responses and demanded honest engagement. The rulebook that emerged from that conversation was useful enough that it seemed worth packaging for others.

The user is the kind of person who notices when AI agrees too easily and refuses to accept that as the price of using it. This skill is for people like them.

## License

MIT. Use it, fork it, modify it. If you improve it, consider sharing the improvements.

## Honest caveats

- This skill does not make Claude infallible. Claude can still be wrong. The skill makes Claude more likely to express uncertainty and surface counter-arguments, not more likely to be correct.
- The skill works best when the user brings real material — actual customer conversations, real numbers, specific frustrations. Generic inputs still produce limited outputs, even with friction enabled.
- The user remains responsible for the final decision. Claude is a sparring partner, not a verdict-maker. This skill makes the sparring better. It does not transfer the judgment.
