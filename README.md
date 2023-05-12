# Hello there, I'm Tomás 👋

I am an avid Apple platforms user and developer, with extensive experience creating iOS and macOS apps since 2018. My expertise spans across startups, consulting businesses, and multinational corporations and my won side-projecst, where I have contributed to developing new projects or improving existing ones. My work has been instrumental in expanding revenue, increasing userbase, and earning high praise from users and the media. My apps have been featured by Apple on their App Store, websites, and keynote events. In addition, I am an active member of the iOS community, contributing to open-source projects, conducting presentations for iOS-related events, and coaching team members.

If you're looking for an experienced and dedicated developer to bring your product to life or take your existing solution to the next level, I'm here to help. Feel free to reach out to me through any of the following channels:

- [LinkedIn[(https://www.linkedin.com/in/tfmart)
- [Twitter](https://twitter.com/tommycadle)

# Previous Clients/Employers

Here are all the projects I've worked in the past:

## Guru

At Guru, I had the opportunity to work with a dynamic startup in the financial industry, whose goal was to revolutionize the investment experience for the new generation of Brazilian investors. My role was to assist in transforming the existing portfolio manager app into a fully-featured broker app, using a mobile-first approach that simplifies the interface and experience for newcomers.

To achieve this goal, I collaborated closely with the product and design team to develop a new Design System and improved user experience using SwiftUI. As early adopters of this technology in the Brazilian market, we were able to greatly reduce the cost of implementing new features while advocating for the adoption of other iOS platform features like Widgets and AppIntents. I played a critical role in mentoring the engineering team on the implementation of these new features, and I also led negotiations with the product team on how best to integrate them into our app.

Thanks to our efforts, the Guru app quickly became a standout in the digital broker market, garnering high user satisfaction and accolades from industry experts. Our app was named one of the "Top 10 Financial Apps" in the Brazilian App Store, and was even featured in the Main Event of WWDC 2022 due to its integration with Siri. I'm proud to have been part of this exciting journey and to have contributed to its success.

### Featured in:
- [Top 10 Finance Apps (Brazilian App Store, as of May 2023)](https://apps.apple.com/br/story/id1599761254)
- [Featured in WWDC 2022 Keynote, due to it's integrations with Siri (at 16:32)](https://www.youtube.com/live/q5D55G7Ejs8?feature=share&t=986)

### Stack
- Swift
- SwiftUI
- UIKit (Auto Layout on code)
- MVVM-C
- Firebase (Remote Config, A/B Testing, App Distribution)
- Fastlane
- CI/CD
- Automated tests
- CocoaPods and Swift Package Manager
- WidgetKit
- AppIntents

## GFG (through Dextra Digital)

During my time at Dextra Digital, I worked on the three main projects of Global Fashion Group in Latin America: Dafiti, Kanui, and Tricae. Our team's mission was to improve the maintenance and performance of these three fashion marketplace apps, which were built using Objective-C and MVC design pattern. My contribution involved separating common business logic and visual components between the apps into separate dependencies, while also converting existing code and developing new ones with Swift using the MVVM pattern.

Our efforts resulted in more reliable products for the hundreds of thousands of users across Latin America. By writing scalable and maintainable code, we were able to fix many bugs and errors affecting the userbase. Our solutions enabled the apps to survive stress tests during many shopping holidays, making them the main point of sale for all three marketplaces and ultimately increasing revenue.

Our work even resulted in the main app of the suite, Dafiti, being featured on the App Store and on the Brazilian website of Apple Pay.

### Featured in:
- [App of the Day](https://apps.apple.com/br/story/id1368071848)
- [Apple Pay Website (Brazil)](https://www.apple.com/br/apple-pay/)

### Stack
- Swift
- Objective-C
- UIKit (Auto Layout, XIBs and Storyboards)
- MVVM (Refactored Code) and MVC (Legacy Code)
- Fastlane
- Firebase (Remote Config, A/B Testing, App Distribution)
- CI/CD
- Automated tests
- CocoaPods

# Side Projects

These are apps that have been entirely designed, developed and published by me:

## AirScrobble

*[Download for free](https://apps.apple.com/us/app/airscrobble/id1618366994 )*

AirScrobble started as single-purpose tool with one goal: allow users of the music website Last.fm to identify songs that were playing in real life, like on a concert, at a café or at their record players, and log them to their profile in the website. I had the idea for the app as live events started to comeback after the pandemic started winding down. There were many tools that allow us to scrobble songs we listen through the digital medium, such as music being streamed or played from our phones or laptops, but I couldn't find a good solution if I wanted to scrobble along a set list of a concert I was attending on or if the venue I was visiting had a playlist going on that was right on my alley. So I designed AirScrobble to fill this gap, which I ended finding out that it ended scratching an itch of many different people

I've designed the experience to be the most streamlined and ease to use as possible. Upon opening the app, the user is presented with a big red record button. Although simple, this design is intentional so that the button can be easily be pressed without having to distract the user on what they're experiencing in the moment, so you can, for example, name the and scrobble tunes that are playing on your local café without distracting you from the conversation you might be having with your friends there. When a song is matched, it takes center stage as the app adapts its interface to the artwork of the current song, if any, so that they can have a nicer layout if the user ends up paying mind to the app. A button to scrobble the current match is readily available alongside the big record button, so you can easily keep the matching going

The app is built entirely in SwiftUI and makes uses of AVFoundation to listen to the user's microphone, ShazamKit to pass the audio stream from the microphone to the Shazam media recognition tool and then interacts with Last.fm REST API in order to scrobble songs to the service. Since the app's debut in August 2022, I've also implemented many new framework and features in order to make it a good iOS citizen, such as integration with the Music app, Lock Screen Widgets and, the most popular one so far, Live Activites.

I leveraged the Live Activities framework to build a feature name Auto Match, which let users listen and scrobble to songs playing around them or through their device speakers continuously, even if the app is in the background or the device is locked. By pressing and holding the record button, the Auto Match feature is activated, so the user can then dismiss the app or lock their device, while keeping on track on what's playing around them with the Live Activity widget which, just like inside the app, blends it's visuals nicely with the artwork of what's playing in the moment. Users with the Dynamic Island can also keep track of what's playing on it

The app also has an iPad version that takes advantage of the screen real estate, by providing a new visual for the discovery history page in the app, having full support to multitasking modes, such as Split View and Stage Manager, and keyboard shortcut support for quickly moving around the app

The userbase loves the experience that AirScrobble brings to the table, with many leaving great reviews in the store and some reaching me out to tell me about their experiences. We had a user that used the app to convert cassette mixtapes that were playing on their stereo into Apple Music playlists, one that used the app to scrobble the soundtrack of the movie they were watching at the movie theater and others to scrobble a DJ set. The app also has been covered by the press on websites like MacStories and MacMagazine

Launching AirScrobble, which was my first self-published app in the App Store has been a tremendously rewarding experience, as I learned more about how to work with more Apple frameworks and how can they work together, got more experience on how to design an experience that filled the needs of my users and to get direct feedback from them. 

### Stack
- Swift
- SwiftUI
- MVVM
- AVFoundation
- ShazamKit
- Last.fm REST API
- WidgetKit
- ActivityKit
- MusicKit
- UIAccessiblity
- StoreKit 2
- UserNotification
- AppIntents

### Featured in:
- [🇧🇷 MacMagazine: "Faça scrobble das músicas que ouve em tempo real com o AirScrobble"](https://macmagazine.com.br/post/2023/05/01/faca-scrobble-das-musicas-que-ouve-em-tempo-real-com-o-airscrobble/)
- [🇩🇪 iPhoneblog.de: "AirScrobble – die freihändige Musikerkennung"](https://www.iphoneblog.de/2023/02/27/airscrobble-die-freihandige-musikerkennung/)
- [🇬🇧 MacStories: "Scrobbling Apple Music to Last.fm from Windows with AirScrobble and Cider"](https://club.macstories.net/posts/scrobbling-apple-music-to-last-fm-from-windows-with-airscrobble-and-cider)

## Fujilingua

_To be released..._

In the last few of years, I've switched my camera gear to Fujifilm due to their X-Series line of cameras, that have been very popular lately. Not only the camera bodies of this line have a trendy retro look, but the images they can produce with the built-in film simulation filters can also have a very analog film look, which is also in demand. These filters can be configured inside the camera in order to get the image you want SOOC (straight out of the camera), so many have been experimenting with these filters and have been sharing them online on Instagram and YouTube. There's even websites dedicated to sharing these recipes online, such as [FujiXWeekly](https://fujixweekly.com/)

There are many recipes to be found in these online community nowadays, chances are that if you have a certain style in mind for your next pictures there's a recipe posted out there that at least gets close to what you want. However, if you need a very specific visual for your images, you might not find exactly what you're looking for straightaway, so the only options are to try to experiment with the camera settings yourself or using a Fujifilm RAW Studio program on your computer, both options that can be pretty intimidating for new comers.

With the explosion of ChatGPT on early 2023, I've seen many different use cases for the LLM. One that caught my attention though, was when I saw on Twitter that someone had been using it to generate gradients based on certain themes. After that, I wondered if this ChatGPT "vision" could be applied to create recipes for the Fujifilm cameras. I always wanted to create a recipe that mimics the colorful palletes of [Hiroshi Nagai artworks](https://www.instagram.com/hiroshipenguinjoe/), so I asked ChatGPT to generate one for me and it surprisingly got pretty close! A few tweaks were needed to get the desired look I want, but still it was way less work than having to create it from scratch

So with that, Fujilingua was born: an app that let users use natural language to generate film simulation recipe for the Fujifilm cameras through ChatGPT API. Users can create filters from the colors of a specific movie scene, a painting they want to mimic, a mood they want to convey... there are many possibilities and the users can get very specific with their prompts if they want to. The app then will use OpenAI API to send the request to ChatGPT and then display the answer from the LLM. The app will always present the required settings along with an explanation of how they can help the user achieve the look they're after

All generated recipes are stored locally on device, where they can refer to them later and even add images they've captured with the generated recipe, so they can refer on how it looks. If the users wishes to tweak the recipe further, they can quickly edit the recipe settings in the app

I'm planning to release the app in by the end of June, but still it has been quite an great experience. It's been great to get to know OpenAI's API quirks and limits and how to work with a LLM, which is definitely something that we will probably have to be more familiar with in the future. It also provided me with a chance to play with custom controls and animations in SwiftUI, such as the loading animation I built and the custom White Balance Picker I've built, that mimics the one you'd find in an actual Fujifilm camera.

### Stack
- Swift
- SwiftUI
- MVVM
- OpenAI REST API
- ChatGPT
- UIAccessiblity
- StoreKit 2

# Presentations

## AppIntents & Shortcuts (@ CocoaHeads Campinas)

I've found the AppIntents API to be one of the most underrated from 2022's WWDC. It provided with an API that makes it soooo much easier to add support for Siri, Shortcuts, Spotlight and possibly other features in the future. After working with it on both Guru and AirScrobble, I've decided to spread the word about it and share my experience on implementing it on both apps with the local iOS community in Campinas

The presentation is in Portuguese, but both the slides and the demo code of the presentation are in English and you can check them out on the links below:

- Presentation
- Demo code

## Round-table discussion about WWDC 2022 (@ CocoaHeads Campinas)

On the first CocoaHeads meetup after the WWDC 2022 event, I've joined other developers to discuss all the news from the event, sharing my opinions and discussing with the other members how these new features and APIs could impact the products we were working on.

This discussion was also in Portuguese

# Open Source

Below are my most notable open-source projects. If you want to checkout some other open source work I've done, you can find them on my Github page. Feel free to contribute to any of them!

## LottieUI

LottieUI is a wrapper for the popular Lottie animation library from Airbnb, providing a more declarative API in order to display animations both stored locally and on the web, while providing a set of modifiers to customize the playback of an animation. The goal was to allow users to display Lottie animation on a API that feels right at home with other SwiftUI views

You can learn more on the LottieUI repository

## Giphy

Giphy is a small package to display animated GIFs in SwiftUI. The Giffy view wraps Flipboard's FLAnimatedImage component, which has been field-tested in many major apps such as Facebook and Slack, so you can assure all animations will be memory-efficient

You can learn more on the Giffy repository
