# Brightcove Ingest Profiles

Custom and experimental Ingest Profiles for Brightcove Video Cloud.

## Asia-STARTER
Low-bandwidth short-form videos for mobile-first viewers. 16x9 MP4 + HLS, up to 600Kbps 768x432, VBR capped at 780Kbps.

## Asia-STANDARD
Default for news and entertainment content monetised via ads. 16x9 MP4 + HLS, up to 900Kbps 960x540, VBR capped at 1.2Mbps.

## Asia-PREMIUM
Premium, directly monetised content: Pay-per-View, Subscription VOD, Sponsored. 16x9 MP4 + HLS, up to 1.5Mbps 1280x720 (720p), VBR capped at 1.8Mbps.

## Asia-PREMIUM DASH-CENC
Based on Asia-PREMIUM, DRM-protected with DASH-CENC, packaged for **Widevine Modular**, PlayReady, Marlin

## Asia-PREMIUM DASH-CENC and Widevine Classic
Based on Asia-PREMIUM, DRM-protected with Widevine Classic and DASH-CENC, packaged for **Widevine Classic**, PlayReady, Marlin

Documentation on Ingest Profiles: https://docs.brightcove.com/en/video-cloud/ingest-profiles-api/reference/profile-fields-reference.html
