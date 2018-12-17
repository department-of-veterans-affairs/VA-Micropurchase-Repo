# Mayo Clinic Interview Notes

Journey they been on has been interesting. Have a lot of physician leaders, who have had interesting ideas. A lot more apps in app store 3-4 years ago. More consolidation of brands and apps over past few years. Mayo Clinic App is flagship app, serving multiple audiences.

Were into high 40s of apps; now down to 10s or so. Will continue to do that as product’s reach end of life. But will continue to provide experience in the flagship app.

As talk to partners like Apple and Google, and tested with patients, they were getting confused as to which app to use. Decided needed to do a better job of consolidating and creating an integrated experience.

## 1. Can you describe the app your company has created and give me a high-level view of how it relates to other services or products you offer?

N/A

## 2. What can you do on the app that you can’t do on the website, and vice versa?

N/A

## 3. In the time since it’s launch -- how has it changed?

N/A

## 4. Have you observed any interesting usage from customers that surprised you?

N/A

## 5. Do reviews matter to your team on the app/play store?

N/A

## 6. Did the technical limitations or capabilities from app to web usage factor into product decisions? How so?

Interesting question. It’s a balancing act.

Have two main user groups -- patients, consumers / health seekers. Have complementary online portal for patients. Try to maintain parity in features between web and mobile in order to deliver consistent experience. Has been a challenge as of late. Mayo in process of switching over EHR to Epic, which has been as open / extensible via APIs as would like. Decided to maintain a unique experience for patients in order to help differentiate from others.

Different on consumer side. Two features: curated set of content and clinic search. Some parity, but not as much on patient side.

When there’s lack of parity, tends to be more features on the web.

Done a good job of providing Epic’s features both on the web and mobile app. Challenge has been to get Epic to expose data in a way that makes sense to Mayo’s users. Would love to see Epic open-up API stack.

## 7. How would you describe the breakdown of device usage (iPhone, Android, Tablet, etc.)?

Mainly target iOS and Android.

Device form factors: phone and tablet.

Also support Apple Watch, And Androidware. Use of those apps lower.

Tablet growth has tapered off. Less and less ppl using those. Will stay committed to tablet as long as they keep producing. Users expect experiences on these devices.

## 8. Does your app take advantage of any native capabilities of the device or native platform SDKs? If so, for what features?

For both iOS and Android, completely native. Feel these provide best experience.

Cross-compile apps give you a mobile experience, but don’t feel appropriate for their uses.

Mobile clients themselves are pretty simple. Don’t maintain any logic or data. Built all business logic, etc. into API layer. Just make changes in service, not in the client.

## 9. What technical stack did you use for the mobile app? (i.e. language, frameworks, toolkits, approaches)

Try to take advantage of many as possible where it makes sense. For example, Map Integration, Camera Integration, Apple Wallet for appointments.

## 10. What have you learned about the technical stack you used? What worked well, and what was problematic? Would you use it again?

iOS converted to Swift. Conversion done quickly b/c of API stack.

Android on Java, but looking to convert to Kotlin.

Don’t spend a lot of time on low bandwidth or no access. Approached from assumption some access is needed. Tradeoff is about security. Feel like in order to protect data, best not to keep on device.

In terms of authentication, users demanded fingerprint / face ID authentication.

## 11. What parts of your technology are shared between your website/web app and your mobile app? How is that sharing being accomplished? Is it working well for you?

Content is shared. ID mgmt platform is shared. Analytics platform is shared so analytics team can look across all devices. Patient data is shared. This about of extent that can be shared.

Smart services -- think of these as shared between mobile and web. Really worked to create a shared service stack.

Summary: one application with web, native iOS, native Android and they are made up of common services.

Architecture have now gives most flexibility to support mobile.

Don’t think would create one app to support all mobile experience, but rather to take advantage what’s native in each platform.

Create as much of a seamless experience between the two as possible.

Appointments and quick access to reviewing results and messaging are key mobile features.
