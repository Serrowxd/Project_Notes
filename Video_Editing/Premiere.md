# Adobe Premiere Notes!

## Section 1

**Stablizing:** Effects -> Video Effects -> Distort -> Warp Stabilizer

Clicking `fx` in the Effect Controls will turn the effect on or off.

GPU Acceleration is the _go-to_ if possible, otherwise you'll have more issue rendering large films.

---

**Display Format:**

_Video_ is normally `Timecode` but if you're editing something that was shot on film you would use Feet + Frames or Frames.

_Audio_ is Audio Samples

Capture is if you have a deck plugged into your computer and you want to capture a tape - don't worry about adjusting it.

**Scratch Disk:**

Normally just save them as `Same as Project`

---

V1, V2, V3, etc.. Are `Video Tracks`

A1, A2, A3, etc.. Are `Audio Tracks`

`B-Roll`, also known as **cutaway footage**, is videos, photos, or graphics that is intercut with the main shot.

Always try to keep yourself organized by making `bin` folders for each of your assets to help block them out.

---

**10 Keyboard Shortcuts for Faster Editing**

- Import: Ctrl + I
- Rewind, Pause, Play: J, K, L
- Increase/Decrease Clip Volume: [ or ]
- Copy Clips: Alt-click a clip, drag to a new part of the timeline.
- New Folder/Bin in Project Pannel: Ctrl + B
- Nudge Clip: (Shift) + Alt + Left / Right
- Razor Blade Editor: C
- Link / Unlink: Ctrl + L
- Mark In / Out: I / O
- Export Media: Ctrl + M

You can get more shortcuts [Here](https://helpx.adobe.com/premiere-pro/using/default-keyboard-shortcuts-cc.html)

---

If you have weird video footage that was imported, you can use `Media Browser` to navigate to the proper folder, then you're able to import footage regardless of the format.

---

**Create a new Sequence**

Pick the video that's the most popular or going to be the most used footage in your clip.

`+` or `-` will zoom in or out of your timeline.

Starting a new sequence you can also right click on the "new file" button and choose a new sequence, or you can go up to `file`, `new`, `sequence`.

You'll want to set the sequence to, as previously stated, the same timebase and sample rate as how you captured **all** your footage.

Audio Sample Rate should be 48000 Hz

You can create audio or video tracks by simply dragging and dropping the video above into the empty sections.

---

When shooting with multiple cameras, you want to sync your footage.

The higher the number, the higher the specificity that it will be displayed at.

To `Synchronize Audio` you select the two audio clips you want to sync, right click, and then hit `Synchronize` - click Audio, then `Downmix`. This will try to Sync your audio wavelengths.

`Insert` splits the current section of the clip and pushes them aside to make room for the video clip - this splits **ALL** the video and **ALL** the audio.

`Overwrite` overrides to the new clip without stopping the main video clip.

You can change the track selection for override by selecting the furthest left selection V1 and A1 - it adds it to the proper track that we have selected for both video and audio.

`Ripple Edit` will jump all the footage to the connection bit where it is selected **[B]** - you can also just hit control when doing the normal selection tool.

`Rolling Edit` will edit both clips rather than just the selected clip.

`Double Razor` will cut **EVERYTHING** on the timeline - **[Shift]**
