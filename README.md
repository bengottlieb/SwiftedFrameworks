# SwiftedFrameworks
Swift wrappers around useful system frameworks

Using these wrappers, you can add access to 'legacy' code libraries that currently require Objective-C code to use.

Notes:

- drag the desired framework into your project
- make sure it's an "optional", not "required" framework (Utilities panel, Target Membership)
- for zlib, add the corresponding library to your project (libz.tbd)

- You can now access the functions defined in the header directly from Swift, without requiring an Objective-C bridge.
