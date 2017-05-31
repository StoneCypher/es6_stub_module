# es6_stub_module
I use this to show that build systems are working.  There's nothing interesting down here.

MIT licensed because fuck you, viral licenses

## what?

this is a single template string as an arrow function, which is exported.

the whole codebase, at time of writing:

```javascript
const bar = (whom:string) : string => `Hello, ${whom}!  This is a successfully exported template arrow.`;

export { bar };
```

the goal is to show that a downstream build system consumes and packs es6 modules correctly.