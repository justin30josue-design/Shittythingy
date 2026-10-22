# v2.28.0
- Android64 support (GD 2.2081). Pause menu buttons replace the F-keys: Stage, Console, Path, Auto, Forget.
- New setting: prediction time budget on phones (default 4 ms).
- Settings apply live; the selected stage is remembered between launches.
- Level memory is written atomically and also saved when you pause.
- Fix: input no longer keeps firing after dying while holding (CPS spike). Added a self-input guard.
