source "https://rubygems.org"

gem 'fastlane'
gem 'cocoapods', :git => 'https://github.com/CocoaPods/CocoaPods.git'
gem 'cocoapods-core', :git => 'https://github.com/CocoaPods/Core.git'
gem 'xcodeproj', :git => 'https://github.com/CocoaPods/Xcodeproj.git'

gem 'cocoapods-keys', :git => 'https://github.com/orta/cocoapods-keys.git'

gem 'xcpretty'
gem 'shenzhen'
gem 'sbconstants'

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
