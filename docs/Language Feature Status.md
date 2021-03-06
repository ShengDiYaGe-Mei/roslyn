# Language Feature Status

This document reflects the status, and planned work, for the compiler team.  It is a live document and will be updated as work progresses, features are added / removed, and as work on feature progresses.  

## C# 7.0 and VB 15

| Feature | Branch | State | Owners | LDM Champ |
| ------- | ------ | ----- | ------ | --------- |
| [Async Main](https://github.com/dotnet/roslyn/issues/7476) | none  | Feature Specification | [tyoverby](https://github.com/tyoverby), [agocke](https://github.com/agocke) | [stephentoub](https://github.com/stephentoub) |
| Address of Static | none | Feature Specification | | [jaredpar](https://github.com/jaredpar) |
| [Binary Literals](https://github.com/dotnet/roslyn/issues/215) | [master](https://github.com/dotnet/roslyn/tree/master)  | Finishing | | [gafter](https://github.com/gafter) |
| [Digit Separators](https://github.com/dotnet/roslyn/issues/216) | [master](https://github.com/dotnet/roslyn/tree/master)  | Finishing | | [gafter](https://github.com/gafter) |
| [Local Functions](https://github.com/dotnet/roslyn/blob/master/docs/features/local-functions.md) | [master](https://github.com/dotnet/roslyn/tree/master)  | Finishing | [agocke](https://github.com/agocke), [jaredpar](https://github.com/jaredpar), [vsadov](https://github.com/vsadov) | [gafter](https://github.com/gafter) |
| [Type switch](https://github.com/dotnet/roslyn/blob/master/docs/features/patterns.md) | [master](https://github.com/dotnet/roslyn/tree/master) | Finishing | [gafter](https://github.com/gafter), [alekseyts](https://github.com/alekseyts), [agocke](https://github.com/agocke) | [gafter](https://github.com/gafter) |
| [Ref Returns](https://github.com/dotnet/roslyn/issues/118) | [master](https://github.com/dotnet/roslyn/tree/master) | Finishing | [vsadov](https://github.com/vsadov), [agocke](https://github.com/agocke), [jaredpar](https://github.com/jaredpar) | [vsadov](https://github.com/vsadov) |
| [Source Generation](https://github.com/dotnet/roslyn/blob/master/docs/features/generators.md) | [master](https://github.com/dotnet/roslyn/tree/features/generators) | Prototyping | [cston](https://github.com/cston), [vsadov](https://github.com/vsadov),  [agocke](https://github.com/agocke) | [mattwar](https://github.com/mattwar) |
| [Throw Expr](https://github.com/dotnet/roslyn/blob/features/patterns/docs/features/patterns.md) | [features/patterns](https://github.com/dotnet/roslyn/tree/features/patterns) | Finishing | [agocke](https://github.com/agocke), [tyoverby](https://github.com/tyoverby), [gafter](https://github.com/gafter) | [gafter](https://github.com/gafter) |
| [Tuples](https://github.com/dotnet/roslyn/issues/347) | [features/tuples](https://github.com/dotnet/roslyn/tree/features/tuples) | Finishing | [vsadov](https://github.com/vsadov), [jcouv](https://github.com/jcouv) | [madstorgersen](https://github.com/MadsTorgersen) |
| [Out var](https://github.com/dotnet/roslyn/blob/features/outvar/docs/features/outvar.md) | [features/outvar](https://github.com/dotnet/roslyn/tree/features/outvar) | Prototyping | [alekseyts](https://github.com/alekseyts) | [gafter](https://github.com/gafter) |
| [ValueTask<T>](https://github.com/ljw1004/roslyn/blob/features/async-return/docs/specs/feature%20-%20arbitrary%20async%20returns.md) | None | Prototyping | [alekseyts](https://github.com/alekseyts) | [lucian](https://github.com/ljw1004) |

## (C# 7.0 and VB 15) + 1

| Feature | Branch | State | Owners | LDM Champ |
| ------- | ------ | ----- | ------ | --------- |
| [private protected](https://github.com/dotnet/roslyn/blob/features/privateProtected/docs/features/private-protected.md) | [features/privateProtected](https://github.com/dotnet/roslyn/tree/features/privateProtected) | Prototyping | | [gafter](https://github.com/gafter) |
| [Non-null Ref Types](https://github.com/dotnet/roslyn/blob/features/NullableReferenceTypes/docs/features/NullableReferenceTypes/Nullable%20reference%20types.md) | [features/NullableReferenceTypes](https://github.com/dotnet/roslyn/tree/features/NullableReferenceTypes) | Prototyping | [alekseyts](https://github.com/alekseyts) | [mattwar](https://github.com/mattwar) |
| [Better Betterness](https://github.com/dotnet/roslyn/issues/250) | none | Feature Specification | | [gafter](https://github.com/gafter) |
| [Records](https://github.com/dotnet/roslyn/blob/features/records/docs/features/records.md) | [features/records](https://github.com/dotnet/roslyn/tree/features/records) | Feature Specification | [jcouv](https://github.com/jcouv) | [gafter](https://github.com/gafter) |
| [With Exprs](https://github.com/dotnet/roslyn/blob/features/records/docs/features/records.md) | [features/records](https://github.com/dotnet/roslyn/tree/features/records) | Feature Specification | [gafter](https://github.com/gafter) | [gafter](https://github.com/gafter) |
| [Pattern Matching](https://github.com/dotnet/roslyn/blob/features/patterns/docs/features/patterns.md) | [features/patterns](https://github.com/dotnet/roslyn/tree/features/patterns) | Prototyping | [gafter](https://github.com/gafter), [alekseyts](https://github.com/alekseyts), [agocke](https://github.com/agocke) | [gafter](https://github.com/gafter) |

# FAQ

- **Is target version a guarantee?**: No.  It's explicitly not a guarantee.  This is just the planned and on going work to the best of our knowledge at this time.
- **Where are these State values defined?**: Take a look at the [Developing a Language Feature](contributing/Developing a Language Feature.md) document.
