target 'TryProcedureKit' do
  platform :osx, '10.11'

  use_frameworks!

  pod 'ProcedureKit/All', :path => 'submodules/ProcedureKit'

  target 'TryProcedureKitTests' do
    inherit! :search_paths
    pod 'TestingProcedureKit', :path => 'submodules/ProcedureKit'
  end
end

target 'TryProcedureKit iOS' do
  platform :ios, '10'
  use_frameworks!

  pod 'ProcedureKit/All', :path => 'submodules/ProcedureKit'
  pod 'ProcedureKit/Mobile', :path => 'submodules/ProcedureKit'  

  target 'TryProcedureKit iOSTests' do
    inherit! :search_paths
    pod 'TestingProcedureKit', :path => 'submodules/ProcedureKit'
  end
end
