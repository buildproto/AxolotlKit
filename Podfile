source 'https://github.com/boompayments/boompods.git'
source 'https://github.com/CocoaPods/Specs.git'

platform :ios, '6.0'

target 'AxolotlKit' do
  pod 'Curve25519',      '2.0.3', :inhibit_warnings => true
  pod 'HKDFKit',         '~> 0.0.3'
  pod 'ProtocolBuffers', '~> 1.9.7'

  target 'AxolotlKitTests' do
    inherit! :search_paths
  end
end

