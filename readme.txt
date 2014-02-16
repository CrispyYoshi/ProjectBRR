This is the BRR repository, where the goal is to organize SNES instruments (custom imported BRRs too!) by the instrument type. The game each instrument is from is included in the filename, labelled as SNESMusic.org does for consistency.

Anyone is allowed to amend to the list, however I only ask that the format is kept consistent to the rest of the repository. Please do not modify any files created by other users. (You can add instruments to the proper folders though.)

--How the repository is structured--
So for the most part, just copy what everyone else did in the repo. This wall of text only exists if someone has questions about specific cases:

Each instrument's in its own folder, and each folder has various versions of that instrument from different games. For example, "trumpet" could have the "[ff6] trumpet" and "[kss] trumpet". If you prefer finding instruments from a specific game, search by the game, like "[ff6]". General MIDI is tagged [midi] and any custom instrument is tagged as [custom]. Everything is in lower-case and based off the SNESMusic.org rsn tagging system.

The brass and percussion get their own sub-folder with even more instruments. This is to keep things organized.

At the end of each BRR is the information you would put in #instruments, followed by any additional information you think may be necessary to know. For example, a percussion instrument would have information about octave/pitch at the end like "[ff6]_snare $FF $E0 $B8 $0F $58 (o3c).brr". For easy reading purposes, a comma followed by a space would help separate hex commands, and is highly encouraged. Ex: "[custom]_belltree $84 $CC $00 $04 $00 , $EB $00 $F4 $FA (o4e).brr"

If there are different ways of playing an instrument, the instrument's name comes first, followed by an underscore and the gameID, followed by the way it's played. For example, "acoustic bass" and "slap bass" would both be in a folder named "basses", and their BRRs would be structured "bass_[gameID]_acoustic" and "bass_[gameID]_slap". Another example: "crash cymbal" and "ride cymbal" would be "crash_[gameID]_cymbal" and "ride_[gameID]_cymbal".

****If you do not know what your instrument is, please put it in the "_____other" folder with the format "[gameID]_unknown1.brr". Any unidentified synths should be in the "synths" folder labelled as "synth_[gameID]_unknown1.brr".