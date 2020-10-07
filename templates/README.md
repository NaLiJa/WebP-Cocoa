<p align="center">
    <img src="https://github.com/TimOliver/WebP-Cocoa/raw/main/banner.png" width="731" alt="WebP-Cocoa Banner" />
</p>

[WebP](https://developers.google.com/speed/webp) is a modern image file format that provides amazing lossy and lossless compression fidelity. WebP is developed by Google and is freely distributed as open source software.

Google provides prebuilt binaries of WebP for both iOS and macOS on [WebP's download page](https://developers.google.com/speed/webp/download). However, at the time of writing, their build pipeline has not yet been updated to include Apple's other platforms, module support to allow Swift support, or architectural support for Mac Catalyst.

Using Google's original build script as a base, this repository both directly builds and serves prebuilt binaries for all of Apple's platforms. In addition to iOS and macOS support, watchOS and tvOS is also supported as well as Mac Catalyst via Apple's new `xcframework` format.

There are 4 separate frameworks available for each platform:

* **WebP**: Both encoding and decoding capabilities for the WebP format.
* **WebPDecoder**: Just the decoding capabilities for the WebP format.
* **WebPMux**: Enables manipulation of WebP container image features like color profile, metadata, animation.
* **WebPDemux**: Enables extraction of image and extended format data from WebP files.

# Instructions

1. Download and extract the package for your platform and capabilities of choice.
2. Drag the `framework` folder into your Xcode project.
3. When prompted, make sure *Copy items if needed* is checked before proceeding.

# Download Frameworks

For ultimate convenience, the prebuilt frameworks have been packaged up into multiple combinations of ZIP archives. 
Simply click one of the links below to begin downloading.

<table>
    <tr>
        <td colspan="4" align="center">
            <strong><a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework.zip">Download All Frameworks for All Platforms (ZIP)</a></strong>
        </td>
    </tr>
    <tr>
        <th>Platform</th>
        <th>Versions</th>
        <th>Slices</th>
        <th>Download Packages</th>
    </tr>
    <tr>
        <td><b>iOS</b><br />(Mac Catalyst)</td>
        <td>iOS 11.0 and up.<br/>macOS 10.15 and up.</td>
        <td>
            <ul>
                <li><code>arm64</code></li>
                <li><code>x86_64</code> (Mac Catalyst)</li>
                <li><code>x86_64</code> (Simulator)</li>
            </ul>
        </td>
        <td>
            <ul>
                <li>
                    <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-ios-catalyst.zip">
                        <strong>Download All (ZIP)</strong>
                    </a>
                </li>
                <li>
                    <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-ios-catalyst-webp.zip">
                        <code>WebP.xcframework</code>
                    </a>
                </li>
                <li>
                    <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-ios-catalyst-webpdecoder.zip">
                        <code>WebPDecoder.xcframework</code>
                    </a>
                </li>
                <li>
                    <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-ios-catalyst-webpdemux.zip">
                        <code>WebPDemux.xcframework</code>
                    </a>
                </li>
                <li>
                    <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-ios-catalyst-webpmux.zip">
                        <code>WebPMux.xcframework</code>
                    </a>
                </li>
            </ul>
        </td>
    </tr>
    <tr>
        <td><strong>iOS</strong></td>
        <td>iOS 9.0 and up.</td>
        <td>
            <ul>
                <li><code>arm64</code></li>
                <li><code>armv7</code></li>
                <li><code>armv7s</code></li>
                <li><code>x86_64</code></li>
                <li><code>i386</code></li>
            </ul>
        </td>
        <td>
            <ul>
                <li>
                    <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-ios.zip">
                        <strong>Download All (ZIP)</strong>
                    </a>
                </li>
                <li>
                    <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-ios-webp.zip">
                        <code>WebP.xcframework</code>
                    </a>
                </li>
                <li>
                    <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-ios-webpdecoder.zip">
                        <code>WebPDecoder.xcframework</code>
                    </a>
                </li>
                <li>
                    <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-ios-webpdemux.zip">
                        <code>WebPDemux.xcframework</code>
                    </a>
                </li>
                <li>
                    <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-ios-webpmux.zip">
                        <code>WebPMux.xcframework</code>
                    </a>
                </li>
            </ul>
        </td>
    </tr>
    <tr>
        <td><strong>macOS</strong></td>
        <td>OS X 10.9 and up.</td>
        <td>
            <ul>
                <li><code>x86_64</code></li>
            </ul>
        </td>
        <td>
            <ul>
            <li>
                <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-macos.zip">
                    <strong>Download All (ZIP)</strong>
                </a>
            </li>
            <li>
                <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-macos-webp.zip">
                    <code>WebP.xcframework</code>
                </a>
            </li>
            <li>
                <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-macos-webpdecoder.zip">
                    <code>WebPDecoder.xcframework</code>
                </a>
            </li>
            <li>
                <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-macos-webpdemux.zip">
                    <code>WebPDemux.xcframework</code>
                </a>
            </li>
            <li>
                <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-macos-webpmux.zip">
                    <code>WebPMux.xcframework</code>
                </a>
            </li>
            </ul>
        </td>
    </tr>
    <tr>
        <td><strong>tvOS</strong></td>
        <td>tvOS 9.0 and up.</td>
        <td>
            <ul>
                <li><code>arm64</code></li>
                <li><code>x86_64</code></li>
            </ul>
        </td>
        <td>
            <ul>
            <li>
                <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-tvos.zip">
                    <strong>Download All (ZIP)</strong>
                </a>
            </li>
            <li>
                <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-tvos-webp.zip">
                    <code>WebP.xcframework</code>
                </a>
            </li>
            <li>
                <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-tvos-webpdecoder.zip">
                    <code>WebPDecoder.xcframework</code>
                </a>
            </li>
            <li>
                <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-tvos-webpdemux.zip">
                    <code>WebPDemux.xcframework</code>
                </a>
            </li>
            <li>
                <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-tvos-webpmux.zip">
                    <code>WebPMux.xcframework</code>
                </a>
            </li>
            </ul>
        </td>
    </tr>
    <tr>
        <td><strong>watchOS</strong></td>
        <td>watchOS 2.0 and up.</td>
        <td>
            <ul>
                <li><code>arm64_32</code></li>
                <li><code>armv7k</code></li>
                <li><code>i386</code></li>
                <li><code>x86_64</code></li>
            </ul>
        </td>
        <td>
            <ul>
                <li>
                    <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-watchos.zip">
                        <strong>Download All (ZIP)</strong>
                    </a>
                </li>
                <li>
                    <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-watchos-webp.zip">
                        <code>WebP.xcframework</code>
                    </a>
                </li>
                <li>
                    <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-watchos-webpdecoder.zip">
                        <code>WebPDecoder.xcframework</code>
                    </a>
                </li>
                <li>
                    <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-watchos-webpdemux.zip">
                        <code>WebPDemux.xcframework</code>
                    </a>
                </li>
                <li>
                    <a href="https://github.com/TimOliver/WebP-Cocoa/releases/download/{tag_version}/libwebp-{tag_version}-framework-watchos-webpmux.zip">
                        <code>WebPMux.xcframework</code>
                    </a>
                </li>
            </ul>
        </td>
    </tr>
</table>

# Credits

Repository created and maintained by [Tim Oliver](http://twitter.com/TimOliverAU). WebP icon artwork by [Simo99](https://commons.wikimedia.org/wiki/User:Simo99) used under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/). WebP is developed by [Google](http://about.google).

# License

All code in this repository is under the BSD-3-Clause License. Please see the [LICENSE](LICENSE) file for more information.