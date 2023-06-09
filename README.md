# SDLC Activity Based Learning - scientific calculator
![maths2](https://user-images.githubusercontent.com/36398260/114144855-67df4780-9933-11eb-9ffe-48cf0093065c.jpg)
Build | Code Quality | Unity |
------|----------|-------|
[![C/C++ CI - Build Status](https://github.com/sxk9676/Agile-Multi-File-C-Language-Scientific-Computation/actions/workflows/c-cpp.yml/badge.svg)](https://github.com/sxk9676/Agile-Multi-File-C-Language-Scientific-Computation/actions/workflows/c-cpp.yml)|[![CodeQuality Dynamic Code Analysis Valgrind](https://github.com/sxk9676/Agile-Multi-File-C-Language-Scientific-Computation/actions/workflows/code_quality_dyanamic.yml/badge.svg)](https://github.com/sxk9676/Agile-Multi-File-C-Language-Scientific-Computation/actions/workflows/code_quality_dyanamic.yml) [![Codacy Badge](https://app.codacy.com/project/badge/Grade/fd98a6e8584244428c888aabbcd02c0a)](https://app.codacy.com/gh/sxk9676/Agile-Multi-File-C-Language-Scientific-Computation/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade) [![CI-Coverage](https://github.com/sxk9676/Agile-Multi-File-C-Language-Scientific-Computation/actions/workflows/gcov.yml/badge.svg)](https://github.com/sxk9676/Agile-Multi-File-C-Language-Scientific-Computation/actions/workflows/gcov.yml) | [![Unit Testing - Unity](https://github.com/sxk9676/Agile-Multi-File-C-Language-Scientific-Computation/actions/workflows/unity.yml/badge.svg)](https://github.com/sxk9676/Agile-Multi-File-C-Language-Scientific-Computation/actions/workflows/unity.yml)
## Folder Structure
Folder             | Description
-------------------| -----------------------------------------
`1_Requirements`   | Documents detailing requirements and research
`2_Design`         | Documents specifying design details
`3_Implementation` | All code and documentation
`4_Test_plan`      | Documents with test plans and procedures
## Challenges Faced and How Was It Overcome
| No |Challenge  | Solution
|--|--|--|
| 01 |Resource unavailable while using system commands  | Uninstalled MacAfee anti-virus  |
| 02 | Make file not working even after following all steps  |renamed Mingw/bin/mingw32-make.exe to Mingw/bin/make.exe  |
# Usage Of the Project
```sh
# For Building the main application
make create
# For Running the main application
make run
# For Building the test file
make create_test
# For Running the test file
make run_test
```
