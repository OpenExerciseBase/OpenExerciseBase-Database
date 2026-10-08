# OpenExerciseBase-Database

The exercise data of [OpenExerciseBase](https://openexercisedatabase.at), an open, evolving infrastructure for structured exercise knowledge.

## Branches

- `main`: validated exercises, which have undergone professional review.
- `community`: contributed exercises that are unreviewed or were rejected.

The review status of every exercise is also recorded in its `metadata.reviewStatus`.

## Contents

- `exercises/`: one JSON file per exercise (`EX-<name>-<identifier>.json`).
- `images/<exercise_id>/`: the images of an exercise.
- `index.json`: a summary list of the exercises on the branch.

The schema is described in the [documentation](https://openexercisedatabase.at/documentation).

## Access

Clone this repository, browse and download exercises on the [website](https://openexercisedatabase.at/explore), or use the read endpoint `/api/exercises`.

## Licence

Copyright © 2026 Ludwig Boltzmann Institute for Digital Health and Prevention. The data is licensed under [CC BY-NC 4.0](LICENSE). You may share and adapt it for non-commercial purposes with appropriate credit.

## Citing

[Citation of the OpenExerciseBase paper]

## Contributing

Contribute through the website. See the [contribution guidelines](https://openexercisedatabase.at/contribution-guidelines).
