
project('base', 'cpp', default_options:['cpp_std=c++14'])

srcs = files(['srcs/main.cpp', 'srcs/foo.cpp'])

incdir = include_directories('include')
fmt_dep = dependency('fmt')
project_dep = declare_dependency(include_directories:incdir, sources:srcs, dependencies:[fmt_dep])

executable('base', dependencies:[project_dep])

