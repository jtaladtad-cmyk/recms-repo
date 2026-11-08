# RECMS: Research Ethics Committee Management System

Working prototype for the MSIT 1101 (Software Engineering) final project at Notre Dame of Dadiangas University.

## Contents

- `RECMS_Prototype.html`: the full prototype in one self-contained file. Open it in any modern browser; no build step or server is needed.

## Using the prototype

- Transactional screens cover the three designed transactions: submission and validation, review assignment and recording, and revision handling.
- The Usability test page runs the five test sessions and stores results in the browser under the localStorage key `recms_usability_results_v1`.
- Seeded sample data is included so every screen has content on first load.

## Notes

- All data is kept in the browser. Clearing site data resets the prototype.
- Scoring for the SUS questionnaire follows the standard method: odd items minus 1, even items 5 minus the response, sum multiplied by 2.5.
