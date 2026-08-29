# Rennan Ribeiro

Founder of [Moviie](https://moviie.ai): video infrastructure for creators and course
businesses. Hosting, adaptive streaming, a white-label player, AI dubbing, captions,
chapters and clips, and first-party analytics, in one platform.

Most of my work is on the player. Moviie ships three playback surfaces from a single
API contract: an embeddable web player, a native React player, and a React Native /
Expo player. In practice that means living with HLS alternate-audio renditions for
dubbed tracks, dynamically generated manifests, DRM, subtitle and chapter tracks, and
the distance between what MSE does and what AVPlayer does with the same stream.

### Packages

| Package | What it is |
| --- | --- |
| [`@moviie/player-react`](https://www.npmjs.com/package/@moviie/player-react) | The Moviie player for the web (React DOM) |
| [`@moviie/player-expo`](https://www.npmjs.com/package/@moviie/player-expo) | The Moviie player for Expo / React Native |
| [`@moviie/player-sdk`](https://www.npmjs.com/package/@moviie/player-sdk) | Vendor-agnostic SDK: playback metadata, HTTP client, telemetry |
| [`@moviie/player-types`](https://www.npmjs.com/package/@moviie/player-types) | The public Player API contract, shared by every surface |

[moviie.ai](https://moviie.ai) · [API docs](https://docs.moviie.ai) · [React player demo](https://github.com/moviie-ai/player-react-demo)
