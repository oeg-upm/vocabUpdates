# vocabUpdates
This repo allows you to add new ontologies to be included in http://vocab.linkeddata.es

Steps for adding a new vocabulary

1) add a new line to the Vocabularies.csv file with the format: URI;{list of domains, comma separated}

2) make pull request or commit to the develop branch

3) wait for some VIP to accept it


You can check the log at: http://jarsomatic.linkeddata.es/getlog (or ask Ahmad who is the only one who can understand the logs)

Check the gh-page branch (e.g. http://oeg-upm.github.io/vocabUpdates/site) to check whether the new site is ok or not before making the pull request to master (so that it is updated in vocab.linkeddata.es)
