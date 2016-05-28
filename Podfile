workspace 'RWPickFlavor'
use_frameworks!

def ios_platform
  platform :ios, '8.0'
end

def mac_platform
  platform :osx, '10.9'
end

def my_shared_pods
  pod 'Reachability'
end

target 'RWPickFlavor-iOS' do
	link_with 'RWPickFlavor-iOS'
	ios_platform
	my_shared_pods
end

target 'RWPickFlavor-Mac' do
	link_with 'RWPickFlavor-Mac'
	mac_platform
	my_shared_pods
end



