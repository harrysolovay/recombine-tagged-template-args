```ts
import {recombineTaggedTemplateArgs} from "recombine-tagged-template-args";

recombineTaggedTemplateArgs(["Hello"], " world!");
//                           ^          ^
//                           |          ...strings[]
//                           TemplateStringsArray
```
