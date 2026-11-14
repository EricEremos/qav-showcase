<p align="center"><strong>QAV</strong></p>

<h1 align="center">Measure the line.<br>Straighten what's yours.</h1>

<p align="center">A Mac menu bar app that reads your whole connection as one line, fixes the parts this Mac can fix, and checks every fix on and off.</p>

<p align="center"><a href="#one-line-from-this-mac-to-the-web">See how it works</a> · <a href="#development-status">Development status</a></p>

<p align="center"><a href="assets/qav-promo-20261114.mp4"><img src="assets/qav-promo-20261114.gif" alt="Qav film: in the dark, the app's own opening straightens a tangled cord with its amber lamp until one loop is left. The menu bar panel reads Slow, with the loop at the provider. Fixing: sending calls first; the loop unties and the whole line lights. Fixed: 240 to 24 ms. The Fixes table shows what was kept and what turned itself off, and the cap row says what is not this Mac's to fix. It ends on qav. with its lamp: Qav means line." width="100%"></a></p>

<p align="center"><sub>Every picture in the film is drawn by Qav itself from its newest code (10 November 2026), with the app's built-in sample data; the figures are sample readings, not a measurement of a real line.</sub><br><a href="assets/qav-promo-20261114.mp4">Watch the full film</a> · <a href="assets/qav-promo-20261114-poster.png">Still frame</a> · <a href="assets/qav-promo-20261114-manifest.json">Capture details</a></p>

## One line, from this Mac to the web

**This Mac → Wi-Fi → router → provider → VPN → internet**

Qav reads the connection as one line and shows where it bends. A bend is a loop in shadow; a handled stretch runs straight and lit. The verdict is one word and a lamp: *Fine.* *Slow.* *Fixed.*

<p align="center">
  <img src="assets/qav-panel-slow-20261114.png" width="300" alt="Qav's menu bar panel: Slow. Studio Wi-Fi. The line from This Mac to the internet with a loop at the provider. At Provider, latency 240 ms: 18 ms without a download, 240 ms during one. Downloads line up ahead of your calls, so calls wait. Fix now turns on Calls first; you can undo it any time." />
  &nbsp;&nbsp;
  <img src="assets/qav-panel-fixed-20261114.png" width="300" alt="Qav's menu bar panel after the fix: Fixed. The whole line lit. Downloads no longer hold up your calls. 240 to 24 ms. Undo, See results." />
</p>

<p align="center"><sub>The menu bar panel before and after one fix, drawn by the app with its sample data.</sub></p>

## Straighten what's yours

Qav fixes only what is on this Mac, and each fix can be undone:

| Fix | What it does |
|---|---|
| **Speed limit** | Holds this Mac's traffic just under the plan's cap, so the queue stays short and on this Mac. |
| **Calls first** | Keeps the queue short and gives calls and video a small lane of their own. |
| **DNS repair** | Sends only the names your network misroutes to another resolver. |
| **Pause AirDrop** | Pauses the radio that makes Wi-Fi hop channels while it is on. |
| **Use iPhone data** | Sends this Mac's traffic over a USB iPhone, up to a daily limit. |

## Every fix is checked, on and off

**Proof** measures each fix off and on, on your Mac. A fix that does not help turns itself off, and Qav says so.

<p align="center"><img src="assets/qav-fixes-20261114.png" width="100%" alt="Qav's Fixes window: five ways Qav fixes what's on this Mac, each checked on and off. Speed limit, packet loss 8 to 0.6 percent, kept, it helps here. Calls first, lag under load 410 to 160 ms, kept. DNS repair, misrouted names 3 to 0, off. Pause AirDrop, slowest Wi-Fi replies 31 to 29 ms, turned off here: it didn't help; Qav tries it again 30 Oct. Use iPhone data needs an iPhone sharing its connection."></p>

<p align="center"><sub>The Fixes window, drawn by the app with its sample data.</sub></p>

## Be honest about the rest

What Qav measures but cannot fix, such as a plan's cap or loss inside the provider's network, is listed plainly. Qav does not make a plan faster than it is; it removes what wastes the speed you already have.

## Development status

Qav is in development. A public download is not available here, and its implementation and local connection records remain private.

<details>
<summary>About the film and the screens</summary>

The film and the screens on this page were rendered on 14 November 2026 by Qav's own snapshot mode and its own line renderer, built from its newest code (10 November 2026), using the sample data the app ships for design checks. The film adds only the dark ground, its lines and the amber rings. No real connection was measured for this page.

</details>

---

[More projects by Hyunjun Kim](https://github.com/EricEremos) · [Get in touch](https://www.linkedin.com/in/ericmos/)
