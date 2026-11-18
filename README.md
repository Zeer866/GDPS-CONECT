# GDPS Connect

A Geode mod project by **Zeer** for managing saved Geometry Dash Private Server (GDPS) profiles.

## Project status

**Early scaffold — not a functional GDPS switcher yet.** The initial Geode project files and source-check workflow are in place. Profile management UI, GDPS endpoint integration, and restart-based switching still need implementation and testing.

## Planned behavior

1. Add and save GDPS profiles.
2. Validate a profile address before saving it.
3. Select the active profile.
4. Apply the selected server configuration and restart Geometry Dash when necessary.

## Platforms

The project is configured for Windows (win) and Android (android). Actual builds must be tested against the matching Geode SDK, Geometry Dash version, and Android ABI.

## Build

Install the Geode CLI and SDK, then build for your platform:

    geode sdk install
    geode sdk install-binaries
    geode build

For Android, install the Android NDK and Geode Android binaries, then use:

    geode sdk install-binaries -p android64
    geode build -p android64

For 32-bit Android, use android32 if your Geometry Dash/Geode installation requires it.

See the official Geode mod creation guide: https://docs.geode-sdk.org/getting-started/create-mod

## License

License to be selected before public distribution.
