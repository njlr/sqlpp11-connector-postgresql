include_defs('//BUCKAROO_DEPS')

cxx_library(
  name = 'sqlpp11-connector-postgresql',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('include', '**/*.h'),
  ]),
  headers = subdir_glob([
    ('src', '**/*.h'),
  ]),
  srcs = glob([
    'src/**/*.cpp',
  ]),
  deps = BUCKAROO_DEPS, 
  visibility = [
    'PUBLIC',
  ],
)
