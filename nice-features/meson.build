project('nice-features', 'c')

c=meson.get_compiler('c')

c_version = c.version()

message('compiler version ' + c_version)

if c_version.version_compare('< 7.0.0')
   message('Please upgrade to at least 7.0.0')
endif
