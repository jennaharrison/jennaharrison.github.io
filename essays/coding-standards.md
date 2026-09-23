---
layout: essay
type: essay
title: "Why Should I Care About ESLint???"
# All dates must be YYYY-MM-DD format!
date: 2026-09-22
published: true
labels:
  - TypeScript
  - ESLint
  - Coding Standards
---

## What is ESLint and why do I need it?

ESLint is a very useful tool for making sure your code follows coding standards. This differs from normal TypeScript error checking because ESLint can return errors when you are not following the required standards. For example, if you forget a semicolon at the end of a line, TypeScript usually will not give you an error, but ESLint can. This can be annoying at times, but it is very useful in the long run.

## Benefits of ESLint

I think the biggest benefit of ESLint is code readability. By encouraging you to follow to coding standards, it makes your code easier for others to read and update later on. It's never fun when you need to make changes to code, but you can't tell what any of it does because it is written so poorly. It also helps when collaborating with others. If a project has multiple functions that need to work together, following the same coding standards can make it easier for team members to understand each other's code and connect their work.

ESLint can also catch problems that may not affect the way your TypeScript code runs. One example of this is an unused variable. Creating a variable that you never use will not necessarily cause your program to crash. However, ESLint can warn you about it because the unused variable is unnecessary and can make your code more confusing.

For example, this code creates a variable called `name`, but never actually uses it:

```typescript
const name = 'John';

console.log('Hello!');
```

ESLint would throw an error, but your TypeScript file would be completely fine with it. The code still runs, but there is no reason to have that name variable there. There are two ways we can fix this. We can either delete the variable entirely, or we can update our code to use the variable like this:

```typescript
const name = 'John';

console.log(`Hello, ${name}`);
```

This may seem like a small issue, but unused variables can become much more difficult to deal with in a larger project. Someone reading your code might see a variable and assume it is important, only to discover that it is never used anywhere.

Overall, ESLint just helps make your code readable to you and other people. I can't count the amount of times I've come back to my code after a long break and not known what was going on. ESLint can help make that a little more manageable.

## My Frustrations

At first, I was really frustrated with ESLint. My TypeScript file went from almost no errors to about 30 in the blink of an eye. When I ran ESLint for the first time, I had no idea what was going on. All of these errors were completely new to me, and I did not understand why my code was suddenly considered "wrong." 

It took lots of practice, but I was finally able to understand the standards that ESLint is trying to help me uphold. Even just trying to get it to install onto my VSCode environment was frustrating. I ran into many issues, but I'm glad I stuck with it. In the end, I honestly believe the benefits outweigh all of my frustrations.

## AI Use

I used ChatGPT while writing to help me fix my grammar and to proofread.
