# Windows 11 — Exclusion Patterns by ICF Functional Classification

Reference material: potential exclusions organized by ICF (International Classification of Functioning) body function and activity/participation categories.

## Energy and drive functions

**ICF Category:** Other/Context — Energy and drive functions

### Perceivable

- Focus Session timers in Clock use small, low-contrast toasts; users with magnification can miss break cues.
- Taskbar progress overlays (e.g., downloads) are subtle and color-only; color filters/grayscale hide state.
- Lock screen's rotating background can cause visual fatigue; no simple toggle for a static image during focus.

### Operable

- Long troubleshooters time out without an "extend" option; keyboard-only or switch users may abandon.
- Cumulative updates sometimes require multiple restarts; sustaining attention/energy across cycles is hard.
- Battery-saver prompts appear late in workflow; fatigued users may not complete shutdown sequences.

### Understandable

- Windows Update messages vary in tone and surface (toast vs. Settings); effort/duration is hard to gauge.
- Battery performance modes use vague terms ("Balanced", "Best performance") without energy impact context.

### Robust

- Focus Session state isn't consistently exposed for AT to announce remaining time/breaks.
- Performance overlays conflict with battery notifications, duplicating or contradicting signals.

## Sound discrimination

**ICF Category:** Hearing — Sound discrimination

### Perceivable

- System notification and error chimes share similar pitch/envelope; urgency is hard to tell by sound alone.
- Audio Devices auto-switch lacks synchronized visual cues; device changes are missed by deaf/HoH users.
- Service alerts (e.g., deprecations) reuse generic tones; auditory differentiation is impossible.
- Startup and error sounds play from same channel; no directional cue for unilateral hearing loss.

### Operable

- When Bluetooth audio switches, there's no caption/notification; users can't confirm device routing.

### Understandable

- Per-app volume mixer concepts (system vs. app vs. input) aren't labeled plainly.
- Sound themes are abstractly named ("Default", "Sonata"); users can't infer cue semantics.
- Audio troubleshooting uses device IDs, not friendly names; repair steps are unclear.

## Managing one's own behavior

**ICF Category:** Cognition — Managing one's own behavior

### Perceivable

- Widget notifications surface behind full-screen apps without persistent indicators.
- Focus Assist banners appear only momentarily; users needing extra time miss cues.

### Operable

- Focus mode toggles differ in Clock vs. Quick Settings; muscle memory fails across surfaces.
- Windows tips may reopen after dismissal; repeated interruptions disrupt routines.

### Understandable

- Settings alternates "Notifications", "Banners", and "Alerts"; control concepts blur.
- Performance recommendations use ambiguous wording ("may improve"); outcomes unclear.

### Robust

- Focus/Do Not Disturb state isn't consistently exposed to companion apps for routine support.
- Disabling Notification Center via registry blocks accessibility tools from retrieving alerts.
- Cross-device sync duplicates alerts; routine management becomes inconsistent across surfaces.

## Articulation of consonants

**ICF Category:** Speech — Articulation of consonants

### Perceivable

- Voice typing confirmation tones are subtle; users can't tell when dictation begins/ends.
- Voice access status text is small; users with mixed speech/visual impairment can't verify mode.

### Operable

- Dictation bar requires mouse for punctuation; verbal-only users must spell every mark.
- Speech profiles don't migrate with MS account; re-training needed after device change.

### Understandable

- Error copy cites device/privacy issues but lacks concrete repair steps.
- Error text uses technical phrasing ("speech service unavailable"); plain tips absent.

### Robust

- AT can't request alternative modalities (e.g., auto-open OSK) when speech confidence is low.
- Voice access logs aren't exposed to AT; users can't audit failed attempts for patterns.

## Parietal lobe

**ICF Category:** Cognition — Parietal lobe

### Perceivable

- Snap layouts rely on hover near window buttons; affordances are missed with spatial attention issues.
- Virtual Desktop thumbnails are small; magnifier users can't distinguish contexts without labels.

### Operable

- Drag-and-drop in File Explorer demands precise placement; keyboard reordering is inconsistent.
- Multi-monitor Arrange requires fine pointer control; keyboard-only repositioning is unclear.

### Understandable

- "Pin to taskbar" vs. "Pin to Start" is unclear; users misplace programs.
- Virtual Desktop names don't persist; context for task switching is lost.

### Robust

- Assistive overlays can't query desktop thumbnails via secure compositor; location awareness drops.
- Custom shell replacements misreport window positions; overlays can't anchor accurately.

## Frontal lobe

**ICF Category:** Cognition — Frontal lobe

### Perceivable

- "Finish setting up device" banner blends with background; onboarding is forgotten.

### Operable

- Hello recovery repeats identity confirmations; progress is lost across restarts.
- Nested Settings categories require many clicks; task completion strains planning.

### Understandable

- Multi-step flows (BitLocker, Storage Spaces) hide prerequisites; users can't plan.
- Update channels (stable/beta/dev) aren't contrasted plainly; stability tradeoffs unclear.
- Backup options mix File History and OneDrive terms; scope of protection is unclear.

### Robust

- AT querying dialog focus can return stale handles; navigation order is unreliable.
- Legacy MMC tools don't expose semantic roles; automation can't convey hierarchy.

## Hand and arm use

**ICF Category:** Mobility — Hand and arm use

### Perceivable

- Resize handles in Explorer panes/splitters are narrow; grab area isn't perceived with magnification.
- Icon spacing in Explorer is dense; large cursors cause mis-targeting.

### Operable

- Gesture-only actions (three-finger trackpad, back swipes) lack keyboard parity in some shells.
- Closing notifications via tiny "X" needs fine control; keyboard dismissal isn't advertised.

### Understandable

- Pen/Ink settings use technical terms ("palm rejection", "hover"); mapping to outcomes is unclear.
- Mouse Keys vs. Sticky Keys vs. Filter Keys aren't contrasted; wrong motor aid is chosen.
- Pointer speed vs. precision settings are separated; users misconfigure expecting one control.

### Robust

- Full-screen apps can capture mouse, blocking AT from generating synthetic clicks reliably.
- HID remapping via third-party drivers conflicts with accessibility hooks; AT can't intercept.

## Looking after one's health

**ICF Category:** Other/Context — Looking after one's health

### Perceivable

- Accessibility shortcuts (Win+U) list is dense with limited grouping; relevant features are overlooked.
- Windows Security health banner uses small, icon-only indicators; risks aren't noticed quickly.

### Operable

- Windows Update restarts may schedule without an accessible snooze in keyboard-only flow.
- Magnifier reading mode cannot toggle while modal dialogs are open; users lose access mid-task.

### Understandable

- Privacy & Security health checks list issues without prioritization; users can't tell what to fix first.
- Update health recommendations use jargon ("servicing stack"); plain-language summaries are missing.

### Robust

- Some Windows Security reports export as unstructured images; data is not programmatic.
- Reliability Monitor CSV exports lack headers; AT parsing and auditing are impeded.

## Retrieval of memory

**ICF Category:** Cognition — Retrieval of memory

### Perceivable

- Clipboard history previews truncate text without tooltips; users can't perceive which entry to recall.
- Notification history hides older toasts behind small chevrons; past cues needed for recall are visually buried.

### Operable

- Keyboard navigation of "Quick Access" and "Recent" lists is inconsistent across dialogs; users can't efficiently re-open prior items.
- Win+V Clipboard history requires precise focus management; switch users lose context when entries close on selection.

### Understandable

- Similar icons and names across MRU items (e.g., multiple "Document1") lack disambiguating metadata like path or last action.
- Search Scope labels ("All", "Apps", "Documents", "Web") are not explained; users misinterpret where results come from.
- Clipboard history uses terse labels; users can't predict how pinned items persist across reboots.

### Robust

- Search indexer pauses under power-saving rules without signaling to AT; recall features silently degrade.
- Cloud-backed recents (OneDrive/SharePoint) fail offline; fallback metadata isn't exposed for AT to announce.
- Notification Center history isn't consistently exposed via automation; AT cannot retrieve prior toasts on demand.

## Psychomotor functions

**ICF Category:** Mobility — Psychomotor functions

### Perceivable

- Pointer trails and cursor size previews are small; users can't perceive motion assistance effects before applying.
- Touch targets for title bar controls are compact; hit areas aren't clearly delineated at high DPI.
- Double-click speed test UI provides limited visual feedback; users can't perceive timing success/failure.

### Operable

- Hold-to-drag thresholds and window resize corners require fine control; one-switch or head-pointer users can't operate reliably.
- Context menus close on minor pointer jitter; tremor makes activation and selection unreliable.
- Touchpad three-finger gestures invoke global actions accidentally; disabling per-gesture requires deep settings navigation.

### Understandable

- "Enhance pointer precision" label doesn't explain acceleration; users misconfigure for fine motor control.
- Gesture nomenclature ("tap-and-hold", "press-and-hold", "drag") is inconsistent across tutorials.

### Robust

- Custom HID drivers override system mappings; AT cannot reliably intercept or synthesize input events.
- Some legacy dialogs don't honor system pointer size; visual affordances for motor targeting disappear.
- Per-app high-DPI behavior breaks consistent hit testing; automation coordinates reported to AT are inaccurate.
- Secure desktops (UAC/lock) restrict OSK and AT invocation; motor accommodations drop at critical moments.

## Emotional functions

**ICF Category:** Cognition — Emotional functions

### Perceivable

- Error states use red and motion without alternative cues; users experiencing anxiety miss the actual message.
- Urgent toasts overlap with other banners; critical context is occluded during heightened arousal.
- Full-screen warnings dim the background heavily; content contrast becomes too low for accurate reading.
- Security badge icons are small; users can't perceive severity differences at a glance.

### Operable

- Timed dialogs (e.g., restart countdowns) lack a clear "pause/snooze"; users under stress can't act in time.
- SmartScreen/UAC steal focus unexpectedly; keyboard users activate default actions by mistake.
- Critical notifications stack behind modals; reaching the right control requires complex focus recovery.
- High-salience sounds can't be muted independently from other cues; startle responses impair operation.

### Understandable

- Alarmist copy ("Act now") appears without context; users can't assess real risk.
- Mixed terminology ("threat", "issue", "recommendation") lacks definitions; severity isn't clear.
- Error dialogs suggest multiple unrelated fixes; users can't choose a first step.
- Restart prompts don't estimate duration; uncertainty elevates stress and avoidance.

### Robust

- Assistive technologies can't prioritize or filter high-stress alerts via a consistent severity taxonomy.
- Security notifications arrive via multiple channels (toasts, Action Center, banners) without de-duplication signals for AT.
- Some warning banners are bitmaps in WebView content; AT cannot parse the underlying structure.
- Programmatic hooks for countdown timers are inconsistent; AT can't announce remaining time reliably.

## Regulation of emotion

**ICF Category:** Cognition — Regulation of emotion

### Perceivable

- Notifications about failures (sync, backup) lack persistent indicators; users can't pace responses or return later.
- Auto-playing instructional videos in Settings draw attention away from self-calming strategies.
- High-motion UI during restore/reset keeps animating; users can't maintain emotional focus on steps.
- Color-only severity cues (yellow vs. red) are subtle in some themes; stress signals are misread.

### Operable

- Update countdowns and forced restarts offer limited snooze ranges; users can't defer until calm/focused.
- Do Not Disturb toggles reset after reboots; users lose protective buffers they rely on.
- Toast groups can't be batch-dismissed with a single keyboard action; clutter sustains arousal.
- Live Captions window steals focus when undocking/redocking; regaining control adds frustration.

### Understandable

- Security recommendations lack a calming "safe path" summary; users ruminate on worst-case outcomes.
- Multiple settings influence interruptions (Focus, Priority, App permissions); guidance for a single quiet state is missing.
- Language in recovery flows warns of data loss without graded scenarios; users avoid necessary repairs.
- Error messages omit estimated effort; users can't plan micro-breaks to regulate emotions during fixes.

### Robust

- AT cannot subscribe to a unified "quiet mode" signal across OS surfaces; regulation strategies don't propagate.
- Some apps bypass Focus/Do Not Disturb via legacy APIs; emotional buffers fail unpredictably.
- Programmatic labels for alert severity vary by subsystem; AT can't consistently down-rank low-risk messages.
- Exported logs (reliability, updates) lack machine-readable cause?fix mapping; coaching agents can't scaffold de-escalation.

## Visuospatial perception

**ICF Category:** Cognition — Visuospatial perception

### Perceivable

- Snap layout guides appear near tiny window controls; users miss spatial options when relying on magnifier.
- Taskbar overflow tray uses compact icon-only items; relative positions are hard to perceive at high DPI.
- Virtual desktop indicators rely on faint bottom bars; active context is easy to misread.
- Multiple monitor edges show minimal visual anchors for dragging; screen boundaries are unclear.

### Operable

- File Explorer drag-and-drop requires precise hit targets between folders; users misplace items.
- Window resizing on thin borders demands accurate cursor placement; tremor or neglect impairs operation.
- Arrange Displays requires dragging monitor thumbnails to match physical layout; keyboard alternative is obscure.
- Grid snapping positions differ across mixed-DPI displays; predictable geometry breaks.

### Understandable

- Icon meaning vs. app instance (pinned vs. running) on the taskbar isn't clearly differentiated; users lose spatial mapping.
- Folder grouping and sort order visuals can conflict; users can't infer where a moved file will appear.
- Snap groups vs. individual windows aren't labeled plainly; layouts are mistaken for separate apps.
- Display scaling warnings are terse; users don't understand why UI elements appear misaligned.

### Robust

- AT cannot consistently enumerate snap groups and their screen coordinates; spatial structures aren't exposed programmatically.
- Legacy apps render non-client areas differently; automation hit-testing for borders is unreliable.
- Secure desktop surfaces (UAC/lock) suppress custom pointers; spatial orientation aids disappear.
- High-DPI per-monitor awareness varies by app; reported bounds to AT don't match visual positions.

## Pace of thought

**ICF Category:** Cognition — Pace of thought

### Perceivable

- Transient system toasts auto-dismiss quickly; users who need more processing time miss key information.
- Loading indicators are minimal in Settings; users can't perceive when it's safe to proceed.
- Auto-advancing OOBE screens animate forward; longer processing time users lose content.
- Live Captions small "connected"/"disconnected" status text is easy to miss during setup.

### Operable

- Restart countdowns allow limited snooze choices; users can't defer until they're ready.
- Timed authentication prompts (Hello/OTP) expire mid-navigation; keyboard-only users can't respond in time.
- Installers lock UI during checks; pause/resume is unavailable for paced task execution.
- Automatic focus shifts (e.g., dialog steals focus) break step-by-step pacing strategies.

### Understandable

- Complex flows (BitLocker, Storage Spaces) lack up-front time/effort estimates; planning is hard.
- "Processing" messages don't say what's happening; users can't anticipate next steps.
- Update terminology ("cumulative", "feature", "quality") isn't explained; decision-making slows.
- Settings surfaces change section names between versions; learned pathways no longer map.

### Robust

- AT can't query toast remaining time; tools can't extend/hold notifications for slow processing.
- Some progress UIs are bitmap-only; AT can't read stage counts or durations.
- Power policies throttle indexer/services unpredictably; assistive reminders fall behind real time.
- Modal system surfaces (UAC/lock) block task automation; pacing assistance can't continue.

## Higher-level cognitive functions

**ICF Category:** Cognition — Higher-level cognitive functions

### Perceivable

- Task Manager uses dense tables by default; executive function users can't perceive priorities quickly.
- Security & privacy settings split across multiple pages; critical controls lack visual prominence.
- Policy notifications in Settings appear as small banners; governance impact isn't noticeable.
- App permission prompts use tiny toggles; implications aren't visually emphasized.

### Operable

- Switching between multiple administrative tools (MMC, Settings, Control Panel) requires context juggling.
- Group Policy/Registry edits demand precise sequences; mis-clicks cause wide-ranging effects.
- Managing notifications per-app demands repetitive navigation; no batch operations for common strategies.
- Window focus changes when new admin prompts appear; keyboard users lose their place.

### Understandable

- Advanced options (Hyper-V, WSL, virtualization) are jargon-heavy; users can't map to real tasks.
- Security recommendations don't rank by impact/effort; prioritization is guesswork.
- Multiple backup paradigms (OneDrive, File History, system image) lack a single mental model.
- Task Manager "Efficiency mode" and "Power usage trend" lack clear relationships; reasoning is difficult.

### Robust

- Automation hooks differ across Settings/Control Panel/MMC; AT can't deliver consistent guidance.
- Some admin surfaces render as custom UI without roles; screen readers can't parse structures.
- Policy-driven states aren't always exposed programmatically; companion coaching apps can't adapt.
- Exported reports (e.g., security) lack machine-readable severity; external tools can't synthesize a plan.

## Organization and planning

**ICF Category:** Cognition — Organization and planning

### Perceivable

- Start menu groups "Recommended" items without category cues; planning next steps is hard to perceive.
- Settings breadcrumbs are small and truncated; users lose sense of location within a plan.
- Taskbar badges overlap icons; outstanding work isn't visually prioritized.
- File Explorer's "Home" view mixes content types; planning workflows from a single hub is confusing.

### Operable

- Pinning/unpinning apps requires multiple locations (Start/Taskbar/All apps); maintaining an organized workspace is tedious.
- Renaming and reordering virtual desktops needs several steps; keyboard workflows aren't obvious.
- Scheduling restart times for updates opens separate surfaces; cohesive planning is interrupted.
- Focus/Quiet hours rules require navigating multiple panes; batch configuration is missing.

### Understandable

- Start pin recommendations don't explain rationale; users can't predict what belongs in their plan.
- "Apps for websites" and default apps settings overlap; mapping tasks to handlers is unclear.
- Taskbar multi-instance grouping rules aren't documented; users lose planned window arrangements.
- Storage cleanup recommendations lack effort and risk estimates; sequencing actions is guesswork.

### Robust

- Programmatic access to Start layout varies by edition/policy; planning tools can't maintain consistency.
- Some shell states (pinned apps, snap groups) aren't exposed with stable IDs; external organizers can't sync.
- Calendar/clock integrations surface via different APIs; AT can't aggregate schedules reliably.
- Notification scheduling metadata isn't standardized; assistants can't coordinate across apps.

## Reception of language

**ICF Category:** Communication — Reception of language

### Perceivable

- Live Captions uses small status and speaker labels; users miss who is speaking in multi-source audio.
- Narrator default speech rate and punctuation verbosity make long dialogs hard to parse on first exposure.
- In Settings, explanatory text blends with interactive text; readers can't distinguish instructions from actions.
- Region/language indicators in the taskbar language switcher are two-letter codes; low-vision users misread the active input language.

### Operable

- Changing display language requires multiple restarts/logouts; users relying on translated UI can't operate interim steps.
- Captions windows don't always remember position/size across sessions; users must repeatedly adjust to read comfortably.
- Text-to-speech voices can't be switched quickly from the screen; deep navigation interrupts comprehension strategies.
- The IME/keyboard language flyout closes on minor focus changes; keyboard-only users lose access to language toggles mid-task.

### Understandable

- Settings labels mix "language", "region", "locale", and "speech" without plain guidance; users can't predict which affects UI text.
- Live Captions doesn't surface accuracy caveats (e.g., domain terms); users misinterpret critical information.
- Narrator verbosity presets aren't described with outcomes (e.g., "concise for dialogs"); trial-and-error is required.
- The difference between display language and app language is not explained; users expect all apps to switch automatically.

### Robust

- Caption APIs expose text but limited context (speaker/source); third-party AT can't provide full comprehension aids.
- Some UWP/Win32 apps ignore system language settings; mixed-language UIs break comprehension flow.
- Offline TTS voice fallback is inconsistent; comprehension aids fail when connectivity is restricted.
- Programmatic events for language change are inconsistent across shells; AT can't reliably re-announce new UI language.

## Expression of language

**ICF Category:** Communication — Expression of language

### Perceivable

- Voice typing start/stop indicators are subtle; users can't perceive when text entry is live.
- IME composition windows use small candidates and low contrast; users miss the intended selection.
- OSK feedback for long-press diacritics is visually tight; diacritic options are missed at high magnification.
- Microphone level meters are compact with thin bars; users can't perceive adequate input levels while dictating.

### Operable

- Dictation and voice access share conflicting shortcuts; switching modes mid-field requires extra steps.
- IME candidate selection demands fine target acquisition; switch/eye-gaze users struggle to confirm choices.
- Punctuation via voice requires verbose phrasing; there's no terse, consistent command set across apps.
- Moving focus between fields can terminate dictation; users must repeatedly restart expression aids.

### Understandable

- Voice command grammar isn't demonstrated in-product; examples for editing and formatting are sparse.
- IME personalization and learning features aren't explained; users don't know how to teach preferred vocabulary.
- Differences between Dictation, Voice access, and Narrator "type with voice" are unclear; users choose the wrong tool.
- OSK advanced layouts (split, one-handed) lack scenario guidance; users can't match layout to motor strategy.

### Robust

- Speech services require connectivity for best accuracy; enterprise blocks cause silent quality degradation.
- AT can't automatically trigger alternative modalities on low speech-confidence (e.g., prompt OSK); expression stalls.
- IME APIs differ across Win32/UWP; third-party AT can't maintain consistent candidate control.
- Clipboard and input method events aren't unified; external AAC tools can't reliably insert text across shells.

## Simple calculation

**ICF Category:** Cognition — Simple calculation

### Perceivable

- Storage sizes in Settings mix units (GB, GiB) without visual emphasis; users misread quantities.
- Battery estimates show fluctuating numbers in small type; users can't perceive stable values for planning.
- Time zone offsets and DST indicators are subtle; calculating local time becomes error-prone.
- Calculator history uses light separators; previously computed results are hard to pick out.

### Operable

- Copying values from Task Manager graphs requires precise selection; keyboard access to exact numbers is limited.
- Calculator mode switching (Standard/Scientific/Programmer) hides functions across menus; quick access is slow.
- Percent and unit conversions are buried; users must navigate multiple clicks to perform simple math.
- Selecting numeric text in Settings (e.g., disk quotas) is inconsistent; spin controls lack predictable keyboard increments.

### Understandable

- "Available vs. Used" storage concepts aren't explained with examples; users miscalculate free space.
- Network speed units (Mbps vs. MB/s) aren't clarified; users misjudge download times.
- Battery "Estimated time remaining" lacks method disclosure; users can't gauge accuracy.
- Calculator order-of-operations mode isn't explicit; novices misinterpret multi-step results.

### Robust

- Programmatic access to numeric values in custom charts is limited; AT can't retrieve exact data points.
- Locale settings affect decimal separators; some apps don't follow system conventions, breaking calculations.
- Copy-as-text from system surfaces strips units; downstream tools can't preserve meaning.
- Calculator's history export lacks a tagged structure; external coaching tools can't analyze steps.

## Experience of self and time functions

**ICF Category:** Cognition — Experience of self and time functions

### Perceivable

- Notification timestamps collapse to relative phrases ("a moment ago"); users can't perceive exact time anchors.
- Lock screen clock is small on some layouts; users miss current time and next calendar item.
- Focus Sessions progress indicators lack prominent end-time; temporal goals aren't visible.
- File Explorer date columns default to relative dates; exact times are hidden without view changes.

### Operable

- Switching time zones requires multiple pages; travelers can't quickly orient when landing in a new locale.
- Alarms & Clock app requires precise pointer actions to set durations; keyboard entry paths are non-obvious.
- Timeline-like activity recall is fragmented (Recent files, Jump Lists, Notifications); operating a coherent history is difficult.
- Scheduling quiet hours across weekdays vs. weekends needs repetitive configuration; batch edit is absent.

### Understandable

- Auto time sync vs. set time manually isn't contrasted; users can't reason about drift symptoms.
- Focus Sessions lacks plain guidance for break ratios; users can't plan self-paced cycles.
- Relative vs. absolute time in file views isn't explained; users misjudge recency.
- Notifications center mixes app and system events; understanding daily rhythm is difficult.

### Robust

- Programmatic access to absolute timestamps in notifications is limited; AT can't announce exact times on demand.
- Calendar widgets from different apps use different APIs; assistants can't aggregate a stable "now/next".
- Time zone changes aren't consistently broadcast to all apps; some surfaces show stale times post-travel.
- Exporting activity history is fragmented; external tools can't reconstruct a timeline for orientation aids.

## Visual acuity (far/near)

**ICF Category:** Sensory — Visual acuity (far/near)

### Perceivable

- Taskbar badges use tiny numerals; at 125-150% scaling the glyphs remain small and low-contrast.
- Title-bar window controls shrink on high-DPI monitors; hit targets and icons are difficult to resolve at distance.
- Settings side-nav uses compact text with limited weight contrast; near acuity challenges reduce readability.
- File Explorer column headers truncate without tooltip expansion; users can't perceive full labels at common zoom levels.

### Operable

- Increasing text size doesn't consistently enlarge controls in legacy dialogs; users still must operate small targets.
- Magnifier docked mode hides parts of controls; pointer and focus are hard to coordinate on small widgets.
- OSK resize handle is subtle; users with near-vision challenges struggle to adjust keyboard size quickly.
- Context menu submenus auto-open on hover; overshooting small items makes activation unreliable.

### Understandable

- Differences between "Text size", "Display scale", and "Ease font" aren't explained; users pick the wrong setting for acuity needs.
- High DPI warnings use technical phrasing; users can't predict which apps won't scale text properly.
- Cursor size and thickness controls are in different panes; users expect a single place to tune visibility.
- "Make everything bigger" labels don't disclose exceptions (legacy apps); expectations aren't set for mixed results.

### Robust

- Some Win32 apps render text as bitmaps; screen magnification and AT can't improve clarity programmatically.
- Per-monitor DPI awareness varies; app bounds reported to AT don't match visual scale for precise targeting.
- System font scaling isn't uniformly honored in WebView/embedded controls; mixed legibility across surfaces.
- AT cannot query per-control font scale overrides; companion tools can't enforce consistent readable sizing.

## Quality of vision

**ICF Category:** Sensory — Quality of vision

### Perceivable

- Acrylic/translucent backgrounds reduce text contrast in Start and context menus; halos blur letterforms.
- Thin glyph styles in system icons reduce stroke clarity; low-contrast themes further degrade legibility.
- Notification toasts use image-heavy previews; compression artifacts and small text impair recognition.
- Subpixel rendering varies across monitors; clarity shifts when moving windows between displays.

### Operable

- Low-contrast focus indicators in some controls make keyboard traversal hard for users with blurred vision.
- Edge-resize cursors are thin; users with ghosting/diplopia can't confirm they've hit the edge to drag.
- Small, low-contrast scrollbars in modern apps hinder precise scrolling when vision quality fluctuates.
- Color filter and contrast themes don't apply inside some custom-rendered panes; interaction remains visually noisy.

### Understandable

- "Transparency effects" doesn't explain readability tradeoffs; users can't connect the toggle to clarity issues.
- "Contrast themes" vs. "Dark mode" aren't contrasted; users expect dark mode to meet contrast needs.
- Font smoothing options use technical names; users can't choose the clearest rendering for their display.
- HDR/cleartype calibration flows don't preview common UI surfaces; users misjudge real-world clarity.

### Robust

- Some app surfaces bypass system theme contrast; AT and system policies can't enforce readable color pairs.
- Per-app rendering engines (WinUI, WPF, Electron) expose different accessibility trees; clarity aids can't be applied uniformly.
- Wallpaper/theme sync changes appearance across devices unexpectedly; clarity settings don't roam predictably.
- Programmatic color/contrast metrics aren't exposed for all elements; tooling can't detect low-clarity states.

## Visual field functions

**ICF Category:** Sensory — Visual field functions

### Perceivable

- Key indicators (toast close button, taskbar overflow chevron) sit at screen edges; users with tunnel vision don't see them.
- System dialogs can appear behind fullscreen apps; peripheral-only banners go unnoticed.
- Snap hints render near the top edges; users focusing centrally miss spatial cues.
- Notification counter in Action Center is small and off-axis; peripheral scotomas hide it.

