project('libhttp', 'c',
        license: 'MIT',
        version: '0.1.0')

subdir('include/http')

http_inc = include_directories('include')
http_src = files('lib/http.c')

http_lib = library('http', http_src)
http_dep = declare_dependency(include_directories: [http_inc], link_with: [http_lib])
