project('videoInput', 'cpp', version: '1.0.0')

vi_inc = include_directories([
   'videoInputSrcAndDemos/libs/DShow/Include',
   'videoInputSrcAndDemos/libs/extra',
   'videoInputSrcAndDemos/libs/glfw',
   'videoInputSrcAndDemos/libs/videoInput',
])
vi_lib = static_library(
    'videoInput',
    include_directories: vi_inc,
    sources: [
        'videoInputSrcAndDemos/libs/videoInput/videoInput.cpp',
    ]
)
vi_dep = declare_dependency(
    link_with: vi_lib,
    include_directories: vi_inc,
)
