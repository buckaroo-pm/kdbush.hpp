prebuilt_cxx_library(
  name = 'kdbush', 
  header_namespace = '', 
  header_only = True, 
  exported_headers = subdir_glob([
    ('include', '**/*.hpp'), 
  ]), 
  visibility = [
    'PUBLIC', 
  ], 
)

cxx_binary(
  name = 'test', 
  header_namespace = '', 
  headers = [
    'include/kdbush.hpp', 
  ], 
  srcs = [
    'test.cpp', 
  ], 
)

cxx_binary(
  name = 'bench', 
  header_namespace = '', 
  headers = [
    'include/kdbush.hpp', 
  ], 
  srcs = [
    'bench.cpp', 
  ], 
)
