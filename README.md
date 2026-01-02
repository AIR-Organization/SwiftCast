# SwiftCast

An AI search tool attempt. This tool tries to get the latest news for a given topic. This tool is still under development.

## Structure

This flowchart below is an outline of planned structure of the SwiftCast.

```mermaid
flowchart TD
    front[Frontend] <--> middleground[Middleground]
    middleground --> data[Backend data]
    middleground --> storage[Backend storage]
    middleground --> summary[Backend summary]
```
