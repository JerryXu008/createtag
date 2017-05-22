
platform :ios, '8.0'

# Import CocoaPods sources
source 'https://github.com/CocoaPods/Specs.git'
source 'https://github.com/JerryXu008/Spec.git'
target 'hubeicfc' do
    
    pod 'test', :path => 'LocalLib/test/test.podspec' #本地的
    
    #pod 'paipaixin', :path => 'LocalLib/paipaixin/paipaixin.podspec'
    #pod 'hbuilder', :path => 'LocalLib/hbuilder/hbuilder.podspec'
    pod 'hbuilder', '0.0.1' #加入到MySpec中了
    # pod 'paipaixin', '1.0.0'
    pod 'paipaixin', '0.0.3'
    #pod  'paipaixin/DataModel', '1.0.0' #加载paipaixin的子模块
end

 
