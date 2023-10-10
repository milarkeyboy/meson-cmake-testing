# Meson CMake Testing

Currently, I have observed that CMake subprojects in Meson generate non-existent
include directories. These cause compilation errors with GCC if you have all
warnings on and warnings-as-errors.
