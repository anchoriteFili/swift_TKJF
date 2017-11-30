# 使用pod导入所有用到的三方
用到的三方
```
target 'SwiftTKJF' do
end
platform :ios, '8.0'
use_frameworks!
pod 'ReachabilitySwift'
pod 'SnapKit', '~> 3.2.0'
pod 'Alamofire'
pod 'RxSwift'
pod 'RxCocoa'
pod 'Moya'
pod 'ObjectMapper'
pod 'Result', '~> 3.0.0'
pod 'Moya/RxSwift'
pod 'Masonry'
pod 'DGElasticPullToRefresh'
```
### ReachabilitySwift
[git地址](https://github.com/ashleymills/Reachability.swift "悬停提示")
这是一个网络判断的三方，用于网络判断。
