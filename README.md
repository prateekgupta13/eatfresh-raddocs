# Raddocs

Raddocs is a browser for JSON outputted by the `rspec_api_documentation` gem.

## Install

`Gemfile`

	gem 'raddocs'

`config/routes.rb`

	...
	match "/docs" => Raddocs, :anchor => false
	...