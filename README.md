## The Amazon Template Library

A collection of general purpose C++ utilities that play well with the Standard
Library and Boost.

### How to use

Using the AmazonTemplateLibrary from CMake is very easy. Simply make sure the
library can be found as part of your `CMAKE_PREFIX_PATH`, and then do the
following from your `CMakeLists.txt`:

```cmake
find_package(AmazonTemplateLibrary)
target_link_libraries(your-target PRIVATE AmazonTemplateLibrary::atl)
```

### License

This library is licensed under the Apache 2.0 License.
