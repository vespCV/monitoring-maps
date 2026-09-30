# Hornet monitoring maps

Daily maps of citizen-science hornet reports in three Dutch regions. Each map shows the hottest 250×250 m cells for this week so field people can see where Asian hornet (*Vespa velutina*) and European hornet (*Vespa crabro*) observations cluster.

## Maps

- [Dordrecht](maps/map_dordrecht.html)
- [Rotterdam agglomeration](maps/map_rotterdam.html)
- [Schouwen-Duiveland](maps/map_schouwen_duiveland.html)

## Legend

Marker colors:

- Asian hornet individual: red
- Asian hornet nest: brown
- European hornet individual: yellow
- European hornet nest: black

Each marker shows this week's observation count and a trend symbol (↑ rising, ↓ falling, → stable) against the prior three weeks. The map legend repeats these meanings.

## Updates

Maps refresh about once a day in the early morning (Europe/Amsterdam). Fixed URLs are overwritten; there is no public archive of older days.

## Limits

- Counts are exposure (how many reports fall in a cell), not abundance or detector hit-rate.
- A nest marker does not mean the nest is still there; nests may already have been removed after the report.
- Asian hornet data may include a Meldpunt snapshot as well as Waarneming.nl; European hornet is Waarneming.nl only.
- Validated and unvalidated reports are both shown.

Pipeline and private cache stay in a separate private repo. This repository holds the published region maps and this page only.
