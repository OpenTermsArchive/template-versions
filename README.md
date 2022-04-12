# Open Terms Archive - template for versions

This is a template for the `versions` repository of [Open Terms Archive](https://opentermsarchive.org)

**NOTE**: When creating from this template, please keep the naming structure of `${instanceName}-versions` in order to keep consistency across repos and organisations. 

In order to use it, follow this simple steps:
- Navigate to https://github.com/OpenTermsArchive/template-versions
- Click on `Use this template`
- Enter the name of the target repository `${instanceName}-versions` and the target organization

or check the complete doc: [How to use a template on Github](https://docs.github.com/en/github-ae@latest/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template)

Then you just need to
- clone the repository you just created and named `${instanceName}-versions`
- launch `./init.sh ${instanceName} "${instanceMaintainer}"` (instanceMaintainer being the name of the entity that will maintain the declarations)
- commit the files to git `git add . && git commit -m "Initiate instance"`

This will replace the corresponding variables in the files and remove the now useless files.


- - - -

## License

The code in this repository is distributed under the GNU Affero General Public Licence (AGPL) v3.0.