#source 'git@github.com/CocoaPods/Specs.git'
source "https://github.com/CocoaPods/Old-Specs”

platform :ios, '7.0'
#inhibit_all_warnings!

def common
    pod 'WeexSDK', :path=>'../sdk/'
    pod 'WXDevtool', '0.8.2'
    pod 'SDWebImage', '3.7.5'
    pod 'SocketRocket', '0.4.2'
    pod 'ATSDK-Weex', '0.0.1'
end

target 'WeexDemo' do
    common
end

target 'WeexUITestDemo' do
    common
end
