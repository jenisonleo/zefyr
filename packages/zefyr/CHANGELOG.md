## 0.2.0

* Breaking change: `ZefyrImageDelegate.createImageProvider` replaced with
  `ZefyrImageDelegate.buildImage`.
* Fixed redundant updates on composing range for Android.
* Added TextCapitalization.sentences
* Added docs for embedding images.

## 0.1.2

* Fixed analysis warnings.
* UX: User taps on padding area around the editor and in empty space inside it now look for the nearest
  paragraph to move caret to.
* UX: Toggle selection toolbar on double tap instead of refreshing it.

## 0.1.1

* Fixed: Prevent sending excessive value updates to the native side
  which cause race conditions (#12).

## 0.1.0

*  Initial release.
