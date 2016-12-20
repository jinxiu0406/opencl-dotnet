
# OpenCL .NET

## Todo

- [x] Separate into three projects: Native Core, CLR Wrapper, Test Program
- [x] HandleBase class, which is the base class for all OpenCL classes that need a handle
- [x] Rename the arguments of the native methods
- [ ] Rename Info to Information
- [ ] Add compiler log to exception, when program cannot be build
- [ ] Add method to compile multiple sources at once
- [ ] Add method to compile from file
- [ ] Add method to compile from Stream/Streams
- [ ] Put the different APIs of the native wrapper into different classes
- [ ] Create a class that converts byte arrays into CLR types
- [ ] Port the whole API surface area
- [ ] Finish documentation