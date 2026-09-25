# Short Responses

For this short response assignment, aim to write a response with the following
qualities (your instructor will give you feedback on these areas):

- [ ] Addresses all parts of the prompt
- [ ] Accurately uses relevant technical terminology
- [ ] Is free of grammar and spelling mistakes (double check with Grammarly!)
- [ ] Uses markdown to enhance readability (preview in VS Code with
      Command/Control + Shift + V)
- [ ] Is easy to comprehend

Write your response in the space provided. Make sure to preview your markdown
to check how it is rendered before submitting.

## Question 1

### Prompt 1

You are building an app and have to store data about user profiles. Each
profile is a dictionary with an `id`, a `username`, and a `password`.

A **list of dictionaries**:

```python
users_list = [
    {"id": 214, "username": "Spongebob", "password": "dandelion"},
    {"id": 592, "username": "Squidward", "password": "clarinet"},
    {"id": 723, "username": "Patrick", "password": "whoareyoupeople???"},
]
```

A **dictionary of dictionaries**, keyed by username:

```python
users_dict = {
    "Spongebob": {"id": 214, "username": "Spongebob", "password": "dandelion"},
    "Squidward": {"id": 592, "username": "Squidward", "password": "clarinet"},
    "Patrick": {"id": 723, "username": "Patrick", "password": "whoareyoupeople???"},
}
```

Compare and contrast the two. Which would *you* choose, and why? What are the
tradeoffs of each container? Consider finding a user by username, finding one
by `id`, looping over all of them, adding and removing users, keeping them in
order, and what happens when two users want the same username.

### Response 1

Your response here...
