project('libSOIL', 'c', version: '0.0.29')

sources = ['image_DXT.c', 'image_helper.c', 'SOIL.c', 'stb_image_aug.c']
dependencies = [dependency('gl')]
libSOIL = shared_library('libSOIL',
      sources,
      dependencies: dependencies,
      link_args: ['-framework', 'CoreFoundation'])
