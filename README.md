# Dolby.io (dolby-io)

Dolby.io (now branded as Dolby OptiView) is Dolby Laboratories' developer platform for media, streaming, communications, and advertising APIs. Originally launched as a hub for Dolby's audio and video processing services (Media APIs, Communications APIs), the platform has consolidated around three OptiView pillars — Real-time Streaming (formerly Millicast), Live Streaming (formerly THEOlive), and Playback (formerly THEOplayer) — with an Advertising pillar built on Server-Guided Ad Insertion. The platform powers live sports streaming for the NFL, NASCAR, Paddy Power, and other large broadcasters, with sub-500ms WebRTC delivery, multi-format ingest (WHIP/WHEP, SRT, RTMP), and cross-platform playback SDKs.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/dolby-io/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Media, Streaming, Real-time Streaming, WebRTC, Live Streaming, Low Latency, Video, Audio, Broadcast, Player, Advertising, Dolby OptiView, Millicast, THEOlive, THEOplayer

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Dolby OptiView Real-time Streaming API

Real-time WebRTC streaming platform (formerly Millicast). Manage publish and subscribe tokens, configure webhook delivery, retrieve account analytics, and discover regional cluster URLs. WHIP/WHEP, SRT, RTMP/RTMPS ingest with H.264, H.265, VP8, VP9, AV1 video and Opus audio. Sub-500ms global latency.

