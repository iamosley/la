## Language Area Research

### Repo for code investigating the dominant non-official languages in Canada.

Language distribution using choropleth maps can be difficult. Within any specific geography many languages exist and are typcially overshadowed by English and French. This methodology demonstrates a way to reliably identify principal "language areas" and which ones are the most dense (population per km<sup>2</sup> in a neighbourhood (for this application, Dissemination Areas).

## An Example

All analysis for this project was done at the [Dissemination Area]: https://www150.statcan.gc.ca/n1/pub/92-195-x/2011001/geo/da-ad/da-ad-eng.htm level. In downtown Toronto, DA '35202296' has a combination of English, Italian, Protuguese and Spanish speakers. Let's look at this DA's language profile:

#### Table 1.
| Language   | Count | % of Total |
|------------|-------|------------|
| English    |   295 |      71.08 |
| Italian    |    60 |      14.46 |
| Protuguese |    35 |       8.43 |
| Spanish    |    25 |       6.03 |

When creating a choropleth map, English would typically be the identified language for this DA since it has an overwhelming 71.08% representation. This is not surprising. But what I wanted to achieve is a way to identify other languages that were significant but not well represented by a simple percentage calculation. Thinking (a lot) about this, I used a measure of population density per square kilometre to see how the language would 'rank'.

#### Table 2.
| Language   | Language Density per km<sup>2<\sup> |
|------------|--------|
| English    |   3.98 |
| Italian    |  39.25 |
| Protuguese | 143.11 |
| Spanish    |  73.97 |
