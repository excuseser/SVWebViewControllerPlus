# SVWebViewControllerPlus

Base on [SVWebViewController](https://github.com/TransitApp/SVWebViewController) for app  [ip-helper](https://itunes.apple.com/us/app/ip-helper-ping-tracert-whois/id622012742?l=zh&ls=1&mt=8)

![SVWebViewController](https://raw.githubusercontent.com/excuseser/SVWebViewControllerPlus/master/screen/shot_jpg.jpg)


## Differents
- Add progressview for loading.
- ADD url address Bar.

## Usage

same as SVWebViewController

(see sample Xcode project in `/Demo`)

Just like any UIViewController, SVWebViewController can be pushed into a UINavigationController stack:
```objective-c
SVWebViewController *webViewController = [[SVWebViewController alloc] initWithAddress:@"http://google.com"];
[self.navigationController pushViewController:webViewController animated:YES];
```

It can also be presented modally using `SVModalWebViewController`:

```objective-c
SVModalWebViewController *webViewController = [[SVModalWebViewController alloc] initWithAddress:@"http://google.com"];
[self presentViewController:webViewController animated:YES completion:NULL];
```
## Credits

SVWebViewController is brought to you by [Sam Vermette](http://samvermette.com) and [contributors to the project](https://github.com/samvermette/SVWebViewController/contributors). If you have feature suggestions or bug reports, feel free to help out by sending pull requests or by [creating new issues](https://github.com/samvermette/SVWebViewController/issues/new). If you're using SVWebViewController in your project, attribution is always appreciated.
