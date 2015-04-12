## Sensu-Plugins-erlang

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-erlang.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-erlang)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-erlang.svg)](http://badge.fury.io/rb/sensu-plugins-erlang)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-erlang/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-erlang)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-erlang/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-erlang)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-erlang.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-erlang)

## Functionality

## Files
 * bin/check-erlang-mailboxes
 * bin/metrics-erlang

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-erlang -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-erlang`

#### Bundler

Add *sensu-plugins-erlang* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-erlang' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-erlang' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes
