# Why MCVSAID

**Set up five dedicated phones. Press one button. Every camera starts recording, streaming, or both.**

MCVSAID turns spare Android phones into a managed, self-healing multi-camera rig. One local computer runs it, and an
optional AI director can choose the shots by watching each moment before it airs. There is no cloud and no
subscription, and no footage leaves the building.

Most phone multicam tools stop once the feeds reach a switcher. Most auto-directors either choose shots from audio
levels alone or work only with their own cameras. MCVSAID covers the whole chain: setup, health, sync, colour, shot
choice and edit-ready recordings. You can steer it at any step in plain language, or out loud. Put a phone on a
low-cost gimbal and it becomes a camera you can aim from the dashboard, or one that follows a face by itself. Faces can
be blurred on the phone itself, before any picture leaves it.

![The Show page: ready for a show, every camera streaming, the programme being recorded](docs/screenshots/01-show.png)

## At a glance

- **Five dedicated phones, one button:** every camera recording or streaming at once.
- **No camera operators needed:** a handful of spare phones and one computer make a directed multicam show.
- **Phones on gimbals become robotic cameras:** aimed from the dashboard, or following a face or a named performer
  by themselves.
- **Faces blurred on the camera itself**, with the computer as a backup that catches the faces a phone misses.
- **An AI director that watches every camera before the audience does**, and takes notes in plain English.
- **Mount the phones once.** Set them up, match their colour, update and fix them from a browser.
- **Your show, your computer:** no cloud, no subscription, and no footage leaves the building.
- **The AI's cut is a starting point.** Every show comes with each camera's own file and the edit.

## What MCVSAID does that others don't

### 1. Dedicated phones, one button: every camera recording or streaming at once

If all you want is five dedicated phones that start recording, streaming, or both at a single button press, MCVSAID is
built for you. The Show page arms, starts and stops every camera together, and one readiness line tells you when all of
them are good to go.

Getting there is just as simple. A factory-reset phone taps its welcome screen six times, scans a code, installs the
signed app and joins the camera network, with no cable needed. From then on it is managed remotely: arm it, restart
it, update it one camera at a time, and correct its clock. Each phone revives a frozen picture on its own, rejoins
Wi-Fi, holds its battery short of full, and goes silent while armed. Other phone apps assume someone is holding the
phone. With MCVSAID you mount the phones once and never touch them again.

### 2. A director that sees the shot before the audience does

A look-ahead holds the programme a few seconds behind real life. A vision model running on your own computer rates
every camera from the phones' own pictures, so each cut lands cleanly on air. In the demo, the model rated six cameras
in about half a second, and every cut was seen 0.7 to 5 seconds before OBS showed it. Audio-only switchers react after
the fact, and they can't tell an empty or blurry shot from a good one.

![The Director page: how shots are chosen](docs/screenshots/06-director.png)

### 3. Directing in plain language, or out loud, mid-show

A standing brief sets the intent, for example "stay on whoever is singing; the drums for fills". During the show,
Scene Chat takes wishes such as "less on the drums". Up to four wishes are active at once, each lasts 15 minutes, and
the log explains every cut. A host can also **call shots aloud**: say "cut to the overhead" or "show the stove" and the
director cuts to that camera and holds it. That's on by default in Cooking and Creator Studio, where one person talks
to their own cameras, and off where music or a congregation could set it off by mistake. Speech is recognised on the
computer, and nothing heard is sent anywhere or kept. We haven't found another auto-director that takes live
direction in words.

![Scene Chat beside the Show page](docs/screenshots/24-scene-chat.png)

### 4. Shot logic tuned to the kind of event

Live music, worship, podcasts, panels, theatre and cooking each have their own camera roles and pacing. Talk formats
cut to whoever is speaking and allow for mic bleed, coughs and pauses. Cooking follows a loaded recipe step by step,
makes sure each step's station is seen, and can put the recipe, a QR code and captions on screen. Creator Studio lets
you build your own framings from body regions.

### 5. Virtual camera operators: zoom, follow, solo, gaze, crowd

The director can crop in on a performer and follow them. It won't zoom in on an empty frame, and it never drops below
a resolution you set, such as 1080p. It switches a phone to its telephoto lens only while that camera is off air. It
favours the instrument that leads the mix, cuts to whoever a performer is looking at, and shows the crowd only when
the crowd is lively and the stage is quiet. One fixed phone does the work of an operator with a zoom lens.

### 6. Robotic cameras for the price of a phone gimbal

Put a camera phone on a **Hohem iSteady X3 or MT3** gimbal, a consumer gimbal costing a small fraction of a PTZ camera,
and the camera app drives it over Bluetooth, with no extra box or cable. Hold an arrow on the camera's card and it turns;
let go and it eases to a stop. Press **Follow** and the phone keeps the most prominent face in frame by itself, still
following someone who turns away by their body, at a Calm, Normal or Quick pace. With performer recognition on, it can
follow a named, consenting performer instead, so the director's zoom on that camera follows them too. It works hung
upside down, and the director keeps cutting between this camera and the rest as usual.

![A camera on a gimbal, following a face](docs/screenshots/05c-gimbal.png)

### 7. Faces blurred on the camera, before anything leaves it

For a camera that must never record or send an unblurred face, such as an audience camera, a church congregation or a
school event, the phone itself finds and blurs every face before encoding. Its stream, OBS and every recording of that
camera are blurred for good, and no unblurred copy exists anywhere. The production computer can act as a backup,
watching the same camera a few seconds ahead of the programme and covering any face the phone missed, such as someone
walking into shot. The phone reports what it blurred in each frame, so only the misses are added. On the computer
alone, faces can be blurred in OBS for every face, everyone except consenting performers, or only chosen people. It's
experimental, and we say so plainly: it can miss faces.

