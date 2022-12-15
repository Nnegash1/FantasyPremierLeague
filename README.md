# Fantasy Premier League

**Kotlin Multiplatform** project with Jetpack Compose, Compose for Desktop and SwiftUI clients (and using Ktor for remote API requests and Realm for persistence). Currently running on:
* Android (Jetpack Compose)
* iOS (SwiftUI)
* Desktop (Compose for Desktop)


Related posts:
* [Using Realm persistence library in a Kotlin Multiplatform project](https://johnoreilly.dev/posts/realm-kotlinmultiplatform/)
* [Using new Swift Async Algorithms package to close the gap on Combine](https://johnoreilly.dev/posts/swift-async-algorithms-combine/)


### Building
This project currently uses iOS16 features (e.g. Swift Charts) so requires use of XCode 14 beta. 

Note that we're not handling realm db migrations yet so, for now, you may need to clear app data and re-run if you encounter "Migration is required" type errors.


## Screenshots
|Platform|Screenshot|
|---|---|
|Android|<img src="/art/screenshot1.png?raw=true" width=300/>|
|iOS|<img src="/art/screenshot2.png?raw=true" width=300/>|
|Desktop|<img src="/art/screenshot3.png?raw=true" width=300/>|
