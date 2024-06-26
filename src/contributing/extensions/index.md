# Introduction to extensions

## A Reader Without Servers

When developing a Reader, first and foremost, you need to gather your content from somewhere.

If you do not hold this kind of infrastructure, as Paperback does not, the app needs to be designed in a way where it can dynamically read other content providers.

This design paradigm has many benefits. The Apple App Store is very restrictive on content provided to iOS and iPadOS devices, however with a generic extension system which can be added into the application at runtime allows all sorts of content to be made available, only requiring the users to install each module correctly.

## Where do I start?

Developing an extension is pretty easy, you only need basic programming knowledge. Some understanding of TypeScript, nodeJS and Git may help but is not required.

- First, check out the [quick start](/contributing/extensions/quick-start) guide for a place to begin.

- Then, use one of our guides to learn more about extension development:

  - [A practical guide to Parsing](/contributing/extensions/parsing-guide)
  - [v0.8 Reference](/contributing/extensions/reference-0.8/)
