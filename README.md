# CREATE lab website

Jekyll site, built automatically by GitHub Pages on every push to `main`.

## Editing

- **People**: `_data/people.yml`. Add a photo to `assets/img/` and reference it by filename.
- **Papers**: `_data/papers.yml`, newest first. Members' names are bolded automatically when they match `_data/people.yml`.
- **Intro, group photo**: `index.html`.
- **Styles**: `assets/css/style.css`.

## Deploying

In the repository settings, under Pages, choose *Deploy from a branch*, branch `main`, folder `/ (root)`.
Build logs appear under the Actions tab.

`baseurl` in `_config.yml` must match where the site is served: keep `/create-lab` for
`https://<user>.github.io/create-lab/`, or set it to `""` for a user/org site or a custom domain.

## Running locally

```
bundle install
bundle exec jekyll serve
```

Then open the printed URL (it includes the `baseurl`).
