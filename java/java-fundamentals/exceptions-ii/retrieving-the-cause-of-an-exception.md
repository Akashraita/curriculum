---
author: adamMontgomerie
type: normal
category: tip
tags:
  - exceptions
  - chained-exceptions
links:
  - >-
    [Chained Exceptions](https://docs.oracle.com/javase/tutorial/essential/exceptions/chained.html){website}
revisionQuestion:
  formats:
    - fill-in-the-gap
    - type-in-the-gap
  context: standalone
---

# Retrieving the cause of an exception


---

## Content

When using chained exceptions, it's useful to be able to find the cause of an exception. This can be done using the `getCause` method. For example:

```java
try {
  ...
}
catch (Exception e) {
  Throwable cause = e.getCause();
}
```

`getCause` will return the `Throwable` object which caused the current exception.

In the case of multiple chained exceptions, we could then call `getCause` again on the returned object `cause` to cycle through exceptions until we find the first exception which caused the chain.



---

## Revision

When using chained exceptions, it's useful to be able to find the cause of an exception using the following code:

```java
try {
  ...
}
catch (Exception e) {
  Throwable cause = e.???;
}
```

- getCause()
- getReason()
- getError()
- throw()
