# Important

whatever error you get, first check there is no comma at the end of the line. like this:
```cmake
target_link_libraries(
    tcp_client_test
    PRIVATE
    xsl_wheel,
)
```