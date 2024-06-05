# OCRWebAPI

This repo is a simple demonstration of the chromium OCR API, you can visit this page here
https://sushanthr.github.io/OCRWebAPI/

Chromium based browser have support for an OCR API to read text from images.
https://source.chromium.org/chromium/chromium/src/+/main:third_party/blink/renderer/modules/shapedetection/text_detector.idl

## Note on Browser Requirement (Chrome/Edge Canary on Windows/Mac)

TextDetection API is new, in development.<br>

For now the latest canary of any chromium based browser:<br>
**Chrome/Edge Canary** on **Windows** / **Mac** have a working implemention<br>

You would also need the experimental API enabled, paste the following URL in the address bar to get to that settings page.

```
edge://flags/#enable-experimental-web-platform-features
```

Please pay attention to the warning WebNN is an experimental API, proceed at your own risk.<br>
WARNING: EXPERIMENTAL FEATURES AHEAD! By enabling these features, you could lose browser data or compromise your security or privacy. Enabled features apply to all users of this browser. If you are an enterprise admin you should not be using these flags in production.

Chrome Canary https://www.google.com/chrome/canary/ <br>
Edge Canary https://www.microsoft.com/en-us/edge/download/insider?form=MA13FJ
