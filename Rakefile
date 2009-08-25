# -*- ruby -*-

require 'rubygems'
require 'hoe'
require 'hoe/signing'
require './tasks/spec.rb'
require './tasks/yard.rb'

Hoe.spec('ronin') do
  self.rubyforge_name = 'ronin'
  self.developer('Postmodern','postmodern.mod3@gmail.com')
  self.remote_rdoc_dir = 'docs/ronin'
  self.extra_deps = [
    ['hoe', '>=2.0.0'],
    ['yard', '>=0.2.3.5'],
    ['nokogiri', '>=1.2.0'],
    ['extlib', '>=0.9.13'],
    ['data_objects', '>=0.10.0'],
    ['do_sqlite3', '>=0.10.0'],
    ['dm-core', '>=0.10.0'],
    ['dm-types', '>=0.10.0'],
    ['dm-validations', '>=0.10.0'],
    ['dm-predefined', '>=0.1.3'],
    ['chars', '>=0.1.2'],
    ['parameters', '>=0.1.8'],
    ['contextify', '>=0.1.3'],
    ['reverse-require', '>=0.3.1'],
    ['repertoire', '>=0.2.1'],
    ['thor', '>=0.11.5']
  ]

  self.extra_dev_deps = [
    ['rspec', '>=1.1.12']
  ]

  self.spec_extras = {:has_rdoc => 'yard'}
end

# vim: syntax=Ruby
