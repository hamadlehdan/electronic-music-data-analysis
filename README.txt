ELECTRONIC MUSIC — CLEANED DATA

Source: five user-supplied Spotify playlist CSV exports.
Prepared: 21 September 2026, with AI assistance.

156 source entries; 156 retained. No rows removed.
Two ISRC formatting corrections:
- dub_techno.csv, source row 83: GB-QLP-08-00215 -> GBQLP0800215
- minimal_tech.csv, source row 13: NL-PJ6-10-00004 -> NLPJ61000004
Source row numbers include the header as row 1.

FILES
Electronic_Music_Cleaned.csv: all five playlists combined, with Playlist,
Source File and Source Row columns for traceability; all 19 source fields preserved.
cleaned_playlists/: one cleaned CSV per playlist, preserving the source schema.
Electronic_Music_Cleaning_Log.csv: every changed field and original value.

CHECKS
Checked row structure, track ID and ISRC format, positive duration,
explicit flags, addition dates, album-date format and full calendar dates,
popularity range, and duplicate track IDs within each playlist.
No duplicate track IDs found within playlists. Cross-playlist entries retained.
No missing values were filled or guessed. Optional empty fields remain empty.
Original source files were not changed.

INTERPRETATION
These are playlist snapshots, not listening logs. Added At is the recorded
addition timestamp, not playback time. Album dates may reflect reissues.
Popularity is an exported value, not a verified current listening count.
Playlist names are curator labels, not verified genres for each track.
The dashboard derives artist displays and metrics from these source fields.
Review the cleaning log before describing this as independently completed work.