### Operable

- Edge-swipe gestures on tablets require peripheral awareness; users with hemianopia can't trigger reliably.
- Drag-to-reorder taskbar icons depends on lateral vision; keyboard alternatives aren't obvious.
- Multi-monitor cursor travel crosses bezels; users with field loss lose pointer and context.
- Window controls are spaced widely; users relying on central islands of vision overshoot buttons.

### Understandable

- No in-product guidance explains how to reposition UI (e.g., toast origin) for central vision users.
- Pointer trails vs. large pointer aren't contrasted; users don't know which helps field loss more.
- "Automatically hide taskbar" doesn't warn about discoverability impacts for reduced peripheral vision.
- Snap layouts vs. zones aren't described with central-vision examples; users can't choose supportive patterns.

### Robust

- AT can't change toast anchor or safe area programmatically; peripheral placement remains inaccessible.
- Per-monitor taskbars and overlays expose inconsistent bounds; assistive focus boxes misalign across displays.
- Secure desktop prevents custom focus rings/trails; field-compensation aids disappear at critical moments.
- OS doesn't expose a unified "central focus mode" signal; apps can't adapt layouts for narrowed fields.

## Sound detection

**ICF Category:** Hearing — Sound detection

### Perceivable

- Minor system sounds lack parallel visual cues; users who don't detect soft beeps miss status changes.
- Bluetooth connect/disconnect tones are quiet and similar; users can't perceive device state transitions.
- Noisy backgrounds mask alert chimes; toast banners fade quickly before they're noticed.
- Battery low alerts are brief; users with limited hearing don't detect the short tone in time.

### Operable

- There's no single toggle to convert all critical sounds into persistent visual alerts; configuration is scattered.
- Hardware volume keys provide tonal feedback without haptic/visual parity; users can't operate volume changes confidently.
- Per-app sound routing lacks a clear on-screen confirmation; deaf/HoH users can't verify with a glance.
- Live Captions doesn't auto-start on system boot; users can't operate a "sound detection first" workflow hands-free.

### Understandable

- Sound theme names don't communicate urgency semantics; users can't map tones to importance.
- Mixer terms (input/output, system vs. app) are jargon; users can't reason about where audio goes.
- Spatial audio labels suggest directionality for alerts; users expect location cues that aren't provided.
- "Mono audio" setting doesn't clarify effect on stereo alerts; users misinterpret what's merged.

### Robust

- Caption and notification APIs don't uniformly expose non-speech audio events; AT can't detect all cues.
- Some system sounds originate from drivers/OEM tools outside accessibility hooks; visual parity isn't triggered.
- Audio device changes may not fire consistent automation events; companion apps miss state transitions.
- There's no severity taxonomy for alerts across subsystems; assistants can't prioritize conversions to visual alarms.

## Sound discrimination

**ICF Category:** Hearing — Sound discrimination

### Perceivable

- Critical error, warning, and information tones share similar timbre and duration; urgency is hard to distinguish by ear alone.
- Quiet "device connected" and "device disconnected" tones sound alike; users can't perceive which event occurred.
- Volume change "ticks" mask concurrent notification chimes; overlapping sounds blur distinctions.
- Background Focus music and system alerts mix at similar loudness; signals are not perceptually separated.

### Operable

- There is no "preview all system sounds with labels" panel; testing differences requires hunting through multiple dialogs.
- Per-app volume mixer lacks a one-step "solo alerts" control; isolating notification sounds during setup is tedious.
- Hardware media keys produce tones without on-screen type/level indicators; non-hearing users can't confirm the action taken.
- Sound theme changes are buried; switching quickly to a high-contrast audio set isn't streamlined.

### Understandable

- Sound theme names are aesthetic ("Calligraphy", "Default") rather than semantic; users can't infer alert hierarchy.
- Mixer labels like "System sounds" vs. "Notifications" aren't defined; users can't map tones to categories.
- Auto-ducking is described briefly; users don't understand why music dips when alerts play.
- Spatial audio marketing copy implies clarity improvements; users expect better discrimination that isn't provided for alerts.

### Robust

- Audio notification metadata (type, priority) isn't uniformly exposed to AT; third-party captioners can't label tones distinctly.
- Driver-level tones (Bluetooth stack, camera) bypass system hooks; visual equivalence isn't guaranteed.
- Exclusive-mode audio from apps can mask or delay alert cues; no guaranteed side-channel for critical signals.
- No shared urgency taxonomy across subsystems; assistants can't programmatically style or rank alert sounds.

## Localization of sound source

**ICF Category:** Hearing — Localization of sound source

### Perceivable

- System alerts don't include optional visual "source" badges; users can't perceive which app or device produced the sound.
- Per-app meters in the volume mixer are small; quickly perceiving which app is sounding is difficult.
- Device-connection tones are identical for different ports (USB-C vs. dock); source localization by context is weak.
- No visual spatial map for multi-output setups; users can't see which physical device is active when a sound plays.

### Operable

- Switching default output via Quick Settings doesn't highlight the originating app; re-routing sound is trial-and-error.
- There is no "Identify playing app" shortcut; users must open the mixer and scan small meters.
- When multiple devices play system tones, there's no per-device visual ping; locating the speaker requires manual testing.
- Mono audio mode removes directional cues without adding visual alternatives; operation relies on guesswork.

### Understandable

- "App volume and device preferences" lacks examples; users don't understand how to bind one app to one device.
- Labels like "Default communications device" vs. "Default device" are not explained; routing rules are opaque.
- Spatial audio descriptions emphasize immersion; users expect it to identify sources of alerts, which it doesn't.
- No guidance on using visual indicators (toasts, badges) to substitute for sound localization cues.

### Robust

- Apps using exclusive-mode or custom engines don't surface activity to system mixers; AT can't discover the source.
- Bluetooth multipoint switching isn't consistently signaled via automation events; assistants miss device changes.
- No standardized event for "this app is currently emitting audio" across all frameworks; captions can't follow sources reliably.
- Per-device diagnostics aren't exposed programmatically; third-party tools can't flash or ping physical speakers.

## Lateralization of sound

**ICF Category:** Hearing — Lateralization of sound

### Perceivable

- Left/right balance indicators are hidden behind small sliders; users can't perceive channel dominance at a glance.
- No built-in stereo test with clear labels; users can't quickly perceive which channel is active.
- Channel badges in the mixer are absent; per-app panning isn't perceivable visually.
- Mono audio toggle gives no preview; users can't perceive its effect before applying.

### Operable

- Adjusting balance requires deep navigation; there's no quick toggle to center audio during calls.
- Per-app balance/pan isn't exposed; users can't lateralize only media while keeping alerts centered.
- Hotkeys to switch between mono/stereo don't exist; switching during a task interrupts flow.
- External DACs can override OS balance; operating a consistent lateralization strategy fails.

### Understandable

- Explanations of "mono audio" vs. "balance" are terse; users don't know which helps unilateral hearing.
- Spatial audio features are marketed for immersion; users wrongly assume they control lateralization of alerts.
- Communications ducking is unclear; users think the voice is panned when volume simply lowers.
- No guidance on keeping alerts centered while allowing media to be lateralized for cochlear implants.

### Robust

- Some drivers ignore OS balance settings; AT can't guarantee channel adjustments persist.
- Wireless headsets switch profiles (A2DP/HFP) mid-call; lateralization states reset.
- No event exposes per-app panning to automation; captions/visualizers can't mirror lateral position.
- Shared-mode mixing hides channel metadata from system APIs; external tools can't read or set per-stream balance.

## Articulation of consonants

**ICF Category:** Speech — Articulation of consonants

### Perceivable

- Voice access misrecognition feedback is subtle; users can't perceive which phoneme caused failure.
- Dictation confidence indicators aren't visible by default; users miss when accuracy drops due to articulation.
- Microphone noise-reduction status isn't surfaced clearly; users can't see when clarity aids are off.
- Per-language phonetic hints aren't shown in UI; second-language users can't perceive target sounds.

### Operable

- Training acoustic models requires long sessions; users with fatigue can't operate incremental tuning.
- Switching quickly from voice access to OSK on failure isn't one action; recovery from misarticulation is slow.
- Noise suppression and mic boost live in different panes; rapidly toggling clarity aids mid-call is cumbersome.
- Per-app microphone selection is buried; using a closer mic for clearer consonants requires multiple steps.

### Understandable

- Voice command grammar lacks minimal pairs examples; users can't learn distinctions for similar consonants.
- Error messages cite "network" or "service" instead of "low clarity/low confidence"; users misdiagnose issues.
- Microphone setup wizards don't explain distance/placement effects on sibilants and plosives.
- No plain-language guidance on using phonetic alphabets to disambiguate commands.

### Robust

- Recognition APIs expose text results but limited phoneme/confidence traces; AT can't coach articulation improvements.
- Offline recognition quality varies widely by language; misarticulation handling degrades without connectivity.
- App sandboxes limit cross-surface mic control; an AT can't switch devices to improve consonant capture.
- No system-wide signal of "speech confidence low"; companions can't prompt alternate input automatically.

## Articulation of vowels

**ICF Category:** Speech — Articulation of vowels

### Perceivable

- Voice typing gives limited on-screen feedback for vowel substitutions ("sheet"?"shit"); misrecognitions aren't visually emphasized.
- Dictation underlines corrections briefly; users with magnification miss the subtle correction marks indicating vowel errors.
- Input language indicator uses two-letter codes; users can't easily perceive when a different vowel inventory is active.
- Mic quality warnings are buried; users can't perceive when poor SNR increases vowel confusion.

### Operable

- Correcting a single misheard vowel requires selecting the word, re-dictating, or navigating candidate lists; one-step vowel replacement is missing.
- Switching to a closer microphone to improve vowel clarity takes several settings pages; rapid recovery is hard.
- Voice access lacks quick phonetic spelling mode ("A as in Alpha") on demand; users can't operate fast disambiguation.
- IME/Dictation interplay can steal focus mid-correction; keyboard fallback during speech repair is unreliable.

### Understandable

- No inline tips explain how mic distance and room acoustics affect vowel quality; guidance is web-only.
- Recognition errors attribute to "network" or "service" rather than "low confidence on vowels"; users misdiagnose causes.
- Language settings don't explain vowel inventory differences between dialect packs; users expect identical recognition.
- Correction UI doesn't preview alternatives with minimal pairs; choosing the target vowel is guesswork.

### Robust

- Speech APIs expose text but limited phoneme/confidence traces; AT can't coach vowel articulation or suggest minimal pairs.
- Offline speech packs vary widely in vowel modeling; recognition quality degrades without connectivity.
- Cross-app dictation contexts reset adaptation; learned vowel preferences don't persist between shells.
- No system signal for "speech confidence low"; helpers can't auto-prompt OSK when vowel confusion spikes.

## Mobility of a single joint

**ICF Category:** Mobility — Mobility of a single joint

### Perceivable

- Small toggle switches in Settings have minimal labels and spacing; users relying on one-finger input mis-tap.
- Window resize handles are thin; users with limited finger flexion can't perceive a reliable grab area.
- Touch keyboard key popups are small; near-vision plus single-joint constraints reduce recognizability of alternates.
- System tray icons collapse into overflow with tiny chevrons; single-finger reach and sightline make discovery hard.

### Operable

- Drag gestures (rearranging tiles, sliders) require continuous movement; single-joint mobility makes sustained drags painful.
- Context menus open on press-and-hold; maintaining pressure is difficult for limited joint mobility.
- Closing notifications requires tapping a small "X"; keyboard dismissal shortcuts aren't surfaced near the control.
- Precision selection in text fields is hard with single-finger input; handles are small and close to content.

### Understandable

- Settings do not explain difference between Sticky Keys, Filter Keys, and Mouse Keys for single-joint strategies.
- Touch gestures vs. tap alternatives aren't documented in-product; users assume drag is required.
- No clear guidance on enlarging hit targets beyond system scale; users expect one control to increase all tap areas.
- Pen button mapping lacks examples for "hold-to-right-click" alternatives suitable for single joint use.

### Robust

- Not all apps honor system-wide touch target sizes; AT can't enforce larger minimum hit areas programmatically.
- Secure desktop blocks custom gesture substitution; single-joint shortcuts fail on UAC/lock screens.
- Automation coordinates differ across frameworks; pointer prediction for single-finger taps is inconsistent.
- OSK invocation/dismissal events aren't unified; companion tools can't guarantee one-tap keyboard access.

## Mobility of several joints

**ICF Category:** Mobility — Mobility of several joints

### Perceivable

- Quick Settings tiles are compact and arranged tightly; scanning for the right tile is hard with limited head/arm mobility.
- Virtual desktop thumbnails are small; with restricted movement and magnification, context cues are missed.
- Edge gestures and corner targets rely on large range-of-motion; elements at extremes are hard to spot.
- Fine-grain sliders (volume, brightness) have thin tracks; state is difficult to perceive while minimizing movement.

### Operable

- Multi-step flows (Bluetooth pairing, network sign-in) require repeated reach to opposite UI regions; compounded motion is painful.
- Drag-and-drop operations across windows require gross arm movement; keyboard equivalents aren't obvious.
- Snap Layouts via hover demands precise placement; invoking via keyboard is not discoverable.
- Context switching between Settings panes resets scroll position; re-navigation adds unnecessary motion.

### Understandable

- No in-product patterns explain "minimal-movement" alternatives (shortcut keys, search-first) for common tasks.
- Gestures vs. keyboard routes aren't contrasted for each task; users can't choose the least motion path.
- Settings for pointer speed/acceleration don't explain tradeoffs for limited range of motion.
- Snap/Desktops documentation lacks examples optimized for small, consistent movements.

### Robust

- AT cannot uniformly remap high-motion gestures to simple key combos across legacy and modern shells.
- Some apps hard-code drag-only interactions; automation layers can't substitute click-then-select sequences.
- Window managers conflict with external macro tools; movement-saving routines fail unpredictably.
- Programmatic scroll anchors aren't always exposed; returning to prior position for reduced movement is unreliable.

## Power of isolated muscles

**ICF Category:** Mobility — Power of isolated muscles

### Perceivable

- Focus rings and hover states are subtle; users relying on small, weak movements can't perceive successful targeting.
- Button press feedback is minimal in some dialogs; weak clicks don't yield visible confirmation.
- OSK key activation highlights are brief; users can't perceive whether a light tap registered.
- Scrollbars auto-hide; weak micro-scrolls don't reveal the bar, obscuring position.

### Operable

- Press-and-hold gestures (right-click, drag) require sustained force; weak muscle power can't maintain activation.
- Small checkboxes and radio buttons demand precise activation; accidental misses force repeat attempts.
- Window snapping by drag requires grip strength; keyboard routes aren't discoverable for low-power users.
- Hardware keys (volume, brightness) need travel/force; software alternatives are hidden.

### Understandable

- There's little guidance on reducing required press force (e.g., enabling "Tap to click", "Sticky Keys").
- "Filter Keys" benefits for tremor vs. weakness aren't explained; users choose ineffective aids.
- Pointer acceleration and dwell-click options aren't related in docs; users can't design low-force strategies.
- Accessibility shortcuts list doesn't suggest combinations to minimize effort (e.g., Win+U, Win+Ctrl+Enter).

### Robust

- Not all frameworks expose a "dwell click" action; AT can't universally substitute forceful clicks with dwell.
- Synthetic click events from AT are blocked by some secure surfaces; low-force workflows break.
- Per-control minimum sizes aren't queryable; companions can't enforce low-effort hit targets across apps.
- Focus and activation events fire inconsistently across app types; weak-tap detection is unreliable for AT.

## Power of muscle groups

**ICF Category:** Mobility — Power of muscle groups

### Perceivable

- Subtle pressed states on large buttons (e.g., Quick Settings tiles) don't visibly confirm activation after light taps.
- Cursor focus rings are faint during drag operations; users can't perceive whether a low-force grab "took."
- Taskbar auto-hide provides minimal visual affordance; small shoulder or elbow movements fail to reveal targets.
- On-screen keyboard (OSK) modifier latch indicators are small; users can't see when Shift/Ctrl are engaged for low-force typing.

### Operable

- Multi-key shortcuts (e.g., Win+Shift+S) require concurrent arm/hand actions; low proximal strength users can't perform them.
- Dragging windows between monitors requires sustained shoulder movement; keyboard alternatives aren't discoverable.
- Resize/drag of split views demands continuous force; there's no "select size" alternative without holding.
- Press-and-hold to invoke context menus is fatiguing; dwell-click isn't available natively across all surfaces.

### Understandable

- Settings don't plainly explain how Sticky Keys and Toggle Keys reduce simultaneous press force for common shortcuts.
- Pointer acceleration vs. speed isn't framed for reduced gross-motor power; users can't tune to minimize effort.
- Documentation doesn't offer "low-force" patterns (e.g., Win+X menu, search-first) for frequent admin tasks.
- No step-by-step guidance to replace drag operations with select-then-apply actions to conserve muscle power.

### Robust

- Frameworks expose inconsistent APIs for dwell/toggle activation; AT can't reliably replace forceful press-and-hold.
- Secure surfaces (UAC, lock) block automation-based shortcuts; low-force workflows collapse at critical prompts.
- Third-party mouse drivers override OS click settings; low-force click strategies don't persist system-wide.
- Programmatic minimum target sizes aren't enforceable across apps; companions can't guarantee large, low-effort hit areas.

## Watching

**ICF Category:** Activities — Watching

### Perceivable

- Default subtitle size and contrast in some apps are small/low; long-form viewing strains visual tracking.
- Auto-hide media controls obscure progress and caption toggles; users miss when playback state changes.
- HDR and auto-brightness shifts cause sudden luminance jumps; details wash out during critical scenes.
- Picture-in-picture windows have tiny controls; viewers can't perceive available actions at typical distances.

### Operable

- Keyboard media shortcuts vary across apps; pausing or toggling captions isn't operable with consistent keys.
- Seeking requires precise pointer control on thin progress bars; switch/keyboard users can't nudge timecodes reliably.
- Full-screen toggles don't announce or preserve focus; exiting returns focus unpredictably for AT users.
- Live Captions window overlaps content and steals focus; users can't operate playback while reading.

### Understandable

- Differences between app subtitles and system Live Captions aren't explained; users choose the wrong captioning layer.
- HDR/SDR tone mapping settings are technical; users can't predict readability of UI over video.
- Auto-play previews in Start/Widgets lack controls disclosure; users don't know how to stop motion.
- Scaling and caption style interactions aren't documented; text appears clipped after zoom changes.

### Robust

- DRM-protected video can render captions in bitmaps; screen readers and AT can't access caption text programmatically.
- Now Playing metadata and timecodes aren't consistently exposed; assistants can't synchronize guidance with scenes.
- Per-app caption engines vary (WebView, UWP, Electron); style and persistence don't roam uniformly.
- Display power plans throttle brightness adjustments; AT prompts for rest breaks can't read accurate luminance state.

## Listening

**ICF Category:** Activities — Listening

### Perceivable

- Global media controls show small artwork and truncated labels; it's hard to perceive what is playing.
- Device-switch toasts are brief and low-contrast; users miss that audio moved to a different output.
- Loudness normalization state isn't indicated; users can't perceive why volume fluctuates across tracks.
- Per-app meters in the mixer are thin; users with low vision can't perceive active streams.

### Operable

- Quickly routing one app to headphones and another to speakers takes many steps; everyday listening setups are hard to operate.
- Media keys don't always control the intended app; users must cycle focus to regain control.
- There's no system gesture to boost dialog frequencies temporarily; speech becomes unintelligible without deep app EQ.
- Mono toggle and spatial audio are in separate panes; switching modes mid-listen interrupts flow.

### Understandable

- Terms like "Exclusive mode", "Communications device", and "Duck other sounds" aren't explained with scenarios.
- Spatial audio branding implies benefits for speech clarity; users expect intelligibility gains that alerts/music modes don't deliver.
- Mixer separates input vs. output without plain-language guidance; users misconfigure microphones vs. speakers.
- Loudness normalization vs. dynamic range compression isn't contrasted; users can't choose for quiet environments.

### Robust

- Now Playing/Media Session metadata is inconsistently implemented; AT can't reliably announce track and time.
- Exclusive-mode apps bypass system effects and captions; listening accommodations don't apply universally.
- Bluetooth profile switches (A2DP/HFP) aren't consistently broadcast; assistants miss audio-path changes.
- No unified API to request "speech-optimized" EQ at OS level; third-party tools can't standardize clarity aids.

## Other purposeful sensing

**ICF Category:** Activities — Other purposeful sensing

### Perceivable

- System status signals (network, storage, battery) hide in small tray icons; purposeful monitoring is hard at a glance.
- Background task progress shows as thin taskbar lines; users can't perceive multi-app progress concurrently.
- Reliability Monitor warnings use dense tables; anomalies aren't visually prioritized for sensing.
- Quiet Hours icon is subtle; users can't perceive if sensing is temporarily suppressed.

### Operable

- Aggregating health data (updates, security, storage) requires switching panels; operating a single "status board" isn't supported.
- Toast history isn't easily filterable by type; users can't operate targeted sensing for security vs. system vs. app.
- Pinning live tiles/Widgets for sensing is limited; users can't persistently surface custom indicators.
- Keyboard access to system trays varies; sensing tasks require mouse to drill into each indicator.

### Understandable

- Severity terminology differs across subsystems ("warning", "recommendation", "attention"); sensing priorities are unclear.
- Update vs. upgrade language isn't plain; users misinterpret what requires action now vs. later.
- Iconography for similar states (syncing vs. paused) isn't explained; users misread sensor cues.
- No overview mapping which settings affect sensing (Focus, battery saver, notifications); users accidentally silence signals.

### Robust

- APIs for system status are fragmented; AT can't build a unified sensing dashboard that stays in sync.
- OEM tools duplicate or override system indicators; sensing signals conflict or drift.
- Some alerts are bitmap-only banners; automation can't extract semantic state for sensing logs.
- Notifications lack standardized fields (severity, owner); assistants can't prioritize sensing across apps.

## Copying

**ICF Category:** Activities — Copying

### Perceivable

- Clipboard history (Win+V) thumbnails truncate text and images; learners can't perceive which item to replicate.
- Copy progress (Explorer) uses thin taskbar overlays; the extent of a copy task isn't clearly visible.
- Drag-while-holding Ctrl shows a small "plus" badge; the cue for "copy vs. move" is easy to miss.
- Format painters in some Office-hosted surfaces provide icon-only feedback; style being copied isn't visually explicit.

### Operable

- Copy/paste keyboard shortcuts differ for some international layouts; learners can't operate consistent muscle memory.
- Explorer copy with keyboard only requires multiple steps to set destination; learners lose focus switching panes.
- Right-click menus move "Copy as path" and "Copy" between classic and modern menus; learners can't operate a stable flow.
- Selecting non-contiguous text with keyboard is inconsistent across apps; copying examples to compare is difficult.

### Understandable

- Distinctions among copy, cut, link, and shortcut aren't explained; learners confuse duplication with reference.
- Clipboard format retention (rich vs. plain text) isn't surfaced; pasted results don't match expectations.
- Drag-copy rules (Ctrl vs. Alt modifiers) aren't taught in-product; learners can't predict outcomes.
- Cloud clipboard sync lacks simple examples; learners don't understand what travels across devices.

### Robust

- Clipboard APIs expose limited formatting metadata; AT can't warn if content will lose structure on paste.
- Some legacy dialogs block clipboard events; screen readers can't confirm that copy actually occurred.
- Cloud clipboard may be disabled by policy without notice; learning flows relying on cross-device examples fail.
- Drag-and-drop copy operations aren't consistently exposed to automation; teaching tools can't mirror steps.

## Learning to read

**ICF Category:** Learning — Learning to read

### Perceivable

- System fonts and small default sizes in Settings reduce letterform distinction; new readers struggle to track lines.
- High-motion UI (widgets, tips) competes with reading surfaces; sustained attention is harder.
- Caret and selection contrast is low in some apps; learners can't perceive where decoding should start.
- Narrator's default verbosity floods screens with info; decoding the primary sentence becomes harder.

### Operable

- Turning on reading aids (Magnifier read aloud, Text size, Contrast themes) requires multiple surfaces; learners can't operate them independently.
- Scroll and zoom gestures are sensitive; young learners overshoot lines during guided reading.
- Live Captions steals focus when toggled; keyboard navigation through reading content is interrupted.
- Switching TTS voice or speed is buried; learners can't quickly adapt the voice for phonics practice.

### Understandable

- No in-product "reading mode" guidance explains combining word highlighting, line focus, and reduced distractions.
- Terminology overlaps (Narrator vs. Read aloud vs. Live Captions); learners and educators pick unsuitable tools.
- Phonics and syllable support aren't surfaced in OS tools; expectations for decoding aids are unclear.
- Language packs vs. TTS voices differences are not explained; downloaded voices don't match the text language.

### Robust

- Not all apps expose text to accessibility APIs; reading tools can't provide synchronized word highlights.
- TTS and word-highlighting events aren't unified; third-party tutors can't track progress consistently.
- Family Safety/education policies can disable features; reading supports silently disappear on managed devices.
- Offline voice models vary in quality; reading comprehension aids degrade without internet.

## Learning to write

**ICF Category:** Learning — Learning to write

### Perceivable

- Cursor and selection handles are small in touch contexts; emerging writers can't perceive insertion points.
- Spellcheck underlines are thin and low-contrast; learners miss feedback about errors.
- Handwriting panel previews are compact; letterforms aren't easy to compare to targets.
- Dictation confirmation tones are subtle; learners can't tell when voice-to-text is active to practice drafts.

### Operable

- Switching between pen input, OSK, and hardware keyboard takes multiple steps; learners can't fluidly try modalities.
- One-handed keyboard layouts are hidden; students with developing motor skills can't operate comfortable layouts.
- Undo/redo shortcuts vary in some locales (Ctrl+Z/Y vs. Z/Z); learners can't reliably fix mistakes.
- Voice typing stops when focus changes; learners lose text mid-exercise while selecting examples.

### Understandable

- No scaffolded guidance for stages (trace, copy, compose); OS doesn't suggest features for each stage.
- Autocorrect vs. spellcheck vs. predictive suggestions are not differentiated; learners don't learn from errors.
- Handwriting recognition settings don't explain training benefits; practice doesn't seem to improve results.
- Voice vs. typing vs. pen tradeoffs for early writers aren't described; tool choice is guesswork.

### Robust

- Some apps render text canvases without accessibility trees; AT can't provide writing prompts or feedback.
- IME/handwriting services differ across frameworks; third-party tutors can't maintain consistent insertion.
- Policy or privacy settings can block speech services; voice-writing supports fail silently in classrooms.
- Export of writing attempts lacks tagged feedback; analytics tools can't track development over time.

## Learning to calculate

**ICF Category:** Learning — Learning to calculate

### Perceivable

- Calculator's thin symbols and tight spacing reduce legibility of operators for new learners.
- Graph and chart labels in learning apps render small; numeric scales are hard to read at default sizes.
- Number formatting (grouping/decimal) changes with locale; learners can't perceive consistent place value.
- Taskbar progress overlays for downloads/installations don't show numeric percentages; learners can't compare quantities.

### Operable

- Switching between Calculator modes hides key functions; learners can't operate a steady set of buttons.
- Selecting numbers from tables with keyboard is inconsistent across apps; copying data into Calculator is error-prone.
- OSK number row lacks tactile cues; students enter digits slowly or inaccurately.
- High-contrast themes make some graph points invisible; interacting with plots becomes difficult.

### Understandable

- Order of operations and integer division behavior aren't explained in-app; learners misinterpret results.
- Unit conversion vs. arithmetic modes are not distinguished; students attempt conversions in Standard mode.
- Locale's decimal/grouping rules aren't taught; learners misread 1,000 vs. 1.000.
- Percent key behavior varies by mode; no examples show how it applies in common problems.