**Human URL:** [https://optiview.dolby.com/docs/millicast/](https://optiview.dolby.com/docs/millicast/)

- [Documentation — Millicast Overview](https://optiview.dolby.com/docs/millicast/)
- [Documentation — Token API](https://optiview.dolby.com/docs/millicast/token-api/)
- [Documentation — Webhooks](https://optiview.dolby.com/docs/millicast/webhooks/)
- [Documentation — Automate with REST APIs](https://optiview.dolby.com/docs/millicast/getting-started/using-rest-apis/)
- [OpenAPI](openapi/dolby-io-realtime-streaming-api-openapi.yml)
- [Naftiko Capability — Publish Tokens](capabilities/realtime-streaming-publish-tokens.yaml)
- [Naftiko Capability — Subscribe Tokens](capabilities/realtime-streaming-subscribe-tokens.yaml)
- [Naftiko Capability — Webhooks](capabilities/realtime-streaming-webhooks.yaml)
- [Naftiko Capability — Analytics](capabilities/realtime-streaming-analytics.yaml)
- [JSON Schema — Publish Token](json-schema/dolby-io-publish-token-schema.json)
- [JSON Schema — Subscribe Token](json-schema/dolby-io-subscribe-token-schema.json)
- [JSON Schema — Webhook](json-schema/dolby-io-webhook-schema.json)
- [JSON-LD Context](json-ld/dolby-io-context.jsonld)

### Dolby OptiView Live (THEOlive) API

Low-latency live streaming API (formerly THEOlive). Programmatic control of Channels, Ingests (RTMP push/pull, SRT, SDI), Engines (transcoding, DRM, overlays, ABR ladders), Distributions (geo-blocking, IP/referrer restrictions, WebRTC delivery), Regions, Webhooks, and Analytics. v2 API at api.theo.live with HTTP Basic auth.

**Human URL:** [https://optiview.dolby.com/docs/theolive/api/](https://optiview.dolby.com/docs/theolive/api/)

- [Documentation — THEOlive Overview](https://optiview.dolby.com/docs/theolive/)
- [Documentation — API Reference](https://optiview.dolby.com/docs/theolive/api/)
- [OpenAPI — Upstream Swagger](https://api.theo.live/v2/api-docs/swagger.json)
- [OpenAPI — Local Copy](openapi/dolby-io-theolive-api-openapi.yml)
- [Naftiko Capability — Channels](capabilities/theolive-channels.yaml)
- [Naftiko Capability — Ingests](capabilities/theolive-ingests.yaml)
- [Naftiko Capability — Engines](capabilities/theolive-engines.yaml)
- [Naftiko Capability — Distributions](capabilities/theolive-distributions.yaml)
- [Naftiko Capability — Webhooks](capabilities/theolive-webhooks.yaml)

### Dolby.io Media API

Legacy Dolby.io Media APIs for cloud audio and video processing. Includes Enhance (noise reduction, leveling, dialog isolation), Analyze (loudness, speech metrics, diagnostics), Transcode (web/mobile output formats), Diagnose (audio quality reporting), and Music Mastering. Migration to the OptiView platform is in progress.

**Human URL:** [https://docs.dolby.io/media-apis/](https://docs.dolby.io/media-apis/)

- [Documentation](https://docs.dolby.io/media-apis/)
- [Postman Workspace](https://www.postman.com/dolbyio/dolby-io-media-apis/overview)

### Dolby.io Communications API

Legacy Communications APIs for high-quality WebRTC voice and video conferencing with spatial audio, music mode, noise suppression, and dial-in/dial-out. Includes Client Access Token, Conference, Recording, Monitor, Mixer Direct, Streaming (RTMP/HLS), and Webhooks services. Generally superseded by the OptiView product line.

**Human URL:** [https://docs.dolby.io/communications-apis/](https://docs.dolby.io/communications-apis/)

- [Documentation](https://docs.dolby.io/communications-apis/)
- [Documentation — Streaming API](https://docs.dolby.io/communications-apis/reference/introduction-to-streaming-api)

### Dolby OptiView Ads API

Server-Guided Ad Insertion (SGAI) for live streaming. The Signaling Service enriches origin manifests with ad-break markers and integrates with Google Ad Manager; the Ad Engine transforms ad formats; the OptiView Player handles client-side ad replacement. Supports Full Screen, Double Box, and L-shape formats.

**Human URL:** [https://optiview.dolby.com/docs/ads/](https://optiview.dolby.com/docs/ads/)

- [Documentation — Ads](https://optiview.dolby.com/docs/ads/)
- [Documentation — Ad Engine](https://optiview.dolby.com/docs/ad-engine/)

### Dolby OptiView Player SDK (THEOplayer)

Cross-platform video player (formerly THEOplayer) with SDKs for Web, Android, iOS & tvOS, React Native, Flutter, Chromecast, and Roku. Supports HLS, MPEG-DASH, DRM, advertising integration, low-latency WebRTC playback, and the Open Video UI component library.

**Human URL:** [https://optiview.dolby.com/docs/theoplayer/](https://optiview.dolby.com/docs/theoplayer/)

- [Documentation — THEOplayer](https://optiview.dolby.com/docs/theoplayer/)
- [Documentation — Open Video UI](https://optiview.dolby.com/docs/open-video-ui/)

## Common Properties

- [Portal — optiview.dolby.com](https://optiview.dolby.com)
- [Portal — dolby.io](https://dolby.io)
- [Documentation — OptiView Docs](https://optiview.dolby.com/docs/)
- [Documentation — Legacy docs.dolby.io](https://docs.dolby.io/)
- [GettingStarted](https://optiview.dolby.com/docs/millicast/getting-started/)
- [SignUp — Streaming Dashboard](https://streaming.dolby.io)
- [StatusPage](https://status.dolby.io)
- [Pricing](https://optiview.dolby.com/plans/)
- [Blog](https://dolby.io/blog/)
- [PrivacyPolicy](https://www.dolby.com/about/legal/privacy-policy/)
- [TermsOfService](https://www.dolby.com/about/legal/terms-of-service-for-dolby-io/)
- [TrustCenter](https://trust.dolby.com/)
- [GitHubOrganization — dolbyio](https://github.com/dolbyio)
- [GitHubOrganization — dolbyio-samples](https://github.com/dolbyio-samples)
- [SDK — REST APIs Client for Node.js](https://github.com/dolbyio/dolbyio-rest-apis-client-node)
- [SDK — REST APIs Client for Python](https://github.com/dolbyio/dolbyio-rest-apis-client-python)
- [SDK — REST APIs Client for .NET](https://github.com/dolbyio/dolbyio-rest-apis-client-dotnet)
- [SDK — Real-time Streaming UIKit for iOS](https://github.com/dolbyio/rts-uikit-ios)
- [Tool — WebRTC Stats Parser](https://github.com/dolbyio/web-webrtc-stats)
- [CodeExamples — Dolby.io Samples](https://github.com/dolbyio-samples)
- [CodeExamples — WHIP/WHEP Node Sample](https://github.com/dolbyio-samples/streaming-WHIP-WHEP-node-sample)
- [CodeExamples — Streaming Webhook Thumbnails](https://github.com/dolbyio-samples/streaming-webhook-thumbnails)
- [CodeExamples — 4K Low-Latency WebRTC Streaming App](https://github.com/dolbyio-samples/stream-app-web-viewer)
- [Tools — Awesome Audio](https://github.com/dolbyio/awesome-audio)
- [Forum — GitHub Discussions](https://github.com/orgs/dolbyio/discussions)
- [Webhooks](https://optiview.dolby.com/docs/millicast/webhooks/)
- [ChangeLog](https://optiview.dolby.com/docs/release-notes/)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Dolby OptiView Real-time Streaming API](openapi/dolby-io-realtime-streaming-api-openapi.yml)
- [Dolby OptiView Live (THEOlive) API](openapi/dolby-io-theolive-api-openapi.yml)

### JSON Schema

- [Publish Token](json-schema/dolby-io-publish-token-schema.json)
- [Subscribe Token](json-schema/dolby-io-subscribe-token-schema.json)
- [Webhook](json-schema/dolby-io-webhook-schema.json)

### JSON-LD

- [Dolby.io Context](json-ld/dolby-io-context.jsonld)

### Naftiko Capabilities

- [Real-time Streaming — Publish Tokens](capabilities/realtime-streaming-publish-tokens.yaml)
- [Real-time Streaming — Subscribe Tokens](capabilities/realtime-streaming-subscribe-tokens.yaml)
- [Real-time Streaming — Webhooks](capabilities/realtime-streaming-webhooks.yaml)
- [Real-time Streaming — Analytics](capabilities/realtime-streaming-analytics.yaml)
- [OptiView Live — Channels](capabilities/theolive-channels.yaml)
- [OptiView Live — Ingests](capabilities/theolive-ingests.yaml)
- [OptiView Live — Engines](capabilities/theolive-engines.yaml)
- [OptiView Live — Distributions](capabilities/theolive-distributions.yaml)
- [OptiView Live — Webhooks](capabilities/theolive-webhooks.yaml)

### Examples

- [Create Publish Token](examples/dolby-io-create-publish-token-example.json)
- [Create Subscribe Token](examples/dolby-io-create-subscribe-token-example.json)
- [Create Webhook](examples/dolby-io-create-webhook-example.json)

### Vocabulary

- [Dolby.io Vocabulary](vocabulary/dolby-io-vocabulary.yml)

### Spectral Rules

- [Dolby.io Spectral Rules](rules/dolby-io-rules.yml)

### Plans, Rate Limits & FinOps

- [Plans & Pricing](plans/dolby-io-plans-pricing.yml)
- [Rate Limits](rate-limits/dolby-io-rate-limits.yml)
- [FinOps](finops/dolby-io-finops.yml)

## Features

- OptiView Real-time Streaming (Millicast) — sub-500ms WebRTC streaming to 100k+ viewers
- WHIP and WHEP protocol support for standards-based publish and playback
- Multi-protocol ingest — WebRTC, SRT, RTMP, RTMPS
- Video codec support — H.264, H.265, VP8, VP9, AV1; Opus audio
- Publish and Subscribe token APIs with regex stream names, geo restrictions, IP binding
- Webhooks for feeds, recordings, thumbnails, transcoders, and viewer connections (HMAC-SHA1 signed)
- Account-level analytics — publish minutes, viewer minutes, bytes transferred
- OptiView Live (THEOlive) — live channels with low latency, Nielsen tracking, DRM, server-side ads
- Channels, Ingests, Engines, Distributions resource model with full REST and GraphQL surfaces
- Server-Guided Ad Insertion (SGAI) with Google Ad Manager integration
- OptiView Player SDKs — Web, Android, iOS/tvOS, React Native, Flutter, Chromecast, Roku
- Open Video UI component library for player customization
- Legacy Media APIs — Enhance, Analyze, Transcode, Diagnose, Music Mastering
- Legacy Communications APIs — WebRTC conferencing, spatial audio, recording, RTMP/HLS streaming
- Official REST API client SDKs for Node.js, Python, and .NET
- Region presence across US East/West, Europe, Asia-Pacific, and South America
- Bearer-token authentication via per-account API Secrets
- Status page tracking core services and regional infrastructure

## Maintainers

- **Kin Lane** — info@apievangelist.com — [apievangelist.com](https://apievangelist.com)

## Position

Consuming

## Specification

apis.yml `0.16`
