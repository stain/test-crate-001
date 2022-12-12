# ro-crate-template

This is an an [RO-Crate](https://www.researchobject.org/ro-crate/) that is published to GitHub Pages. This repository is based on the 
[ro-crate-gh-template](https://github.com/ResearchObject/ro-crate-gh-template) template repository.

The GitHub worfklow in `.github/workflows` uses the [ro-crate-preview](https://github.com/marketplace/actions/ro-crate-preview) action to generate `ro-crate-preview.html` from `ro-crate-metadata.json` before publishing this whole data repository as-is to GitHub Pages.

You may need to use [Git LFS](https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage) for any files largers than 100 MB.

## Using this template

To use this template, click the **Uee this template** butto to clone this repository.

Modify `ro-crate-metadata.json` according to the [RO-Crate specifications](https://w3id.org/ro/crate/1.1). Note that the template contain several examples you may want to delete or modify. Most attributes shown are optional and can also be deleted.

In the new repository, go to Settings and GitHub Pages to select _"Build from GitHub Actions"_. Any following commits to the `main` branch should now be published to `https://USERNAME.github.io/REPO` with the generated RO-Crate preview acting as `index.html`.

## License

This template and its examples are licensed as [Creative Commons Zero v1.0 Universal](https://spdx.org/licenses/CC0-1.0) (CC0-1.0) and can be used and modified without any attribution. 

It is recommended to use CC0 as metadata license (for the RO-Crate JSON) and [CC-BY-4.0](https://spdx.org/licenses/CC-BY-4.0) for the RO-Crate overall, covering this repository. Make sure you update the `"license"` field in the `ro-crate-metadata.json` to reflect your chosen license -- delete the `"description"` on those two licenses if you agree with this suggestion.
