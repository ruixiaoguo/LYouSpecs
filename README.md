# The CocoaPods MySpecs Repo

## 私有库git地址
This repository contains the public [CocoaPods](https://github.com/ruixiaoguo/LYouSpecs.git) specifications.

## 私有库使用方法
        
        platform :ios, '10.0'
        source 'https://github.com/CocoaPods/Specs.git'
        source 'https://github.com/ruixiaoguo/LYouSpecs.git'
        target 'XXX' do
        ### 私有仓库
                pod 'XXX'
        ### use_framework !

        end
