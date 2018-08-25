project('docopt', 'cpp',
    default_options: ['cpp_std=c++11'])
headers = [
    'docopt_private.h',
    'docopt_util.h',
    'docopt_value.h',
    'docopt.h'
]
sources = ['docopt.cpp'] + headers
l = static_library('docopt', sources)
i = include_directories('.')
docopt_dep = declare_dependency(include_directories: i,
    link_with: l)
