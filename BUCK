load('//:buckaroo_macros.bzl','buckaroo_deps')

cxx_library(
  name = 'nanogui',
  header_namespace = 'nanogui',
  exported_headers = subdir_glob([
    ('include/nanogui','**/*.h'),
  ]),
  visibility = ['PUBLIC'],
  deps = buckaroo_deps(),
)
