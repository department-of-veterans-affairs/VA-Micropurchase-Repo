# City of Boston Interview Notes

This interview focused on the Boston Digital Service 311 project. Please note this project doesn’t currently have an app in production. They’re working on building new backend infrastructure to support a new web app, with the hopes of it scaling to being a native application.

## 1. Can you describe the app your company has created and give me a high-level view of how it relates to other services or products you offer?

For 311 we’re building a new backend to replace the third-party service (connected bits). Mostly an issue of staffing and expertise, we don’t have enough engineers to do three versions for a thing.

Apps are good for offline, photo uploading through an app because it can retry, etc.

Used to work on developer tools; they had more infrastructure for services for apps crashing out in the wild (worked at Twitter, they acquired Crashlytics in order to manage remote usage crashing) and there’s a tremendous amount of extra infrastructure.

How do people discover the app?

Offline saving of appt reminders, working with your calendar, I use one medical chat and it’s nice to use the app.

## 2. What can you do on the app that you can’t do on the website, and vice versa?

Offline and low connectivity is the biggest thing, progressive apps are coming with more OS support slowly, doing anything with the camera, barcode scanning, taking photos.

The phone can give you a session without having to do username and password a little better than a web browser.

People will always use the same phone; unlike desktop where people might switch computers.

## 3. In the time since it’s launch, how has it changed?

It’s taking longer than we thought, in general features have stayed as intended, our classification model has shifter for how people classify an issue, tweaking the UI based on user research.

## 4. Have you observed any interesting usage from customers that surprised you?

Mostly it’s about usability, ignoring text boxes etc, people missing UI stuff. Don’t be too clever, do what people expect.

We did prototyping of a native app, building it to rise to a native app.

If I were to do it in Boston I would definitely do it in React Native. It lowers the cost of developing for iOS and Android.

## 5. Do reviews matter to your team on the app/play store?

Experience from Twitter -- you have to see it to download it, so you do some across it and if it only has three stars I worry about what I’m getting into, especially if it’s going to make them think it’s a crappy government website.

## 6. Did the technical limitations or capabilities from app to web usage factor into product decisions? How so?

N/A

## 7. How would you describe the breakdown of device usage (iPhone, Android, Tablet, etc.)?

More android than you expect, no one uses tablets, still more iOS and Android folks don’t use apps as often.

55 desktop

40 mobile

5 tablet

74% Apple

13% Samsung

## 8. Does your app take advantage of any native capabilities of the device or native platform SDKs? If so, for what features?

If your app doesn’t you don’t need an app -- we’d use push notifications camera microphone.

## 9. What technical stack did you use for the mobile app (i.e. language, frameworks, toolkits, approaches)?

Somewhat hypothetical.

React Native -- personal preference and also transferable skills on the team.

Native SDK hooks have more differences, different conventions.

If I wanted to win an apple design award it might be different.

Staffing would be easier with React Native.

Crashlytics (or something similar) -- crash reporting, you need this!

## 10. What have you learned about the technical stack you used? What worked well, and what was problematic? Would you use it again?

N/A

## 11. What parts of your technology are shared between your website/web app and your mobile app? How is that sharing being accomplished? Is it working well for you?

Backend would be shared.

I’d use GraphQL (replacement for REST) -- a protocol for communicating between a client and a server be able to talk to the same backend.

Upgrades are another concern -- apps automatically upgrade, running it from 6 months ago they might get an old version.

To what degree they can download new content is important, push as much to the server as possible so you can update things without needing to update on the device by the user.

**Okay with publishing interview notes by name?**

This interview was with Fin Hopkins.

Yes is ok with publishing, but is not acting as an official spokesperson for the City of Boston, and their views do not necessarily the City of Boston’s views.
