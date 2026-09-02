# Contributing

Thanks for your interest. A few things to know before you open a pull request.

## What this repository is

Workshop material, not a supported product. It is maintained on a best-effort
basis by the dbt Labs sales engineering team. That shapes what we can accept.

## What we welcome

- Fixes to broken instructions, dead links, or typos
- Corrections where a model does not do what its documentation says
- Compatibility fixes for newer dbt versions

## What we will probably decline

- New models, metrics, or tracks. The scope is deliberately small so the
  workshop fits its time slot.
- Fixes to the data-quality problems in `seeds/cpg_records.csv`. Those are
  intentional — finding and fixing them is the exercise.
- Reformatting or restyling passes.

If you are unsure whether a change is in scope, open an issue first and ask.

## Before you open a pull request

1. Point the project at your own warehouse account and confirm `dbt build`
   behaves as you expect. Do not commit a `profiles.yml`.
2. Keep the diff focused on one thing.
3. Never commit credentials, key material, or real data. All sample data in
   this repository is synthetic and must stay that way.

## Security

Do not report security problems through pull requests or public issues. See
[SECURITY.md](SECURITY.md).
