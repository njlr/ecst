include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'ecst',
  header_only = True,
  header_namespace = '',
  exported_headers = subdir_glob([
    ('include', '**/*.hpp'),
    ('include', '**/*.h'),
    ('include', '**/*.inl'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
