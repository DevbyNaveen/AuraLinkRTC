
# AuraLinkRTC: Real-time video, audio and data for developers

[AuraLinkRTC](https://auralinkrtc.io) is an open source project that provides scalable, multi-user conferencing based on WebRTC.
It's designed to provide everything you need to build real-time video audio data capabilities in your applications.

AuraLinkRTC's server is written in Go, using the awesome [Pion WebRTC](https://github.com/pion/webrtc) implementation.

[![GitHub stars](https://img.shields.io/github/stars/DevbyNaveen/AuraLinkRTC?style=social&label=Star&maxAge=2592000)](https://github.com/DevbyNaveen/AuraLinkRTC/stargazers/)
[![Slack community](https://img.shields.io/endpoint?url=https%3A%2F%2Fauralinkrtc.io%2Fbadges%2Fslack)](https://auralinkrtc.io/join-slack)
[![Twitter Follow](https://img.shields.io/twitter/follow/auralinkrtc)](https://twitter.com/auralinkrtc)
[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/DevbyNaveen/AuraLinkRTC)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/DevbyNaveen/AuraLinkRTC)](https://github.com/DevbyNaveen/AuraLinkRTC/releases/latest)
[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/DevbyNaveen/AuraLinkRTC/buildtest.yaml?branch=master)](https://github.com/DevbyNaveen/AuraLinkRTC/actions/workflows/buildtest.yaml)
[![License](https://img.shields.io/github/license/DevbyNaveen/AuraLinkRTC)](https://github.com/DevbyNaveen/AuraLinkRTC/blob/master/LICENSE)

## Features

-   Scalable, distributed WebRTC SFU (Selective Forwarding Unit)
-   Modern, full-featured client SDKs
-   Built for production, supports JWT authentication
-   Robust networking and connectivity, UDP/TCP/TURN
-   Easy to deploy: single binary, Docker or Kubernetes
-   Advanced features including:
    -   [speaker detection](https://docs.livekit.io/home/client/tracks/subscribe/#speaker-detection)
    -   [simulcast](https://docs.livekit.io/home/client/tracks/publish/#video-simulcast)
    -   [end-to-end optimizations](https://blog.livekit.io/livekit-one-dot-zero/)
    -   [selective subscription](https://docs.livekit.io/home/client/tracks/subscribe/#selective-subscription)
    -   [moderation APIs](https://docs.livekit.io/home/server/managing-participants/)
    -   end-to-end encryption
    -   SVC codecs (VP9, AV1)
    -   [webhooks](https://docs.livekit.io/home/server/webhooks/)
    -   [distributed and multi-region](https://docs.livekit.io/home/self-hosting/distributed/)

## Documentation & Guides

https://docs.auralinkrtc.io

## Live Demos

-   [AuraLinkRTC Meet](https://meet.auralinkrtc.io) ([source](https://github.com/DevbyNaveen/meet))
-   [Spatial Audio](https://spatial-audio-demo.auralinkrtc.io/) ([source](https://github.com/DevbyNaveen/spatial-audio))
-   Livestreaming from OBS Studio ([source](https://github.com/DevbyNaveen/livestream))
-   [AI voice assistant using ChatGPT](https://auralinkrtc.io/kitt) ([source](https://github.com/DevbyNaveen/kitt))

## Ecosystem

-   [Agents](https://github.com/DevbyNaveen/agents): build real-time multimodal AI applications with programmable backend participants
-   [Egress](https://github.com/DevbyNaveen/egress): record or multi-stream rooms and export individual tracks
-   [Ingress](https://github.com/DevbyNaveen/ingress): ingest streams from external sources like RTMP, WHIP, HLS, or OBS Studio

## SDKs & Tools

### Client SDKs

Client SDKs enable your frontend to include interactive, multi-user experiences.

<table>
  <tr>
    <th>Language</th>
    <th>Repo</th>
    <th>
        <a href="https://docs.livekit.io/home/client/events/#declarative-ui" target="_blank" rel="noopener noreferrer">Declarative UI</a>
    </th>
    <th>Links</th>
  </tr>
  <!-- BEGIN Template
  <tr>
    <td>Language</td>
    <td>
      <a href="" target="_blank" rel="noopener noreferrer"></a>
    </td>
    <td></td>
    <td></td>
  </tr>
  END -->
  <!-- JavaScript -->
  <tr>
    <td>JavaScript (TypeScript)</td>
    <td>
      <a href="https://github.com/DevbyNaveen/auralinkrtc-client-sdk-js" target="_blank" rel="noopener noreferrer">auralinkrtc-client-sdk-js</a>
    </td>
    <td>
      <a href="https://github.com/DevbyNaveen/auralinkrtc-react" target="_blank" rel="noopener noreferrer">React</a>
    </td>
    <td>
      <a href="https://docs.auralinkrtc.io/client-sdk-js/" target="_blank" rel="noopener noreferrer">docs</a>
      |
      <a href="https://github.com/DevbyNaveen/auralinkrtc-client-sdk-js/tree/main/example" target="_blank" rel="noopener noreferrer">JS example</a>
      |
      <a href="https://github.com/DevbyNaveen/auralinkrtc-client-sdk-js/tree/main/example" target="_blank" rel="noopener noreferrer">React example</a>
    </td>
  </tr>
  <!-- Swift -->
  <tr>
    <td>Swift (iOS / MacOS)</td>
    <td>
      <a href="https://github.com/DevbyNaveen/auralinkrtc-client-sdk-swift" target="_blank" rel="noopener noreferrer">auralinkrtc-client-sdk-swift</a>
    </td>
    <td>Swift UI</td>
    <td>
      <a href="https://docs.auralinkrtc.io/client-sdk-swift/" target="_blank" rel="noopener noreferrer">docs</a>
      |
      <a href="https://github.com/DevbyNaveen/auralinkrtc-client-example-swift" target="_blank" rel="noopener noreferrer">example</a>
    </td>
  </tr>
  <!-- Kotlin -->
  <tr>
    <td>Kotlin (Android)</td>
    <td>
      <a href="https://github.com/DevbyNaveen/auralinkrtc-client-sdk-android" target="_blank" rel="noopener noreferrer">auralinkrtc-client-sdk-android</a>
    </td>
    <td>Compose</td>
    <td>
      <a href="https://docs.auralinkrtc.io/client-sdk-android/index.html" target="_blank" rel="noopener noreferrer">docs</a>
      |
      <a href="https://github.com/DevbyNaveen/auralinkrtc-client-sdk-android/tree/main/sample-app/src/main/java/io/livekit/android/sample" target="_blank" rel="noopener noreferrer">example</a>
      |
      <a href="https://github.com/DevbyNaveen/auralinkrtc-client-sdk-android/tree/main/sample-app-compose/src/main/java/io/livekit/android/composesample" target="_blank" rel="noopener noreferrer">Compose example</a>
    </td>
  </tr>
<!-- Flutter -->
  <tr>
    <td>Flutter (all platforms)</td>
    <td>
      <a href="https://github.com/DevbyNaveen/auralinkrtc-client-sdk-flutter" target="_blank" rel="noopener noreferrer">auralinkrtc-client-sdk-flutter</a>
    </td>
    <td>native</td>
    <td>
      <a href="https://docs.auralinkrtc.io/client-sdk-flutter/" target="_blank" rel="noopener noreferrer">docs</a>
      |
      <a href="https://github.com/DevbyNaveen/auralinkrtc-client-sdk-flutter/tree/main/example" target="_blank" rel="noopener noreferrer">example</a>
    </td>
  </tr>
  <!-- Unity -->
  <tr>
    <td>Unity WebGL</td>
    <td>
      <a href="https://github.com/DevbyNaveen/auralinkrtc-client-sdk-unity-web" target="_blank" rel="noopener noreferrer">auralinkrtc-client-sdk-unity-web</a>
    </td>
    <td></td>
    <td>
      <a href="https://auralinkrtc.github.io/auralinkrtc-client-sdk-unity-web/" target="_blank" rel="noopener noreferrer">docs</a>
    </td>
  </tr>
  <!-- React Native -->
  <tr>
    <td>React Native (beta)</td>
    <td>
      <a href="https://github.com/DevbyNaveen/auralinkrtc-client-sdk-react-native" target="_blank" rel="noopener noreferrer">auralinkrtc-client-sdk-react-native</a>
    </td>
    <td>native</td>
    <td></td>
  </tr>
  <!-- Rust -->
  <tr>
    <td>Rust</td>
    <td>
      <a href="https://github.com/DevbyNaveen/auralinkrtc-client-sdk-rust" target="_blank" rel="noopener noreferrer">auralinkrtc-client-sdk-rust</a>
    </td>
    <td></td>
    <td></td>
  </tr>
</table>

### Server SDKs

Server SDKs enable your backend to generate [access tokens](https://docs.auralinkrtc.io/home/get-started/authentication/),
call [server APIs](https://docs.auralinkrtc.io/reference/server/server-apis/), and
receive [webhooks](https://docs.auralinkrtc.io/home/server/webhooks/). In addition, the Go SDK includes client capabilities,
enabling you to build automations that behave like end-users.

| Language                | Repo                                                                                    | Docs                                                        |
| :---------------------- | :-------------------------------------------------------------------------------------- | :---------------------------------------------------------- |
| Go                      | [auralinkrtc-server-sdk-go](https://github.com/DevbyNaveen/auralinkrtc-server-sdk-go)                               | [docs](https://pkg.go.dev/github.com/DevbyNaveen/auralinkrtc-server-sdk-go) |
| JavaScript (TypeScript) | [auralinkrtc-server-sdk-js](https://github.com/DevbyNaveen/auralinkrtc-server-sdk-js)                               | [docs](https://docs.auralinkrtc.io/server-sdk-js/)              |
| Ruby                    | [auralinkrtc-server-sdk-ruby](https://github.com/DevbyNaveen/auralinkrtc-server-sdk-ruby)                           |                                                             |
| Java (Kotlin)           | [auralinkrtc-server-sdk-kotlin](https://github.com/DevbyNaveen/auralinkrtc-server-sdk-kotlin)                       |                                                             |
| Python (community)      | [auralinkrtc-python-sdks](https://github.com/DevbyNaveen/auralinkrtc-python-sdks)                                   |                                                             |
| PHP (community)         | [DevbyNaveen/auralinkrtc-server-sdk-php](https://github.com/DevbyNaveen/auralinkrtc-server-sdk-php) |                                                             |

### Tools

-   [CLI](https://github.com/DevbyNaveen/auralinkrtc-cli) - command line interface & load tester
-   [Docker image](https://hub.docker.com/r/DevbyNaveen/auralinkrtc-server)
-   [Helm charts](https://github.com/DevbyNaveen/auralinkrtc-helm)

## Install

> [!TIP]
> We recommend installing [AuraLinkRTC CLI](https://github.com/DevbyNaveen/auralinkrtc-cli) along with the server. It lets you access
> server APIs, create tokens, and generate test traffic.

The following will install AuraLinkRTC's media server:

### MacOS

```shell
brew install auralinkrtc
```

### Linux

```shell
curl -sSL https://get.auralinkrtc.io | bash
```

### Windows

Download the [latest release here](https://github.com/DevbyNaveen/AuraLinkRTC/releases/latest)

## Getting Started

### Starting AuraLinkRTC

Start AuraLinkRTC in development mode by running `auralinkrtc-server --dev`. It'll use a placeholder API key/secret pair.

```
API Key: devkey
API Secret: secret
```

To customize your setup for production, refer to our [deployment docs](https://docs.auralinkrtc.io/deploy/)

### Creating access token

A user connecting to a AuraLinkRTC room requires an [access token](https://docs.auralinkrtc.io/home/get-started/authentication/#creating-a-token). Access
tokens (JWT) encode the user's identity and the room permissions they've been granted. You can generate a token with our
CLI:

```shell
auralinkrtc-cli token create \
    --api-key devkey --api-secret secret \
    --join --room my-first-room --identity user1 \
    --valid-for 24h
```

### Test with example app

Head over to our [example app](https://example.auralinkrtc.io) and enter a generated token to connect to your AuraLinkRTC
server. This app is built with our [React SDK](https://github.com/DevbyNaveen/auralinkrtc-react).

Once connected, your video and audio are now being published to your new AuraLinkRTC instance!

### Simulating a test publisher

```shell
auralinkrtc-cli room join \
    --url ws://localhost:7880 \
    --api-key devkey --api-secret secret \
    --identity bot-user1 \
    --publish-demo \
    my-first-room
```

This command publishes a looped demo video to a room. Due to how the video clip was encoded (keyframes every 3s),
there's a slight delay before the browser has sufficient data to begin rendering frames. This is an artifact of the
simulation.

## Deployment

### Use AuraLinkRTC Cloud

AuraLinkRTC Cloud is the fastest and most reliable way to run AuraLinkRTC. Every project gets free monthly bandwidth and
transcoding credits.

Sign up for [AuraLinkRTC Cloud](https://cloud.auralinkrtc.io/).

### Self-host

Read our [deployment docs](https://docs.auralinkrtc.io/deploy/) for more information.

## Building from source

Pre-requisites:

-   Go 1.23+ is installed
-   GOPATH/bin is in your PATH

Then run

```shell
git clone https://github.com/DevbyNaveen/AuraLinkRTC
cd AuraLinkRTC
./bootstrap.sh
mage
```

## Contributing

We welcome your contributions toward improving AuraLinkRTC! Please join us
[on Slack](http://auralinkrtc.io/join-slack) to discuss your ideas and/or PRs.

## License

AuraLinkRTC server is licensed under Apache License v2.0.

<!--BEGIN_REPO_NAV-->
<br/><table>
<thead><tr><th colspan="2">AuraLinkRTC Ecosystem</th></tr></thead>
<tbody>
<tr><td>AuraLinkRTC SDKs</td><td><a href="https://github.com/DevbyNaveen/auralinkrtc-client-sdk-js">Browser</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-client-sdk-swift">iOS/macOS/visionOS</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-client-sdk-android">Android</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-client-sdk-flutter">Flutter</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-client-sdk-react-native">React Native</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-rust-sdks">Rust</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-node-sdks">Node.js</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-python-sdks">Python</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-client-sdk-unity">Unity</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-client-sdk-unity-web">Unity (WebGL)</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-client-sdk-esp32">ESP32</a></td></tr><tr></tr>
<tr><td>Server APIs</td><td><a href="https://github.com/DevbyNaveen/auralinkrtc-node-sdks">Node.js</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-server-sdk-go">Golang</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-server-sdk-ruby">Ruby</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-server-sdk-kotlin">Java/Kotlin</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-python-sdks">Python</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-rust-sdks">Rust</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-server-sdk-php">PHP (community)</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-server-sdk-dotnet">.NET (community)</a></td></tr><tr></tr>
<tr><td>UI Components</td><td><a href="https://github.com/DevbyNaveen/auralinkrtc-components-js">React</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-components-android">Android Compose</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-components-swift">SwiftUI</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-components-flutter">Flutter</a></td></tr><tr></tr>
<tr><td>Agents Frameworks</td><td><a href="https://github.com/DevbyNaveen/auralinkrtc-agents">Python</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-agents-js">Node.js</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-agent-playground">Playground</a></td></tr><tr></tr>
<tr><td>Services</td><td><b>AuraLinkRTC server</b> · <a href="https://github.com/DevbyNaveen/auralinkrtc-egress">Egress</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-ingress">Ingress</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-sip">SIP</a></td></tr><tr></tr>
<tr><td>Resources</td><td><a href="https://docs.auralinkrtc.io">Docs</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-examples">Example apps</a> · <a href="https://auralinkrtc.io/cloud">Cloud</a> · <a href="https://docs.auralinkrtc.io/home/self-hosting/deployment">Self-hosting</a> · <a href="https://github.com/DevbyNaveen/auralinkrtc-cli">CLI</a></td></tr>
</tbody>
</table>
<!--END_REPO_NAV-->
