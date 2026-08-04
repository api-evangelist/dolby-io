# Dolby.io (dolby-io)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Dolby.io (now branded as Dolby OptiView) is Dolby Laboratories' developer platform for media, streaming, communications, and advertising APIs. Originally launched as a hub for Dolby's audio and video processing services (Media APIs, Communications APIs), the platform has consolidated around three OptiView pillars — Real-time Streaming (formerly Millicast), Live Streaming (formerly THEOlive), and Playback (formerly THEOplayer) — with an Advertising pillar built on Server-Guided Ad Insertion. The platform powers live sports streaming for the NFL, NASCAR, Paddy Power, and other large broadcasters, with sub-500ms WebRTC delivery, multi-format ingest (WHIP/WHEP, SRT, RTMP), and cross-platform playback SDKs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dolby-io/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dolby-io/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Media
- Streaming
- Real-time Streaming
- WebRTC
- Live Streaming
- Low Latency
- Video
- Audio
- Broadcast
- Player
- Advertising
- Dolby OptiView
- Millicast
- THEOlive
- THEOplayer

## Timestamps

- **Created:** 2026-05-25T00:00:00.000Z
- **Modified:** 2026-05-25

## APIs

### Dolby OptiView Real-time Streaming API

Real-time WebRTC streaming platform (formerly Millicast). Manage publish and subscribe tokens, configure webhook delivery for feeds, recordings, thumbnails, transcoders, and viewer connections, retrieve account analytics, and discover regional cluster URLs. Supports WHIP/WHEP, SRT, RTMP/RTMPS ingest with H.264, H.265, VP8, VP9, AV1 video and Opus audio. Sub-500ms latency to global audiences at scale.

