project('test', 'c', subproject_dir: 'deps')

mpcdec = dependency('mpcdec', required: true)

exe = executable(
    'main',
    'main.c',
    dependencies: mpcdec,
    install: true,
)