### 8. Heat treated as a first-class problem

MCVSAID tracks each phone's temperature, its trend and a forecast against the planned show length. You can compare
runs side by side. It also controls clip-on Black Shark coolers over Bluetooth and keeps their lights off. Coolers are paired, moved
between phones or re-paired all at once from the dashboard, each to the phone it is clamped to. In early tests, a
Galaxy S23 with a cooler stayed at 22 to 25 °C while streaming and recording 4K for 2¼ hours. Without a cooler, it
reached 43 to 44 °C streaming alone.

### 9. One answer to "are we ready?"

A single readiness line checks the computer, OBS, the network, the camera relay, the model and every camera, then says
what needs attention and how to fix it. Stage Shots lays the cameras out as they stand on stage, and a room map shows
what each lens sees. You can share the page with a phone in the crowd, behind a passcode.

![The room map: each camera placed and turned, with the wedge it sees](docs/screenshots/04e-room-map.png)

### 10. Frame-accurate sync and colour matching across mixed phones

A hidden timing strip lines every feed up to the frame. One page sets white balance and exposure on every phone and
builds a LUT for each camera. The LUT can come from a colour chart or from matching to a reference camera. The camera
relay cut OBS's memory use from 11.0 GB to 2.6 GB with six 4K cameras.

### 11. Recordings ready for the edit

Each programme recording comes with a file per camera, the cuts as an EDL for Resolve, Premiere or Final Cut, and each
camera's LUT. Recordings made on the phones are copied over and verified after the show. You can re-cut the AI's show
instead of living with it.

### 12. Private, local and consent-based

Everything runs on one Mac or Linux computer, including the model, and nothing is sent to the project. Performer
recognition identifies only people who have consented, purpose by purpose. Their data is encrypted and deleted after
the show day, and every page shows when recognition is on. Face blur and voice shot calls run on the phones and the
computer too, never in a cloud service. AI is optional, so a modest computer can still run a show.

## How it compares

The comparison below is based on the public pages linked under [References](#references), as of October 2026.

| Capability | MCVSAID | Switcher Studio | Blackmagic Camera (Android) | Mevo Multicam | Audio auto-switchers |
| --- | --- | --- | --- | --- | --- |
| Android phones as cameras | Yes, as a managed fleet | Yes, as sources | Yes | No, Mevo cameras only | Needs its own switcher |
| Live switching | Yes, into OBS | Yes, by the operator | No | Yes | Yes, in vMix, ATEM or TriCaster |
| Automatic shot choice | Vision model and rules | Not stated | No | Auto-director | Mic levels |
| Sees the shot before it airs | Yes, look-ahead | No | No | Not stated | No |
| Direction in plain language | Yes, Scene Chat, and shots called aloud | No | No | No | No |
| Phones on gimbals, aimed and following | Yes, X3 and MT3, from the dashboard | No | No | Not applicable | No |
| Faces blurred on the camera | Yes, with the computer as backup | No | No | No | No |
| Event-specific modes | 6 modes plus Creator Studio | No | No | Not stated | Talk formats |
| Remote phone management and self-healing | Yes | No | Remote settings | Not applicable | Not applicable |
| Heat forecasting and cooler control | Yes | No | No | No | No |
| Per-camera files, EDL and LUTs | Yes | Not stated | Per-phone files | Not stated | No |
| Runs fully local, no subscription | Yes | No, monthly plan | Yes, free | App with a Pro plan | Yes, one-time licence |

"Not stated" means the pages we reviewed don't mention the feature; it may still exist. Product names belong to their
owners. Corrections are welcome at **mcvsaid@proton.me**.

## Requirements and limitations

- **A capable production computer.** MCVSAID has been tested on a gaming laptop with 32 GB of RAM and 16 GB of VRAM,
  and on a MacBook Pro with an M5 Pro and 48 GB of RAM. Smaller machines haven't been tested yet.
- **Dedicated phones.** Camera phones must be spare, factory-reset devices, because the app becomes each phone's device
  owner.
- **Heat.** Without a cooler, phone heat still limits recording on the phone during a show.
- **Experimental parts.** Face blur can miss faces (small, turned, fast-moving or partly hidden), so don't rely on it
  to hide anyone yet. Cooler and gimbal control use commands worked out from the makers' own apps, so a firmware
  update could change them; only the Black Shark MagCooler 5 Pro and the Hohem iSteady X3 and MT3 have been tried. An
  MT3's built-in AI tracker can be seen from the dashboard, but only started and stopped at the gimbal.
- **Delay.** The programme runs a few seconds behind real life, by design, so the director can see each moment first.
- **Platforms.** Cameras are Android only, output goes through OBS, and MCVSAID is in private beta.

## Try it

- **Demo:** the real dashboard with simulated cameras runs in your browser at
  [mcvsaid.github.io](https://mcvsaid.github.io/). Nothing is connected, and nothing you press leaves your browser.
- **Join the beta:** email **mcvsaid@proton.me** with what you film and how often, the computer you'd run it on, and
  the phones and network you have.

## References

- [MCVSAID demo dashboard](https://mcvsaid.github.io/)
- [Switcher Studio review (Dupple)](https://dupple.com/reviews/switcher-studio)
- [Blackmagic Camera for Android 2.0 (AlternativeTo)](https://alternativeto.net/news/2025/1/blackmagic-camera-2-0-for-android-adds-multi-phone-control-extended-device-support-and-more)
- [Mevo Multicam app](https://mevo.com/pages/multi-camera-app)
- [Virtual Video Director](https://www.streamingvalley.nl/product/virtual-video-director-for-vmix-atem-and-tricaster/)
