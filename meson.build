project('foo', 'cpp',
    default_options: [
        'warning_level=everything',
        'werror=true'
    ]
)

cmake = import('cmake')
bar = cmake.subproject('bar')

foo = executable('foo',
    'main.cpp',
    dependencies: bar.dependency('bar_lib')
)
