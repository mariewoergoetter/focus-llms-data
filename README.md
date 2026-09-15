# Focus, LLMs! — Evaluation Data

This repository contains the experimental stimuli and anonymised human response data associated with the workshop paper **“Focus, LLMs! Evaluating Focus Sensitivity in Text and Audio Language Models.”**

## Dataset

The dataset contains **75 manually constructed items**, equally distributed across five syntactic focus groups:

- Subject
- Object
- Adjective
- Adjunct
- Verb phrase

Each item contains:

- a neutral sentence;
- a corresponding focus-marked cleft sentence;
- a transcript indicating the constituent receiving prosodic focus in the audio condition;
- a focus-supported continuation (C1);
- a focus-contradicting continuation (C2).

The benchmark targets a contrastive, approximately exhaustive (“only”-like) interpretation of focus.

## Repository contents

- `focus_dataset.csv` — textual evaluation items
- `audio_files_focus.zip` — neutral and prosodically focused audio stimuli
- `text_experiment_human_results.csv` — anonymised Prolific result file from the text experiment
- `audio_experiment_human_results.csv` — anonymised Prolific result file from the audio experiment

All Prolific participant identifiers and other identifying information have been removed from the released human result files.

## Audio stimuli

The audio stimuli were generated using a synthetic female voice from Rime AI. Focused versions were manually created in Praat by manipulating duration, intensity, F0 contour, and, where appropriate, pause placement.

All manipulated recordings were subsequently listened to by the authors to verify that the intended focused constituent was perceptually salient and that no obvious audio artefacts or intelligibility problems had been introduced.

## Associated paper

Marie-Léontine Wörgötter, Gaurav Kamath, and Sebastian Schuster.  
**Focus, LLMs! Evaluating Focus Sensitivity in Text and Audio Language Models.**

The current workshop paper is non-archival. Citation information for an archival version will be added here if one becomes available.

## Interim citation

Until an archival version is available, please cite this repository as:

> Wörgötter, Marie-Léontine, Gaurav Kamath, and Sebastian Schuster. 2026. *Focus, LLMs! Evaluation Data*. GitHub repository.
