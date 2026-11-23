# ReefSpark site

The public pages of ReefSpark, served by GitHub Pages:

- `index.html` - the offer to reef researchers: free 3D processing in exchange
  for training data. Clips in `media/` come from our own surveys.
- `label/<code>/` - one labelling page per partner, at a random code that only
  that partner is sent. Made from the pipeline repo with
  `uv run python scripts/publish_labeller.py <labelset> --site ../reefspark-site`.

`label/` is kept out of search engines (`robots.txt`, plus a noindex tag on
each page), but this repository is public: anyone browsing it can see the
labelling folders. Remove a partner's folder once their labels are back.
