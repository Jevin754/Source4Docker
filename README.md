# Source4Docker
Source files for docker-build.

## PyTorch-1.0.1
While installing pytorch1.0.1 with conda, there is a bug about the setting of 'D_GLIBCXX_USE_CXX11_ABI' compiling flag in cpp_extension.py.
To fix the bug, replace PYTHON_LIB/torch/util/cpp_extension.py with pytorch1.0.1/cpp_extension.py in this repository.

## Ubuntu-config
Some configurations of tmux, vim, etc., are included in Ubuntu-config.
