# CustomNotes

Sample code for the blog post "[Making a Share Extension that accepts text and URLs in combination with CoreData Swift 3](https://medium.com/@ales.musto/making-a-share-extension-that-accepts-text-and-urls-in-combination-with-coredata-swift-3-a0139c0f9800)"

## Getting Started

Open the `CustomNotes.xcodeproj` in Xcode.

**IMPORTANT:** If you do not have an Apple ID with a developer account for code signing iOS apps, the build will fail with a code signing error. If you have a developer account, you can create the file "Xcode-Configurations/DEVELOPMENT_TEAM.xcconfig" with the following build setting as its content:
> DEVELOPMENT_TEAM = [Your TeamID]

For a more detailed description of this, you can have a look at the comments at the end of the file "Xcode-Configurations/Base.xcconfig". 

It's also necessary to replace all instances of "group.com.sandromusto.notes" with something matching the pattern "group.YOUR_TLD.YOUR_DOMAIN.notes" and "com.Lmusto.CustomNotes" with "YOUR_TLD.YOUR_DOMAIN.CustomNotes". I recommend creating a separate commit for this and rebasing it onto the current git HEAD as needed.

You can now click Run in Xcode.
