# Assignment
# Problem: Invalid URL Handling in requests

## Current Behavior
When a URL without a scheme (e.g. "example.com") is passed to requests.get(),
the library raises an unclear or inconsistent exception.

## Expected Behavior
The library should raise a clear ValueError indicating that the URL is invalid
and must include a scheme such as http:// or https://.

## Why This Matters
Clear validation improves developer experience and prevents confusing runtime errors.

## Scope
This problem focuses only on URL validation behavior.
No refactoring or new features are required.
