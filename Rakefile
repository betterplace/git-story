# vim: set filetype=ruby et sw=2 ts=2:

require 'gem_hadar'

GemHadar do
  name        'git-story-workflow'
  path_name   'git/story'
  author      'Florian Frank'
  email       'flori@ping.de'
  homepage    "http://flori.github.com/#{name}"
  summary     'Gem abstracting a git workflow'
  description "#{summary}…"
  test_dir    'spec'
  ignore      '.*.sw[pon]', 'pkg', 'Gemfile.lock', 'coverage', '.rvmrc',
    '.AppleDouble', 'tags', '.byebug_history', 'errors.lst', '.DS_Store'
  readme      'README.md'
  title       name.camelize
  executables << 'git-story'

  dependency 'infobar'
  dependency 'tins'
  dependency 'mize'
  dependency 'term-ansicolor'
  dependency 'complex_config'
  dependency 'search_ui'

  development_dependency 'rake'
  development_dependency 'simplecov'
  development_dependency 'rspec'
  development_dependency 'byebug'
  licenses << 'Apache-2.0'
end

task :default => :spec
