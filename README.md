# LV32.2020..ClassLoader
Source repository for [LV32.2020..PPL.ClassLoader][1] which contains VIs for easy support of dynamic loading of classes stored in PPLs.


## Functionality

```
- Scan PPL folder for all classes. 
  The PPL folder is the folder where the PPL built from this project resides, 
  all PPLs are assumed to be placed in the same folder.
- Load any class from the PPL folder by name or qualified name
- Front-loading of cached data or caching (and un-load on request)
- Get filtered class hierarchies 
  (e.g. return hierarchy for all members of the Message class hierarchy)
- Get Members of a class, get hierarchy of a class, get if a class is an interface.
- Populate Tree, Ring and Listboxes with a class hierarchy.
```


## Test
Test the functionality from the main project or look in the Test-folder (only manual testing).


## Build
Post build copy the product into [LV32.2020..PPL.ClassLoader][1] from the target PPL folder from where it should be committed to GitHub.


[1]: https://github.com/HenrikDueholm/LV32.2020..PPL.ClassLoader