
project('base', 'cpp', default_options:['cpp_std=c++14'])

src = files(['src/main.cpp','src/foo.cpp'])

incdir = include_directories('include')
fmt_dep = dependency('fmt')
poco_dep = dependency('poco')
project_dep = declare_dependency(include_directories:incdir, sources:src, dependencies:[fmt_dep, poco_dep])

executable('base', dependencies:[project_dep])

