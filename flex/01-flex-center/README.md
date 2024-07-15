# CENTER THIS DIV
This one is simple, but it's something that you'll want to do ALL THE TIME.  Might as well get it out of the way now.

All you need to do is center the red div inside the blue container.

## Desired Outcome
![outcome](./desired-outcome.png)

### Self Check
- Is the red div centered?
- Did you _only_ use flexbox to center it?

---
### *my notes*

- [x] 'activate' the flexbox functionality.
    - via `display: flex;` in the container which now makes the child '.box' susceptible to flex related properties.
- [x] center the items within the container on the primary axis.
    - via `justify-content: center;`
- [x] center the specific item on the cross axis
    - via `align-self: center;`

