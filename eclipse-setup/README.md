##Code Formatter installation
1. Go into "Java > Code Style > Formatter"
2. Click "Import..." and choose eclipse-formatter.xml
3. Make sure "NortalLab" is set as Active Profile

##Clean Up settings installation
1. Go into "Java > Code Style > Clean Up"
2. Click "Import..." and choose eclipse-cleanup.xml
3. Make sure "NortalLab" is set as Active Profile
4. Uncheck "Show profile selection dialog for the 'Source > Clean Up' action

##Code Templates installation
1. Go into "Java > Code Style > Code Templates"
2. Click "Import..." and choose eclipse-codetemplates.xml

##Save Actions configuration
1. Go into "Java > Editor > Save Actions"
2. Check "Perform the selected actions on save"
3. Check "Format source code" with "Format edited lines"
4. Check "Organize imports"
5. Check "Additional actions" and click "Configure"
6. In "Code Style" tab check "Use blocks in if/while/for/do statements" and select "Always"
7. In "Code Style" tab check "Use modifier 'final' where possible" and check "Private fields" and
"Parameter"
8. In "Member Access" tab check "Use declaring class as qualifier" and check "Change all "
9. In "Missing Code" tab check everything that can be checked
10. In "Unnecessary Code" tab check "Remove unused imports" and "Remove unnecessary casts"
11. Click "OK". Now your additional actions summary should look like this:
Convert control statement bodies to block  
Add final modifier to private fields  
Add final modifier to method parameters  
Remove unused imports  
Add missing '@Override' annotations  
Add missing '@Override' annotations to implementations of interface methods  
Add missing '@Deprecated' annotations  
Remove unnecessary casts  

##Further Eclipse configuration
1. Go to "General > Editors > Text Editors"
1.1 Set "Displayed tab width" to 4  
1.2 Check "Insert spaces for tabs"  
1.3 Check "Show print margin"  
1.4 Set "Print margin column" to 150  
1.5 Check "Show line numbers"  
1.6 Click "Apply"  

2. Go to "General > Workspace"
2.1 Choose Text file encoding: "Other: UTF-8"  
2.2 Choose New text file line delimiter: "Other: Unix"  
2.3 Click "Apply"

4. Go to "XML > XML Files > Editor"
4.1 Set "Line width" to 150  
4.2 Select "Ident using spaces"  
4.3 Set "Identation size" to 4  
4.4 Click "Apply"  
