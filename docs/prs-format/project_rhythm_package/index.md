---
table_of_contents:
    <ul>
    <li><a href="#project-rhythm-package">(Top)</a></li>
    <li><a href="#structure">Structure</a></li>
    <li><a href="#purpose">Purpose</a></li>
    </ul>
---

# Project Rhythm Package

Project Rhythm Package (PRP) is the official package format for Project Rhythm. The primary purpose of this format is to package both the chart and the audio into one file while also saving a bit of space. Like lots of other file types, PRP files are actually zip files with a specific structure. This format was introduced in Project Rhythm 0.5.55 and PRSEdit v1.1.36.

# Structure

A PRP package contains two files: the chart and the audio.

The chart is always a [PRS file](/docs/prs-format/project_rhythm_song/) named `notes.prs`. It contains the notes, events, and other relevant information about the song, such as the title and artist (PRSv1.3 and later). It is required for the song to load properly.

The audio has the stem `song` and is in one of these 5 formats: `.mp3`, `.wav`, `.flac`, `.aac`, `.ogg`. The audio is not required, but is highly recommended.

# Purpose

The PRP format was created to make delivery of custom songs easier by combining the audio and the chart into one file. This also makes importing the song into Project Rhythm easier, as there is only one file to import instead of two.
