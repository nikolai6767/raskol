project(
  'raskol',
  'c',
  version: '0.1.0',
  default_options: [
    'c_std=c17',
    'warning_level=3',
    'werror=true',
  ],
)

raskol_inc = include_directories('include')

raskol_sources = files(
  'src/main.c',
)

executable(
  'raskol',
  raskol_sources,
  include_directories: raskol_inc,
  install: true,
)
