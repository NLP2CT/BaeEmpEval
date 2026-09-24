# Audio Setup

Audio files are not distributed with this repository. The BAEmpEval release contains only the annotations and the corresponding source dialogue/utterance IDs.

To build the demo:

1. Download the audio from the original datasets under their respective access and license terms. If the original dataset provides official timestamps or utterance boundaries, use them to split the downloaded audio into the corresponding clips.
2. Match each example to its source audio using the IDs provided in the annotation files.
3. Place the matched audio files in this directory.
4. Update the `<audio>` file paths in `index.html` to point to those files.

The current demo uses `Sample/place_holder.wav`. You can replace this file for a quick test or update each audio player to use a different file.

Please do not commit or redistribute source audio unless permitted by the original dataset’s license.
