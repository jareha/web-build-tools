[Home](./index) &gt; [@microsoft/node-core-library](./node-core-library.md) &gt; [IFileWriterFlags](./node-core-library.ifilewriterflags.md)

# IFileWriterFlags interface

Interface which represents the flags about which mode the file should be opened in.

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [`append`](./node-core-library.ifilewriterflags.append.md) | `boolean` | Open file for appending. |
|  [`exclusive`](./node-core-library.ifilewriterflags.exclusive.md) | `boolean` | Fails if path exists. The exclusive flag ensures that path is newly created. On POSIX systems, path is considered to exist even if it is a symlink to a non-existent file. The exclusive flag may or may not work with network file systems. |
