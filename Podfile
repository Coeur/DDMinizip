
abstract_target 'host' do
   # temporary workaround until https://github.com/nmoinvaz/minizip/pull/122 gets merged
   #pod 'Minizip/minishared', :git => 'https://github.com/nmoinvaz/minizip.git'
   pod 'Minizip/minishared', :podspec => 'https://raw.githubusercontent.com/Coeur/minizip/patch-2/Minizip.podspec'

   target 'DDMinizip-OSX' do
      platform :osx
   end
   target 'DDMinizip-IOS' do
      platform :ios
   end
end