### Robust

- Programmatic access to intermediate calculation steps is limited; tutors can't analyze learner strategies.
- Math expressions in some apps are images; AT can't parse or read aloud structure (e.g., MathML absent).
- Clipboard copies of results may drop units; downstream tools lose context for learning tasks.
- Different frameworks handle keyboard input (numpad vs. top row) inconsistently; automation for practice drills fails.

## Acquiring skills

**ICF Category:** Learning — Acquiring skills

### Perceivable

- Tips and tutorial toasts are brief and low-contrast; new users don't perceive guidance when practicing a skill.
- Settings search results highlight small fragments of text; learners miss which control to open.
- Taskbar badges and progress overlays use subtle color differences; novices can't perceive practice milestones.
- Short onboarding videos auto-play without captions enabled by default; instructions aren't perceivable for deaf/HoH learners.

### Operable

- Practice flows (e.g., setting up backups, printers) span multiple panes; keyboard-only learners lose place.
- Tutorial steps in apps open external Settings pages; returning to the lesson requires complex navigation.
- Learning gestures (snap, drag, multi-finger) require precise timing; switch and eye-gaze users can't operate reliably.
- Voice access and OSK can't be toggled in a single action; learners can't quickly try alternative input during practice.

### Understandable

- "Get started" cards lack clear outcomes and required time; learners can't predict commitment for the skill.
- Settings copy mixes similar terms (account sync vs. backup); mental models don't form during learning.
- No step-by-step scaffolding for novice?intermediate paths (e.g., shortcuts for the same task); users stall.
- Error prompts use technical causes rather than teachable fixes; learners don't understand how to recover.

### Robust

- Tutorial surfaces differ by framework; AT can't consistently announce step status or progress.
- Some lessons launch WebView content without proper landmarks; screen readers can't navigate instructions.
- Feature availability varies by policy/edition; learning content doesn't adapt, causing dead-ends.
- Export/print of step-by-step guides lacks structure; external coaches can't track skill acquisition.

## Focusing attention

**ICF Category:** Mental functions — Focusing attention

### Perceivable

- Widget panel motion and rotating backgrounds draw visual attention away from the active task surface.
- Transient notifications cover controls; the focal target is occluded during attention-critical steps.
- Cursor and focus indicators are faint in some apps; users can't perceive the current point of focus.
- Animations in Start/Task View continue during Focus Assist; motion competes with concentration.

### Operable

- Quickly enabling a "quiet workspace" requires touching multiple settings (Focus, notifications, badges, tips).
- Closing background apps to reduce stimuli is multi-step; there's no one-click "reduce distractions."
- Focus sessions can't lock out screen motion app-wide; users must hunt per-app to tame distractions.
- Narrator and magnifier toggles are separate; operating both for focused reading takes extra steps.

### Understandable

- Overlap of Focus Assist, Do Not Disturb, and Priority notifications isn't explained; users expect a single "focus mode."
- "Battery saver" and "background app permissions" aren't connected to distraction reduction in guidance.
- Settings call features by multiple names across versions; users can't build stable attention strategies.
- No built-in recipe lists for attention modes (study, deep work, reading); users lack templates.

### Robust

- Apps can bypass Do Not Disturb with legacy APIs; attention shields fail unpredictably.
- Automation events for "focus mode on/off" aren't consistent; AT can't synchronize complementary supports.
- Programmatic access to suppress motion is limited; tools can't enforce reduced animation across frameworks.
- Cross-device sync duplicates alerts; attention fragments when the same cue appears twice.

## Focusing on one task

**ICF Category:** Mental functions — Focusing on one task

### Perceivable

- Multiple live indicators (badges, tooltips, tips) compete for gaze; the single task's primary cue is lost.
- Auto-playing previews in Start/Widgets divert attention from the task window in focus.
- PIP windows can obscure the working area; single-task focus is visually fragmented.
- Background sync banners surface mid-task; the main workflow is visually interrupted.

### Operable

- No single toggle disables badges, tips, and app suggestions together; streamlining one-task mode is cumbersome.
- Task View still shows other desktops and suggestions; hiding alternatives to stay on one task is not operable.
- Keyboard focus can jump to toasts when they appear; returning to the task requires extra keystrokes.
- Focus sessions don't block new app launches; accidental Alt+Tab breaks one-task commitment.

### Understandable

- Guidance doesn't outline how to combine Kiosk mode, Focus, and app restrictions for single-task work.
- "Efficiency mode" messaging centers on power; users don't understand its role in limiting background distractions.
- Settings don't present sample "single-task" configs (hide badges, disable widgets); users must discover each toggle.
- There's little explanation of Narrator/Focus mode interplay to keep reading confined to one window.

### Robust

- Legacy apps can raise topmost windows; one-task shells can be hijacked by modal dialogs.
- No universal "quiet mode" API; third-party focus aids can't reliably suppress cross-app cues.
- AT hooks for focus redirection vary; returning focus after an alert isn't consistent.
- Policies to enforce app whitelists don't expose user-friendly events; assistants can't explain denials contextually.

## Shifting between tasks

**ICF Category:** Mental functions — Shifting between tasks

### Perceivable

- Taskbar icons for multiple instances look identical; users can't perceive which window to shift to.
- Alt+Tab thumbnails are small on high-DPI; it's hard to perceive context quickly when switching.
- Snap group labels aren't visible; users can't tell which layout contains the needed task.
- Virtual desktop previews rely on tiny thumbnails; the right context for the next task is unclear.

### Operable

- Alt+Tab and Task View require sustained key holds or pointer movement; low-mobility users can't shift smoothly.
- Moving a window to another desktop requires multiple steps; keyboard routes aren't discoverable.
- Re-creating a lost snap group is manual; switching contexts after accidental closure is high-effort.
- Audio output/input follows the last active app; shifting tasks requires reconfiguring devices.

### Understandable

- The difference between virtual desktops, snap groups, and individual windows isn't explained; users mix them up while switching.
- Settings don't clarify which items persist when switching (audio, clipboard, window positions).
- Taskbar grouping rules aren't documented simply; users misinterpret why windows collapse into one icon.
- No guidance exists for creating labeled contexts (desktop names, color themes) to aid task switching.

### Robust

- Programmatic IDs for snap groups/desktops aren't stable across sessions; AT can't restore or shift contexts reliably.
- Automation access to window lists differs by framework; switcher tools can't show a unified model.
- Cross-monitor DPI and scaling alter coordinates; assistive switchers misplace focus after a shift.
- Notification routing doesn't follow the active context; alerts from old tasks intrude after switching.

## Reading

**ICF Category:** Activities — Reading

### Perceivable

- Default font sizes and thin weights in Settings reduce legibility for continuous reading sessions.
- Notification banners overlap text in the active app; the reading line is occluded mid-sentence.
- Low-contrast hyperlinks in some system pages are hard to distinguish from body text while scanning.
- Scrolling indicators and page positions are subtle; readers can't perceive progress in long documents.

### Operable

- Turning on a "reading setup" (text size, contrast theme, focus mode) requires multiple surfaces; flow breaks.
- Magnifier "read from here" loses focus when dialogs pop; resuming the reading position is cumbersome.
- Keyboard scrolling increments vary by app; readers can't rely on predictable line/paragraph movement.
- Narrator + word highlight isn't available across all surfaces; operating synchronized tracking is inconsistent.

### Understandable

- "Narrator", "Read aloud", and "Live Captions" are not contrasted; readers don't know which to use.
- Text size vs. display scale differences aren't explained; users expect all text to grow uniformly.
- Focus Assist doesn't clearly indicate which banners will still appear; readers can't predict interruptions.
- Reading order settings for Narrator profiles lack plain examples; users can't tune verbosity for comprehension.

### Robust

- Some app content is canvas/bitmap; screen readers and read-aloud tools can't access the text stream.
- Automation events for selection change aren't consistent; external reading aids can't track the caret reliably.
- Contrast and color settings don't propagate into all embedded WebView surfaces; accessible reading styles break.
- Programmatic landmarks are missing in legacy dialogs; navigation-by-heading for long text is unavailable.

## Reading simple sentences

**ICF Category:** Activities — Reading simple sentences

### Perceivable

- System pages use dense paragraphs with limited line spacing; beginning readers lose the sentence line.
- Caret is thin in some edit fields; the starting point for the next simple sentence is hard to locate.
- Animated tips near text pull focus; readers miss a one-line instruction while animations persist.
- Relative timestamps ("a moment ago") replace clear times; simple sentences referencing time become ambiguous.

### Operable

- Line-by-line reading with Magnifier requires repeated commands; simple-sentence practice is laborious.
- Narrator's next/previous sentence command isn't supported in all controls; navigation granularity breaks.
- Turning on color filters to emphasize sentence strips affects the whole OS; quick toggling for practice is hard.
- Keyboard shortcuts to increase line spacing aren't available system-wide; learners can't operate a consistent layout.

### Understandable

- There's no guided "line focus" recipe in Settings; users must assemble features from different panes.
- Verbosity settings aren't labeled with examples ("read punctuation at sentence ends"); comprehension tuning is guesswork.
- Contrast themes vs. dark mode aren't explained for early readers; users expect dark mode to increase legibility.
- Simplified language options for system text aren't surfaced; simple-sentence practice is limited.

### Robust

- Sentence-level navigation isn't exposed uniformly in accessibility trees; coaching tools can't guide line practice.
- Some edit fields don't emit caret-moved events; AT can't synchronize highlighting for sentence reading.
- Exported reading logs (from apps) lack semantic tags; progress on sentence complexity can't be analyzed.
- Focus/quiet mode state isn't broadcast consistently; practice sessions are interrupted by stray alerts.

## Reading complex text

**ICF Category:** Activities — Reading complex text

### Perceivable

- Task Manager, Event Viewer, and MMC surfaces use dense tables; complex prose explanations are hard to pick out.
- Small headings and weak hierarchy obscure the structure of long guidance pages in Settings.
- Mixed relative/absolute dates in lists break narrative flow; complex text referencing time becomes confusing.
- Inline code/monospace snippets use low contrast; readers miss technical tokens within text.

### Operable

- Jumping by heading/landmark in some system docs isn't supported; operating a table-of-contents workflow is difficult.
- Selecting multi-paragraph spans for TTS is error-prone; focus is lost when notifications arrive.
- Scrolling large panes with keyboard varies by control; readers overshoot sections during study.
- Copying formatted examples loses structure; readers can't operate side-by-side comparison effectively.

### Understandable

- Docs use technical terms without in-place definitions; complex passages require context switching to the web.
- Error messages reference components ("servicing stack", "WU") without plain expansions; causal chains are unclear.
- Narrator punctuation and symbol reading defaults overwhelm comprehension; tuning guidance is sparse.
- Examples mix PowerShell, GUI, and registry steps; readers can't follow a single coherent path.

### Robust

- Headings/landmarks are missing from some in-app help; AT can't offer structural navigation for complex pages.
- Export/print of long help topics loses headings; study tools can't preserve structure for annotation.
- Some panes render as images; selectable text and citations aren't accessible to reading tools.
- Stateful docs in Settings don't expose anchors; external notes can't deep-link to sections.

## Reading symbols

**ICF Category:** Activities — Reading symbols

### Perceivable

- System icons use thin strokes or filled variants inconsistently; symbol meaning is hard to perceive at a glance.
- Two-letter language and input codes in the taskbar aren't self-explanatory; symbol decoding is slow.
- Battery and network glyphs vary by theme and OEM; users misread status symbols under low contrast.
- Privacy indicators (camera/microphone) are small; symbol alerts about active sensors are overlooked.

### Operable

- Accessing symbol legends requires hovering or opening deep pages; keyboard-only users can't reveal meanings quickly.
- Changing icon size affects all elements; there's no per-symbol enlargement for critical indicators.
- High-contrast themes can remove internal icon detail; symbols become indistinguishable during operation.
- Tray overflow hides less-used symbols behind a small chevron; reaching legends for those is cumbersome.

### Understandable

- Iconography isn't accompanied by plain-language labels consistently; users can't build symbol literacy.
- Similar symbols for different states (syncing vs. paused) aren't explained; misinterpretation is common.
- Badge semantics (dot, number, exclamation) lack a global legend; meaning differs by app.
- Language/input codes (ENG, DEU, IME) aren't decoded in-tool; users must remember mappings.

### Robust

- Symbol roles/labels are inconsistently exposed via accessibility APIs; AT can't always announce meanings.
- OEM utilities override system icons; symbol semantics drift across devices and aren't programmatically aligned.
- Theming frameworks differ (WinUI, WPF, legacy); symbol sets aren't unified for assistive overlays.
- No standardized export of symbol legends; training tools can't present a consistent glossary.

## Writing

**ICF Category:** Activities — Writing

### Perceivable

- Caret and selection contrast is low in some editors and dialogs; writers can't perceive the active insertion point.
- Spellcheck underlines are thin; misspelled words are difficult to notice at common zoom levels.
- OSK key popups and alternative character hints (diacritics) are small; visual feedback is easy to miss.
- Dictation status and level meters are compact; writers can't perceive whether the system is actively listening.

### Operable

- Switching between hardware keyboard, OSK, handwriting, and voice input requires multiple panes; flow breaks mid-sentence.
- Undo/redo and selection shortcuts vary across locales/layouts; operating consistent edits is difficult.
- Selecting and moving text with touch requires precise handles; tremor or limited fine motor control impairs operation.
- Voice typing stops on focus change; correcting and resuming via keyboard takes several steps.

### Understandable

- Differences between Dictation, Voice access, and IME aren't explained in-product; writers choose suboptimal tools.
- Prediction, autocorrect, and spellcheck aren't clearly contrasted; users misinterpret how text changes occur.
- OSK layout options (split, one-handed) lack guidance; writers don't know which layout fits their context.
- Clipboard plain vs. rich paste behavior isn't surfaced; formatting changes surprise writers.

### Robust

- Text fields implemented as canvas/bitmaps don't expose caret/selection events; AT can't provide writing support.
- Speech services require connectivity for best accuracy; offline modes degrade writing reliability without notice.
- IME behavior differs across frameworks (Win32/WPF/UWP/WebView); third-party writing aids can't maintain consistency.
- Clipboard events/metadata are inconsistent; automation can't reliably suggest corrections after paste.

## Using general skills of writing process

**ICF Category:** Activities — Using general skills of writing process

### Perceivable

- Version history and change tracking indicators are subtle across apps; stages of draft/revision aren't obvious.
- File Explorer "Recent" and Start "Recommended" mix content types; planning stages aren't perceivable at a glance.
- Multiple windows for research (browser, PDF, notes) lack strong visual anchors; writers lose where sources are.
- Notification banners obscure citation or outline panes; process cues are visually interrupted.

### Operable

- Switching among outline, draft, and reference windows requires precise window management; keyboard routes aren't discoverable.
- Creating and restoring snap groups for a writing workspace takes many steps; process breaks on restart.
- Pinning research files across apps is inconsistent; moving between sources and draft is high-friction.
- Voice access and dictation can't be toggled alongside note-taking tools in one action; iteration slows.

### Understandable

- There's no OS-level guidance on building a writing workflow (outline ? draft ? revise ? proof) with Windows features.
- Storage options (OneDrive, File History, local copies) aren't explained with writing scenarios; version safety is unclear.
- Focus sessions aren't mapped to writing phases; users don't know how to combine timers with draft goals.
- Search, tagging, and naming conventions aren't exemplified; writers can't maintain a findable corpus.

### Robust

- Programmatic IDs for snap groups and virtual desktops aren't stable; writing workspaces can't be restored by AT.
- File metadata (tags, comments) is inconsistently exposed; assistants can't manage draft states reliably.
- Cross-app accessibility trees vary; outlining and citation panes aren't uniformly navigable.
- Exported activity logs lack process semantics; coaching tools can't infer writing-stage transitions.

## Using grammatical conventions in writing

**ICF Category:** Activities — Using grammatical conventions in writing

### Perceivable

- Grammar suggestions appear as subtle underlines or tooltips; users miss the nature of the grammatical issue.
- Punctuation and symbol glyphs are thin at default sizes; misused marks aren't easily spotted.
- Autocorrect corrections don't always show explicit change highlights; writers don't see what was modified.
- IME and dictation substitution feedback is minimal; grammatical errors from recognition are hard to perceive.

### Operable

- Accepting or rejecting suggestions requires small target clicks; keyboard-first routes aren't consistent across apps.
- Switching punctuation input modes (straight vs. smart quotes, locale-specific marks) is buried in settings.
- Voice corrections for punctuation require verbose commands; quick insertion of marks isn't streamlined.
- Language detection toggles move between app and system settings; operating correct grammar language is error-prone.

### Understandable

- Suggestion explanations are terse or missing; users don't learn the rule behind a fix.
- Locale rules (comma vs. period decimal, spacing before punctuation) aren't explained in OS guidance.
- Autocorrect vs. grammar suggestion vs. style guidance isn't differentiated; users conflate types of feedback.
- IME conversion and grammar rules interplay isn't described; writers misapply conventions in mixed-language text.

### Robust

- Accessibility APIs often expose only final text; assistants can't access rule IDs or suggestion metadata.
- Per-app grammar engines differ; third-party AT can't provide a unified command set to manage suggestions.
- Offline language packs vary in grammar coverage; rules disappear without connectivity.
- Clipboard and input events don't encode punctuation semantics; downstream tools lose grammatical intent.

## Using general skills to write compositions

**ICF Category:** Activities — Using general skills to write compositions

### Perceivable

- Outline panes and heading levels lack strong hierarchy; structure of an essay isn't easily perceived.
- Citation/error banners are small; issues in sources or references are overlooked while drafting.
- Multiple monitors with different DPI make paragraph widths inconsistent; visual rhythm is hard to maintain.
- Distraction surfaces (Widgets, tips) remain visually active while composing; focal cues are diluted.

### Operable

- Managing references, notes, and the draft requires juggling windows; keyboard-centric workspace setup is nontrivial.
- Moving sections (multi-paragraph) is cumbersome across apps; drag+drop reordering lacks safe keyboard alternatives.
- Setting consistent styles across apps is multi-step; operating a unified "composition" theme is hard.
- Dictation and research (copy/paste) conflict for focus; resuming compose state takes extra interactions.

### Understandable

- No OS-level templates demonstrate composition patterns (thesis ? evidence ? synthesis); users lack scaffolds.
- Style vs. formatting vs. accessibility guidance isn't integrated; writers can't meet clarity and inclusion goals together.
- Project folders vs. libraries vs. cloud locations aren't explained with composition workflows; files scatter.
- Track changes/comments terminology differs across editors; collaboration guidance isn't uniform.

### Robust

- Outline/heading semantics aren't consistently exposed; AT can't help restructure long documents across apps.
- Citation managers integrate via different frameworks; automation to fetch/update references isn't reliable.
- Snap group IDs and window bounds aren't stable; composition workspaces can't be restored automatically.
- Export formats drop comments and structure variably; external reviewers lose context and annotations.

## Calculating

**ICF Category:** Activities — Calculating

### Perceivable

- Calculator uses tight spacing and small operator buttons; visual parsing of operations is difficult.
- Percentages and units in Settings appear in small, low-contrast text; quantities are hard to compare.
- Taskbar download/progress overlays lack numeric labels; users can't perceive exact values for mental math.
- Currency and date formats vary by locale; inconsistent grouping marks make place value harder to perceive.

### Operable

- Switching Calculator modes (Standard/Scientific/Programmer) hides needed keys; frequent toggling breaks flow.
- Copying numbers from charts or dialogs requires precise selection; keyboard paths to exact values are inconsistent.
- Converting units needs multiple clicks through nested menus; quick mental-check workflows are cumbersome.
- Number entry in some settings uses spinners with large steps; entering exact values by keyboard isn't reliable.

### Understandable

- Order of operations and integer vs. floating division aren't explained; users misinterpret results.
- Percent key behavior differs across modes; no in-app examples for common scenarios (tax, discounts).
- Network speed units (Mbps vs. MB/s) and storage units (GB vs. GiB) aren't clarified; estimates are wrong.
- Rounding rules in displays (battery, storage) are not disclosed; users can't reconcile numbers.

### Robust

- Graph points and progress indicators are often bitmap-only; AT can't retrieve numeric values programmatically.
- Locale settings don't propagate consistently; some apps ignore decimal/grouping conventions.
- Clipboard copies from system surfaces may drop units; downstream tools lose semantic meaning.
- Calculator history export lacks tagged steps; external tutors can't analyze calculation sequences.

## Solving problems

**ICF Category:** Activities — Solving problems

### Perceivable

- Error banners use small text and subtle colors; the problem statement isn't obvious during troubleshooting.
- Multiple alerts stack behind modals; the salient clue is visually buried.
- Settings search results show partial matches without context; users can't perceive which result solves the issue.
- Logs and diagnostics (Event Viewer) use dense tables; key signals are hard to detect.

### Operable

- Troubleshooters launch separate apps and wizards; switching windows mid-problem is high-friction.
- Safe mode and recovery require key sequences and restarts; keyboard-only access paths aren't obvious.
- Copying error codes from dialogs isn't consistent; users retype complex codes manually.
- Network and driver resets demand precise timing and confirmations; assistive workflows are brittle.

### Understandable

- Troubleshooter outcomes don't explain root cause or next steps; users can't learn from the attempt.
- Technical jargon ("servicing stack", "policy") appears without definitions; decision trees are unclear.
- Settings interdependencies (firewall, network profiles, app permissions) aren't mapped; mental models are weak.
- Error dialogs propose multiple unrelated fixes; users can't prioritize the first action.

### Robust

- Diagnostic data is spread across tools (Event Viewer, Reliability, Device Manager); AT can't aggregate signals.
- Some dialogs are bitmap surfaces; automation can't extract codes or copy text.
- Policy/edition differences hide features; problem paths dead-end without clear programmatic remediations.
- Automation events for fix attempts aren't standardized; assistants can't track which step helped.

## Making decisions

**ICF Category:** Activities — Making decisions

### Perceivable

- Security and update prompts use small toggles and subtle severity colors; decision stakes aren't salient.
- Comparison views (storage cleanup options, app defaults) don't highlight differences; choices are hard to see.
- Privacy permissions lists are long with compact rows; important tradeoffs aren't visually prominent.
- Battery/performance sliders lack clear labels; consequences are hard to perceive.

### Operable

- Related controls live in separate panes (e.g., notifications vs. Focus); acting on a decision requires cross-navigation.
- Batch-select or "apply to all" is missing in many lists; repetitive changes are fatiguing.
- Default-app setting requires per-type confirmation; choosing a global decision isn't operable.
- Keyboard focus jumps after confirmation toasts; continuing with the next choice requires recovery steps.

### Understandable

- Copy doesn't summarize tradeoffs (risk, effort, reversibility) for each choice; decisions feel opaque.
- Terminology differs across surfaces ("quiet hours", "focus", "do not disturb"); users can't map choices.
- Policy impacts aren't flagged; users assume a decision didn't "stick" without knowing it's managed.
- No preview/sandbox for choices like default-app changes; outcomes can't be tested safely.

### Robust

- Programmatic decision models (impact, scope) aren't exposed; assistants can't rank or justify options.
- Settings state events are inconsistent; AT can't confirm a decision applied across all relevant surfaces.
- OEM and app layers override system choices; decisions drift without machine-readable reasons.
- Undo history for system changes isn't unified; external tools can't roll back decisions reliably.

## Undertaking a single task

**ICF Category:** Activities — Undertaking a single task

### Perceivable

- Badges, tips, and background notifications compete with the task window; primary cues aren't prominent.
- Task View and Widgets show alternative content; single-task intent isn't visually reinforced.
- Multiple cursor/focus indicators (app vs. OS) can conflict; the active task target is unclear.
- Progress for the current task is indicated by subtle animations; completion state isn't obvious.

### Operable

- No "one-task" toggle to disable launching/alt-tabbing to other apps; staying within the task requires discipline.
- Kiosk/Assigned access isn't easy to configure for personal use; single-task modes are buried.
- Opening help or settings for the task often spawns new windows; returning to the task requires extra steps.
- Voice and keyboard focus can be stolen by toasts; resuming requires multi-step recovery.

### Understandable

- There's no recipe to combine Focus, notifications, and taskbar settings into a single-task profile.
- Guidance doesn't explain persistence-what remains after reboot for a one-task workspace.
- Messaging around "Efficiency mode" is power-centric; users don't realize it can limit background noise.
- No sample templates for single-task activities (exam, writing sprint); users start from scratch each time.

### Robust

- Legacy apps can raise modal/topmost windows; single-task shells are interrupted by system-level dialogs.
- No unified "quiet mode" signal; third-party aids can't reliably suppress cross-app interruptions.
- Programmatic IDs for snap groups/desktops aren't stable; single-task layouts can't be restored post-reboot.
- Focus state isn't consistently broadcast; external tools can't ensure the task window retains input.

## Undertaking multiple tasks

**ICF Category:** Activities — Undertaking multiple tasks

### Perceivable

- Taskbar badges and progress rings are small; users can't quickly perceive which tasks are active vs. idle.
- Alt+Tab thumbnails compress text; task context is hard to recognize when many windows are open.
- Snap group indicators are faint; users miss which cluster of windows belongs to which task set.
- Notification center mixes system/app toasts; parallel task status cues are visually crowded.

### Operable

- Rearranging windows between snap groups requires drag precision; keyboard routes aren't obvious for multi-tasking.
- Audio output follows the last focused app; operating multiple audio tasks requires repeated routing changes.
- Copy/paste between apps is interrupted by modality changes (UAC prompts, dialogs); workflows stall.
- Virtual desktops require several steps to move an app between contexts; quick task switching is cumbersome.

### Understandable

- Differences among snap groups, desktops, and taskbar groups aren't explained; users can't form a mental model.
- No templates show how to set up multi-task workspaces (e.g., research + chat + editor) with shortcuts.
- Focus Assist/Do Not Disturb and per-app notifications interplay isn't clear; concurrent tasks generate noisy cues.
- Clipboard and Cloud Clipboard behavior across apps/devices isn't illustrated; users lose copied context.

### Robust

- Programmatic IDs for groups/desktops aren't stable; AT can't restore multi-task layouts after reboot.
- Media Session/Now Playing metadata is inconsistent; assistants can't manage multi-source audio predictably.
- Automation events for window creation/activation differ by framework; multi-task trackers miss state changes.
- Notification metadata lacks standardized priority/owner; tools can't merge or sort cues across tasks.

## Carrying out daily routine

**ICF Category:** Activities — Carrying out daily routine

### Perceivable

