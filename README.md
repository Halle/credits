# My Apple Security Releases Credits

Security credits I have received from Apple in reverse chronological order. A finding that was fixed in several releases appears once for each release.

| # | Release | Date | Component | CVE | Note |
|---|---|---|---|---|---|
| 18 | [macOS Sequoia 15.4](https://support.apple.com/en-us/122373) | 2025-03-31 | Share Sheet | CVE-2025-30438 | A malicious sandboxed app, in combination with a lock screen bug, could result in a dismissed lock screen notification that a screen recording with microphone (this could include a continuity camera microphone) had been started on the locked device. This included recordings started by someone with physical access but no credentials. The exploit also demonstrated automatic recording exfiltration to remote server without a networking grant, and track-covering, at user unlock time. |
| 17 | [iOS 18.4 and iPadOS 18.4](https://support.apple.com/en-us/122371) | 2025-03-31 | Share Sheet | CVE-2025-30438 | Same finding as #18, fixed in iOS and iPadOS. |
| 16 | [tvOS 18.4](https://support.apple.com/en-us/122377) | 2025-03-31 | Share Sheet | CVE-2025-30438 | Same finding as #18, fixed in tvOS. |
| 15 | [visionOS 2.4](https://support.apple.com/en-us/122378) | 2025-03-31 | Share Sheet | CVE-2025-30438 | Same finding as #18, fixed in visionOS. |
| 14 | [watchOS 11.4](https://support.apple.com/en-us/122376) | 2025-04-01 | Share Sheet | CVE-2025-30438 | Same finding as #18, fixed in watchOS. |
| 13 | [macOS Sequoia 15.2](https://support.apple.com/en-us/121839) | 2024-12-11 | WindowServer | CVE-2024-54539 | A malicious sandboxed app without capabilities or permission grants could capture keyboard events from the lock screen. This was a shared credit which was reported independently by two reporters, 11 days apart. My report included the root cause research and a full exploit demonstrating the cause, with a demonstrated simple exfiltration of the logged username and password, along with the user's name, if present, and their IP address. |
| 12 | [macOS Sonoma 14.7.2](https://support.apple.com/en-us/121840) | 2024-12-11 | WindowServer | CVE-2024-54539 | Same finding and shared credit as #13, fixed in Sonoma. |
| 11 | [macOS Ventura 13.7.2](https://support.apple.com/en-us/121842) | 2024-12-11 | WindowServer | CVE-2024-54539 | Same finding and shared credit as #13, fixed in Ventura. |
| 10 | [macOS Sequoia 15.1](https://support.apple.com/en-us/121564) | 2024-10-28 | Screen Sharing Server | CVE-2024-44248 | A standard user with screen sharing access could view the screen of another user who was an admin. |
| 9 | [macOS Sonoma 14.7.2](https://support.apple.com/en-us/121840) | 2024-12-11 | Screen Sharing Server | CVE-2024-44248 | Same finding as #10, fixed in Sonoma. |
| 8 | [macOS Ventura 13.7.2](https://support.apple.com/en-us/121842) | 2024-12-11 | Screen Sharing Server | CVE-2024-44248 | Same finding as #10, fixed in Ventura. |
| 7 | [macOS Sequoia 15](https://support.apple.com/en-us/121238) | 2024-09-16 | Screen Capture | CVE-2024-44137 | Someone with physical access could share items from the lock screen. |
| 6 | [macOS Sonoma 14.7.1](https://support.apple.com/en-us/121570) | 2024-10-28 | Screen Capture | CVE-2024-44137 | Same finding as #7, fixed in Sonoma. |
| 5 | [macOS Ventura 13.7.1](https://support.apple.com/en-us/121568) | 2024-10-28 | Screen Capture | CVE-2024-44137 | Same finding as #7, fixed in Ventura. |
| 4 | [macOS Sequoia 15](https://support.apple.com/en-us/121238) | 2024-09-16 | AppSandbox | CVE-2024-27795 | A camera extension could reach the internet. Related to CVE-2023-41994 (#3). |
| 3 | [macOS Sonoma 14](https://support.apple.com/en-us/120950) | 2023-09-26 | CoreMedia | CVE-2023-41994 | A camera extension could see the camera view of apps it had not been granted permission for. The exploit chain demonstrated persistence, arbitrary starting and stopping of video capture whether another video app was in use or not, a strategy for reducing the noticeability of the camera indicator, a simple remote command-and-control demonstration including switching continuity camera views, and exfiltration without a granted networking capability. |
| 2 | [macOS Ventura 13](https://support.apple.com/en-us/102853) | 2022-10-24 | CoreMedia | CVE-2022-42838 | A camera extension could keep receiving video after the app that activated it had closed. |
| 1 | [macOS Monterey 12.1](https://support.apple.com/en-us/102874) | 2021-12-13 | Security | none | Acknowledgement under "Additional recognition". |
