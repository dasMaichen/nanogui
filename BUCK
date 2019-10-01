load('//:buckaroo_macros.bzl','buckaroo_deps')

prebuilt_cxx_library(
  name = 'nanogui',
  soname = 'libnanogui.so',
  shared_lib = 'libnanogui.so'
  header_namespace = 'nanogui',
  exported_headers = subdir_glob([
    ('include/nanogui','**/*.h'),
  ]),
  deps = buckaroo_deps(),
  visibility = ['PUBLIC']
)
