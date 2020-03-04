project( 'bullet', 'cpp', version : '2.89', default_options : [ 'cpp_std=c++03' ] )

if meson.get_compiler( 'cpp' ).has_argument( '-Wno-unused-variable' )
    add_project_arguments( '-Wno-unused-variable', language : 'cpp' )
endif
if meson.get_compiler( 'cpp' ).has_argument( '-Wno-unused-function' )
    add_project_arguments( '-Wno-unused-function', language : 'cpp' )
endif

subdir( 'src' )
