Intervals
=========

Half-step: Two notes immediately adjacent to each other (i.e., C to C#).

Whole-step: Two half-steps.

| Half-Steps | Interval    | Abbr. | Notes                       |
|------------|-------------|-------|-----------------------------|
| 1          | minor 2nd   | m2    |                             |
| 2          | Major 2nd   | M2    |                             |
| 3          | minor 3rd   | m3    |                             |
| 4          | Major 3rd   | M2    |                             |
| 5          | Perfect 4th | P4    |                             |
| 6          | Tritone     | -     |                             |
| 7          | Perfect 5th | P5    |                             |
| 8          | minor 6th   | m6    |                             |
| 9          | Major 6th   | M6    |                             |
| 10         | minor 7th   | m7    | Also known as dominant 7th. |
| 11         | Major 7th   | M7    |                             |
| 12         | Octave      | -     |                             |

Intervals for each Major Key
----------------------------

| Key | Root | m2      | M2 | m3      | M3 | P4     | Tritone      | P5 | m6      | M6 | m7     | M7 |
|-----|------|---------|----|---------|----|--------|--------------|----|---------|----|--------|----|
| C   | C    | Db      | D  | Eb      | E  | F      | F# / Gb      | G  | Ab      | A  | Bb     | B  |
| G   | G    | Ab      | A  | Bb      | B  | C      | C# / Db      | D  | Eb      | E  | Fn     | F# |
| D   | D    | Eb      | E  | Fn      | F# | G      | G# / Ab      | A  | Bb      | B  | Cn     | C# |
| A   | A    | Bb      | B  | Cn      | C# | D      | D# / Eb      | E  | Fn      | F# | Gn     | G# |
| E   | E    | Fn      | F# | Gn      | G# | A      | A# / Bb      | B  | Cn      | C# | Dn     | D# |
| B   | B    | Cn      | C# | Dn      | D# | E      | E# (F) / Fn  | F# | Gn      | G# | An     | A# |
| Gb  | Gb   | Abb (G) | Ab | Bbb (A) | Bb | Cb (B) | Cn / Dbb (C) | Db | Ebb (D) | Eb | Fb (E) | F  |
| Db  | Db   | Ebb (D) | Eb | Fb (E)  | F  | Gb     | Gn / Abb (G) | Ab | Bbb (A) | Bb | Cb (B) | C  |
| Ab  | Ab   | Bbb (A) | Bb | Cb (B)  | C  | Db     | Dn / Ebb (D) | Eb | Fb (E)  | F  | Gb     | G  |
| Eb  | Eb   | Fb (E)  | F  | Gb      | G  | Ab     | An / Bbb (A) | Bb | Cb (B)  | C  | Db     | D  |
| Bb  | Bb   | Cb (B)  | C  | Db      | D  | Eb     | En / Fb (E)  | F  | Gb      | G  | Ab     | A  |
| F   | F    | Gb      | G  | Ab      | A  | Bb     | Bn / Cb (B)  | C  | Db      | D  | Eb     | E  |

Note: Some people like to use the key of C# instead of Db, the key of Cb instead of B, and the key
of F# instead of Gb.  I've chosen to omit them in order to remove duplicates and simplify the table.

Calculating this table starts with calculating the major key (M2, M3, P4, P5, M6, M7).  The decision
for choosing sharps and flats is based on *notational convenience* when using a staff.  As a result,
you'll notice that each key contains the letters A-G exactly once.

Then, to calculate the minor intervals (m2, m3, m6, m7), simply take the major equivalent and add a
flat.  Again, this choice is based on *notational convenience*.  When a flat cancels out with a
sharp, the result is a natural (i.e., the m2 of B is C natural, written "Cn", because the M2 is C#,
and adding a flat will cancel the sharp).

Lastly, the Tritone can be calculated either by sharpening the P4 or flattening the P5, so both are
included.

This strategy results in double flats (like Bbb).  That's okay.  Since the naming is based on
*notational convenience*, the reason double flats exist is because one flat comes from the key
signature, and the other flat comes from flattening the note individually on the staff.

"Notational Convenience"
------------------------

Why the round-about calculation?  Because music is a victim of the language used to transcribe
music.

There are 12 notes in an octave, but the staff only allows 7 notes to be represented.  In order to
allow the staff to express more notes, accidentals are added (sharp, flat, natural).

When writing a song in Bb, the vast majority of the time the composer wants the note Bb (instead of
B).  Instead of writing accidentals on every single B on the staff, accidentals are added to the key
signature to apply it to the entire song.  So when a B is seen, it's understood to perform a Bb
instead.

In hindsight, there are probably much better ways to design a transcription language for music, but
I suppose this one has survived because it's good enough, and it does make sense once you understand
the logic behind it.  It really isn't completely arbitrary, though it can feel that way at first.

The frustration with the notation depends on your perspective.  It's a language designed to help
someone *play back* the music -- it's goal is to help the performer *think* about the music a
certain way *to aid playing*.

If your goal is to understand the mathematics of music, it's annoying to remember that Fb is E, and
G# is Ab -- afterall, it is *the same damn note, at the same damn frequency*.  But music notation
is not designed to aid mathematical understanding.