source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '8.1'

xcodeproj 'BlockKVO'

use_frameworks!

pod 'Block-KVO'

# using the post_install below removes error "Too many arguments to function call", but results in a new error:
# "Block-KVO/MTKObserving.h file not found"

#post_install do |installer|
# 	installer.project.targets.each do |target|
# 		target.build_configurations.each do |config|
# 			config.build_settings['ENABLE_STRICT_OBJC_MSGSEND'] = "NO"
# 		end
# 	end
# end