- Start "Recommended" items rotate; routine anchors (what's next) aren't visually stable.
- Calendar and clock flyout show small event details; upcoming routine steps aren't prominent.
- Badge counts lack severity cues; users can't perceive which routine actions are urgent.
- Quiet Hours icon is subtle; routine reminders appear suppressed without a clear visible state.

### Operable

- Setting up recurring focus sessions requires multiple panes; daily routines aren't operable with one control.
- Pinning routine apps to Start/Taskbar is multi-step; maintaining a stable routine layout is tedious.
- Notification rules per app require repetitive configuration; batch editing a routine's signals is missing.
- Switching networks/devices for daily calls takes several actions; routine transitions are friction-heavy.

### Understandable

- Guidance doesn't present "daily startup" and "shutdown" checklists using built-in features (updates, backups, cleanup).
- Focus/Do Not Disturb vs. notification priority is unclear; users misunderstand why reminders don't show.
- Power plans and sleep settings aren't framed around routines; users can't predict device availability.
- Time zone and locale effects on schedules aren't explained; routines fail after travel.

### Robust

- APIs for reminders, calendar, and notifications are fragmented; assistants can't build unified routine dashboards.
- OEM utilities override power/boot behaviors; routine timings drift unexpectedly.
- Quiet modes aren't broadcast consistently; routine alerts are silenced without machine-readable reason.
- Roaming settings sync unpredictably; routine layouts and pins don't persist across devices.

## Handling stress

**ICF Category:** Activities — Handling stress

### Perceivable

- Unexpected full-screen prompts (updates, UAC) interrupt workflows; stress spikes due to loss of visible control.
- Critical alerts share similar visuals with routine tips; stressful events aren't visually distinguished.
- Progress feedback is vague ("working on it"); stress increases when outcomes aren't perceivable.
- Background motion and sounds persist during focus sessions; sensory load stays high.

### Operable

- No single "calm mode" toggle to pause animations, mute non-critical sounds, and suppress badges.
- Restart countdowns allow limited deferral; users can't regain control when stress is high.
- Batch-snoozing notifications across apps isn't available; silencing stressors takes many steps.
- Emergency accessibility shortcuts (contrast, text size) aren't grouped; rapid relief requires hunting.

### Understandable

- System messages rarely state risk and reversibility plainly; users can't judge urgency vs. wait.
- Guidance doesn't explain which features reduce sensory load (reduce motion, mono audio, contrast themes) by scenario.
- Update and security terminology is dense; stress rises when meaning must be researched mid-task.
- Focus sessions lack built-in breathing/pausing cues; coping strategies aren't modeled.

### Robust

- No unified API to request "low-stimulus" mode; third-party aids can't reliably calm the OS environment.
- Apps can bypass quiet modes via legacy notifications; stressors leak through.
- Automation can't pause motion/auto-play across frameworks; calming tools are inconsistent.
- System state for "high urgency" isn't exposed; assistants can't elevate only truly critical alerts.

## Managing one's own behavior

**ICF Category:** Activities — Managing one's own behavior

### Perceivable

- Usage feedback (screen time, app launches) isn't prominent; behavior patterns aren't visible.
- Focus session progress is subtle; users can't perceive adherence to planned behavior.
- Badge and banner designs don't differentiate habits vs. alerts; self-management cues are buried.
- Privacy indicators for camera/mic are small; recognizing when to change behavior (mute/stop video) is delayed.

### Operable

- Rules for app limits require Family Safety or third-party tools; self-imposed constraints aren't operable system-wide.
- Turning on distraction limits (hide badges, mute sounds, reduce motion) involves many toggles across panes.
- There's no quick "lock to app/layout" for self-control; accidental wandering breaks commitments.
- Audit trails of changes (like Focus settings) are sparse; managing one's rules lacks actionable history.

### Understandable

- No first-party guidance on building behavior plans (goals, prompts, locks) with Windows features.
- Terminology across attention features isn't unified; self-regulation plans are hard to articulate.
- Feedback on rule violations (opening blocked apps) lacks plain language; behavior adjustments aren't reinforced.
- Settings don't model graduated steps (e.g., from reminders ? soft blocks ? hard blocks) for behavior change.

### Robust

- No system-wide "self-control" API; assistants can't enforce app limits or layouts universally.
- Focus/quiet mode state isn't consistently broadcast; companion apps can't align reinforcement cues.
- Policy-managed devices override personal rules; self-management tools break without clear signals.
- Activity and usage metrics aren't exposed in a standard way; behavior analytics can't integrate across apps.

## Communicating with - receiving spoken messages

**ICF Category:** Communication — Receiving spoken messages

### Perceivable

- Live Captions window can obscure the speaker video; visual access to lip cues and captions simultaneously is limited.
- Caption font size defaults are small; fine detail in domain terms is hard to perceive at normal viewing distance.
- System mic/speaker change toasts are brief; users miss when audio routes away from their assistive device.
- Audio meter lines in the mixer are thin; it's hard to perceive whether the call/app is actually producing speech.

### Operable

- Starting Live Captions requires opening Quick Settings or Settings; one-keystroke operation during calls is missing.
- Switching the active output to hearing aids or headphones takes several steps; comprehension suffers during the switch.
- Per-app volume balancing needs the mixer; rapid fine-tuning speech vs. background sources is cumbersome.
- Pinning the captions window while controlling the call UI is awkward; focus shifts interrupt reading.

### Understandable

- It's unclear when to use system Live Captions vs. app-native captions; users choose suboptimal caption sources.
- Spatial audio and mono audio toggles aren't explained in relation to speech intelligibility; users misconfigure sound.
- Noise suppression labels vary by app/device; users can't predict how it affects receiving speech.
- Caption accuracy limits (domain vocabulary, accents) aren't surfaced; users over-trust transcripts.

### Robust

- Caption text isn't exposed uniformly across frameworks; assistive tools can't always access the live transcript.
- Exclusive-mode audio can bypass system effects; speech clarity aids don't apply consistently.
- No OS-wide "speech priority" signal; competing audio streams can mask spoken messages without mitigation.

## Reception of single spoken messages

**ICF Category:** Communication — Reception of single spoken messages

### Perceivable

- Toast previews for voicemail/voice notes truncate text; users can't perceive the full single-message context.
- Small caption timing markers make it hard to align a short utterance with the speaker's visual cue.
- Mic mute indicators are subtle; users may not perceive that they missed a brief spoken instruction.
- Audio notifications for a single message play while other sounds are active; the cue isn't distinct.

### Operable

- Replaying the last 10 seconds of system audio isn't available natively; catching a missed line requires app features.
- Quickly turning on captions for a single message needs multiple steps; the message is over before captions start.
- Device switching (speakers ? headset) interrupts the single message; there's no "hold message" control during transfer.
- Keyboard routes to focus the caption window and the call window aren't harmonized; operating both is slow.

### Understandable

- System doesn't explain how latency affects short utterances; users assume all words will appear instantly.
- "Communications device" vs. "Default device" isn't clarified; single-message alerts route unpredictably.
- Caption punctuation settings aren't described; phrasing of short commands gets misread.
- No inline guidance on setting per-app priority so single messages from the call app override background audio.

### Robust

- Caption APIs don't expose "rewind/playback" controls; third-party tools can't fetch or replay the last utterance.
- Some call apps render captions as bitmaps; AT can't read or store the single message text.
- Notification metadata lacks urgency/owner; assistants can't prioritize the call app's single cue over others.
- Audio ducking behavior differs across engines; speech cues may not reliably rise above other audio.

## Reception of complex spoken messages

**ICF Category:** Communication — Reception of complex spoken messages

### Perceivable

- Multi-speaker captions show minimal speaker labels; users can't perceive who is speaking in technical discussions.
- Long captions scroll quickly in a small pane; key clauses are lost from view during complex explanations.
- Contrast of captions over video varies with content; readability drops during diagrams or slides.
- Small timeline/seek controls make it hard to locate specific parts of a long audio recording.

### Operable

- Searching within captions for keywords isn't available system-wide; finding a definition or term is slow.
- Pinning captions beside slides requires manual window management; complex message context is fragmented.
- Speed controls for long recordings are app-specific; operating a consistent 0.75"/1.25" workflow isn't possible.
- Exporting a caption log for later study needs app support; OS-level capture isn't operable from captions UI.

### Understandable

- No guidance on using Focus sessions with long talks (break timers, checkpoints); comprehension wanes.
- It's unclear how caption language vs. display language affect technical terms; mixed-language talks confuse users.
- Caption punctuation/formatting options aren't explained; paragraphs vs. single-line styles impact understanding.
- Users aren't taught to pair captions with transcript after the meeting; review strategies aren't modeled.

### Robust

- Speaker-attribution metadata isn't unified across apps; third-party tools can't color/segment captions reliably.
- Long-session captions may be truncated or cleared; persistence across app changes isn't guaranteed.
- Programmatic hooks for caption search/export are limited; study tools can't integrate consistently.
- Network constraints degrade ASR quality; OS doesn't expose confidence to help manage uncertain segments.

## Communicating with - receiving nonverbal messages

**ICF Category:** Communication — Receiving nonverbal messages

### Perceivable

- Video tiles shrink in grid view; facial expressions and gestures are hard to perceive at default sizes.
- Low-contrast UI over video obscures subtle signals like nods or raised eyebrows.
- Camera privacy indicator is small; users miss when their own nonverbal cues are visible to others.
- Screen-share cursors are thin; pointing gestures in shared content are easy to miss.

### Operable

- Zooming a participant tile during a call isn't standardized; making a signer or speaker large is multi-step.
- Pinning multiple tiles (speaker + interpreter) relies on app support; OS-level layout controls are limited.
- Switching from captions to full-screen video hides the transcript; operating both views at once is awkward.
- Color filters/contrast themes don't always apply to video overlays; enhancing gestures requires per-app workarounds.

### Understandable

- Guidance doesn't explain pairing captions with interpreter view (tile pinning, layout) for mixed communication.
- Users aren't taught to disable background effects that mask hands/faces; nonverbal signals get lost.
- Camera and lighting recommendations aren't surfaced; poor exposure reduces gesture readability.
- Icon-only reaction badges (??, ??) lack text equivalents in some views; intent of nonverbal feedback is unclear.

### Robust

- App frameworks expose video overlays differently; AT can't consistently magnify or enhance gesture regions.
- Reaction/emoji events aren't standardized across apps; assistants can't aggregate nonverbal signals.
- Low-level video processing for contrast/zoom lacks OS APIs; external tools can't reliably improve nonverbal clarity.
- Focus and layout state aren't broadcast; pinned tiles or interpreter layouts don't persist across sessions.

## Communicating with - receiving written messages

**ICF Category:** Communication — Receiving written messages

### Perceivable

- Notification toasts truncate subject lines and use small text; the full message can't be perceived at a glance.
- Action Center mixes app and system banners with low hierarchy; urgent written messages aren't visually prominent.
- Phone Link and chat previews use compact bubbles; long messages and alt-text get clipped.
- High-motion widgets beside text distract from reading the incoming message body.

### Operable

- Expanding a toast to read more requires precise pointer targeting; keyboard routes to "expand" aren't obvious.
- Focus/Do Not Disturb must be toggled in multiple places; operating a "messages-only" mode is cumbersome.
- Switching font size and contrast for messages requires leaving the app; quick readability changes interrupt flow.
- Copying text from some toasts isn't supported; saving a message for later reference is unreliable.

### Understandable

- Notification categories (priority, alarms) aren't explained; users can't set clear rules for written messages.
- Differences between app-native subtitles, Live Captions, and message previews aren't clarified.
- Badge counts don't convey urgency or sender; users misinterpret which written message needs attention.
- Accessibility guidance doesn't model "reading mode" for messages (increase text, reduce motion, pin pane).

### Robust

- Some message previews are bitmap surfaces; AT can't extract or read text programmatically.
- Notification payloads lack standardized metadata (sender role, importance); assistants can't route intelligently.
- Cross-device sync duplicates or drops banners; written messages aren't reliably consolidated.
- Different frameworks (UWP, Win32, WebView) expose message text differently; reading tools behave inconsistently.

## Communicating with - receiving messages in formal sign language

**ICF Category:** Communication — Receiving messages in formal sign language

### Perceivable

- Interpreter tiles are small in multi-participant grids; handshapes and facial grammar are hard to perceive.
- Low-contrast overlays and banners cover signing space; critical nonmanual markers are obscured.
- Variable frame rate/exposure under auto settings reduces motion clarity; fast signing blurs.
- Pinned tiles can be pushed aside by incoming toasts; the signing stream is briefly occluded.

### Operable

- Promoting the interpreter tile to largest view isn't standardized across apps; keyboard routes are inconsistent.
- Pinning two tiles (speaker + interpreter) requires precise pointer work; OS lacks a universal "dual pin."
- Color filters and contrast themes don't reliably apply to video overlays; enhancing hand/face contrast is manual.
- Switching cameras or layouts during signing is multi-step; the interpreter view can be lost.

### Understandable

- Guidance doesn't explain best-practice layouts (interpreter + content + captions) for sign-centric meetings.
- Users aren't taught to disable background blur/effects that remove hands or faces during signing.
- Camera/lighting recommendations for signing clarity aren't surfaced in Settings.
- App-specific "sign language view" features are not contrasted with OS controls; expectations are mismatched.

### Robust

- OS-level APIs don't expose semantic video regions; AT can't consistently magnify the signing area.
- Video layout/pinning states aren't broadcast; interpreter configurations aren't restorable across sessions.
- Reaction/emoji signals aren't standardized; assistants can't correlate nonverbal feedback with signed content.
- Caption and video pipelines are separate; synchronizing sign view with transcripts isn't programmatic.

## Speaking

**ICF Category:** Communication — Speaking

### Perceivable

- Microphone level meters are small and hidden in sub-menus; users can't perceive if speech is being captured.
- Mute indicators are subtle; speakers miss that no one can hear them.
- Noise suppression status isn't prominent; users can't see when clarity aids are off.
- Voice access/dictation states aren't always visible; it's unclear whether the OS is listening for speech.

### Operable

- Push-to-talk and global mute hotkeys aren't standardized; operating speech across apps is inconsistent.
- Switching microphones (laptop ? headset) takes several steps; mid-call changes disrupt speaking.
- Adjusting gain and noise suppression lives in different panes/drivers; quick tuning mid-speech is hard.
- Voice access and call controls can't be toggled together; managing OS commands while speaking is clumsy.

### Understandable

- Labels like "Default device" vs. "Default communications device" aren't explained; speech goes to the wrong path.
- Mic privacy and app permissions interplay isn't surfaced; users misinterpret why speech isn't heard.
- Noise suppression, AGC, and beamforming differences aren't explained; speakers can't choose suitable settings.
- Voice access vs. dictate vs. call controls aren't contrasted; users expect one to control all speech contexts.

### Robust

- Exclusive-mode apps can seize the mic; OS-level aids (noise suppression) don't apply consistently.
- Automation events for mute/unmute aren't unified; assistants can't enforce safe speaking states.
- Driver panels implement clarity features outside accessibility hooks; AT can't control them.
- No OS signal for "speech in progress"; other alerts interrupt speaking without coordination.

## Producing single words (speech)

**ICF Category:** Communication — Producing single words (speech)

### Perceivable

- Voice command feedback is subtle; users can't perceive which one-word command was recognized.
- Confidence/alternatives aren't shown; single-word misrecognitions go unnoticed.
- Wake words and hotwords lack clear visual confirmation; users aren't sure if the word triggered.
- Latency indicators are absent; short words feel "dropped" without visible processing cues.

### Operable

- Switching to a phonetic alphabet mode isn't one-step; operating corrections for single words is slow.
- Fallback to keyboard or OSK after a misheard word takes multiple actions; rapid recovery isn't operable.
- Per-app microphone selection is buried; choosing a closer mic for single-word clarity is cumbersome.
- No system-level "repeat last recognition" hotkey; practicing single-word articulation is manual.

### Understandable

- Users aren't taught minimal pairs or phonetic hints to correct short commands; learning is slowed.
- Noise suppression and mic placement guidance for single-word clarity isn't offered inline.
- Differences between dictation commands and shell commands aren't clear; "delete" behaves inconsistently.
- Language packs vs. recognition models aren't contrasted for single-word accuracy; expectations don't match results.

### Robust

- Recognition APIs expose text but limited phoneme/confidence data; AT can't coach articulation of short words.
- Offline models vary by language; single-word recognition degrades without connectivity.
- App sandboxes restrict mic/device switching; companions can't route to the best input dynamically.
- No global "low-confidence" event; the OS can't prompt alternative input automatically after a miss.

## Producing sentences (speech)

**ICF Category:** Communication — Producing sentences (speech)

### Perceivable

- Dictation provides minimal on-screen confirmation for multi-word recognition; users can't perceive where errors occurred in a sentence.
- Voice access feedback toasts are small and transient; sentence-level command failures aren't obvious.
- Microphone activity and noise suppression states are buried; users can't quickly see if conditions support clear sentences.
- Confidence/alt hypotheses aren't shown inline; misheard clauses blend into accepted text without visual flags.

### Operable

- Editing a misrecognized clause requires precise selection and re-dictation; no "correct last phrase" hotkey exists system-wide.
- Switching mics (laptop ? headset) during dictation is multi-step; sentence flow breaks mid-thought.
- Punctuation insertion by voice demands exact phrasing; repairing sentence structure is slow.
- Toggling voice access while keeping the app's push-to-talk engaged isn't coordinated; operation conflicts.

### Understandable

- Guidance doesn't explain sentence grammar commands (cap next, period, new line) with examples; users can't form mental models.
- It's unclear when to use Dictation vs. Voice access for composing sentences; expectations differ.
- Differences among languages/accents and their impact on long-utterance accuracy aren't surfaced.
- Microphone placement and room acoustics guidance isn't in-product; sentence clarity tips are missing.

### Robust

- Recognition APIs expose final text but limited token/phoneme timing; AT can't align corrections with sentence spans.
- Offline recognition quality varies by language; long sentences degrade without connectivity.
- Exclusive-mode apps seize the mic; sentence composition aids don't apply consistently.
- No system signal for "dictation low confidence"; helpers can't suggest alternate input during difficult sentences.

## Producing nonverbal messages

**ICF Category:** Communication — Producing nonverbal messages

### Perceivable

- Reaction badges (??, ??) may show icon-only overlays; recipients with low vision can't perceive the gesture's meaning.
- Camera preview is small by default; senders can't perceive if gestures are within frame.
- Background effects hide hands/face edges; nonverbal cues aren't visible to the sender or audience.
- Pointer/highlight tools during screen share are thin/low-contrast; pointing gestures aren't noticeable.

### Operable

- Pinning self-view large for gesture checks isn't consistent across apps; operation is app-specific.
- Switching between captions and full video to monitor reactions requires multiple steps; gesture timing is lost.
- Toggling background effects and exposure adjustments lives in different panes; rapid correction is hard.
- No OS-level hotkey to broadcast a standardized reaction; nonverbal responses depend on app features.

### Understandable

- Guidance doesn't explain which backgrounds/lighting preserve hand visibility; users pick ineffective settings.
- Reaction icon semantics differ by app; users assume universal meanings that aren't shared.
- No examples show combining pointer highlights with captions to clarify nonverbal intent.
- Camera/mic privacy indicators aren't tied to clear instructions; senders misjudge when they're visible/audible.

### Robust

- Video overlay APIs differ; AT can't consistently amplify hand/face regions for nonverbal clarity.
- Reaction events aren't standardized; assistants can't aggregate nonverbal outputs across apps.
- Screen-share cursors are not exposed semantically; external tools can't reinforce pointing gestures.
- Pinned layout state isn't broadcast; self-view/recipient-view arrangements don't persist across sessions.

## Producing messages in formal sign language

**ICF Category:** Communication — Producing messages in formal sign language

### Perceivable

- Self-view tile is small; signers can't perceive if hands and facial grammar remain within frame.
- Auto-exposure and background blur reduce contrast of handshapes; articulation isn't visible.
- Overlaid UI (toolbars, captions) covers the signing space; critical nonmanual markers are hidden.
- Frame rate drops under power-saving; fast signs appear smeared to the sender.

### Operable

- Switching layouts to maximize self-view and interpreter takes multiple controls; sign feedback loops are slow.
- Adjusting camera settings is split across the app and OS camera controls; tuning while signing is cumbersome.
- Pinning interpreter + content simultaneously depends on app; there's no OS-level dual-pin.
- Color filters don't apply uniformly to video; enhancing hand/face contrast requires per-app tweaking.

### Understandable

- No built-in tips about camera distance, angle, and lighting for clear signing.
- Guidance doesn't explain disabling background effects that occlude hands.
- The interplay of captions, interpreter view, and content sharing isn't documented for sign-first workflows.
- App vs. OS responsibility for sign layouts is unclear; users blame the wrong layer.

### Robust

- No API for semantic "signing area"; AT can't guarantee persistent magnification of hands/face.
- Video layout states aren't exposed; assistants can't restore signer-centric arrangements.
- Reaction/emoji streams aren't standardized; nonverbal feedback can't be correlated with signed output.

## Writing messages

**ICF Category:** Communication — Writing messages

### Perceivable

- Message compose areas use small fonts and thin carets; authors can't perceive insertion or selection easily.
- Spell/grammar markers are subtle; feedback on errors in short messages is easy to miss.
- IME candidate lists are compact; alternative characters are hard to perceive at normal distance.
- Dictation confirmation icons are small; it's unclear when speech-to-text is capturing a message.

### Operable

- Switching between keyboard, OSK, handwriting, and voice input is multi-step; composing quickly is difficult.
- Attachment and emoji pickers require precise pointer control; keyboard routes differ by app.
- Undo/redo and selection commands vary across locales; fixing mistakes in short messages is inconsistent.
- Voice typing stops on focus change; message text can be lost when switching apps.

### Understandable

- Plain-language guidance doesn't show how to enable "messages mode" (bigger text, reduce motion, captions nearby).
- IME vs. autocorrect vs. predictive suggestions aren't explained; users confuse how text changes.
- Language detection and switching rules aren't visible; mixed-language messages surprise writers.
- Clipboard behavior (rich vs. plain) during paste isn't surfaced; formatting in messages changes unexpectedly.

### Robust

- Text areas implemented as canvases don't expose caret/selection; AT can't assist composing.
- Speech services and IME providers differ across frameworks; input consistency varies by app.
- Notification focus stealing can interrupt composition; automation can't guarantee message persistence.
- Clipboard metadata is limited; downstream tools lose context like sender/subject when pasting.

## Conversation

**ICF Category:** Communication — Conversation

### Perceivable

- Live Captions can overlap video tiles or shared content; turn-taking cues and captions compete visually.
- Active speaker highlight is subtle in some apps; users can't easily perceive who currently holds the floor.
- Notification toasts pop over call controls; in-call chat or reactions hide conversation context.
- Mixer meters are thin; it's hard to perceive which app is producing the conversation audio.

### Operable

- No single hotkey starts/stops OS captions across apps; enabling support mid-conversation is multi-step.
- Switching audio output to a headset during a call requires several clicks; conversation flow is interrupted.
- Pinning the interpreter and speaker tiles simultaneously is app-specific; OS-level layout controls are limited.
- Global push-to-talk/mute isn't standardized; operating consistent turn-taking is difficult.

### Understandable

- It's unclear how Focus/Do Not Disturb interacts with call alerts and chat; users can't predict interruptions.
- Differences between app captions and system Live Captions aren't explained; users choose suboptimal layers.
- Guidance doesn't model setups (caption window + chat + content) for clear conversational flow.
- Audio device roles ("communications device" vs. default) aren't explained with conversation scenarios.

### Robust

- Caption text exposure varies by framework; AT can't reliably access conversation transcripts.
- Exclusive-mode audio bypasses system effects; conversation clarity aids don't apply uniformly.
- Notification metadata lacks standardized priority; assistants can't suppress non-conversation alerts reliably.
- Layout state (pinned tiles, window sizes) isn't broadcast; conversation setups can't be restored.

## Discussion

**ICF Category:** Communication — Discussion

### Perceivable

- Multi-speaker captions have minimal speaker labels; attributions are hard to perceive in debates.
- Small thumbnails in Task View hide which window contains relevant notes or references for the discussion.
- Screen-shared pointers are thin; gestures supporting arguments are easy to miss.
- Simultaneous chat and reactions crowd the view; discussion threads and cues compete for visibility.

### Operable

- Searching within captions for earlier points isn't available system-wide; revisiting arguments is slow.
- Managing a tri-pane layout (slides + captions + notes) requires manual snapping; keyboard routes aren't obvious.
- Switching audio sources for side-by-side videos (clip + call) needs mixer steps; discussion comparisons stall.
- Global hotkeys for "mark moment" or "bookmark" during a talk don't exist; capturing key points is cumbersome.

### Understandable

- No templates show how to arrange windows for structured discussion (evidence, counterpoint, notes).
- Caption settings (punctuation, line length) aren't explained for debates; readability tradeoffs aren't taught.
- Audio ducking and priority cues aren't documented with examples; side audio competes with speakers.
- Guidance doesn't describe recording + captions privacy implications; participants misinterpret consent signals.

### Robust

- Speaker-label metadata isn't standardized; assistants can't color/segment captions by person.
- Caption logs aren't uniformly exportable; study tools can't reconstruct discussion threads.
- Window and app framework differences block unified shortcuts; external "debate tools" can't manage layouts reliably.
- Privacy APIs for recording indicators differ; AT can't consistently announce recording state.

## Using communication devices and techniques

**ICF Category:** Communication — Using communication devices and techniques

### Perceivable

- Settings for TTY, mono audio, and caption styles are in different places; users can't perceive a unified setup.
- Device-switch toasts are brief; users miss when audio routes away from their assistive device.
- Small indicators for Bluetooth profile (A2DP/HFP) hide whether the mic path supports calls or media.
- Mic privacy status is subtle; users can't perceive blocks that prevent assistive speech tools.

### Operable

- Routing one app to headphones and another to speakers requires multiple mixer steps; everyday comm setups are hard.
- Enabling captions, noise suppression, and mic boost isn't one action; operating assistive chains is tedious.
- Per-app mic selection is buried; switching to a proximity mic mid-call is cumbersome.
- TTY or relay preferences aren't surfaced during call setup; accessible dialing takes extra steps.

### Understandable

- The difference between "Default device" and "Default communications device" isn't explained in plain scenarios.
- Bluetooth profiles and their tradeoffs (HFP vs. A2DP) aren't described; users expect full quality + mic simultaneously.
- Caption vs. transcript vs. chat terminology isn't contrasted; expectations for persistence and search are unclear.
- Relay/TTY setup lacks step-by-step walkthroughs; new users can't validate their path before a call.

### Robust

- Now Playing/Media Session and call metadata differ by app; AT can't unify controls for assistive devices.
- Exclusive-mode audio bypasses OS effects and captions; assistive chains break unpredictably.
- Device role and route changes aren't consistently broadcast; companions miss important state transitions.
- APIs for caption text and call state aren't uniform; external aids can't depend on stable hooks.

## Changing basic body position

**ICF Category:** Mobility — Changing basic body position

### Perceivable

- UI targets (close buttons, sliders) are small; users shifting posture can't perceive stable targets quickly.
- Auto-hide taskbar shows minimal affordance; when reclining or standing, users miss where to aim.
- Orientation/scale changes blur text briefly; after repositioning the device, readability drops.
- OSK overlap with apps hides inputs; when changing position to touch type, fields are obscured.

### Operable

- Switching between keyboard, pen, touch, and voice isn't one action; posture-driven modality changes are slow.
- Rotation and scaling settings are split; operating a "standing desk mode" requires several panes.
- Dragging windows while standing needs sustained reach; keyboard routes to snap/resize aren't discoverable.
- Toggling OSK on secure surfaces isn't consistent; changing position at sign-in blocks text entry.

### Understandable

- No guidance explains posture-based profiles (sit/stand/recline) combining input modes and scaling.
- Touch target size, pointer speed, and dwell settings aren't tied to posture scenarios; tuning is guesswork.
- Power/timeout settings aren't framed for position changes; users don't know how to avoid lockouts mid-move.
- Shortcuts for keyboard-free snapping/resizing aren't highlighted; users assume drag is required.

### Robust

- Secure desktop and some apps block OSK/injection; posture-based alternative input fails at critical moments.
- Frameworks vary in exposing hit targets; AT can't enforce larger minimum sizes during posture shifts.
- Auto-rotation and scaling events aren't consistently exposed; companions can't adjust layouts reliably.
- Focus and activation aren't broadcast uniformly; external tools can't keep the intended window active after movement.

## Maintaining a body position

**ICF Category:** Mobility — Maintaining a body position

### Perceivable

- Auto-hide taskbar and small affordances require head/torso lean to reveal; targets aren't perceivable at rest.
- Low-contrast cursors and thin focus rings make it hard to locate the pointer without leaning in.
- Notifications appear far from the current gaze area on ultrawide displays; posture changes are needed to read them.
- Subtle window-resize handles lack clear edges; users must adjust posture to perceive hit zones.

### Operable

- Switching inputs (voice, OSK, pen) isn't a single action; maintaining posture while changing modality is difficult.
- Keyboard-only routes to snap/resize aren't discoverable; users must reach and drag, breaking a comfortable position.
- Touch gestures require reach across large screens; posture must shift to hit distant controls.
- Brightness and volume keys are split across hardware and software; making comfort tweaks breaks position.

### Understandable

- There's no "posture profile" guidance (sit/stand/recline) combining larger targets, louder UI, and reduced motion.
- Pointer speed vs. acceleration isn't framed for minimal movement; users tune settings that increase reach.
- Narrator and Magnifier combinations for distance viewing aren't modeled; reading at rest is harder.
- Workflow recipes for keyboard-first windowing (Win+Arrow, Win+Ctrl+D) aren't surfaced as posture-saving options.

### Robust

- Secure surfaces and some apps block OSK/voice; posture-preserving alternatives fail at sign-in or UAC.
- Frameworks expose hit targets inconsistently; AT can't enforce larger targets across all apps.
- External monitors with differing DPI/scaling cause misaligned hit zones; posture-stable pointing becomes unreliable.
- No single API to request "minimal reach mode"; companions can't coordinate UI enlargement system-wide.

## Fine hand use

**ICF Category:** Mobility — Fine hand use

### Perceivable

- Resize handles, splitter bars, and scrollbars are thin; precise finger placement cues are hard to see.
- Small caret/selection handles in touch contexts hide the true selection range.
- Icon-only toolbars don't reveal state (bold/italic, mic mute) clearly; fine adjustments are error-prone.
- Drag "ghosts" are faint; users can't perceive whether a tiny drag actually engaged.

### Operable

- Small checkboxes/toggles require pinpoint taps; there's no OS enforcement of minimum touch target size across apps.
- Press-and-hold gestures to reveal context menus strain fine control; alternatives aren't universal.
- Precision pointer paths (drawing, curve handles) lack magnetic/snapping aids at OS level.
- Dragging to select noncontiguous items is inconsistent; keyboard equivalents aren't discoverable.

### Understandable

- Guidance doesn't explain Sticky Keys/Filter Keys for compensating tremor in multi-key actions.
- Touchpad precision vs. tap-to-click and palm rejection tradeoffs aren't framed for fine control.
- Pen calibration and pressure curves aren't described in functional terms; users can't tune for steadiness.
- No examples show replacing drag operations with select-then-apply to reduce small muscle strain.

### Robust

- Third-party drivers override OS click/drag settings; fine-motor accommodations don't persist.
- Canvas-based controls don't expose granular hit regions; AT can't enlarge or snap to micro-targets.
- DPI scaling changes alter effective target sizes unpredictably; assistive overlays misalign.
- No OS-wide API for "snap to control edges" for pen/mouse; precision aids are app-specific.

## Hand and arm use

**ICF Category:** Mobility — Hand and arm use

### Perceivable

- System feedback for drag targets (snap zones, docking) is subtle; extended reach makes cues easy to miss.
- Thin window borders obscure grab regions; arm extension is required to test edges visually.
- Cursor changes for resize/move are small; when reaching across screens, users can't perceive mode changes.
- Taskbar overflow chevron is small; finding hidden icons requires arm repositioning and visual search.

### Operable

- Window dragging between monitors demands sustained arm elevation; keyboard-only move/snap paths aren't discoverable.
- Resizing split views requires continuous hold; there's no select-then-apply size operation.
- Context menus triggered by long-press are fatiguing; alternate activation methods are inconsistent.
- Scrolling long panes without auto-scroll zones forces repetitive arm movement; OS lacks dwell-scroll.

### Understandable

- No guidance explains keyboard-centric window movement (Alt+Space, Win+Arrow) as arm-sparing techniques.
- Pen vs. mouse vs. touch tradeoffs for reach aren't described; users pick high-effort inputs.
- Settings don't illustrate low-effort patterns (search-first, Win+X) to avoid deep navigation.
- Sticky Keys/Toggle Keys benefits for multi-key actions aren't demonstrated for arm-lift reduction.

### Robust

- Automation to replace drag/hold varies by framework; tools can't emulate low-effort gestures universally.
- Secure dialogs block alternative input; arm-sparing flows fail at UAC or credential prompts.
- Pointer device settings don't roam consistently; arm-friendly tuning is lost across devices.
- Minimum target-size policies can't be enforced OS-wide; companion apps can't guarantee low-reach targets.

## Walking

**ICF Category:** Mobility — Walking

### Perceivable

- UI feedback relies on small, central cues; while moving, users can't perceive status out of the corner of the eye.
- Motion blur on portable screens hides thin type and controls; on-the-go reading suffers.
- Audio notifications mix with environmental noise; spoken prompts lack distinct visual reinforcement.
- Auto-rotate and adaptive brightness change mid-step; sudden shifts reduce readability.

### Operable

- Precise taps and small targets aren't operable while walking; OS doesn't provide enlarged "on-the-move" UI.
- Voice access and dictation can't be toggled together with a hardware key; quick hands-free switch is missing.
- Gesture sensitivity leads to accidental app switching; walking bumps trigger unintended actions.
- One-handed OSK layouts aren't easy to discover; thumb reach while walking is limited.

### Understandable

- No "mobility mode" guidance explains combining large text, high contrast, voice control, and bigger targets for on-foot use.
- Audio ducking and mono audio benefits while outdoors aren't described; speech cues get lost.
- Battery saver and location services impact on real-time navigation isn't explained; expectations misalign.
- Warnings about using devices while moving aren't contextual; users lack prompts to pause safely.

### Robust

- No unified API to request "large targets while mobile"; companion apps can't adapt the shell for walking.
- Sensors and motion state aren't exposed consistently to accessibility layers; AT can't change modes automatically.
- Orientation/brightness events are handled differently by frameworks; hands-free tools can't stabilize display state.
- Offline voice models vary in quality; hands-free control while walking fails without connectivity.

## Looking after one's health

**ICF Category:** Self-care — Looking after one's health

### Perceivable

- Health-related reminders (meds, breaks) rely on small toasts; cues are easy to miss among other notifications.
- Focus session timers and progress rings are subtle; it's hard to perceive adherence to rest schedules.
- Quiet modes hide badges and banners; critical well-being alerts appear suppressed without a clear visible state.
- Blue light and brightness changes provide limited visual feedback; users can't perceive when eye-strain mitigations are active.

### Operable

- Enabling "health mode" (night light, reduce motion, Do Not Disturb) requires multiple panes; operation during symptoms is hard.
- Break reminders can't be snoozed/stacked across apps with one control; adherence becomes click-heavy.
- Adjusting text size/contrast mid-task is multi-step; users experiencing eye strain can't act quickly.
- Per-app sound routing complicates mindfulness or guided-breathing audio while other apps play.

### Understandable

- Guidance doesn't model "self-care profiles" (migraine, sensory overload) using built-in features.
- Night light, HDR, and contrast theme interactions aren't explained; users misinterpret comfort tradeoffs.
- Focus/Do Not Disturb language doesn't clarify which health reminders will still break through.
- Battery saver and performance modes' effects on accessibility (voices, captions) aren't described for health scenarios.

### Robust

- No unified API for "low-stimulus" mode; health companion apps can't reliably calm the environment.
- Accessibility state (contrast, text size) isn't broadcast uniformly; third-party reminders can't adapt displays.
- Notification metadata lacks standardized severity; health alerts can't be prioritized programmatically.
- Policy or OEM overlays override visual comfort settings; health-focused configurations drift.

## Assisting others

**ICF Category:** Domestic life — Assisting others

### Perceivable

- Remote assistance prompts (Quick Assist) use small dialogs; care recipients may miss requests for consent.
- UAC and secure desktop transitions dim the screen; supporters can't perceive when control is paused.
- System status (mic on, recording) indicators are subtle; assistants can't see if communication channels are active.
- Cursor trails and highlight options are limited; care recipients can't perceive where the helper points.

### Operable

- Granting and regaining control in Quick Assist requires precise timing; keyboard-only operation is inconsistent.
- Audio routing between call app and system sounds is manual; side coaching and control conflict.
- Copying error text from system dialogs for the person you're helping isn't reliable; transcription is manual.
- Switching magnification or captioning while assisting requires app and OS coordination; flow breaks.

### Understandable

- Consent, view-only, and full control aren't differentiated clearly in dialogs; roles are misunderstood.
- Guidance doesn't explain safe patterns for sharing credentials or handling UAC prompts while assisting.
- Screen annotation and pointer highlighting features are scattered; collaboration steps aren't modeled.
- Privacy indicators and recording policy during assistance aren't explained; expectations misalign.

### Robust

- Secure desktop blocks remote control; assistance workflows break at critical prompts.
- Accessibility events (focus, selection) aren't relayed over remote sessions uniformly; assistive cues drop.
- App frameworks differ in text extractability; helpers can't programmatically capture errors or logs.
- Network and policy constraints limit screen-sharing features; fallback paths aren't standardized.

## Basic interpersonal interactions

**ICF Category:** Interactions & relationships — Basic interpersonal interactions

### Perceivable

- Presence/availability indicators are small or color-only; users can't perceive social status at a glance.
- Reaction icons in calls may be icon-only; intent isn't perceivable for low-vision users.
- Notification previews truncate sender/context; greeting or acknowledgment cues are missed.
- Mic/camera privacy icons are subtle; others' ability to see/hear you isn't obvious in time.

### Operable

- Switching between chat, captions, and video controls is multi-step; simple greetings/turn-taking are delayed.
- Pinning a participant to better perceive cues depends on the app; OS-level affordances are limited.
- Muting/unmuting isn't standardized globally; quick social responses (yes/no) are hard while navigating.
- Reaction hotkeys aren't unified; nonverbal affirmation requires precise pointer work.

### Understandable

- Status semantics (busy, DND, presenting) vary by app; etiquette expectations aren't explained at OS level.
- Caption vs. chat intent isn't contrasted; users send private messages expecting captions to carry them.
- Privacy signals (recording, streaming) aren't described with examples; social consent is unclear.
- Focus Assist interplay with chat mentions isn't documented; users miss greetings or @-mentions.

### Robust

- Presence and reaction events aren't standardized; assistants can't unify social signals across apps.
- Caption text exposure varies; AT can't provide consistent social comprehension aids.
- Notification metadata lacks sender role/priority; tools can't elevate interpersonal cues.
- Audio/video device state events differ by framework; companions can't keep users "conversation-ready."

## Complex interpersonal interactions

**ICF Category:** Interactions & relationships — Complex interpersonal interactions

### Perceivable

- Multi-speaker layouts compress faces and hands; subtle cues in negotiations or mediation are hard to perceive.
- Overlaid UI (chat, reactions) hides visual hierarchy in shared documents; turn-taking cues are missed.
- Color-only indicators for roles (host, presenter) aren't accessible; social authority isn't perceivable.
- Caption panes scroll quickly; critical qualifiers and hedges drop off-screen during complex exchanges.

### Operable

- Arranging tri-pane views (slides, participants, captions) requires manual snapping; keyboard routes are sparse.
- Swapping audio devices for breakouts vs. plenary is manual; transitions disrupt nuanced interaction.
- Bookmarking or flagging moments in real time isn't available OS-wide; follow-ups are lost.
- Managing interpreter + presenter + content views depends on app; OS doesn't provide stable multi-role layouts.

### Understandable

- Guidance doesn't demonstrate inclusive meeting setups (caption + interpreter + content) with step-by-step recipes.
- Role terminology (host, co-host, presenter) varies; users misinterpret privileges and expectations.
- No examples explain combining Focus/quiet modes to protect sensitive conversations.
- Privacy and consent signals around recording/transcripts aren't summarized plainly for complex interactions.

### Robust

- Speaker attribution and reaction events aren't standardized; assistants can't reconstruct conversational dynamics.
- Caption search/export hooks are limited; analysis tools can't extract threads and decisions reliably.
- Device and route change events are inconsistent; multi-role sessions lose continuity.
- Layout/pinning state isn't exposed; complex setups can't be saved or restored programmatically.

## Relating with strangers

**ICF Category:** Interactions & relationships — Relating with strangers

### Perceivable

- Caller/meeting participant names in system toasts truncate; users can't perceive whether the request is from a stranger.
- Presence indicators (new contact vs. known) are color-only and small; unfamiliarity isn't obvious.
- Consent/recording icons are subtle; users may not perceive when a stranger is recording the session.
- Profile pictures or initials render at low resolution in small tiles; identity cues are hard to discern.

### Operable

- Blocking or limiting DM/chat from unknown senders requires per-app steps; there's no OS-level "stranger restrictions."
- Reporting suspicious calls/messages isn't unified; keyboard routes to "report" vary by app.
- Quickly masking display name, camera, or background before accepting a stranger's invite takes many clicks.
- Approving screen-share control from strangers uses small buttons and timeouts; keyboard-first acceptance is unreliable.

### Understandable

- Guidance doesn't explain safe defaults (camera off, mic muted, blurred background) when meeting unknown people.
- Call and chat apps use different terms for "requests" vs. "invites"; users misinterpret stranger contact.
- Privacy indicators (recording, live) aren't described plainly; expectations for consent are unclear.
- Security prompts (UAC, remote assistance) lack simple "never allow from unknown accounts" recipes.

### Robust

- Caller identity metadata isn't standardized across apps; assistants can't consistently flag unknown parties.
- Recording/streaming state isn't broadcast uniformly; AT can't warn when strangers begin recording.
- Spam/report events are app-specific; OS-level tools can't aggregate or enforce blocking across surfaces.
- Invitation dialogs on secure desktop block AT; safe-accept/decline flows fail programmatically.

## Informal social relationships

**ICF Category:** Interactions & relationships — Informal social relationships

### Perceivable

- Badge counts don't distinguish close friends from general notifications; social priorities aren't perceivable.
- Small avatars in taskbar previews obscure who is messaging; casual contacts are indistinguishable.
- Reaction icons and status colors are low-contrast; informal cues (??, ??) aren't legible for everyone.
- Quiet modes hide chat banners without clear state; friendly pings look like they vanished.

### Operable

- Pinning friends or groups to Start/Taskbar is multi-step and app-dependent; reaching preferred contacts is slow.
- Switching between chat, voice, and screen share for casual collaboration requires several panes.
- Batch muting/reactivating social chats for focus isn't OS-wide; toggling for a hangout takes many clicks.
- Choosing camera/mic devices for a quick call is buried; spontaneous conversations stall.

### Understandable

- There's no OS guidance on setting shared "hangout modes" (captions on, low motion, music ducking).
- Presence semantics differ by app; "available/idle/away" meanings aren't explained with examples.
- Family Safety, Focus, and quiet modes aren't framed for social time; users expect one toggle to manage all.
- Group name/alias behaviors vary; users misinterpret message origin in multi-app social spaces.

### Robust

- Contact presence and chat metadata aren't standardized; assistants can't unify social signals across apps.
- Per-app notification priorities can't be orchestrated OS-wide; social alerts overwhelm or disappear.
- Call/caption text exposure differs by framework; third-party aids can't maintain consistent accessibility.
- Cross-device sync duplicates messages; informal threads fragment between PC and phone.

## Family relationships

**ICF Category:** Interactions & relationships — Family relationships

### Perceivable

- Family Safety alerts and location updates appear as small toasts; important family signals are easy to miss.
- Shared calendar notifications show limited details; who and what in the family event isn't obvious.
- Pinned contact tiles (via apps) use small avatars; distinguishing family members is difficult at a glance.
- Recording/streaming indicators during family calls are subtle; consent cues aren't perceivable to all.

### Operable

- Setting device time limits or content filters for children requires switching between web and OS; operation isn't unified.
- Sharing screens with less-technical family members is multi-step; Quick Assist and call app flows diverge.
- Switching audio and captioning for multi-generational calls (hearing aids, speakers) takes multiple controls.
- Batch muting non-family chats during family time isn't OS-level; users repeat steps per app.

### Understandable

- Roles and permissions for child vs. organizer vs. member aren't explained with family scenarios.
- Guidance doesn't model accessibility setups for grandparents (larger text, captions, louder UI) in family calls.
- Consent and recording expectations in family groups aren't stated plainly; misunderstandings occur.
- Terminology across Family Safety, Focus, and notifications isn't aligned; families can't set predictable rules.

### Robust

- Family Safety signals don't integrate with OS notification priorities; assistants can't elevate urgent family alerts.
- Cross-app calendar/contact data lacks unified APIs; family tools can't present a consistent dashboard.
- Caption and device-route states aren't broadcast; multi-generation accessibility setups don't persist.
- Remote assistance is blocked on secure desktop; caregivers can't help through UAC prompts programmatically.

## Intimate relationships

**ICF Category:** Interactions & relationships — Intimate relationships

### Perceivable

- Private messages and mentions share visual weight with general notifications; intimate cues aren't prominent.
- Recording and screen-sharing indicators are subtle; users may not perceive when sensitive content is visible.
- Small avatar initials and low-contrast names cause confusion between similarly named partners/contacts.
- Do Not Disturb icons are faint; a partner might assume they're being ignored when banners are hidden.

### Operable

- Creating a "partner priority" notification profile requires per-app rules; there's no OS-wide allow-list.
- Switching to secure content-only screen share (hide alerts, badges) is multi-step; sensitive moments are interrupted.
- Quickly enabling captions and mono audio for late-night calls requires several panes.
- Changing camera/mic devices for privacy (headset, blur) is buried; spontaneous conversations are delayed.

### Understandable

- Guidance doesn't present clear patterns for privacy-first calls (auto-hide alerts, blur, captions, headphones).
- Consent and recording are not explained with intimate-context examples; partners misread cues.
- Quiet mode behaviors with priority contacts aren't described; missed messages cause misunderstanding.
- Terminology around call/device roles isn't simplified; users choose wrong audio routes in private spaces.

### Robust

- Notification APIs don't expose relationship priority; assistants can't guarantee partner messages break through.
- Caption text and device state events aren't unified; intimate setups (headset, captions) don't persist across apps.
- Cross-device sync duplicates messages; sensitive threads fragment across phone and PC.
- App framework differences limit automation of privacy layouts; OS can't enforce sensitive-content modes consistently.

## Informal education

**ICF Category:** Education — Informal education

### Perceivable

- Tutorial videos in browser + notes app create competing motion; captions and text compete visually.
- Small default code fonts in terminal/IDE make self-study examples hard to perceive without manual scaling.
- System toasts obscure key steps in on-screen walkthroughs; instructions are hidden mid-lesson.
- Color-only status in package managers or terminals (errors in red) lacks contrast for quick scanning.

### Operable

- Arranging split views (video, notes, sandbox) requires manual snapping; keyboard routes aren't obvious to beginners.
- Switching audio outputs for tutorials vs. notifications needs multiple steps; focus breaks during learning.
- Installing dev tools may require elevation; touch/voice-only learners can't operate UAC prompts easily.
- Magnifier reading controls don't persist across apps; resuming where you left off is cumbersome.

### Understandable

- No OS recipe explains "learning layout" (pin captions, large text, Focus on) for self-study.
- Audio ducking/mono audio isn't framed for tutorial clarity; learners misconfigure device roles.
- Differences between Narrator, Read Aloud, and Live Captions aren't contrasted for study use.
- File execution policies and SmartScreen warnings use technical language; novices don't know safe next steps.

### Robust

- Caption text and player controls vary by app/WebView; study tools can't rely on consistent hooks.
- Terminal/IDE UIs mix frameworks; screen readers receive uneven structure for code blocks and output.
- No unified API to enforce "study mode" across apps; assistants can't stabilize layouts and quiet modes.
- Downloads/installers present bitmap dialogs; AT can't parse instructions programmatically.

## School education

**ICF Category:** Education — School education

### Perceivable

- Exam lockdown apps hide system accessibility cues; students can't perceive caption or magnifier state.
- Small math symbols and low-contrast diagrams in PDFs are hard to perceive without per-app zoom.
- Class notifications compete with background badges; assignment urgency isn't visually prominent.
- Multiple accounts (school/personal) obscure which mailbox/class is active; cues are subtle.

### Operable

- Switching between LMS, video call, and notes requires juggling windows; keyboard routes aren't taught.
- Joining class calls with the right devices (headset, mic) takes several steps; late arrivals miss content.
- Printing or exporting accessible versions (tagged PDFs) from school portals is inconsistent.
- Per-app restrictions in managed devices block screen readers or OSK in tests; accommodations aren't operable.

### Understandable

- Guidance doesn't show how to set a "class layout" (tile pinning, captioning, notes) for lectures.
- Policy messages use admin jargon; students can't tell why apps or features are blocked.
- Terminology across Focus/quiet modes vs. LMS notifications is unclear; students miss deadlines.
- Math input (IME, OSK) and accessibility aren't explained; symbol entry remains mysterious.

### Robust

- LMS apps vary in accessibility tree completeness; AT can't guarantee navigation/reading order.
- Managed policies disable features inconsistently; accommodations fail depending on classroom profile.
- Caption and device-state events aren't exposed; proctoring tools can't coordinate with accessibility.
- Printing/export pipelines drop tags; accessible structure is lost between apps and OS.

## Higher education

**ICF Category:** Education — Higher education

### Perceivable

- Lecture capture players use small controls; perceiving timestamps and captions during dense content is hard.
- Research PDFs include tiny figures and low-contrast axes; critical details aren't visible at standard zoom.
- Multiple monitors with different DPI cause inconsistent text sizes in journals/IDEs; visual rhythm breaks.
- Terminal/IDE error colors aren't accessible; warnings blend into output during labs.

### Operable

- Switching among citation manager, PDF, and notes requires complex windowing; keyboard workflows aren't discoverable.
- VPN and campus security tools interrupt sign-ins; screen readers can't operate injected dialogs reliably.
- STEM input (LaTeX, math IME, symbol pickers) demands precision; touch/voice users struggle.
- Data tools require admin installs; elevation flows block students on managed laptops.

### Understandable

- No OS guidance for "research mode" (snap layouts for PDF+notes+terminal, quiet notifications).
- Accessibility of publisher PDFs vs. scanned copies isn't explained; students can't predict readability.
- Account/tenant switching between campus and personal services is confusing; data ends up in wrong places.
- GPU/Power settings affecting video playback and compute aren't described in study contexts.

### Robust

- PDF accessibility varies widely; reading order and alt text aren't programmatically reliable.
- VPN/SSO overlays differ by vendor; AT can't consistently announce injected prompts.
- Citation managers integrate via different frameworks; automation to fetch metadata isn't consistent.
- Containerized lab apps block accessibility APIs; research tools can't expose structure to AT.

## Remunerative employment

**ICF Category:** Work & employment — Remunerative employment

### Perceivable

- Time-tracking and status badges are small; perceiving work state (on/off task) is difficult.
- Compliance prompts and phishing warnings use subtle colors; risk isn't prominent while multitasking.
- Remote desktop indicators are minimal; employees can't perceive who has control.
- Thin focus cues in dense enterprise apps make it hard to see which field will receive input.

### Operable

- VDI/RDP sessions intercept hotkeys; operating assistive tools and consistent shortcuts is unreliable.
- Security overlays (MFA prompts) steal focus; keyboard/screen reader workflows are interrupted.
- Switching audio/camera devices between meeting and softphone apps takes several panes; calls drop.
- Enterprise installers require elevation and policy exemptions; accommodations can't be installed quickly.

### Understandable

- Policies and error messages use admin jargon; workers can't infer how to complete the task accessibly.
- Quiet modes vs. priority alerts aren't framed for incident response; critical pings are missed.
- Remote work ergonomics (big targets, voice control) aren't modeled in OS guidance for long days.
- Device role terms ("communications device") aren't explained; confusion causes meeting setup delays.

### Robust

- RDP/VDI sessions proxy accessibility events unevenly; AT support is degraded in remote apps.
- Security and compliance software block injection; assistive automations can't operate sensitive dialogs.
- Notification and presence APIs aren't unified across enterprise suites; assistants can't coordinate work state.
- Roaming profiles and policy overrides reset accessibility settings; accommodations don't persist.

## Basic economic transactions

**ICF Category:** Major life areas — Basic economic transactions

### Perceivable

- Store/payment toasts and browser prompts use small text; totals and fees are hard to perceive at checkout.
- Low-contrast fields for card numbers and CVV in embedded WebView forms reduce legibility.
- Autofill dropdowns overlap totals; the amount due is visually occluded during payment.
- Security indicators (lock, certificate) are small; users can't easily perceive site trust while paying.

### Operable

- Switching between password manager, authenticator, and the checkout field requires multiple windows; flow breaks.
- Copying one-time codes from notifications isn't consistent; keyboard-first redemption is unreliable.
- Touch/pen entry for long card numbers needs precise focus; small hit targets increase error rates.
- Changing output to a private headset mid-transaction to hear OTP or TTS requires several steps.

### Understandable

- Terminology across wallet, password manager, and browser autofill isn't contrasted; users misplace credentials.
- Currency, tax, and shipping fields aren't explained with locale examples; totals differ from expectations.
- SmartScreen and payment warnings use technical language; users can't decide whether to proceed safely.
- No OS-level "paying online" recipe (increase text, enable TTS, focus mode) is provided for clarity.

### Robust

- Autofill and payment forms in different frameworks (WebView2/Win32) expose fields inconsistently to AT.
- Notification metadata for OTPs isn't standardized; assistants can't reliably surface time-sensitive codes.
- Clipboard copies of masked values don't expose semantics; tools can't verify or format entries.
- Policy/OEM overlays may block password managers; accessible payment flows fail without clear signals.

## Complex economic transactions

**ICF Category:** Major life areas — Complex economic transactions

### Perceivable

- Long financial forms show dense tables with small type; interest rates and fees aren't prominent.
- PDF disclosures open in viewers with low-contrast annotations; key terms are hard to perceive.
- Multiple windows (ID upload, e-sign, chat) compete visually; the primary step isn't obvious.
- Color-only validation for required fields isn't sufficient; missing items are overlooked.

### Operable

- Switching between webcam capture, file picker, and form fields requires precise focus control; e-KYC is fragile.
- Signing with pen or OSK in embedded canvases lacks zoom/undo; operating signatures is error-prone.
- Two-factor authentication spans SMS/email/app; retrieving codes while the form times out is cumbersome.
- Saving progress for later is app-specific; resuming across windows isn't operable at the OS level.

### Understandable

- Financial jargon in dialogs (APR, escrow) isn't defined inline; users switch contexts to research terms.
- Locale date/number formats aren't clarified; entries like 01/02/03 are ambiguous.
- Consent for data sharing and device permissions uses technical language; implications aren't clear.
- No "review mode" shows only differences between versions; users struggle to verify revisions.

### Robust

- PDF tagging and reading order are inconsistent; assistive reading of disclosures fails unpredictably.
- Camera/scanner APIs differ by vendor; e-KYC capture tools can't rely on stable hooks.
- Session state across WebView and native dialogs isn't shared; progress is lost after interruptions.
- Signature canvases don't expose semantics; AT can't confirm whether a signature was placed correctly.

## Economic self-sufficiency

**ICF Category:** Major life areas — Economic self-sufficiency

### Perceivable

- Budget dashboards show small charts and color-only deltas; trends aren't perceivable at default sizes.
- Storage/usage meters for cloud drives use subtle text; approaching limits is easy to miss.
- Bill reminders are delivered as low-salience toasts; important deadlines blend with other alerts.
- Multiple accounts (personal/work/school) make ownership of files and bills hard to perceive.

### Operable

- Setting up recurring tasks (pay bills, download statements) requires juggling apps; no OS-level routine builder.
- Exporting transactions from web to desktop finance apps involves multiple formats and manual steps.
- Managing passwords/2FA across services is fragmented; switching devices mid-task interrupts access.
- Finding and opening the correct statement in File Explorer is error-prone; naming and tags aren't enforced.

### Understandable

- There's no OS guidance for a "finance workspace" (snap layouts, quiet mode, captioned calls with banks).
- Account vs. profile vs. tenant language for services isn't explained; users misfile financial data.
- Backup and versioning guidance for critical docs isn't framed; users don't set redundancy for statements.
- File naming/tagging practices aren't modeled; statements are hard to find later.

### Robust

- APIs for banking portals, downloads, and notifications aren't unified; assistants can't orchestrate workflows.
- File metadata support (tags, comments) is inconsistent; automation can't track statements across apps.
- Roaming settings and policy overrides reset accessibility; accommodations for finance tasks don't persist.
- Security overlays block AT at key steps; programmatic assistance can't operate protected dialogs.

## Community life

**ICF Category:** Civic life — Community life

### Perceivable

- Event listings and calendar invites use small fonts and low-contrast tags; accessibility info isn't prominent.
- Map and transit apps in WebViews show thin symbols; wayfinding cues are hard to perceive on desktop displays.
- Civic alerts (closures, emergencies) look similar to routine notifications; urgency isn't visible.
- Volunteer sign-up forms bury accommodations fields; needs aren't perceivable without scrolling.

### Operable

- Registering for events requires switching between calendar, email, and payment; keyboard routes are fragmented.
- Joining civic meetings with interpreter + captions needs manual layout management; OS doesn't offer templates.
- Posting to community forums requires precise media uploads and alt-text; touch/voice users struggle.
- Accessing municipal documents in PDFs has inconsistent zoom and tagging; operability varies by viewer.

### Understandable

- No OS guidance for inclusive community participation (captions on, interpreter view, large text, quiet mode).
- Terminology around recordings, transcripts, and public records isn't explained for town halls.
- Time-zone and locale effects on event times aren't highlighted; attendees miss sessions.
- Privacy indicators for streaming/recording aren't summarized; consent in public meetings is unclear.

### Robust

- Event platforms expose captions and layouts differently; assistants can't provide a consistent civic-meeting setup.
- PDFs and embedded maps vary in accessibility; AT can't depend on stable semantics for public docs.
- Notification APIs don't classify civic urgency; assistants can't prioritize community alerts.
- Interpreter and caption pin states aren't broadcast; inclusive layouts can't be restored across sessions.

## Play

**ICF Category:** Community, social & civic life — Play

### Perceivable

- Game Bar overlays and notifications cover small UI in games; playful feedback and instructions are obscured.
- Color-only status (health, cooldowns) in some titles lacks OS overrides; cues aren't perceivable for color-vision diversity.
- HDR/auto-HDR shifts alter contrast of UI text; play cues become hard to read without manual tuning.
- Voice chat indicators are subtle; players can't perceive who is speaking during play.

### Operable

- Controller remapping is split across Xbox Accessories, game settings, and accessibility; operating consistent layouts is complex.
- Alt-Tab and overlay hotkeys conflict with game input; keyboard/voice operation is unreliable in full screen.
- OSK and voice access aren't available on secure or anti-cheat surfaces; text entry during play is blocked.
- Switching audio devices mid-game (headset ? speakers) takes several steps; team chat becomes inoperable.

### Understandable

- No OS guidance for "play mode" that combines large text, narration, controller profiles, and chat captions.
- HDR, refresh rate, and V-sync settings aren't explained in accessibility terms; players can't tune for comfort.
- Voice chat privacy terms and device roles aren't clarified; players misroute audio to the wrong channel.
- Safety prompts use platform jargon; reporting/toxicity tools aren't framed in plain language.

### Robust

- Anti-cheat and exclusive-mode graphics block accessibility hooks; AT can't read or control overlays.
- Caption and voice-chat text exposure varies; assistants can't access transcripts across games.
- Gamepad events aren't standardized across PC layers; helpers can't enforce universal remaps.
- Game Bar APIs don't describe semantic game state; external aids can't adapt to play contexts.

## Sports

**ICF Category:** Community, social & civic life — Sports

### Perceivable

- Streaming score bugs and stats use small type; live information is hard to perceive at desk distance.
- Color-only team indicators and thin cursors in broadcast overlays reduce clarity for quick plays.
- Multiple notifications (scores, chats) stack over the player; key moments are obscured.
- Auto-play motion in side panes distracts from the main sporting content.

### Operable

- Syncing audio description or captions across multiple streams requires per-app controls; operation is fragmented.
- Switching among live stream, stats site, and chat needs manual windowing; keyboard routes aren't obvious.
- Casting to TV while keeping captions on PC is multi-step; accessible dual-screen viewing is hard.
- Per-app geo-permissions for location-based streams aren't centralized; enabling access mid-game is slow.

### Understandable

- No "game night" recipe shows ideal layout (video + captions + stats) and quiet modes.
- Regional blackouts and DRM prompts use technical language; fans can't infer alternatives.
- Audio ducking settings aren't explained for play-by-play clarity; crowd noise overwhelms commentary.
- Latency and sync tradeoffs (live vs. DVR) aren't framed; users choose inconsistent experiences.

### Robust

- Player frameworks expose captions differently; assistants can't ensure consistent subtitle controls.
- DRM blocks programmatic access to streams; AT can't enhance or stabilize accessibility.
- Notification APIs don't classify "live event priority"; sports alerts can't be orchestrated reliably.
- Device-route and sync events aren't unified; dual-screen/casting accessibility is brittle.

## Arts and culture

**ICF Category:** Community, social & civic life — Arts and culture

### Perceivable

- Museum/arts websites in WebViews use small captions and low-contrast text; artwork info is hard to perceive.
- Media players' overlays obscure subtitles or audio description labels.
- Color-only legends in digital exhibits aren't perceivable for many users; OS can't enforce alternatives.
- High motion and parallax in cultural sites distract from reading curatorial notes.

### Operable

- Switching between media (audio guide, transcript, zoomed image) requires manual window management.
- Downloading transcripts or alt-text for pieces is inconsistent across viewers.
- Zoom/pan for high-resolution art lacks keyboard equivalents in some WebViews; fine control is difficult.
- Screen readers encounter unlabeled controls in galleries; navigation stalls.

### Understandable

- No OS recipe shows "gallery mode" (large text, reduce motion, narration) for cultural browsing.
- Terminology around captions vs. audio description isn't explained; users pick the wrong aid.
- File formats and codecs for accessible media aren't clarified; downloads fail to play with assistive features.
- Licensing and reuse messages on collections use legal jargon; users can't tell permitted actions.

### Robust

- WebView and native media players expose accessibility inconsistently; assistants can't rely on stable controls.
- Alt-text and transcript metadata aren't standardized across platforms; AT can't aggregate descriptions.
- Zoomable image canvases lack semantics; tools can't guarantee keyboard access to regions of interest.
- Captions/AD tracks don't expose programmatic state; helpers can't enforce accessibility settings.

## Religion and spirituality

**ICF Category:** Community, social & civic life — Religion and spirituality

### Perceivable

- Livestreamed services show small subtitle text; scripture or sermon quotes aren't easily perceivable.
- Low-contrast hymn or liturgy slides reduce readability; OS can't enforce contrast in embedded viewers.
- Multiple overlays (chat, reactions) obscure sacred text during readings.
- Audio levels vary widely between music and speech; spoken messages are masked without clear indicators.

### Operable

- Switching between stream, captions, and scripture text requires manual layout; keyboard routes are limited.
- Per-app audio ducking to favor speech over music isn't OS-wide; listeners must adjust multiple controls.
- Enabling interpreter view + captions depends on the app; OS can't guarantee dual-view layouts.
- Donation/payment prompts open separate windows; navigating securely while attending is cumbersome.

### Understandable

- No "service mode" guidance shows how to set up inclusive viewing (large text, captions, lower motion).
- Terminology around captions vs. transcripts vs. chat isn't explained for congregations.
- Cross-time-zone event scheduling isn't surfaced; attendees miss live services.
- Privacy and recording indicators during worship aren't described; expectations are unclear.

### Robust

- Streaming platforms expose accessibility features differently; assistants can't provide consistent controls.
- Caption and interpreter pin states aren't broadcast; inclusive layouts can't be restored.
- Donation/payment embeds vary in accessibility; AT can't guarantee secure, readable forms.
- Audio route/state events aren't unified; speech-first configurations don't persist across apps.

## Human rights

**ICF Category:** Community, social & civic life — Human rights

### Perceivable

- Government and NGO alerts appear as low-salience toasts; rights-related notices aren't prominent.
- Policy documents open as dense PDFs with small fonts; key rights language isn't perceivable.
- Recording and streaming indicators are subtle; consent visibility during advocacy meetings is limited.
- Color-only status for petition progress or votes isn't accessible; OS can't enforce alternatives.

### Operable

- Submitting comments to public portals requires switching between identity verification, docs, and forms; operation is fragmented.
- Captioning and interpreter layouts for public meetings depend on the app; OS can't guarantee equitable access.
- Exporting accessible versions of legislation/transcripts varies; saving readable copies is inconsistent.
- Privacy tools to blur background or hide notifications during sensitive calls require multi-pane setup.

### Understandable

- Rights and consent terminology in dialogs isn't simplified; users can't make informed choices quickly.
- No OS guidance on inclusive advocacy setups (caption + interpreter + content + quiet modes).
- Time-zone/locale effects on hearings aren't highlighted; participants miss deadlines.
- Security warnings for activism tools use technical language; users misinterpret risks.

### Robust

- Public platforms and document viewers vary in accessibility; AT can't rely on consistent semantics.
- Meeting platforms don't standardize captions/interpreter events; assistants can't automate inclusive layouts.
- Identity/verification flows use diverse frameworks; automation can't ensure accessible steps end-to-end.
- Recording/streaming and privacy states aren't broadcast; external tools can't protect sensitive participation.

## Political life and citizenship

**ICF Category:** Civic life — Political life and citizenship

### Perceivable

- Government portal notices open as dense PDFs with small fonts; ballot and policy text isn't easily perceivable.
- Hearing/meeting livestream captions are small and obscured by overlays; civic cues are hard to follow.
- Notification toasts for registration deadlines look like routine alerts; urgency isn't visually distinct.
- Color-only map legends in redistricting or results dashboards aren't perceivable for many users.

### Operable

- Submitting comments or registrations requires switching between identity verification, document upload, and forms; keyboard paths are fragmented.
- Joining public meetings with interpreter + captions needs manual window management; OS doesn't provide a template.
- Signing petitions or statements uses canvas inputs without zoom/undo; pen/touch operation is error-prone.
- Accessibility tools (OSK/voice) may be blocked on secure or SSO overlays; critical steps become inoperable.

### Understandable

- Consent/recording and public-record notices use legal jargon; users can't quickly infer implications.
- No OS guidance models inclusive civic participation (large text, captions, interpreter layout, quiet modes).
- Time-zone and locale effects on filing deadlines aren't highlighted; submissions are mistimed.
- Security prompts (SmartScreen, certificate warnings) aren't framed for civic sites; decisions are unclear.

### Robust

- Public sites and viewers expose accessibility unevenly; AT can't rely on stable semantics for civic docs.
- Caption/interpreter pin states aren't broadcast; inclusive layouts can't be restored across sessions.

## Assistive products & technology for communication

**ICF Category:** Products & technology — Assistive communication tech

### Perceivable

- Caption windows and voice access feedback are subtle; users can't perceive assistive states at a glance.
- TTY/relay status isn't surfaced during call setup; access paths aren't visible when needed.
- Mic privacy and per-app permission blocks appear as small icons; users miss why assistive tools are silent.

### Operable

- Routing call audio to hearing aids while media stays on speakers is multi-step; everyday comm setups are hard.
- Enabling captions, mono audio, and mic boost isn't one action; assistive chains require many toggles.
- Switching voice access and dictate modes mid-call is disjointed; operation conflicts.

### Understandable

- Device role terminology ("default" vs. "communications device") isn't explained with assistive scenarios.
- Noise suppression, AGC, and beamforming tradeoffs aren't described; users can't pick the right profile.
- How to pair interpreter view + captions at the OS level isn't modeled; users depend on app-specific features.

### Robust

- Exclusive-mode audio bypasses OS effects; assistive chains (caption + DSP) don't apply consistently.
- Caption text exposure differs across frameworks; AT can't guarantee access to transcripts.
- No unified API for "assistive comms mode"; helpers can't set system-wide profiles reliably.

## Products & technology for education

**ICF Category:** Products & technology — Education technology

### Perceivable

- LMS content and publisher PDFs have small fonts and low-contrast math; details aren't perceivable.
- Lecture capture players show tiny controls; captions and timestamps are hard to see.
- Device/tenant switching hides which course account is active; cues are subtle.
- Exam and proctor overlays dim or block accessibility indicators; accommodation state isn't visible.

### Operable

- Managing tri-pane layouts (slides + captions + notes) requires manual snapping; keyboard routes aren't obvious.
- STEM input (equations, symbol pickers) requires precision; touch/voice users struggle.
- Proctoring apps intercept hotkeys and block OSK/AT; accommodations can't be operated during exams.
- Exporting accessible copies (tagged PDFs, transcripts) is inconsistent across viewers.

### Understandable

- No OS "study mode" recipe (quiet, large text, captioned media) is presented for learners.
- Policy and SSO errors use admin jargon; students can't interpret restrictions.
- Caption vs. transcript vs. notes workflows aren't explained; review strategies are unclear.
- Math accessibility (screen reading of expressions) isn't surfaced in Settings; discovery is poor.

### Robust

- LMS and capture tools mix frameworks; accessibility trees are uneven for AT.
- Caption and interpreter events aren't standardized; assistants can't restore learning layouts.
- Proctoring/DRM blocks programmatic access; study helpers can't stabilize exams.
- PDF tagging varies; reading order/alt text are unreliable across apps.

## Products & technology for employment

**ICF Category:** Products & technology — Employment technology

### Perceivable

- Enterprise apps use dense grids and thin focus cues; active fields aren't perceivable.
- Presence and status icons are color-only; accessibility of social state is limited.

### Operable

- Security overlays (MFA, VPN) steal focus; keyboard/screen reader workflows are interrupted.
- Installing accommodations needs elevation and policy changes; users can't operate setup independently.

### Understandable

- Policy and error messages use admin jargon; workers can't infer accessible next steps.
- Quiet modes vs. incident alerts aren't framed; critical pings are missed.
- Remote ergonomics (big targets, voice control, reduced motion) aren't modeled for long work sessions.
- Device role terms ("communications device") aren't simplified; misrouted audio delays meetings.

### Robust

- RDP/VDI proxy accessibility events unevenly; AT support is degraded in remote apps.
- Security/compliance tools block injection; assistive automations can't operate protected dialogs.
- Notification and presence APIs aren't unified; assistants can't coordinate work state across suites.

## Products and technology for culture; recreation; sport

**ICF Category:** Products & technology — Culture, recreation, and sport

### Perceivable

- Streaming apps in WebViews display small captions and low-contrast overlays; event details and rules are hard to perceive.
- Score/metadata "bugs" in sports streams use tiny type; live stats aren't readable at normal distance.
- Gallery or museum sites rely on color-only legends; artwork metadata is not perceivable for color-vision diversity.
- Game launchers and storefronts show animated carousels next to fine text; motion distracts from reading accessibility notes.

### Operable

- Switching between stream, stats, and chat requires manual snapping; keyboard routes aren't obvious.
- Controller/assistive device remapping is split across OS and game settings; consistent operation is complex.
- Zoom/pan on high-res cultural images lacks consistent keyboard access in some viewers.
- Casting a stream to TV while keeping captions on PC is multi-step; accessible dual-screen setups are brittle.

### Understandable

- No OS "event mode" guidance (quiet notifications, captions on, larger text) for cultural/sports viewing.
- HDR/refresh rate settings aren't explained in accessibility terms; users misconfigure for readability/comfort.
- Audio description vs. captions vs. commentary isn't contrasted; users don't know which aid to enable.
- Geo/DRM restrictions are described with technical jargon; alternatives aren't clear to non-experts.

### Robust

- Player frameworks expose caption/AD controls differently; assistive tools can't rely on stable hooks.
- Exclusive-mode graphics and DRM block accessibility APIs; AT cannot read or control overlays.
- Reaction/emoji and live chat events aren't standardized; assistants can't aggregate engagement signals.
- Casting and device-route events aren't unified; accessibility states (captions) don't persist across devices.

## Assets

**ICF Category:** Environmental factors — Assets (financial/material resources)

### Perceivable

- Budget dashboards and billing toasts use small type and muted color; approaching limits isn't obvious.
- Cloud storage meters are subtle; users don't perceive when backups will stop due to quotas.
- Licensing/subscription dialogs present dense text; renewal dates and terms aren't prominent.
- File Explorer labels for OneDrive status (sync, error) are low-contrast; asset state is unclear.

### Operable

- Exporting statements from portals to desktop apps requires many steps; keyboard-first flows are inconsistent.
- Managing passwords/2FA across services interrupts access to financial assets during timeouts.
- Batch renaming and tagging statements for retrieval lacks templates; long-term organization is hard to operate.
- Setting backups/versioning for critical files is scattered across apps; resilient storage is tedious to configure.

### Understandable

- Terminology around accounts, tenants, and profiles isn't clarified; asset ownership is misunderstood.
- Backup, archive, and retention policies aren't explained in plain language; users assume files are safe.
- File naming/tagging conventions for financial docs aren't modeled; retrieval is unreliable.
- SmartScreen/warning dialogs during downloads use technical language; users abandon legitimate statements.

### Robust

- Banking portals and viewers mix frameworks; AT can't rely on consistent semantics for statements.
- File metadata (tags/comments) isn't standardized across apps; automation can't track assets reliably.
- Notification APIs don't classify billing urgency; assistants can't prioritize renewals or due dates.
- Policies reset accessibility/backup settings; asset-safety configurations don't persist across devices.

## Sound

**ICF Category:** Environmental factors — Sound

### Perceivable

- Audio levels for alerts and speech aren't visually prominent; users can't perceive when sound cues are too low/high.
- Spatial/mono indicators are small; it's unclear how sound will present on headphones vs. speakers.
- Mic/speaker route changes show brief toasts; users miss environment shifts that impact audibility.
- Per-app meters in the mixer are thin; identifying the noisy app is hard.

### Operable

- Setting per-app volume, ducking, and noise suppression requires multiple panes; quick sound adjustments are difficult.
- Switching to hearing aids or private headsets mid-call is multi-step; environmental noise persists.
- Global hotkeys for "lower other sounds" during speech aren't standardized; operation varies by app.
- Sound enhancements live in vendor drivers; keyboard/AT control is inconsistent.

### Understandable

- The relationship between communications device, default device, and app routing isn't explained simply.
- Mono audio, spatial audio, and noise suppression tradeoffs aren't framed for different environments.
- Volume normalization and ducking effects aren't described clearly; expectations don't match outcomes.
- Mic privacy and permission blocks aren't surfaced with plain guidance; users can't diagnose silence.

### Robust

- Exclusive-mode audio bypasses system effects; accessibility sound chains don't apply consistently.
- Bluetooth profile switches (A2DP/HFP) aren't broadcast uniformly; assistants miss route changes.
- Per-app audio APIs differ; tools can't enforce consistent mixing and ducking behaviors.
- No unified signal for "speech priority"; alerts can mask spoken content unpredictably.

## Immediate family

**ICF Category:** Environmental factors — Immediate family

### Perceivable

- Family Safety alerts and shared calendar invites use small toasts; important family signals aren't prominent.
- Presence/availability icons for family members are color-only and subtle; who is reachable isn't clear.
- Pinned contact avatars can be tiny; distinguishing similar initials among family is difficult.

### Operable

- Setting up priority notifications for family requires per-app rules; OS-wide allow-lists aren't straightforward.
- Switching captioning and audio routes for multi-generational calls (hearing aids, speakers) takes several panes.

### Understandable

- Roles/permissions for child vs. organizer vs. member aren't explained with simple family scenarios.
- Guidance doesn't model setups for grandparents (bigger text, captions, higher volume) in family calls.

### Robust

- Caption and device-route states aren't broadcast; accessibility setups for relatives don't persist.

## Health professionals

**ICF Category:** Environmental factors — Health professionals

### Perceivable

- Telehealth apps in Windows present small caption text and low-contrast controls; clinician cues are hard to perceive.
- Mic/camera status indicators are subtle; patients and clinicians can't perceive whether they're connected.
- Notification toasts for appointment reminders look like routine alerts; urgency and context aren't prominent.
- PDF referrals use tiny fonts; diagnostic notes aren't readable at default zoom.

### Operable

- Switching among EHR portal, call, and imaging viewer requires manual windowing; keyboard routes aren't obvious.
- Sharing screens to demonstrate exercises demands precise controls; OS-level "coach mode" isn't available.
- UAC/SSO prompts interrupt screen readers during remote consults; operation stalls.
- Exporting accessible visit summaries (tagged PDFs) is inconsistent across viewers.

### Understandable

- Consent/recording notices use legal jargon; patients can't easily understand participation rights.
- Differences between captions, transcripts, and chat notes aren't explained for telehealth.
- Audio device roles ("communications device") aren't described; the wrong route causes missed counsel.
- Instructions for using Narrator/Magnifier in portals aren't integrated; patients lack plain-language steps.

### Robust

- Telehealth platforms expose accessibility differently; assistants can't enforce consistent caption/interpreter states.
- PDF tagging and reading order vary; AT can't reliably parse visit summaries.
- Device/route change events aren't unified; tools can't protect against accidental mic/camera loss.
- Secure overlays block AT on consent dialogs; programmatic support fails at critical steps.

## Societal attitudes

**ICF Category:** Environmental factors — Societal attitudes

### Perceivable

- Reporting tools for harassment/toxicity use small icons and muted colors; negative social signals aren't perceivable.
- Caption and reaction cues are subtle; inclusive participation isn't visible during public streams.
- Accessibility badges in app stores or settings are low-salience; supportive features are hard to spot.
- Privacy/consent indicators during recordings are small; rights-respecting behavior isn't reinforced visually.

### Operable

- Blocking/reporting harmful content is per-app and multi-step; OS-level safe-participation controls are missing.
- Enabling captions/interpreter layouts requires app-specific steps; equitable access is labor-intensive.
- Turning on high-contrast/large text for public content requires leaving the app; flow breaks.
- Switching to anonymous or privacy-first profiles across apps isn't unified; safe operation is uneven.

### Understandable

- Community-guideline explanations in dialogs are verbose/technical; people can't infer acceptable behavior.
- Inclusive language and alt-text prompts aren't surfaced in OS UI; authors lack clear guidance.
- Recording/consent terminology isn't simplified; bystanders misunderstand their rights.
- Quiet mode vs. priority alerts for safety hotlines isn't modeled; critical messages are missed.

### Robust

- Abuse/harassment reporting events aren't standardized; assistants can't escalate safety issues across apps.
- Caption/reaction metadata lacks common schemas; tools can't measure inclusive participation.
- Privacy state (recording/streaming) isn't broadcast uniformly; companions can't protect bystanders.
- Accessibility settings roaming is inconsistent; supportive environments don't persist across devices.

## Health services; systems; and policies

**ICF Category:** Environmental factors — Health services, systems, and policies

### Perceivable

- Policy banners use subtle colors; mandate/eligibility changes aren't visually prominent.
- Appointment and refill toasts look like routine alerts; urgency isn't differentiated.
- Low-contrast forms hinder viewing of insurance/ID fields in embedded WebViews.

### Operable

- Identity proofing (webcam, file picker) plus forms requires precise focus control; flows break with AT.
- Exporting accessible policy documents is inconsistent; tagged copies aren't always available.
- Per-app permission prompts (location, camera) appear mid-task; keyboard-first operation stalls.
- Enabling captions/interpreter for public briefings needs manual layout; OS lacks a civic template.

### Understandable

- Terms like "covered service," "prior auth," and "EOB" aren't explained; people can't make sense of dialogs.
- No OS recipes explain how to set "health admin mode" (quiet notifications, large text, captioned calls).
- Locale/date/number formats aren't clarified; benefits entries are ambiguous.
- Security warnings for health portals use technical jargon; users abandon legitimate services.

### Robust

- Portal frameworks vary in accessibility trees; AT can't guarantee navigation/reading order.
- Identity, consent, and payment dialogs span frameworks; automation can't guarantee accessible end-to-end flows.
- PDF tagging/structure is inconsistent; programmatic extraction for AT fails.

## Frontal lobe

**ICF Category:** Body structures — Frontal lobe

### Perceivable

- Notification storms lack salience hierarchy; executive overload hides what to perceive first.
- Subtle focus cues make active fields unclear; task intent is hard to track visually.
- Small progress indicators during long ops obscure when a task is proceeding; users lose initiative.
- Dialog text competes with animated backgrounds; attention is diverted from key actions.

### Operable

- Critical actions (install, restart) require multi-step confirmations; sustaining a plan is difficult.
- Keyboard-only routes to snap/switch aren't discoverable; maintaining organized workspaces is hard.
- Undo/redo and history are app-specific; recovering from impulsive clicks is inconsistent.
- Focus Assist and quiet modes require multiple panes; operating a low-distraction state is effortful.

### Understandable

- No "executive function" recipes teach windowing, pinning, and reminders for stepwise tasks.
- Terminology across notifications (priority, alarms) isn't explained; users mis-prioritize.
- Scheduling and task automation guidance is minimal; planning aids aren't surfaced.
- Voice access vs. dictate vs. shortcuts aren't contrasted for planning and control.

### Robust

- APIs don't expose a unified "focus mode"; companions can't enforce low-distraction states across apps.
- Notification metadata lacks task/role semantics; assistants can't prioritize steps programmatically.
- Framework differences block consistent undo/redo/history; safety nets vary.
- Session/layout state events are uneven; work plans can't be restored predictably.

## Parietal lobe

**ICF Category:** Body structures — Parietal lobe

### Perceivable

- Thin borders and small handles reduce spatial clarity; hit targets aren't obvious.
- Inconsistent scaling across monitors affects spatial relationships; layouts are hard to parse.
- Drag-and-drop "ghosts" are faint; users can't perceive object position while moving items.
- Grid/guide cues in design tools aren't reinforced at OS level; spatial judgments are harder.

### Operable

- Precise placement requires long drags; keyboard "move/align" routes aren't discoverable.
- Resize/rotate gestures lack snapping support across apps; spatial operations fatigue quickly.
- Selecting non-contiguous items is inconsistent; spatial grouping isn't operable uniformly.
- OSK/pen alternatives to drag-drop are limited; spatial tasks depend on fine motor control.

### Understandable

- Guidance doesn't teach keyboard-first spatial editing (Alt+Space, arrow nudges, Snap layouts).
- Scaling, DPI, and snapping aren't explained in spatial terms; users can't predict behavior.
- Magnifier's "follow text cursor" vs. "follow mouse" differences aren't framed for spatial tasks.
- Pen calibration and pointer acceleration guidance isn't contextualized for alignment tasks.

### Robust

- Frameworks expose hit regions differently; AT can't guarantee larger spatial targets.
- Multi-monitor DPI events aren't consistent; companions can't normalize spatial scales.
- Canvas-based UIs lack semantics; automation can't snap or align programmatically.
- Window/geometry state isn't broadcast; restoring spatial layouts is unreliable.

## Temporal lobe

**ICF Category:** Body structures — Temporal lobe

### Perceivable

- Speech and system sounds lack distinct visual reinforcement; auditory recognition cues aren't perceivable.
- Caption windows are small; word boundaries and speaker labels are hard to see.
- Notification tones overlap; event timing isn't clear without strong visual correlation.
- Media players hide transcript timelines; temporal context within content isn't perceivable.

### Operable

- Controlling playback speed/pitch is app-specific; adjusting temporal processing is labor-intensive.
- Enabling caption styles with clear word spacing isn't consistent across apps.
- Switching to mono audio for better speech focus is multi-step; operation during calls is slow.
- Bookmarking time-coded moments is not OS-wide; reviewing auditory info later is difficult.

### Understandable

- No guidance connects Live Captions, transcripts, and media controls for auditory comprehension workflows.
- Differences among audio description, captions, and subtitles aren't clarified for language processing.
- Sound settings (ducking, normalization) aren't explained with speech examples.
- File naming for recordings lacks templates; retrieving the right clip by time/context is confusing.

### Robust

- Caption/track APIs vary; assistants can't access time-coded text uniformly.
- Per-app audio events aren't unified; tools can't coordinate auditory cues with visuals.
- Transcripts export inconsistently; programmatic review across apps is unreliable.
- Player canvases hide controls from the accessibility tree; AT can't manage time-based navigation.

## Occipital lobe

**ICF Category:** Body structures — Occipital lobe

### Perceivable

- Low-contrast UI, thin fonts, and small icons hinder visual processing; critical information isn't perceivable.
- Animated wallpapers/widgets distract from reading; visual noise overwhelms content.
- Color-only feedback (errors in red) lacks accessible alternatives; signals aren't perceived.
- Scaling mismatches across monitors produce inconsistent text sizes; reading flow breaks.

### Operable

- Changing contrast, text size, and cursor settings requires multiple panes; visual comfort isn't operable quickly.
- Narrator/Magnifier combinations aren't one-click; switching aids mid-task is cumbersome.
- High-motion effects aren't disabled OS-wide with a single switch; operating low-stimulus mode is hard.
- Zooming PDFs/images differs by app; visual exploration relies on app-specific gestures.

### Understandable

- No "reading mode" recipe combines larger text, reduce motion, and focused layouts for vision processing.
- Contrast themes vs. HDR vs. night light tradeoffs aren't explained; users misconfigure visuals.
- Cursor/indicator customization isn't presented with examples; tracking the pointer remains hard.
- Magnifier views (docked/full/lens) aren't contrasted; users can't choose effective modes.

### Robust

- Framework differences break consistency of contrast and text scaling; AT can't enforce visual settings across apps.
- Canvas/text rendering hides semantics; tools can't adjust colors or extract text programmatically.
- Multi-monitor DPI events are uneven; companions can't stabilize visual scales.
- No unified API for "low-stimulus" mode; assistants can't reduce motion/animations OS-wide reliably.

## Cervical spinal cord

**ICF Category:** Body structures — Cervical spinal cord

### Perceivable

- Thin focus rings and small window controls require head/neck lean-in to see; visual strain exacerbates cervical pain.
- Auto-hide taskbar affordance is subtle; perceiving where to target without neck flexion is difficult.
- Cursor trail/size defaults are small; tracking pointer from a neutral neck posture is hard.
- Low-contrast system toasts appear far from gaze center on ultrawide screens; users must rotate the neck repeatedly.

### Operable

- Dragging windows and reaching for far targets on large displays increases neck/shoulder load; keyboard routes aren't obvious.
- Switching among voice, OSK, and keyboard is multi-step; posture-preserving input changes are slow.
- Precise hit targets (splitters, resize edges) require fine head-guided pointing; no OS snap-to-edge assist.
- Sign-in/UAC surfaces block voice/OSK; alternative input that reduces neck movement isn't operable end-to-end.

### Understandable

- No "low-movement" setup recipe explains large targets, high contrast, and voice routes to limit neck motion.
- Pointer acceleration/speed tradeoffs aren't framed for head-limited users; tuning increases micro-movements.
- Guidance doesn't model hands-free workflows (Voice access, shortcuts) for common shell tasks.
- Docking/monitor placement tips aren't integrated; users can't set neck-neutral layouts confidently.

### Robust

- Frameworks expose target sizes inconsistently; AT can't enforce larger minimums to reduce head-aiming effort.
- Secure desktop blocks alternative input; posture-saving methods fail at credentials and elevation.
- External device gestures (head trackers) lack unified hooks; companions can't guarantee consistent control.
- Multi-monitor DPI events aren't uniform; neck-saving layouts can't be restored predictably.

## Thoracic spinal cord

**ICF Category:** Body structures — Thoracic spinal cord

### Perceivable

- Small UI clustered at screen edges forces trunk rotation to read; notifications sit outside a comfortable field of view.
- Thin scrollbars and handles are hard to see from reclined or braced postures.
- Brightness controls lack obvious visual state; users strain the torso leaning in to verify settings.
- Multi-window thumbnails in Task View are tiny; scanning content demands torso movement.

### Operable

- Snapping/resizing via drag requires trunk flexion; keyboard first routes (Win+Arrow) aren't discoverable.
- Volume/brightness adjustments are split across hardware keys and OS; mid-task corrections require torso reach.
- OSK occasionally covers inputs; operating from a reclined posture becomes trial-and-error.
- Switching display scaling for distant viewing is multi-pane; operability suffers during pain flares.

### Understandable

- No posture profiles demonstrate sit/stand/recline with snap layouts and larger targets to reduce trunk motion.
- Guidance doesn't show using voice to replace long drags and holds.
- Battery/performance modes' impact on accessibility (voices, captions) isn't framed for limited trunk mobility.
- External keyboard/remote pointer options aren't presented for torso-limited operation.

### Robust

- Hit-target semantics differ across frameworks; tools can't enlarge edges/handles uniformly.
- OSK and voice access are limited on secure surfaces; posture-saving alternatives fail during UAC and sign-in.
- Display/scaling events aren't broadcast consistently; companion apps can't maintain torso-friendly layouts.
- Per-app window management APIs vary; automation can't guarantee reduced-movement workflows.

## Lumbar spinal cord

**ICF Category:** Body structures — Lumbar spinal cord

### Perceivable

- System cues are placed at top corners; users seated with limited lumbar flexion can't perceive them without discomfort.
- Small caret and thin selection highlighting requires leaning; visual confirmation strains the lower back.
- Low-contrast resize handles make window edges ambiguous from a relaxed posture.
- Default text sizes in installers are tiny; perceiving steps without leaning forward is difficult.

### Operable

- Frequent drag-and-drop across monitors increases torso rotation; keyboard equivalents aren't surfaced.
- Touch gestures at screen edges require forward reach; OS lacks "bring controls closer" mode.
- Switching to voice/OSK to avoid bending is multi-pane; alternatives aren't operable quickly.
- Power/sleep prompts time out quickly; returning from rest with limited lumbar mobility is rushed.

### Understandable

- No "low-reach" recipes combine larger targets, keyboard windowing, and voice to reduce lumbar strain.
- Instructions don't connect external input devices (trackball, remote) to posture-saving workflows.
- Guidance lacks examples of scaling and text size presets for distance viewing.
- Timeout/sleep settings aren't framed to avoid repeated standing/sitting cycles during breaks.

### Robust

- Minimum target size isn't enforceable OS-wide; companions can't guarantee low-reach UI across apps.
- Secure surfaces restrict AT; posture-preserving input fails at elevation/sign-in.
- DPI/multi-monitor events are inconsistent; distance-view layouts don't persist.
- Window placement APIs are uneven; automation can't prevent far-edge controls reliably.

## Structure of eyeball

**ICF Category:** Body structures — Structure of eyeball

### Perceivable

- Low-contrast UI, thin fonts, and small icons reduce legibility; critical information isn't perceivable.
- Auto-HDR and dynamic brightness change contrast; text readability fluctuates unexpectedly.
- Cursor/selection indicators are subtle; tracking focal point strains the eyes.

### Operable

- Changing text size, contrast theme, and cursor settings requires multiple panes; relief isn't immediate.
- Zooming PDFs/images differs by app; consistent visual exploration isn't operable.
- High-motion effects can't be disabled with a single OS switch; visual fatigue accumulates.

### Understandable

- No "reading mode" recipe explains larger text, reduce motion, and fixed layouts for low-vision comfort.
- Cursor/indicator customization isn't demonstrated; pointer tracking remains difficult.
- Magnifier modes (docked/full/lens) aren't contrasted with concrete tasks.

### Robust


## Structure of inner ear

**ICF Category:** Body structures — Structure of inner ear

### Perceivable

- System sounds and speech lack clear visual correlates; hearing-impaired users can't perceive audio events easily.
- Spatial/mono indicators are small; it's hard to perceive routing appropriate for hearing devices.
- Captions windows are small with limited word spacing; speech clarity cues are lost.
- Auto-rotate/brightness changes shift visual reference while moving; vestibular discomfort increases.

### Operable

- Switching to mono audio or specific hearing devices mid-call is multi-step; operation during symptoms is hard.
- Global "reduce motion" doesn't enforce across all apps; vestibular-safe operation varies.
- Per-app sound routing requires the mixer; quick adjustments during dizziness are difficult.
- Voice access and captions can't be toggled together by hardware; hands-free safe mode is missing.

### Understandable

- No guidance frames settings for tinnitus/vestibular comfort (mono audio, reduce motion, larger text).
- Device role terms and Bluetooth profiles (HFP/A2DP) aren't explained; routing for hearing aids is confusing.
- Caption vs. transcript vs. chat differences aren't clarified; persistence expectations are unclear.
- Audio ducking/normalization tradeoffs aren't described with speech-in-noise examples.

### Robust

- Route/role change events aren't unified; assistants can't maintain stable hearing-aid connections.
- Caption text exposure varies by framework; AT can't ensure uniform access to speech text.
- Motion/animation settings lack a single API; vestibular-safe preferences aren't enforceable OS-wide.

## Structure of larynx

**ICF Category:** Body structures — Larynx (voice production)

### Perceivable

- Voice access on/off indicators are small; users with limited voice strength can't easily perceive state before speaking.
- Mic level meters in Settings are thin; it's hard to perceive whether quiet speech is being captured.
- System feedback after a voice command (confirmation text) is brief; low-voice users miss whether the command executed.
- "Listening" cues in call apps are subtle; users can't tell if push-to-talk is engaged without straining voice.

### Operable

- Toggling dictation vs. Voice access requires separate shortcuts; conserving voice across modes is difficult.
- Global push-to-talk isn't standardized; whisper-level speakers can't reliably operate talk keys across apps.
- Noise suppression profiles aren't one-click; low-volume speech gets clipped by default settings.
- Hands-free mute/unmute for meetings is app-specific; laryngeal rest is hard to maintain.

### Understandable

- Guidance doesn't explain "low-voice" setup (mic boost, AGC off, captions on) to reduce vocal strain.
- Differences between Voice access, Dictation, and app hotkeys aren't contrasted for minimal speaking.
- Device role terms ("communications device") aren't explained; users route voice to the wrong mic.
- No examples show alternating voice/keyboard to rest the larynx during long sessions.

### Robust

- Exclusive-mode audio bypasses OS effects; low-voice profiles aren't honored consistently across apps.
- Caption/ASR text exposure differs by framework; companions can't provide reliable transcription for quiet speech.
- Mic state changes aren't broadcast uniformly; third-party tools miss mute/unmute events.
- Secure surfaces block voice control; essential steps (UAC, sign-in) can't be completed with minimal speech.

## Shoulder region

**ICF Category:** Body structures — Shoulder region

### Perceivable

- UI elements at extreme screen corners force shoulder abduction to see and target precisely.
- Auto-hide controls lack obvious affordances; perceiving activation zones requires arm lift.
- Cursor and focus indicators are small; visual confirmation demands closer shoulder/arm positioning.
- Taskbar overflow chevron is tiny; users raise the arm repeatedly to scan hidden icons.

### Operable

- Dragging windows between monitors requires sustained arm elevation; keyboard move/snap routes aren't discoverable.
- Touch gestures at distant edges increase shoulder reach; there's no OS "close controls to hand" mode.
- Context-menu long-press is fatiguing; shoulder-friendly alternatives aren't universal.
- Brightness/volume require device and OS steps; repetitive shoulder motion is needed for small adjustments.

### Understandable

- No guidance teaches shoulder-saving workflows (search-first, Win+X, keyboard windowing).
- Pen vs. mouse vs. touch tradeoffs for reach aren't framed; users choose high-shoulder-load inputs.
- Sticky Keys/Filter Keys benefits for reducing arm lift aren't illustrated.
- External remotes/trackballs aren't presented as shoulder-friendly options.

### Robust

- Minimum target-size isn't enforced OS-wide; tools can't ensure shoulder-friendly hit areas.
- Secure desktop blocks alternative inputs; shoulder-saving methods fail at elevation/sign-in.
- Multi-monitor scaling events aren't consistent; shoulder-optimized layouts can't be restored reliably.
- Frameworks expose resize handles differently; companions can't replace drags with select-then-apply universally.

## Arm

**ICF Category:** Body structures — Arm

### Perceivable

- Thin borders obscure grab regions; perceiving draggable edges requires arm repositioning.
- Notification banners appear outside the immediate gaze; arm reach increases to acknowledge them.
- Small caret/selection handles on touch demand fine arm control to verify text focus.
- Low-contrast icons for mic/camera make quick posture-preserving checks difficult.

### Operable

- Resizing panes requires continuous hold; arm fatigue accumulates without a select-then-apply size option.
- Scroll without auto-scroll zones forces repeated arm movement on long documents.
- Switching inputs (pen/voice/OSK) isn't unified; minimizing arm movement takes many steps.
- Keyboard routes for windowing (Win+Arrow, Alt+Space) aren't surfaced; users default to arm-intensive drags.

### Understandable

- Guidance doesn't present "low-reach" workflows: search-first, pinned quick settings, and voice toggles.
- Touchpad gestures vs. pointer acceleration tradeoffs aren't explained for reduced arm motion.
- Examples for replacing drag-drop with multi-select + action aren't provided.
- No plain-language tips on arranging monitors/Start/Taskbar to minimize arm travel.

### Robust

- Assistive overlays can't enlarge micro-targets consistently across app frameworks.
- Secure surfaces block OSK/voice; low-arm-movement flows fail at credential prompts.
- Pointer settings don't roam reliably; arm-friendly tuning is lost between devices.
- Window management APIs are uneven; companions can't guarantee arm-sparing operations system-wide.

## Elbow

**ICF Category:** Body structures — Elbow

### Perceivable

- Small hit targets (checkboxes, splitters) require precise elbow flexion to confirm visually.
- Cursor change on resize is subtle; users flex/extend the elbow repeatedly to "hunt" edges.
- Taskbar overflow chevron and system tray arrows are tiny; elbow motion increases to perceive hidden items.
- Context menu hints are faint; confirmation requires repeated elbow movement.

### Operable

- Holding click-and-drag strains the elbow; there's no universal "grab once, then adjust with keys."
- Long press to reveal menus is fatiguing; keyboard alternatives vary by app.
- Precise text selection without sticky drag is limited; elbow-friendly selection modes aren't consistent.
- Switching DPI scaling to bring UI closer is multi-pane; operability suffers during pain flares.

### Understandable

- No guidance on single-click workflows (multi-select + action) to avoid sustained elbow holds.
- Filter Keys/Sticky Keys benefits for tremor or limited flexion aren't illustrated with shell tasks.
- External input (foot switches) isn't documented as an elbow-saving option for clicks.
- Precision touchpad vs. mouse ergonomics aren't framed for elbow comfort.

### Robust

- Frameworks handle long-press and drag differently; assistants can't replace them reliably.
- AT injection is blocked on secure surfaces; elbow-saving macros fail at UAC/sign-in.
- Hit-target semantics aren't uniform; tools can't enforce larger controls to reduce flexion.
- Pointer precision aids (snap to edges) lack OS-wide APIs; app support is inconsistent.

## Forearm

**ICF Category:** Body structures — Forearm

### Perceivable

- Thin scrollbars and small handles reduce perceivable control; users pronate/supinate forearm to search for targets.
- Low-contrast selectors in dense tables require forearm adjustments to verify current cell/focus.
- Subtle pointer trails make it hard to track during forearm tremor; visual effort increases.
- Notification badges overlap content; visual confirmation requires repeated forearm movement.

### Operable

- Precise scroll + hover interactions demand continuous forearm rotation; keyboard equivalents aren't obvious.
- Drag-select across wide areas fatigues supination/pronation; box-select alternatives vary.
- OSK/voice aren't integrated for select-then-apply workflows; forearm-saving sequences are manual.
- Gesture sensitivity triggers unintended actions with tremor; stability aids are app-specific.

### Understandable

- Guidance doesn't show tremor-aware settings (Filter Keys, slower pointer, larger targets) for forearm comfort.
- Pen grip and touchpad options aren't framed for pronation limits; users pick high-effort methods.
- Keyboard-first selection patterns (Shift+Arrow, Ctrl+Click) aren't demonstrated as drag alternatives.
- No recipes for stabilizing layouts (snap, zoom presets) to minimize forearm movement.

### Robust

- Assistive overlays can't enforce bigger scrollbars/handles across frameworks.
- Pointer smoothing/snap aids lack OS-wide APIs; companions can't guarantee tremor support.
- Secure surfaces block alternative input; forearm-saving routes fail at elevation.
- DPI/scaling inconsistency breaks layout stability; low-movement presets don't persist.

## Structure of lower extremity

**ICF Category:** Body structures — Lower extremity

### Perceivable

- UI positioned high on large monitors is hard to perceive without standing; distant cues reduce comfort.
- Small on-screen keyboards and buttons are difficult to confirm visually from wheelchair or reclined positions.
- Thin focus rings on login screens make field identification hard without changing seating position.
- Notification toasts appear off to the side; perceiving them requires repositioning lower body.

### Operable

- Physical reach to hardware buttons (power, volume) is limited; software routes are multi-step.
- Arranging windows via drag is hard without repositioning; keyboard windowing isn't discoverable.
- Accessing ports/peripherals may require standing; pairing/connecting flows aren't operable remotely.
- Wake, sign-in, MFA timeouts demand quick repositioning; lower-body mobility limits cause lockouts.

### Understandable

- No guidance for seated-distance presets (text size, scaling, large targets) for wheelchair users.
- External remote input (air mouse, presenter) isn't positioned as a lower-body-friendly option.
- Sleep/lock policies aren't explained with mobility constraints; users can't tune for longer approaches.
- On-screen power controls and accessibility shortcuts aren't documented as hardware-button alternatives.

### Robust

- Programmatic control of hardware features (power, brightness) is limited; companions can't reduce physical reach.
- Secure desktop blocks voice/OSK; seated-only flows fail at sign-in/UAC.
- Display scaling and DPI events aren't uniform; distance-view layouts can't be enforced across apps.
- Peripheral pairing APIs differ by vendor; remote-only setup isn't reliable.

## Attention functions

**ICF Category:** Mental functions — Sustained, selective, shifting, and divided attention

### Perceivable

- Notification banners and live tiles animate near reading areas; salient motion pulls attention off task content.
- Low-contrast focus rings make the active field unclear; users can't perceive where attention should land.
- Badge counts lack prioritization; urgent items look the same as low-priority pings in the taskbar.
- Background media and auto-play previews compete with work windows; attention is split by unintended stimuli.

### Operable

- Enabling a low-distraction setup (Focus, quiet hours, reduce motion) requires multiple panes; hard to operate at the moment of distraction.
- Window management to isolate a single task (snap layouts, virtual desktops) is manual; keyboard routes aren't obvious.
- Turning off per-app badges and banners is scattered; users repeat steps and lose attention doing so.
- Pinning captions or transcripts while hiding chat/reactions in calls needs per-app controls; sustained attention breaks.

### Understandable

- No OS recipe plainly teaches "focus mode" (one window, quiet notifications, reduced motion, higher contrast).
- Terminology"Focus sessions vs. Focus Assist vs. Do Not Disturb"isn't contrasted; users misconfigure attention tools.
- Snap layouts and virtual desktops aren't explained with attention use-cases (research vs. writing).
- Live captions vs. Read Aloud vs. Narrator for selective attention aren't compared with examples.

### Robust

- Notification metadata lacks "attention priority"; assistants can't enforce quiet except for critical alerts.
- Reduce-motion and badge states aren't uniformly exposed; third-party apps ignore attention preferences.
- Caption/chat frameworks differ; tools can't persist an attention-supporting layout across apps.
- No unified API to freeze background auto-play; attention aids can't reliably suppress distracting surfaces.

## Memory functions

**ICF Category:** Mental functions — Short-term, working, and long-term memory

### Perceivable

- Recent files and clipboard history previews are small and truncated; memory cues are hard to perceive.
- Subtle "unsaved changes" indicators blend with the UI; users miss recall prompts.
- Taskbar thumbnails don't reliably show document titles at readable size; recognition-based recall is hindered.
- Multiple account icons look similar; identity cues for where things are stored are unclear.

### Operable

- Pinning "memory aids" (sticky notes, To Do, recent docs) across virtual desktops is manual and app-specific.
- Creating repeatable project layouts (snap groups) isn't one-click; reinstating working context is laborious.
- Finding prior states (version history, previous windows) requires per-app steps; recall is effortful.
- Recovering clipboard items depends on a small flyout; keyboard-first retrieval is inconsistent.

### Understandable

- No guidance frames Windows features as "memory scaffolds" (pinning, naming conventions, version history).
- Differences between cloud "Recent," File Explorer "Quick Access," and app recents aren't explained.
- Clipboard history vs. Snipping Tool vs. Collections isn't contrasted for working memory.
- Account/tenant terminology isn't plain; users misremember where documents live.

### Robust

- "Recent items" and window layout APIs are inconsistent; assistants can't reliably restore context.
- Cross-app version history and autosave semantics vary; programmatic recall isn't dependable.
- Identity/account metadata isn't standardized; tools can't mark where an item "belongs."
- Clipboard history lacks rich semantics; memory tools can't tag or dedupe items across apps.

## Temperament and personality functions

**ICF Category:** Mental functions — Emotional reactivity, impulse control, adaptability

### Perceivable

- Risk and privacy prompts use subtle colors; people prone to impulsivity may not perceive the consequence level.
- Recording/streaming indicators are small; heightened emotional states miss consent cues.
- Error messages appear and fade quickly; users don't perceive feedback needed to self-regulate.
- Presence/status colors alone convey social availability; misreads trigger impulsive outreach.

### Operable

- Enabling guardrails (app limits, Focus, quiet modes) requires several settings; hard to operate during emotional spikes.
- Undo/restore flows differ by app; recovering from an impulsive action takes expertise.
- Reporting or blocking during harassment demands navigating per-app menus; regulation is slow.
- Switching to captions/notes to slow down a heated call is manual; reflection aids aren't immediate.

### Understandable

- No plain "calm mode" recipe (reduce motion, dim, priority-only notifications, captions) is provided.
- Security/privacy prompts don't include simple examples of consequences; users can't weigh choices.
- Status semantics (DND, presenting, busy) aren't explained; expectations for response are unclear.
- Guidance doesn"t model step-back workflows (take notes, schedule reply) to reduce impulsivity.

### Robust

- Notification APIs lack "sensitivity class"; assistants can't de-escalate stimuli programmatically.
- Recording/streaming state isn't broadcast consistently; companions can't warn in real time.
- Undo/confirm patterns aren't standardized; guardrails can't be applied uniformly.
- Presence semantics vary across apps; tools can't normalize social signals for regulation.

## Seeing functions

**ICF Category:** Sensory functions — Visual acuity, field, and quality

### Perceivable

- Small text and low-contrast UI elements reduce legibility; critical controls aren't perceivable at default scale.
- Thin focus rings and faint caret indicators obscure the current input location.
- Color-only feedback for status/errors lacks alternatives; signals aren't perceived by color-vision diversity.
- Auto-HDR/brightness changes alter contrast; readability shifts unexpectedly.

### Operable

- Changing text size, contrast theme, and cursor size is multi-pane; rapid accommodation isn't operable.
- Magnifier/Narrator toggles aren't one-action; switching aids mid-task is cumbersome.

### Understandable

- No "vision comfort" recipe explains larger text, reduce motion, and fixed layouts for readability.
- Cursor and indicator customization lacks examples; pointer tracking remains difficult.

### Robust


## Hearing functions

**ICF Category:** Sensory functions — Sound detection, discrimination, localization, lateralization

### Perceivable

- Per-app meters in the volume mixer are thin and small; hard to perceive which app is producing sound.
- Indicators for mono/spatial audio and device roles are subtle; users can't quickly perceive routing state.
- Caption windows default to small type; speech content isn't easily perceivable without manual styling.
- Notification sounds don't show prominent visual correlates; alerts are missed when audio is low or off.

### Operable

- Switching media vs. communications devices mid-call takes several panes; hearing-aid routing is cumbersome.
- Enabling Live Captions + microphone input isn't one action; operating both quickly during calls is hard.
- Per-app volume and ducking rules require manual tuning; speech is masked by system audio.
- Selecting a proximity mic for clarity is buried in app and OS menus; operation interrupts meetings.

### Understandable

- Differences among captions, transcripts, and chat aren't explained; expectations for persistence/search are unclear.
- Bluetooth profile and device role terms (A2DP/HFP, "communications device") aren't described plainly.
- Noise suppression, AGC, and beamforming settings lack examples; users can't choose profiles for hearing needs.
- No OS recipe shows "speech-first" setup (mono on, lower other sounds, captions pinned) for comprehension.

### Robust

- Exclusive-mode audio bypasses OS effects; assistive chains (ducking, captions) fail in some apps.
- Route/role change events aren't unified; companions miss when hearing devices switch.
- No standardized API for "speech priority"; assistants can't programmatically keep speech audible.

## Touch function

**ICF Category:** Sensory functions — Tactile perception

### Perceivable

- Touch targets (splitters, resize edges) are thin; it's hard to perceive where to place a finger.
- OSK can obscure fields with minimal visual affordance indicating what's covered.
- No system-wide haptic feedback on many devices; users can't perceive touch confirmation beyond subtle visuals.
- Gesture start zones at screen edges aren't clearly indicated; discoverability is low.

### Operable

- Long-press and drag operations demand sustained contact; difficult for reduced tactile sensitivity.
- Palm rejection and pen/touch switching vary by app; unintentional input disrupts tasks.
- Precise selection lacks snap/expand alternatives; fine motor control is required for handles.
- OS-level "reduce gesture precision" or bigger handles aren't universal; touch workflows degrade.

### Understandable

- Guidance doesn"t teach touch-first equivalents for keyboard operations (move/resize via keys).
- Pen vs. touch roles and best practices aren't framed for users with limited tactile sensation.
- Gesture language (swipe from edge, press-and-hold) isn't illustrated with clear OS-level examples.
- No recipe for "low-precision touch" (large targets, snap layouts, select-then-apply) is provided.

### Robust

- Frameworks expose touch hit regions inconsistently; helpers can't enlarge handles OS-wide.
- OSK/pen behavior varies across apps; programmatic prevention of accidental input isn't reliable.
- Haptics and tactile feedback lack uniform APIs on Windows devices; confirmations can't be standardized.
- Secure surfaces don't expose touch alternatives; critical flows still require precise gestures.

## Sensation of pain

**ICF Category:** Sensory functions — Pain perception and modulation

### Perceivable

- High brightness, motion, and sharp notification sounds are not clearly indicated; pain triggers aren't perceivable in advance.
- Small controls require sustained focus; strain exacerbates headaches and musculoskeletal pain.
- System toasts lack severity tiers; painful interruptions look like routine alerts.
- Auto-HDR and contrast shifts can amplify visual discomfort without warning.

### Operable

- Switching to a low-stimulus setup (reduce motion, dim, quiet notifications) requires multiple panes.
- Global hotkeys to lower all non-speech sounds don't exist; relief during pain spikes is slow.
- Adjusting text size and contrast quickly isn't one-click; flare-ups interrupt tasks.
- Holding clicks/drags increases strain; OS lacks universal alternatives to sustained holds.

### Understandable

- No "low-stimulus mode" guidance with presets (reduced motion, dim theme, priority-only alerts, larger text).
- Sound enhancement and ducking settings aren't explained with pain-trigger examples (migraine, hyperacusis).
- Timeout/sleep settings for pacing breaks aren't framed; users overexert during sessions.
- Cursor speed/acceleration tradeoffs for pain reduction aren't documented with scenarios.

### Robust

- Reduce-motion, brightness, and sound-priority signals aren't unified; companions can't enforce a pain-safe profile.
- Per-app frameworks ignore global comfort settings; accessibility state doesn"t propagate.
- No standard API to classify alert "harshness"; assistants can't down-rank painful stimuli.
- Secure desktop blocks AT; emergency comfort changes aren't possible at sign-in/UAC.

## Control of voluntary movement functions

**ICF Category:** Mental/Neuromusculoskeletal functions — Initiation, coordination, precision of movement

### Perceivable

- Thin focus cues and small handles make precise targets hard to perceive for tremor or dyskinesia.
- Caret and selection visuals are faint; users can't confirm movement-intensive selections.
- Gesture affordances aren't visually explicit; start/stop regions for drags are unclear.
- Feedback for "press and hold" is subtle; users overshoot due to unclear timing cues.

### Operable

- Many operations require continuous holds and fine drags; there"s no OS-wide select-then-apply pattern.
- Mouse Keys/Dwell Click aren't integrated into all contexts; secure surfaces still need precise clicks.
- Keyboard routes to resize/move elements vary; motor-light workflows are inconsistent across apps.
- Voice access and OSK can't control all injected or canvas-based UIs; movement alternatives fail.

### Understandable

- Guidance doesn"t teach "low-movement" patterns: multi-select + action, keyboard windowing, sticky keys.
- Timing settings for press-and-hold, double-click speed, and key repeat aren't framed for motor variability.
- Narrator/voice/keyboard strategies aren't contrasted for tremor vs. spasticity scenarios.
- Examples of replacing drag-drop with shortcuts or context actions aren't provided.

### Robust

- Hit-target sizes and drag semantics differ by framework; AT can't enforce motor-light alternatives.
- Secure desktop blocks assistive input; credentials/UAC remain movement-intensive.
- Canvas/virtualized controls hide semantics; tools can't invoke operations without pointer precision.
- No unified API for "low-movement mode"; companions can't set system-wide motor accommodations.

## Muscle tone functions

**ICF Category:** Neuromusculoskeletal functions — Hypo-/hypertonia, spasticity, rigidity

### Perceivable

- Thin focus rings and small resize handles make target boundaries hard to perceive for users managing spasticity.
- Subtle feedback for press-and-hold gestures doesn"t show required duration; overshoot occurs with tone fluctuations.
- Caret/selection visuals are faint; confirming text selection after involuntary movement is difficult.
- Tiny toggle states (on/off) in Settings are visually ambiguous; motor adjustments are misread.

### Operable

- Continuous holds and precise drags fatigue tone; there"s no OS-wide select-then-apply alternative.
- Double-click and long-press timings aren't easy to tune from a single place; operation varies across apps.
- Dwell click/Mouse Keys are not universally respected; secure surfaces still require precise clicks.
- Accidental activation due to spasms lacks a global "confirm before destructive action" setting.

### Understandable

- Guidance doesn"t present tone-aware setups (larger targets, sticky keys, slower pointer, keyboard windowing).
- Timing controls (key repeat, hold delay) aren't explained with spasticity examples.
- Alternatives to dragging (multi-select + action, menus) aren't showcased for rigidity scenarios.
- No examples of combining voice access with shortcuts to reduce sustained muscle activation.

### Robust

- Frameworks expose hit targets and drag semantics inconsistently; companions can't enforce tone-friendly interactions.
- Secure desktop blocks assistive inputs; tone-aware flows fail at sign-in/UAC.
- Gesture timing APIs aren't unified; tools can't harmonize click/hold thresholds system-wide.
- Canvas controls hide semantics; AT can't invoke commands without pointer precision.

## Gait pattern functions

**ICF Category:** Neuromusculoskeletal functions — Walking pattern, balance, cadence

### Perceivable

- Small UI far from the user"s typical seated distance reduces legibility for those who stand/use mobility aids.
- Login/lock controls use thin focus cues; perceiving fields from a wheelchair position is difficult.
- System toasts appear at screen edges; users miss alerts when away from the keyboard repositioning.
- Remote display on TV lacks persistent captions/large text; content isn't perceivable while moving about.

### Operable

- Waking, unlocking, and passing MFA are time-limited; users with slow or assisted gait get locked out.
- Hardware buttons (power/volume) are hard to reach; OS alternatives are multi-step and scattered.
- Arranging windows via drag isn't practical when standing; keyboard windowing routes aren't discoverable.
- Switching audio output to a remote speaker during movement requires several panes; calls drop.

### Understandable

- No guidance for "standing mode" (larger text, higher contrast, voice shortcuts, longer timeouts).
- Sleep/lock settings aren't framed for slower approaches with mobility devices.
- Casting vs. mirroring vs. remote desktop tradeoffs aren't explained for moving between rooms.

### Robust

- Programmatic control of power/brightness is limited; helpers can't reduce physical reach requirements.
- Timeout and auth policies aren't exposed via a unified API; assistants can't adapt to mobility pace.
- Device-route events for audio/display aren't unified; mobility-friendly casting is brittle.
- Remote control during secure desktop is blocked; caregivers can't assist end-to-end.

## Calculating

**ICF Category:** Mental functions — Arithmetic and numeric reasoning

### Perceivable

- Calculator and spreadsheet results use small fonts and color-only deltas; numeric differences aren't salient.
- Thousands/decimal separators aren't obvious at default scale; values are mis-read.
- Error and overflow states show subtle text; mistaken formulas go unnoticed.
- Inline math in PDFs/webviews renders faintly; equations are hard to perceive.

### Operable

- Switching between reference windows (docs, calc, notes) needs manual snapping; keyboard routes aren't surfaced.
- Numeric keypad and OSK modes aren't coordinated; entering numbers without hardware keys is slow.
- Copying results and formats between apps requires multiple steps; error-prone during time pressure.
- Reading math with screen readers is inconsistent; operating review of expressions is difficult.

### Understandable

- No OS "calc workspace" recipe (snap layouts, large text, fixed-width fonts) for numeric clarity.
- Locale format settings (decimal, groupings, negative) aren't explained with examples.
- Math speech vs. Nemeth/MathML reading modes aren't surfaced; users pick ineffective settings.
- Rounding and precision options aren't framed; misunderstandings persist across apps.

### Robust

- Math accessibility and semantics vary by framework; AT can't ensure consistent reading of expressions.
- Clipboard and paste formats lose numeric metadata; assistants can't preserve number formats.
- PDF/math rendering lacks standard tagging; programmatic extraction fails.
- No unified API for "numeric contrast" or significance; helpers can't emphasize important deltas.

## Solving problems

**ICF Category:** Mental functions — Problem identification, strategy, evaluation

### Perceivable

- Dense dialogs and small text hide key constraints; problem statements aren't perceivable at a glance.
- Change-tracking or diff views use faint colors; important differences are missed.
- Multiple overlapping notifications obscure error context; root causes aren't visible.
- Logs and console output use low contrast; signals are buried in noise.

### Operable

- Collecting evidence (screenshots, logs) spans multiple tools; keyboard-first workflows are fragmented.
- Reproducing issues across virtual desktops and windows is manual; consistent setups are hard.
- Switching between documentation, terminal, and app requires constant re-windowing; operation is slow.
- Assistive tools can't control modal or secure dialogs; troubleshooting stalls.

### Understandable

- No OS recipe for "debug mode" (persistent logs, bigger monospace, reduced motion, quiet alerts).
- Error messages use internal jargon; steps to isolate variables aren't taught.
- Version/system state (driver, policy) isn't summarized plainly; diagnosis is guesswork.
- Task templates for hypothesis ? test ? capture aren't modeled in the shell.

### Robust

- Apps expose logs/diagnostics differently; assistants can't standardize data capture.
- Window/layout state APIs don't guarantee restoration; reproducibility breaks.
- Security overlays hide error context from AT; programmatic troubleshooting fails at critical steps.
- Notification metadata lacks severity/causality; tools can't correlate signals reliably.

## Making decisions

**ICF Category:** Activities & participation — Choosing between alternatives; weighing risks/benefits

### Perceivable

- Security and privacy dialogs use subtle colors and dense text; consequence levels aren't visually distinct.
- Certificate/SmartScreen warnings bury the actual risk signal in small print and links.
- App permission prompts appear behind other windows; the active choice isn't perceivable in time.
- Settings toggles for tracking, diagnostics, and advertising ID look similar; hard to perceive differences.

### Operable

- Comparing options requires opening multiple panes (Settings ? Privacy, Accounts, Windows Update); side-by-side review is manual.
- Undo/restore for risky choices (reset, uninstall) varies by app; operating a safe trial is difficult.
- Keyboard routes to reveal details ("More info", "Show certificate") aren't consistent; screen-reader operation stalls.
- Time-limited prompts (updates/restart) force quick choices; extending time to decide is non-obvious.

### Understandable

- Dialogs don't explain outcomes with plain examples (e.g., what "reset this PC" removes vs. keeps).
- Permissions (camera, mic, location) aren't framed with contextual risks/benefits for common scenarios.
- Update channels and restart options lack simple language; users can't weigh stability vs. speed.
- No "decision mode" guidance (notes + screenshots + rollback plan) is modeled for complex choices.

### Robust

- Risk severity and rationale aren't exposed via standard metadata; assistants can't summarize consequences.
- Confirmation/undo patterns differ across frameworks; protective guardrails can't be applied uniformly.
- Policy and admin prompts use non-semantic surfaces; AT can't present consistent choices.
- Notification APIs lack a "needs deliberation" class; tools can't defer or stage complex decisions.

## Acquiring, keeping and terminating a job

**ICF Category:** Major life areas — Job search, onboarding, retention, offboarding

### Perceivable

- ATS portals and HR PDFs use small text; accommodation policies and deadlines aren't perceivable.
- Interview scheduling emails and toasts blend with other notifications; critical steps look routine.
- Remote desktop or VDI watermarks obscure fine UI; training tasks are hard to see.
- Color-only presence states hide who can approve access; progress through onboarding isn't clear.

### Operable

- Submitting applications requires switching between resume, portfolio, and forms; keyboard/AT routes are fragmented.
- MFA, VPN, and SSO dialogs steal focus; assistive workflows break mid-task.
- Setting up meeting tools, captions, and devices for interviews needs several panes; equitable operation is slow.
- Offboarding steps (export files, revoke access) vary by suite; operating a clean exit is error-prone.

### Understandable

- No OS guidance on "interview mode" (quiet notifications, captions pinned, device test, background blur).
- Policy and compliance prompts use admin jargon; workers can't infer what to do next.
- Offboarding isn't explained with checklists; users miss steps like exporting accessibility settings.

### Robust

- RDP/VDI and HR platforms expose accessibility inconsistently; AT support degrades in remote contexts.
- Notification and presence semantics aren't unified; assistants can't coordinate interview readiness.
- Export/import of accommodations (caption styles, gestures) lacks standardization; settings don't roam.
- SSO/MFA overlays block programmatic control; automation can't ensure end-to-end accessible flows.

## Recreation and leisure

**ICF Category:** Community, social & civic life — Hobbies, media, casual play

### Perceivable

- Media players and launchers use small captions and low-contrast overlays; content details aren't perceivable.
- Auto-play carousels and animated backgrounds compete with reading lists or guides.
- Voice-chat indicators are subtle; who is speaking isn't clear during group leisure.
- Color-only status/rarity indicators in collections aren't perceivable for color-vision diversity.

### Operable

- Switching layouts (video + captions + chat) requires manual snapping; keyboard routes aren't obvious.
- Controller remapping is split across apps and OS; consistent operation is complex.
- Casting while keeping captions on PC takes several steps; dual-screen accessibility is brittle.
- Parental/family filters live in separate apps; enabling safe leisure quickly is hard.

### Understandable

- No "leisure mode" recipe (reduce motion, larger text, captions pinned, quiet notifications) is provided.
- Audio description vs. captions vs. commentary isn't contrasted; users pick ineffective aids.
- HDR/refresh rate guidance isn't framed in comfort terms; readability/strain tradeoffs are unclear.
- Safety/reporting tools are buried in platform jargon; newcomers can't interpret steps.

### Robust

- Caption and voice-chat semantics differ by framework; assistants can't provide consistent controls.
- DRM/exclusive-mode blocks accessibility hooks; AT can't read or control overlays.
- Device-route events for casting aren't unified; accessibility states don't persist across screens.

## Products and technology for personal use in daily living

**ICF Category:** Environmental factors — Consumer devices, home OS features, daily utilities

### Perceivable

- Quick Settings icons and sliders are small; battery, Wi-Fi, and Bluetooth states aren't obvious at a glance.
- OneDrive sync and error badges are low-contrast; file safety isn't perceivable.
- Alarm/Timer visuals are subtle; time-critical cues are missed in household routines.
- Assistive toggles (Magnifier, Narrator, captions) don't present persistent, high-salience status.

### Operable

- Setting up families, sharing, and safety filters spans multiple apps; everyday coordination is cumbersome.
- Switching audio routes across speakers, headsets, and TVs is multi-pane; household use is interrupted.
- Configuring backups and file history requires several wizards; resilient daily storage is hard to operate.
- On-device accessibility shortcuts don't cover secure surfaces; continuity breaks at sign-in/UAC.

### Understandable

- Storage/backup terminology (sync vs. backup vs. version history) isn't explained with examples.
- Device role terms and audio profiles aren't clarified; media ends up on the wrong device.
- Privacy and child account permissions use technical language; families can't make informed choices.

### Robust

- Household apps and OS surfaces vary in accessibility semantics; AT can't present a consistent dashboard.
- Notification metadata lacks priority classes for family/safety; assistants can't elevate urgent alerts.
- Backup APIs and file tags aren't standardized; automation can't guarantee durable daily records.
- Route/role change events aren't unified; daily living setups (captions, devices) don't persist across apps.

## Vestibular functions

**ICF Category:** Sensory — Vestibular functions

### Perceivable

- Window-open and minimize animations use scaling and parallax; users with vestibular sensitivity experience dizziness before they can react.
- Live Tiles and Widgets cycle content with sliding transitions; motion-sensitive users can’t perceive the information without discomfort.
- Snap Assist previews animate windows across the screen; the rapid repositioning triggers nausea for vestibular-affected users.

### Operable

- “Reduce motion” in Accessibility Settings doesn’t suppress all OS animations; users still encounter motion they can’t control.
- Virtual Desktop swipe transitions use a full-screen slide; users who need reduced motion can’t switch desktops comfortably.
- Scroll momentum in Edge and Settings pages continues after input stops; users can’t operate scrollable content without overshoot-induced vertigo.

### Understandable

- “Animation effects” toggle doesn’t describe which motions it controls; users can’t predict what will change.
- “Transparency effects” and “Animation effects” are separate toggles; the relationship between visual comfort settings is unclear.
- Smooth-scrolling options are buried per-app; users can’t understand why some surfaces still animate after disabling system motion.

### Robust

- There’s no unified motion-preference API across Win32 and UWP; AT and browser reduce-motion queries aren’t honored consistently.
- Third-party apps don’t inherit the system “reduce animations” flag; assistive tools can’t enforce motion suppression globally.
- Transition event metadata isn’t exposed to AT; screen readers can’t warn users before an animation plays.

## Proprioceptive function

**ICF Category:** Sensory — Proprioceptive function

### Perceivable

- Touch-keyboard key boundaries lack tactile differentiation; users who can’t sense finger position miss key edges visually.
- Touchpad gesture regions (edge swipes, corners) have no on-screen mapping; users unaware of finger placement miss available actions.
- Pen pressure levels produce subtle line-weight changes; users who can’t feel grip force don’t perceive the visual difference.

### Operable

- Multi-finger trackpad gestures assume users can sense finger spacing; pinch-to-zoom fails without proprioceptive feedback.
- Drag-and-drop in File Explorer gives no haptic or audio confirmation of grab/release; users can’t tell when the action registers.
- Touch targets on tablet-mode taskbar are flush with no raised affordance; users misjudge tap location without body-position awareness.

### Understandable

- “Touch sensitivity” settings don’t explain what physical input changes; users can’t map the slider to their grip experience.
- Pen calibration instructions reference pressure zones without visual guides; users can’t understand what force is expected.
- Gesture tutorials describe motions (“swipe from edge”) without clarifying required speed or distance thresholds.

### Robust

- Touch-input APIs don’t report contact area or pressure to AT; assistive tools can’t adapt target sizing dynamically.
- Pen tilt and pressure metadata aren’t consistently passed to accessibility hooks; alternative input tools can’t replicate intent.
- Surface-level haptic feedback isn’t standardized across OEM hardware; AT can’t guarantee consistent tactile cues.

## Control of voluntary movement functions

**ICF Category:** Mobility — Control of voluntary movement functions

### Perceivable

- Cursor movement doesn’t highlight the active click target; users with involuntary movements can’t see what they’re about to select.
- Scrollbar thumb is narrow and low-contrast; users with tremor lose visual track of their scroll position.
- Touch-keyboard key highlights disappear instantly; users who press slowly can’t confirm which key registered.

### Operable

- Right-click context menus dismiss on any stray pointer movement; users with tremor accidentally close menus before selecting an item.
- Snap Assist drop zones require holding a window while dragging precisely; involuntary release drops the window in the wrong zone.
- Filter Keys configuration demands typing test sequences; users with inconsistent motor control can’t complete the calibration.

### Understandable

- “Pointer speed” and “Pointer precision” are separate sliders with no explanation of how they interact; users misconfigure both.
- Filter Keys, Slow Keys, and Bounce Keys are listed without describing which tremor pattern each addresses.
- Mouse trail and cursor size settings are in different panes; users can’t find all motor-related pointer adjustments in one place.

### Robust

- Pointer-event APIs don’t expose jitter-filtering metadata; AT can’t distinguish intentional movement from tremor.
- Full-screen games capture raw input, bypassing Filter Keys and accessibility hooks; motor accommodations are lost.
- Synthetic click injection from AT conflicts with anti-cheat and DRM hooks; assistive input is blocked in some apps.

## Attention functions

**ICF Category:** Cognition — Attention functions

### Perceivable

- Notification Center stacks alerts with identical styling; users can’t visually distinguish urgent items from routine ones at a glance.
- Taskbar badge counts are small and unaccompanied by text; users scanning quickly overlook pending action indicators.
- Settings search results highlight matches in thin blue; the relevant keyword blends into surrounding text for inattentive readers.

### Operable

- Toast notifications auto-dismiss after a few seconds; users who take longer to shift attention lose the chance to act.
- Start Menu recommended section rotates content on each open; users can’t reliably return to a recently seen item.
- Alt+Tab task switcher cycles linearly; users with attention fatigue overshoot their target window and must loop again.

### Understandable

- Settings categories split related controls across “System”, “Accessibility”, and “Personalization”; users can’t predict where a feature lives.
- Windows Update progress shows percentage without estimated time; users can’t gauge whether to wait or leave.
- “Optional updates” vs. “Feature updates” vs. “Quality updates” aren’t distinguished in plain terms; users ignore important patches.

### Robust

- Notification priority levels aren’t consistently exposed to AT; assistive tools can’t filter and surface only high-priority alerts.
- Focus Assist state isn’t reliably broadcast to third-party apps; companion tools can’t suppress distractions in sync with the OS.
- Live tile and widget refresh events lack semantic tags; AT can’t suppress low-value content changes from interrupting users.

## Seeing functions

**ICF Category:** Vision — Seeing functions

### Perceivable

- File Explorer icon view relies on tiny visual thumbnails; users with low vision can’t distinguish file types without switching to detail view.
- Windows Hello face-recognition feedback is a subtle animated ring; users with limited sight can’t tell if the camera detected them.
- System tray overflow icons are 16×16 pixels with no text labels; magnifier users must zoom in on each one to identify it.

### Operable

- Magnifier lens mode follows the pointer but can’t be pinned to a region; users must continuously track two focal points.
- Narrator scan mode requires learning a separate key map; users transitioning from visual to non-visual input lose orientation.
- High-contrast mode disables some app-custom styling, breaking layouts; users must choose between visibility and functionality.

### Understandable

- “Text size”, “Display scale”, and “Magnifier zoom” are three separate controls; users don’t know which to adjust for their needs.
- Narrator verbosity levels (“1–5”) don’t describe what each level adds or removes; users can’t choose without trial and error.
- Colour filter mode names (“Deuteranopia”, “Tritanopia”) use clinical terms; plain descriptions of what changes aren’t provided.

### Robust

- UWP and Win32 apps expose different automation trees; Narrator announces inconsistent control names across app frameworks.
- PDF and image content in Edge isn’t always OCR-processed; screen readers encounter silent regions in mixed documents.
- Live region updates in web-based Settings panels fire inconsistently; AT misses dynamic content changes.

## Memory functions

**ICF Category:** Cognition — Memory functions

### Perceivable

- Recently opened files in Jump Lists show paths but no timestamps; users can’t visually confirm which version they last worked on.
- Clipboard History entries display plain text snippets without source-app labels; users can’t recognise where content came from.
- File Explorer “Recent” view mixes files from all apps; users with short-term memory loss can’t spot the item they just saved.

### Operable

- Clipboard History clears on restart with no warning; users who relied on stored clips lose them without a chance to save.
- Browser password autofill prompts disappear after a few seconds; users who need more time can’t return to the prompt.
- Settings changes apply immediately with no undo; users who forget what they changed can’t revert without remembering the prior state.

### Understandable

- “Sync settings” doesn’t list which specific preferences are included; users can’t recall what will follow them to a new device.
- OneDrive “Files On-Demand” status icons (cloud, checkmark, green circle) aren’t labeled; users forget which icon means locally available.
- Timeline/Activity History was removed without a clear replacement; users who depended on it can’t find an equivalent recall feature.

### Robust

- Clipboard History API doesn’t expose entry timestamps or source-app metadata to AT; assistive tools can’t help users search clips.
- Jump List entries lack structured metadata beyond file path; AT can’t provide contextual reminders about recent work.
- Undo/redo stacks aren’t standardised across Win32 and UWP; AT can’t offer a consistent “step back” command across apps.

## Lateralization of sound

**ICF Category:** Hearing — Lateralization of sound

### Perceivable

- Stereo notification sounds play from a fixed left or right channel; users with unilateral hearing loss miss alerts assigned to their affected side.
- Spatial Audio in Windows positions sounds in a 3D field with no visual map; users can’t perceive directional cues they’re missing.
- System alerts and app sounds share the same stereo mix; users can’t perceive which source triggered a sound on a particular side.

### Operable

- Channel balance is a single slider buried in Sound properties; users who need per-app left/right adjustment can’t configure it quickly.
- “Mono audio” is an all-or-nothing toggle; users with partial unilateral loss can’t blend partial stereo to their stronger ear.
- Spatial Audio settings apply globally; users can’t disable it for alerts while keeping it for media playback.

### Understandable

- “Mono audio” doesn’t explain that it merges both channels equally; users with asymmetric loss expect a weighted blend toward their good ear.
- Spatial Audio format names (“Windows Sonic”, “Dolby Atmos”) don’t describe the lateralization effect; users can’t choose meaningfully.
- Per-device audio profiles don’t indicate which channel carries speech vs. effects; users can’t plan their listening setup.

### Robust

- Channel-balance metadata isn’t exposed to AT; assistive tools can’t auto-route critical alerts to the user’s stronger ear.
- Spatial Audio APIs don’t share listener-profile data with accessibility hooks; hearing-aid apps can’t compensate for positional effects.
- Mono-audio state isn’t broadcast to third-party media apps; some players continue outputting stereo despite the system setting.

## Undertaking multiple tasks

**ICF Category:** Cognition — Undertaking multiple tasks

### Perceivable

- Taskbar window grouping collapses multiple instances under one icon; users can’t perceive how many tasks are active without hovering.
- Snap layouts show window positions as abstract rectangles; users can’t identify which app goes where without reading tiny previews.
- Virtual Desktop overview thumbnails are small and unlabelled; users juggling tasks across desktops can’t perceive context at a glance.

### Operable

- Splitting two apps with Snap Assist requires a precise drag-then-pick sequence; users managing multiple tasks lose flow between steps.
- Alt+Tab doesn’t allow reordering windows; users can’t group related tasks together for faster switching.
- Background apps that lose focus may pause or throttle; users returning to a secondary task find stale or frozen content.

### Understandable

- “Task View” and “Alt+Tab” overlap in function but show different content (desktops vs. windows); the distinction isn’t explained.
- Snap layout suggestions differ by screen size with no documentation; users on different monitors get inconsistent options.
- Taskbar “End task” vs. “Close window” in right-click menus isn’t clarified; users don’t know which safely preserves their work.

### Robust

- Window-arrangement state isn’t saved across restarts; AT can’t restore a user’s multi-task layout automatically.
- Task View automation properties don’t expose desktop-to-window mappings; AT can’t help users navigate across grouped tasks.
- App suspend/resume events aren’t communicated to AT; assistive tools can’t warn users that a background task has stalled.

## Touch function

**ICF Category:** Sensory — Touch function

### Perceivable

- Touchscreen button states (pressed, selected, disabled) rely on subtle colour shifts; users with reduced touch sensation get no tactile confirmation.
- On-screen keyboard keys provide no haptic pulse on contact; users who can’t feel the glass don’t perceive whether a keypress registered.
- Swipe gesture progress (e.g., pull-down for Notification Center) shows a thin visual strip; users who can’t feel the drag miss the cue.

### Operable

- Long-press actions (right-click equivalent) require sustained finger contact; users with numbness lift too early and trigger a tap instead.
- Edge swipe gestures to open widgets or Task View demand precise finger placement at the bezel; users with reduced fingertip sensation overshoot.
- Pinch-to-zoom requires coordinated two-finger pressure; users who can’t sense contact force either under-zoom or accidentally scroll.

### Understandable

- “Touch feedback” vibration setting doesn’t describe intensity or duration; users can’t predict whether they’ll perceive the haptic.
- Touchscreen calibration asks users to tap crosshairs but doesn’t explain acceptable accuracy tolerance; users unsure of their touch precision don’t know if calibration succeeded.
- “Gesture” settings list action names (“three-finger swipe”) without describing the physical motion required; users can’t map names to movements.

### Robust

- Touch-contact pressure data isn’t forwarded to AT; assistive tools can’t warn users when they’re pressing too lightly to register.
- Haptic-feedback APIs vary across OEM hardware; AT can’t guarantee consistent tactile confirmation on all Windows devices.
- Touch-rejection zones near screen edges aren’t reported to AT; assistive overlays can’t avoid placing targets in dead regions.

## Muscle tone functions

**ICF Category:** Mobility — Muscle tone functions

### Perceivable

- Key-down visual indicators on the on-screen keyboard flash briefly; users with high muscle tone who press slowly miss the feedback.
- Mouse cursor doesn’t change shape during click-and-hold actions; users with spasticity can’t perceive whether their sustained press registered.
- Sticky Keys activation indicator is a small tray icon; users focused on managing their motor effort overlook modifier-key state.

### Operable

- Keyboard shortcuts require simultaneous key presses (Ctrl+Shift+Esc); users with spasticity can’t coordinate multi-key combos even with Sticky Keys.
- Touchpad scrolling requires sustained light contact; users with fluctuating tone alternate between too much and too little pressure.
- File Explorer rename mode exits on any click outside the field; an accidental spastic movement cancels the edit without warning.

### Understandable

- “Key repeat delay” and “Bounce Keys” both address unwanted repeated input but are described differently; users can’t tell which solves their specific tone issue.
- Click Lock description doesn’t explain it replaces sustained holds with a toggle; users with high tone don’t realise it could help.
- Accessibility “interaction” settings are spread across Mouse, Keyboard, and Touch pages; users can’t find all tone-relevant adjustments together.

### Robust

- Input-timing telemetry (hold duration, inter-key gaps) isn’t exposed to AT; assistive tools can’t auto-tune repeat and debounce settings.
- Sticky Keys state isn’t reliably communicated to all app frameworks; some apps still require simultaneous key combos.
- On-screen keyboard key-size and spacing can’t be adjusted programmatically by AT; companion tools can’t adapt the layout to the user’s motor range.
