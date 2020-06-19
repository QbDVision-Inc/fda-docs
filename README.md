# fda-docs
Hosts FDA documents.

# To add a doc
* Pull the latest version.
* Add the pdf to the `guidance-for-industry` directory.
* Add it to index.js to be packaged.
* Increase the version in package.json.
* Checkin and push to github (no need to publish to npm).
* Create a new release by going here: https://github.com/CherryCircle/fda-docs/releases
  * Follow the naming convention of previous releases (ex. v0.1.5)
* Back in QbDVision:
  * Update package.json to point to the new version.
  * Follow the pattern in `iqa.jsx` for using the `ReferenceDocuments` object to get your new doc(s).


