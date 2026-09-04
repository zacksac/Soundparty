
# 🎵 SoundParty

**Transform multiple devices into a unified, synchronized sound system.**

SoundParty is a native Android application designed for synchronized multi-device audio playback over local networks and Bluetooth. Whether you are splitting channels for a true spatial stereo setup or syncing multiple standalone speakers, SoundParty ensures perfectly aligned audio with zero echo.


<img width="700" height="auto" alt="soundpartyinfo" src="https://github.com/user-attachments/assets/dc0f39cb-d289-4202-b241-389889f8541c" />
---

## 🚀 Features

* **Multi-Device Synchronization:** Host a party on one device and broadcast to multiple guest devices seamlessly.
* **Spatial Stereo Configuration:** Assign specific audio channels (**LEFT**, **CENTER**, or **RIGHT**) to individual devices for a true surround-sound experience.
* **Low-Latency Audio Engine:** Built with a custom C++ audio processing pipeline and Kotlin to minimize playback delay.
* **Metronome Calibration:** Fine-tune wireless latency between devices down to the millisecond using the built-in rhythmic metronome and offset controls (-10ms / +10ms).
* **Local Media Support:** Instantly scan and index local `.mp3` files to build your party playlist.

---

## 🛠️ How It Works

### Hosting a Party
1. Tap **BROWSE FOLDER** or **SCANNED** to index local audio tracks.
2. Select your device's audio channel (Left, Center, or Right).
3. Tap **START PARTY (PLAY MUSIC)** to begin broadcasting.

### Joining a Party
1. Open SoundParty on a guest device on the same network.
2. Tap **JOIN PARTY (LISTEN)**.
3. Assign the guest device's spatial channel.

### Fine-Tuning Synchronization
Due to varying Bluetooth latencies, you can perfectly align your speakers using the Metronome tool:
1. Tap **TUNE USING METRONOME** on the host.
2. Listen to the ticks across all devices.
3. Use **-10 MS** (Play Later) or **+10 MS** (Play Earlier) on guest devices until all ticks merge into a single, crisp beat. 

---

## 📥 Download
Download the latest release of SoundParty directly from the [Google Play Store](https://play.google.com/store/apps/details?id=com.zack.soundparty).

---

<img width="768" height="1365" alt="play in stereo" src="https://github.com/user-attachments/assets/e9ba50ef-8150-420d-bf6b-e2f87ca7b386" />
<img width="768" height="1365" alt="sparty sync" src="https://github.com/user-attachments/assets/a7812145-1423-4dc9-a9fe-39776c5f9438" />
<img width="768" height="1365" alt="soundparty play music together" src="https://github.com/user-attachments/assets/aed6390b-9267-4a69-a004-acd74e31cfcd" />


## 💻 Technical Stack
* **Language:** Kotlin, C++ (JNI)
* **Audio Processing:** Custom native audio engine and ring buffers
* **Monetization:** Google Play Billing & AdMob Integrations
