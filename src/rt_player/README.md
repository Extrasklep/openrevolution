# brstm_rt
C++ RtAudio BRSTM player

## Usage
./brstm_rt file.brstm

-v - Verbose output

-q - Quiet output (Don't display the player UI)

--force-sample-rate [sample rate] - Force playback sample rate

--enable-mixer - Enable track mixing for multi-track files

-l - Always loop files with no loop

**Memory modes**

-m - Load the entire file into memory (default for <15MB files)

-s - Stream the file from disk (default for >15MB files)

-d - Decode all audio data into memory before playing

**Controls**

Left and right arrow keys: Seek 1 second

Up/down arrow keys or number keys: Switch tracks (for multi-track files)

Space: Pause

Q: Quit
