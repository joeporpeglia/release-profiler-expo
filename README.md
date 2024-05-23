# Steps to reproduce

1. `bun install`
2. `bun expo prebuild`
3. `bun start --no-dev`
4. `bun android`
5. Let the app run for a few seconds, then press the "Stop profiling" button on the app index screen
6. `bun react-native-release-profiler --fromDownload --appId com.playbackjoe.releaseprofilerexpo`

This produces an empty sampling profiler trace (see example in the repo root).
