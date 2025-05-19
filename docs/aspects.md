# Architectural Aspects (aspects)

Aspects highlight architectural components that implement a specific architectural aspect, such as a business function.
Unlike [contexts](@document/ceaf.app.contexts), aspects are defined directly in 
[components](@document/ceaf.app.components). That is, the component specifies which aspect it implements.

Example of a functional aspect description in the manifest:
```code-frame
/aspects/dochub.gitlab.auth
```

The component specifies which aspects it implements:
```code-frame
/components/dochub.saas.frontend
```

When [selecting an aspect in the menu](@aspect/dochub.gitlab.auth), its card opens. The card contains detailed information
about the aspect, as well as [contexts](@document/ceaf.app.contexts) in which the aspect occurs.

Example representation of the aspect card `dochub.gitlab.auth`:
![Aspect card](@aspect/dochub.gitlab.auth)

