- clone vcpkg
- .\bootstrap-vcpkg.bat on terminal(windows)
- .\vcpkg install sfml

in  CMakeLists.txt replace ( set(SFML_DIR "C:/Users/Dell/Desktop/SFML_VCPKG/vcpkg/installed/x64-windows/share/sfml")) according to where you cloned vcpkg and copy the adress of sfml there

after that if cmake doesn't automatically write build files then select your compiler from kit 
## 1 Build project
cmake --build build(by deafult in Debug directory) for release use cmake --build build --config Release

## 2 Run(go to Debug or Release directory and run) //whichver you have
- ./build/Debug/your_program.exe
