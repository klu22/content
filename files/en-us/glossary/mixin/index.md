---
title: Mixin
slug: Glossary/Mixin
page-type: glossary-definition
---

A _mixin_ is a {{Glossary("class")}} (interface, in WebAPI spec terms) whose {{Glossary("method", "methods")}} and/or {{Glossary("property", "properties")}} are meant to be incorporated into other classes. Any class that implements a mixin gains that mixin's properties and methods. (In particular, the class does not need to descend from the mixin.) Thus, mixins provide a way to reuse code among classes.

For example, the `WindowOrWorkerGlobalScope` mixin provides methods and properties for both the {{domxref("Window")}} and {{domxref("WorkerGlobalScope")}} interfaces.
## See also

- [Mixin](https://en.wikipedia.org/wiki/Mixin) on Wikipedia
