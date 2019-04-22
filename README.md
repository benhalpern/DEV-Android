<div align="center">
  <br>
  <img height=100px src="https://lh3.googleusercontent.com/g7lQCU30H5iAmo2CoBijCmuBF0nE4rZrc9wDBxgOV0lX0aGBb8RD95UvZixfUIwCVA=s180-rw"/>   <img height=100px src="https://upload.wikimedia.org/wikipedia/commons/d/d7/Android_robot.svg"/>
  <h1>DEV Android</h1>
  <strong>The android app</strong>
</div>

<a href="https://codeclimate.com/github/thepracticaldev/DEV-Android/maintainability"><img src="https://api.codeclimate.com/v1/badges/ad31b8a267a37475e14c/maintainability" /></a>
<a href="https://codeclimate.com/github/thepracticaldev/DEV-Android/test_coverage"><img src="https://api.codeclimate.com/v1/badges/ad31b8a267a37475e14c/test_coverage" /></a>

This is the repo for the dev.to Android app. 

<a href='https://play.google.com/store/apps/details?id=to.dev.dev_android&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1'><img width=150px alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png'/></a>


# Design ethose

We will grow to include more native code over time, but for now we are taking the approach of _native shell/web views_. This approach lost favor early in iOS days, but I believe it is a very valid approach these days. It is inspired by how Basecamp does things. Our tech stack is a bit different, but the ideas are the same. 

https://m.signalvnoise.com/basecamp-3-for-ios-hybrid-architecture-afc071589c25

https://signalvnoise.com/posts/3743-hybrid-sweet-spot-native-navigation-web-content

https://signalvnoise.com/posts/3766-hybrid-how-we-took-basecamp-multi-platform-with-a-tiny-team

https://www.youtube.com/watch?v=SWEts0rlezA

By leveraging webviews as much as possible, I think we can make this all pretty awesome and sync up with our web dev work pretty smoothly. And where it makes sense, we can re-implement certain things fully native, or build entirely native features. Life's a journey, not a destination.
