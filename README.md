# MauiTipsAndTricks
Noting all the "interesting" stuff found in .NET MAUI, as well as during the Xamarin.Forms migrations etc.

## Migration checklist
1. check libraries in Xamarin.Forms - what they are added for, are they supported in .NET MAUI (if not, check possible workarounds)
2. design - now we can work with svg, no need to import and support two differents sets of png files
3. check if there are some CustomRenderers in Xamarin.Forms project that should be "migrated" to hanlders
4. work on the Effects if there is any need
5. NOTE: not all UI can be migrated or reused - containers work in a "slightly" different way in .net maui


## Current issues
### CollectionView:
LongPress TouchBehavior - wrong item is selected
https://github.com/CommunityToolkit/Maui/issues/1804 - planned to be fixed in .NET 9 major release
