# sample-realm-ios-project-cocoapods-renovate-demo

## Demo Issue updating Cocoapods dependency
Sample project with automated dependency updates for Cocoapods using Renovatebot.
1. Created sample repo [sample-realm-ios-project-cocoapods-renovate-demo](https://github.com/asoneji/sample-realm-ios-project-cocoapods-renovate-demo.git)
2. Create a sample XCode Project [sample-ios-project](https://github.com/asoneji/sample-realm-ios-project-cocoapods-renovate-demo/tree/master/sample-ios-project)
3. Did `pod init` and added a pod dependency
   * Added at top:
     * `platform :ios, '11.2'`
   * Added Dependency:
     * `pod 'Analytics', '3.8.1'`
4. Connect Renovate using [renovate](https://github.com/marketplace/renovate) to the repo [sample-realm-ios-project-cocoapods-renovate-demo](https://github.com/asoneji/sample-realm-ios-project-cocoapods-renovate-demo).
5. Renovate created a [pr 1](https://github.com/asoneji/sample-realm-ios-project-cocoapods-renovate-demo/pull/1) with renovate config which I merged.
6. Renovate created a [pr 2](https://github.com/asoneji/sample-realm-ios-project-cocoapods-renovate-demo/pull/2) to Update dependency Analytics 3.8.1 to 3.9.0.
   * [Artifact file update failure](https://github.com/asoneji/sample-realm-ios-project-cocoapods-renovate-demo/pull/2#issuecomment-649812927)
   * Job log [here](https://app.renovatebot.com/dashboard#github/asoneji/sample-realm-ios-project-cocoapods-renovate-demo/194341121)
7. Add Realm
   * Added Dependency:
     * `pod 'RealmSwift', '5.0.3'`
8. Renovate created a [pr 4](https://github.com/asoneji/sample-realm-ios-project-cocoapods-renovate-demo/pull/4) to Update dependency Analytics 3.8.1 to 3.9.0.
   * [Artifact file update failure](https://github.com/asoneji/sample-realm-ios-project-cocoapods-renovate-demo/pull/2#issuecomment-649812927)
   * Job log [here](https://app.renovatebot.com/dashboard#github/asoneji/sample-realm-ios-project-cocoapods-renovate-demo/194341121)
