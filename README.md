# CCAsyncRemoteSprite

CCAsyncRemoteSprite is a category that adds methods to CCSprite. Images can be downloaded asynchronously, and be shown in a CCSprite when downloaded. While the image is being downloaded, an optional placeholder image (CCTexture2D) can be shown.

## Installation 

This extension supports installing by CocoaPods. (in-progress)

Checkout Podspecs at [https://github.com/l4u/cocos2d-iphone-podspec](https://github.com/l4u/cocos2d-iphone-podspec)

Alternatively, you can copy the files into your project.

## Example Usage

``` objective-c
    CCSprite *sprite = [CCSprite spriteWithURL:
                        [NSURL URLWithString:@"http://example.org/image.png"]];
```

``` objective-c
    CCSprite *spriteWithplaceholderTexture = [CCSprite 
                                            spriteWithURL:url
                                            placeholderTexture:texture];
```

``` objective-c
    CCSprite *spriteWithURLRequest = [CCSprite 
                                      spriteWithURLRequest: urlRequest 
                                      placeholderTexture:texture];
```

## TODO

* better memory management

## License

[MIT License](http://www.opensource.org/licenses/mit-license.php)

## Related Links

* [AFNetworking](https://github.com/AFNetworking/AFNetworking/)
* [CocoaPods podspec for CCAsyncRemoteSprite](https://github.com/l4u/cocos2d-iphone-podspec)

