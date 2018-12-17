# USAA Interview Notes

## 1. Can you tell us how the app USAA app relates to the rest of USAA services? Is there anything you do on the app that you can’t do on the website, and vice versa?

* App today is big and unwieldy -- tried to manage it to create feature parity

* 10% of the functionality gets 80% of the use

* Tear in the community of should -- pendulum was reductive, app should only have essential experiences

* Pendulum has swung back towards parity being a good thing

* As we grew these features, parity is not the problem, navigation is difficult, 5 pages in you’ll start to see inconsistencies, you can get through a process and lose something

* One of the things we use is -- we have a 3-tier architecture

* App is native (iOS and Android), for most common actions

* After top 10% of use cases -- interacting with mobile web page

* Maintaining low bandwidth dot mobile site because they can’t load it (out on ships deployed etc)

* The goal: move to full responsive, we will be able to retire mdot does have it’s own codebase to maintain

* Services layer more reusable

* One set of APIs you can hit for your functionality -- though they might render differently

* Banking account details, for example, will always be better in a native app

## 2. How has it evolved since it launched?

* People use the app a lot more than they used to, desktop is seeing a decline

* People’s expectations for how they navigate the app has changed a lot with new features

* A lot of it has driven by statistics of what people do a lot

* Help function -- can we get to freeform search, conversational interaction, etc

* Mega menu -- people don’t engage with as much

* Any time you fail in search or bots or conversational -- your user assumes the failure is systemic

* The keyword search is crappy in some places, so they assume none of it is smart

* Fewer entry touchpoints -- only one place to think of usually the functionality is different levels of responses

* One amazing bot with good responses won’t get you that far if it’s expansive

## 3. Have you observed any interesting usage from customers that surprised you?

* Look at traffic

* Top three cards: accounts, investments, claim center

* Money is most active, insurance needs are less frequent

* Active claims need to be higher in the stack

* Very little product acquisition in the mobile channels

* Contextualized seems to be the preference, statusing first

* "I want to see the status of this thing" more than I want to buy/sell/trade/change

* Initiating tasks -- when we have no warning, is hard to find (such as peer to peer payment) but might not come from homepage

## 4. Can you tell us about your approach to shipping changes and updates to the different web platforms (Android/iOS/website)?

* Digital team could give more context

* We engage business partners, they hire IT to deliver for them

* IT builds core services

* Those shops don’t have mobile/native devs in them

* Mobile is a separate shop entirely, requires being passed back to centralized app team, gets approval through apple and google play

* Goal for responsive is: release when ready

* We have more of a release train that goes out to each team to deploy

* We have one dedicated mobile design team (7 people)

* Each of the teams will also do mobile design

* Bill pay, for example, they designed the mobile app

* Could work with or reference central team and work with product owners for mobile app

## 5. Did the technical limitations or capabilities from app to web usage factor into product decisions? How so?

* Login (fingerprint)

* We’re getting better at personalization and tracking on the funnel -- up to buy button or application flow

* We don’t yet have good behavioral data on servicing side of behavioral interactions

* On mobile we have better behavior tracking

* We can do better personalization (what you see is more specific to you)

* We debated a lot -- consistency to the brand vs native environment

* A lot of designers want to push toward a more unified way of calculating

* Venmo or PayPal: Cost entry page doesn’t use native components

* We want to lean on native components and native behaviors of the environment (Android and iOS have different conventions, you stick with what you know)

## 6. How would you describe the breakdown of device usage (iPhone, Android, Tablet, etc.)?

N/A

## 7. Does your app take advantage of any native capabilities of the device or native platform SDKs? If so, for what features?

N/A

## 8. What technical stack did you use for the mobile app (i.e. language, frameworks, toolkits, approaches)?

N/A

## 9. What have you learned about the technical stack you used? What worked well, and what was problematic? Would you use it again?

N/A

## 10. What parts of your technology are shared between your website/web app and your mobile app? How is that sharing being accomplished? Is it working well for you?

N/A

## 11. Can you tell us from a high level how you approach staffing the different teams to support the different platforms?

N/A

## Additional Notes

* Accessibility has been a huge deal

* Working a lot on the design language system

* Code and visual components, lots of efficiency comes from here

* Just getting into it and use it as more than a style guide and use components