- **Human URL:** [https://optiview.dolby.com/docs/millicast/](https://optiview.dolby.com/docs/millicast/)

#### Tags

- Real-time Streaming
- WebRTC
- WHIP
- WHEP
- Live Streaming
- Low Latency
- Tokens
- Webhooks
- Analytics

#### Properties

- [Documentation](https://optiview.dolby.com/docs/millicast/)
- [Documentation](https://optiview.dolby.com/docs/millicast/token-api/)
- [Documentation](https://optiview.dolby.com/docs/millicast/webhooks/)
- [Documentation](https://optiview.dolby.com/docs/millicast/getting-started/using-rest-apis/)
- [OpenAPI](openapi/dolby-io-realtime-streaming-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dolby-io-realtime-streaming-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dolby-io-realtime-streaming-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/dolby-io-publish-token-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/dolby-io-subscribe-token-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/dolby-io-webhook-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/dolby-io-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Dolby OptiView Live (THEOlive) API

Low-latency live streaming API (formerly THEOlive). Programmatic control of Channels, Ingests (RTMP push/pull, SRT, SDI), Engines (transcoding, DRM, overlays, ABR ladders), Distributions (geo-blocking, IP/referrer restrictions, WebRTC delivery), Regions, Webhooks (30+ event types with delivery logs), and Analytics (transcoding minutes, viewing minutes, bytes transferred, browser/country breakdowns). Supports Nielsen tracking, server-side ads, DRM, and DVR. v2 API published at api.theo.live with HTTP Basic auth.

- **Human URL:** [https://optiview.dolby.com/docs/theolive/api/](https://optiview.dolby.com/docs/theolive/api/)

#### Tags

- Live Streaming
- Low Latency
- Channels
- Transcoding
- DRM
- Webhooks
- Analytics

#### Properties

- [Documentation](https://optiview.dolby.com/docs/theolive/)
- [Documentation](https://optiview.dolby.com/docs/theolive/api/)
- [OpenAPI](https://api.theo.live/v2/api-docs/swagger.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/dolby-io-theolive-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dolby-io-theolive-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dolby-io-theolive-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dolby.io Media API

Legacy Dolby.io Media APIs for cloud-based audio and video processing. Includes Enhance (noise reduction, leveling, dialog isolation), Analyze (loudness, speech metrics, diagnostics), Transcode (web/mobile output formats), Diagnose (audio quality reporting), and Music Mastering. Jobs are submitted with media URLs and polled or webhook-notified. Status monitored at status.dolby.io. Use of these APIs is migrating to the OptiView platform.

- **Human URL:** [https://docs.dolby.io/media-apis/](https://docs.dolby.io/media-apis/)

#### Tags

- Media Processing
- Audio Enhancement
- Noise Reduction
- Music Mastering
- Transcoding
- Analyze

#### Properties

- [Documentation](https://docs.dolby.io/media-apis/)
- [Documentation](https://www.postman.com/dolbyio/dolby-io-media-apis/overview)
- [Postman Collection](collections/dolby-io-realtime-streaming-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dolby-io-realtime-streaming-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dolby-io-theolive-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dolby-io-theolive-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dolby.io Communications API

Legacy Communications APIs for high-quality WebRTC voice and video conferencing with spatial audio, music mode, noise suppression, and dial-in/dial-out. Includes Client Access Token, Conference, Recording, Monitor, Mixer Direct, Streaming (RTMP/HLS), and Webhooks services. Documentation now redirects to the OptiView portal; status.dolby.io still tracks these services. Generally superseded by the OptiView product line; existing customers should contact Dolby for migration guidance.

- **Human URL:** [https://docs.dolby.io/communications-apis/](https://docs.dolby.io/communications-apis/)

#### Tags

- Communications
- Conferencing
- WebRTC
- Voice
- Video
- Recording
- Legacy

#### Properties

- [Documentation](https://docs.dolby.io/communications-apis/)
- [Documentation](https://docs.dolby.io/communications-apis/reference/introduction-to-streaming-api)
- [Postman Collection](collections/dolby-io-realtime-streaming-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dolby-io-realtime-streaming-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dolby-io-theolive-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dolby-io-theolive-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dolby OptiView Ads API

Server-Guided Ad Insertion (SGAI) for live streaming. The Signaling Service enriches origin manifests with advanced ad-break markers and integrates with Google Ad Manager for ad decisioning; the Ad Engine handles ad-format transformation; the OptiView Player fetches and replaces creatives client-side. Supports Full Screen, Double Box, and L-shape ad formats across web, mobile, and TV platforms.

- **Human URL:** [https://optiview.dolby.com/docs/ads/](https://optiview.dolby.com/docs/ads/)

#### Tags

- Advertising
- Server-Guided Ad Insertion
- SGAI
- Live Streaming
- Manifest

#### Properties

- [Documentation](https://optiview.dolby.com/docs/ads/)
- [Documentation](https://optiview.dolby.com/docs/ad-engine/)
- [Postman Collection](collections/dolby-io-realtime-streaming-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dolby-io-realtime-streaming-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dolby-io-theolive-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dolby-io-theolive-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dolby OptiView Player SDK (THEOplayer)

Cross-platform video player (formerly THEOplayer) with SDKs for Web, Android, iOS & tvOS, React Native, Flutter, Chromecast, and Roku. Supports HLS, MPEG-DASH, DRM, advertising integration, low-latency WebRTC playback through the OptiView Real-time Streaming feed, and the Open Video UI component library for fully customizable player interfaces. Latest series 11.x; long history of releases back to 4.x.

- **Human URL:** [https://optiview.dolby.com/docs/theoplayer/](https://optiview.dolby.com/docs/theoplayer/)

#### Tags

- Player
- SDK
- HLS
- MPEG-DASH
- DRM
- Advertising

#### Properties

- [Documentation](https://optiview.dolby.com/docs/theoplayer/)
- [Documentation](https://optiview.dolby.com/docs/open-video-ui/)
- [Postman Collection](collections/dolby-io-realtime-streaming-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dolby-io-realtime-streaming-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/dolby-io-theolive-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dolby-io-theolive-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://optiview.dolby.com)
- [Portal](https://dolby.io)
- [Documentation](https://optiview.dolby.com/docs/)
- [Documentation](https://docs.dolby.io/)
- [Getting Started](https://optiview.dolby.com/docs/millicast/getting-started/)
- [Sign Up](https://streaming.dolby.io)
- [Status Page](https://status.dolby.io)
- [Pricing](https://optiview.dolby.com/plans/)
- [Plans](plans/dolby-io-plans-pricing.yml)
- [Rate Limits](rate-limits/dolby-io-rate-limits.yml)
- [Fin Ops](finops/dolby-io-finops.yml)
- [Blog](https://dolby.io/blog/)
- [Privacy Policy](https://www.dolby.com/about/legal/privacy-policy/)
- [Terms of Service](https://www.dolby.com/about/legal/terms-of-service-for-dolby-io/)
- [Trust Center](https://trust.dolby.com/)
- [GitHub Organization](https://github.com/dolbyio)
- [GitHub Organization](https://github.com/dolbyio-samples)
- [SDK](https://github.com/dolbyio/dolbyio-rest-apis-client-node)
- [SDK](https://github.com/dolbyio/dolbyio-rest-apis-client-python)
- [SDK](https://github.com/dolbyio/dolbyio-rest-apis-client-dotnet)
- [SDK](https://github.com/dolbyio/rts-uikit-ios)
- [Tool](https://github.com/dolbyio/web-webrtc-stats)
- [Code Examples](https://github.com/dolbyio-samples)
- [Code Examples](https://github.com/dolbyio-samples/streaming-WHIP-WHEP-node-sample)
- [Code Examples](https://github.com/dolbyio-samples/streaming-webhook-thumbnails)
- [Code Examples](https://github.com/dolbyio-samples/stream-app-web-viewer)
- [Tools](https://github.com/dolbyio/awesome-audio)
- [Forum](https://github.com/orgs/dolbyio/discussions)
- [Webhooks](https://optiview.dolby.com/docs/millicast/webhooks/)
- [Changelog](https://optiview.dolby.com/docs/release-notes/)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
