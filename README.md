# ios-podspec
PodSpec Repo holding references to internal podspec

https://guides.cocoapods.org/making/private-cocoapods.html

## Add your Private Repo to your CocoaPods installation
`pod repo add AbacusPods https://github.com/abacusresearch/ios-podspec`

## Tag/Release the current version of your Podspec
Make sure the github repo has a Release related to the version of your podspec (simply create a new Release with the version e.g. 0.0.1).

## Add your Podspec to your repo
```
cd ~/ios-poi-tracker
pod repo push AbacusPods AbaPOITracker.podspec
```
