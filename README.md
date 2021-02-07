# LV32.2020..ClassLoader
Easy support for dynamic loading of classes stored in PPLs
Implemented functionality:
- Scan PPL folder for all classes. The PPL folder is the folder where the PPL built from this project resides, all PPLs are assumed to be placed in the same folder.
- Load any class from the PPL folder by name or qualified name
- Front-loading of cached data or caching (and un-load on request)
- Get filtered class hierarchies (e.g. return hierarchy for all members of the Message class hierarchy)
- Get Members of a class, get hierarchy of a class, get if a class is an interface.
- Populate Tree, Ring and Listboxes with a class hierarchy.
