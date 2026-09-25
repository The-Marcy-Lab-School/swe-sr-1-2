# Choosing a Data Container

Compare a list of dictionaries against a dictionary of dictionaries, and argue
for one.

- [AI Use on This Assignment](#ai-use-on-this-assignment)
- [Setup](#setup)
- [Instructions](#instructions)
- [Short Response Questions](#short-response-questions)
  - [Prompt 1](#prompt-1)
- [Submitting](#submitting)

## AI Use on This Assignment

These are your own words. Do not use AI to draft or rewrite your responses —
that holds in every mode, including implementer mode. You may use it to check
grammar and spelling on writing you have already done, and you may use it
before you start to quiz you on how each container behaves. Paste this if you
want that kind of help:

> You are acting as a tutor. Quiz me on Python lists and dictionaries until I
> can say what each one is good at and what it is bad at, without looking
> anything up. Tell me when my reasoning is wrong or imprecise. Do not write
> or rewrite any part of my response for me.

The argument has to be yours. An opinion you did not form is impossible to
defend when somebody pushes back on it.

## Setup

Work in `development/mod-1`. Make a draft branch before you start.

```sh
git checkout -b draft
```

## Instructions

Write your response in `short_response.md`. The prompt is repeated here so you
can read the assignment without switching files.

Aim for a response with these qualities. Your instructor will give you
feedback on each one:

- [ ] Addresses all parts of the prompt
- [ ] Accurately uses relevant technical terminology
- [ ] Is free of grammar and spelling mistakes (double check with Grammarly!)
- [ ] Uses markdown to enhance readability (preview in VS Code with
      Command/Control + Shift + V)
- [ ] Is easy to comprehend

Preview your markdown to check how it renders before submitting.

## Short Response Questions

### Prompt 1

You are building an app and have to store data about user profiles. Each
profile is a dictionary with an `id`, a `username`, and a `password`.

Here are two ways to group those profiles together. The first is a **list of
dictionaries**:

```python
users_list = [
    {"id": 214, "username": "Spongebob", "password": "dandelion"},
    {"id": 592, "username": "Squidward", "password": "clarinet"},
    {"id": 723, "username": "Patrick", "password": "whoareyoupeople???"},
]
```

The second is a **dictionary of dictionaries**, keyed by username:

```python
users_dict = {
    "Spongebob": {"id": 214, "username": "Spongebob", "password": "dandelion"},
    "Squidward": {"id": 592, "username": "Squidward", "password": "clarinet"},
    "Patrick": {"id": 723, "username": "Patrick", "password": "whoareyoupeople???"},
}
```

Compare and contrast the two. Which would *you* choose, and why? What are the
tradeoffs of each container?

Think about what each one makes easy and what it makes awkward:

- Finding one user by username
- Finding one user by `id`
- Looping over every user
- Adding a user, and removing one
- Keeping the users in a particular order
- What happens when two users want the same username

## Submitting

```sh
git add -A
git commit -m "your message"
git push
```

Open a pull request to your instructor for feedback.
