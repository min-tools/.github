<p align="center">
  <a href="https://min.tools/"><img src="https://raw.githubusercontent.com/min-tools/.github/main/profile/images/min-tools.png" width="128" alt="Min Tools icon"></a>
</p>

<h1 align="center">Min Tools</h1>

<p align="center"><strong>Apps that keep to themselves.</strong></p>

<p align="center">
  Min Tools is a collection of focused apps built to feel at home on the Mac.<br>
  Each one is written in Swift, runs in the App Sandbox, and has its source on GitHub. No Min&nbsp;Tools accounts, analytics, or servers.
</p>

<p align="center">
  <a href="https://min.tools/">Website</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="https://min.tools/#apps">Apps</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="https://min.tools/#source">Source</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="https://min.tools/#privacy">Privacy</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="https://min.tools/#contribute">Contribute</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/macOS-14%2B-000000?logo=apple&logoColor=white" alt="macOS 14 or later">
  <img src="https://img.shields.io/badge/Apple%20silicon-native-000000?logo=apple&logoColor=white" alt="Apple silicon native">
  <img src="https://img.shields.io/badge/built%20with-Swift-F05138?logo=swift&logoColor=white" alt="Built with Swift">
  <img src="https://img.shields.io/badge/privacy-no%20tracking-6f42c1" alt="No tracking">
  <img src="https://img.shields.io/badge/source-available-2ea44f" alt="Source available">
</p>

## Current apps

<table>
  <tr>
    <td width="33%" align="center">
      <a href="https://min.tools/langmin/"><img src="https://raw.githubusercontent.com/min-tools/.github/main/profile/images/langmin.png" width="88" alt="Langmin icon"></a>
      <h3>Langmin</h3>
      <p>Your language assistant for the whole Mac.</p>
      <p>Proofread, rewrite, explain, summarize, translate, and look words up from any app. Work with recordings, documents, and screenshots using Apple Intelligence on device or your own provider key.</p>
      <p><a href="https://min.tools/langmin/">Website</a> · <a href="https://github.com/min-tools/langmin-macos">Source</a></p>
    </td>
    <td width="33%" align="center">
      <a href="https://min.tools/pastemin/"><img src="https://raw.githubusercontent.com/min-tools/.github/main/profile/images/pastemin.png" width="88" alt="Pastemin icon"></a>
      <h3>Pastemin</h3>
      <p>Your clipboard, ready when you need it.</p>
      <p>Keep a searchable history of copied text and images. Open it from any app, find an earlier item, and put it back on the clipboard in a few keystrokes.</p>
      <p><a href="https://min.tools/pastemin/">Website</a> · <a href="https://github.com/min-tools/pastemin-macos">Source</a></p>
    </td>
    <td width="33%" align="center">
      <a href="https://min.tools/netmin/"><img src="https://raw.githubusercontent.com/min-tools/.github/main/profile/images/netmin.png" width="88" alt="Netmin icon"></a>
      <h3>Netmin</h3>
      <p>Network answers without the terminal.</p>
      <p>Inspect DNS, routing, local devices, mail, TLS, websites, and ports with 84 tools, readable overviews, and the raw output beside them.</p>
      <p><a href="https://min.tools/netmin/">Website</a> · <a href="https://github.com/min-tools/netmin-macos">Source</a></p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="33%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/min-tools/.github/main/profile/images/langmin-hero-dark.png">
        <img src="https://raw.githubusercontent.com/min-tools/.github/main/profile/images/langmin-hero-light.png" alt="Langmin in Explain mode with its editor, result pane, and six language tools.">
      </picture>
    </td>
    <td width="33%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/min-tools/.github/main/profile/images/pastemin-hero-dark.png">
        <img src="https://raw.githubusercontent.com/min-tools/.github/main/profile/images/pastemin-hero-light.png" alt="Pastemin showing searchable clipboard history and a copied item preview.">
      </picture>
    </td>
    <td width="33%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/min-tools/.github/main/profile/images/netmin-hero-dark.png">
        <img src="https://raw.githubusercontent.com/min-tools/.github/main/profile/images/netmin-hero-light.png" alt="Netmin showing its network tools and a readable Network Lookup report.">
      </picture>
    </td>
  </tr>
</table>

## Designed around your Mac

| | |
| --- | --- |
| **Native and sandboxed** | These apps use Swift, AppKit, and SwiftUI. They run in the App Sandbox with Hardened Runtime and need no administrator access. |
| **Keyboard first** | Langmin and Pastemin open from other apps. Netmin lets you find tools and run checks without leaving the keyboard. |
| **No Min Tools account** | None requires an account with Min Tools or contains analytics or advertising trackers. |
| **Local by default** | Pastemin keeps clipboard history on your Mac. Langmin stores provider keys in Keychain. Netmin keeps complete diagnostic output in memory unless you export it. |
| **Connections stay explicit** | Langmin connects to providers and websites you choose. Netmin contacts the targets and lookup services required by each check. Pastemin never uploads clipboard history. |
| **Localized** | Langmin supports 30 interface languages, Pastemin 31, and Netmin 27. |

## Source you can inspect

Their public repositories contain the app source, tests, translations, privacy policies, and supporting documentation. Bug reports, translations, reviews, and focused pull requests are welcome.

These repositories use the [PolyForm Strict License 1.0.0](https://polyformproject.org/licenses/strict/1.0.0/) with added permissions for personal modification and contributions. You may inspect, build, and run the code for noncommercial purposes, modify it for your own personal noncommercial use, and prepare contributions for the official repositories. Redistribution is not permitted. The license does not grant rights to the Min Tools or app names, trademarks, logos, or app icons.

| Repository | What it holds |
| --- | --- |
| [langmin-macos](https://github.com/min-tools/langmin-macos) | Langmin for macOS, its documentation, privacy policy, tests, and translations. |
| [pastemin-macos](https://github.com/min-tools/pastemin-macos) | Pastemin for macOS, its documentation, privacy policy, tests, and translations. |
| [netmin-macos](https://github.com/min-tools/netmin-macos) | Netmin for macOS, its documentation, privacy policy, tests, translations, and command templates. |

## Requirements and support

See each app page for current system requirements, permissions, and network use. The macOS versions of Langmin, Pastemin, and Netmin currently require an Apple-silicon Mac running macOS 14 or later. Some Langmin features require newer macOS versions, an enabled Apple feature, or an account with the provider you choose.

| App | Help | Issues | Privacy |
| --- | --- | --- | --- |
| Langmin for macOS | [Support](https://min.tools/langmin/support/) | [Report a problem](https://github.com/min-tools/langmin-macos/issues) | [Privacy policy](https://min.tools/langmin/privacy/) |
| Pastemin for macOS | [Support](https://min.tools/pastemin/support/) | [Report a problem](https://github.com/min-tools/pastemin-macos/issues) | [Privacy policy](https://min.tools/pastemin/privacy/) |
| Netmin for macOS | [Support](https://min.tools/netmin/support/) | [Report a problem](https://github.com/min-tools/netmin-macos/issues) | [Privacy policy](https://min.tools/netmin/privacy/) |

<p align="center">Made by <a href="https://github.com/iliaross">Ilia Ross</a>.</p>
