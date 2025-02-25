^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package ros_msg_parser
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.6.0 (2025-02-04)
------------------

1.5.0 (2024-09-16)
------------------

1.4.0 (2024-06-17)
------------------

1.3.0 (2024-02-02)
------------------

1.2.0 (2024-02-02)
------------------

1.1.0 (2023-09-25)
------------------
* Updating span.hpp, to account for new CXX17 and 20
* fix license
* 1.0.0
* Fix ReadFromBuffer() for empty strings in Debug mode with assertions enabled
* Fix linking of target ros_parser_benchmark to the Google Benchmark library
  See usage example at https://github.com/google/benchmark#usage-with-cmake.
  There is no CMake target named benchmark.
* allow rapidjson writer to handle nan and inf values
* Direct variant access
* Fix depends that aren't test depends only
* Update shape_shifter.hpp
* Drop unused arg and enforce const-ness
* fix inverted flag
* Fix issue #1
* fix critical bug
* adding pretty printer option
* fix corner case
* added converter to json
* Update README.md
* forking from ros_type_introspection
* Contributors: Davide Faconti, Enrique Fernandez, Johannes Meyer, Kalpesh Lad, Sam Khalandovsky, root
