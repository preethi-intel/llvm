set(CMAKE_CXX_EXTENSIONS OFF)

add_sycl_unittest(ExtensionsTests OBJECT
  DefaultContext.cpp
  FPGADeviceSelectors.cpp
  DeviceArchitecture.cpp
)

