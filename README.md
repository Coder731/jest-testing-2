# jest-testing-2
following tutorial

## Update
Due to a change in Jest's default configuration, you need to add the following code to the top of your test file:

```
/**
 * @jest-environment jsdom
 */
```

Your tests will break if you do not add this block.
