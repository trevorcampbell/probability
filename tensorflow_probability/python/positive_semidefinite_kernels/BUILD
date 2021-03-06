# Copyright 2018 The TensorFlow Probability Authors.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
# ============================================================================
# Library for representation of positive-semidefinite kernel functions.

licenses(["notice"])  # Apache 2.0

package(
    default_visibility = [
        "//tensorflow_probability:__subpackages__",
    ],
)

py_library(
    name = "positive_semidefinite_kernels",
    srcs = ["__init__.py"],
    deps = [
        ":exponentiated_quadratic",
        ":positive_semidefinite_kernel",
        ":util",
    ],
)

py_library(
    name = "positive_semidefinite_kernel",
    srcs = ["positive_semidefinite_kernel.py"],
    deps = [
        # six dep,
        # tensorflow dep,
    ],
)

py_test(
    name = "positive_semidefinite_kernel_test",
    size = "small",
    srcs = ["positive_semidefinite_kernel_test.py"],
    deps = [
        # absl/testing:parameterized dep,
        # numpy dep,
        # tensorflow dep,
        "//tensorflow_probability",
    ],
)

py_library(
    name = "exponentiated_quadratic",
    srcs = ["exponentiated_quadratic.py"],
    deps = [
        # six dep,
        # tensorflow dep,
    ],
)

py_test(
    name = "exponentiated_quadratic_test",
    srcs = ["exponentiated_quadratic_test.py"],
    deps = [
        # absl/testing:parameterized dep,
        # numpy dep,
        # tensorflow dep,
        "//tensorflow_probability",
    ],
)

py_library(
    name = "util",
    srcs = ["util.py"],
    deps = [
        # tensorflow dep,
    ],
)

py_test(
    name = "util_test",
    srcs = ["util_test.py"],
    deps = [
        # numpy dep,
        # tensorflow dep,
        "//tensorflow_probability",
    ],
)
