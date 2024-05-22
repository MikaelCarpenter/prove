# prove

Prove a proposition and assert that it's true. Otherwise, throw an error.

**Install**
```bash
npx jsr add @mikael/prove
```

**Use**
```ts
import prove from "@mikael/prove";

prove(typeof email === "string", "Please provide a valid email.")
```
