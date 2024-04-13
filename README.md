# Listic

Listic markdown task language specification.

We write tasks inside of markdown files to organize our projects. This document describes how to specify them.

### Basic tasks

This is how you create basic task lists:

```
- [ ] This is a task with a checkbox
  - [ ] This is a subtask
  - [ ] This is another subtask
```


### Task explanations

Each task can have explanations:

```
- [ ] This is a task
  - this is the explanation
  - this is another explanation
    - this elaborates the explanation
```

### Urgency

To express urgency, we use exclamation points:

```
- [ ] This is a task!
  - this is urgent!
```

Use multiple `!` to increase urgency levels:

```
- [ ] We need to do this now!!!
```

### Certainty

Sometimes we are not sure if we want to do a task, express it using a question mark:

```
- [ ] Get this done?
  - do we need to do this?
```

Use multiple question marks to decrease the certainty level.

Developed by [Eldøy Projects](https://eldoy.com)
