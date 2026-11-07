# myllm-media

Video and other large media for MyLLMos™ App Gallery apps, served via jsDelivr
(`https://cdn.jsdelivr.net/gh/TeamDzX/myllm-media@main/...`, with raw GitHub as the fallback).

Companion to [myllm-assets](https://github.com/TeamDzX/myllm-assets) and
[myllm-assets-xl](https://github.com/TeamDzX/myllm-assets-xl). It is a separate repository so each one
stays under jsDelivr's 50 MB per-repository limit. Apps treat everything here as optional: if a file
is missing or the device is offline they fall back to their built-in stills.

| Folder | Used by |
|---|---|
| `apps/space-range/` | Space Range world fly-ins (`enter17_N.mp4`) and boss intros (`boss17_N.mp4`) |
| `apps/mochi/` | Mochi living room (`room_day`, `room_night`) and walk scenes (`walk_*.mp4`) |

Clips are generated with ComfyUI (FLUX, Wan 2.2) and Blender. Licence: see `LICENSE`.
