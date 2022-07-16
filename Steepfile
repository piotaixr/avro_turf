D = Steep::Diagnostic

target :lib do
  signature "sig"

  check "lib"

  library "logger", "monitor", 'uri'

  configure_code_diagnostics(D::Ruby.strict)       # `strict` diagnostics setting
end
