target 'Ansi' do
  use_frameworks!
  platform :osx, '10.11'

  podspec
  pod 'FootlessParser', '~> 0.5.2'

  target 'Tests' do
    inherit! :search_paths
    pod 'Quick'
    pod 'Nimble', '< 7.0.0'
  end
end
