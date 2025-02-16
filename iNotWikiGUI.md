Find missing Wikipedia articles from iNaturalist observations using iNotWiki
===============================
[./iNotWiki.md](iNotWiki.md) is a command-line tool to find missing Wikipedia articles for biological taxa using iNaturalist and Wikidata.
This is a GUI for iNatWiki using Github Actions and Github Issues to manage the workflow to identify missing Wikipedia articles driven by iNaturalist observations.

# Steps
1. Fill in the form with A user's iNaturalist username or a iNaturalist project ID. [iNotWiki Form](https://github.com/Micelio/Tarsier/issues/new?template=missing_wikipedia.yaml)
2. Submit the form

iNotWiki will:
- Fetch observations from iNaturalist (with pagination support).
- Check Wikidata to see if taxa have existing Wikipedia pages.
- Output a list of taxa that do not have Wikipedia articles.

The workflow will take several minutes to complete. You can track the progress in the Github Issue, that will be created upon submission of the form.
The list will be published in the Github Issue and will be available for further processing.
