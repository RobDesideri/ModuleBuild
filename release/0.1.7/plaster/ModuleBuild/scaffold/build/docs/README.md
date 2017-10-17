# Additional Documentation
Any *.md file within the Additional folder will be automatically copied to the final doc folder at the root of the project directory.

## ReadTheDocs Manifest Creation
Each folder in this path becomes its own subsection within the ReadTheDocs YML manifest file. This only covers the base folder and all the *.md files within it (so no subfolders will be recognized). Each public function you have in this module will automatically be included in this manifest file under a 'Function' section and do not need to be specified (as they will be automatically generated by PlatyPS).