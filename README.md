# DEVONthink 3 Backlinks  

## A  
[Version A][1] will find links leading to each selected note and add them to the bottom of the text preceded by the delimiter of choice.  
Other options include the use of aliases in the search, the choice wiki links type (automatic and `[[bracketed]]`) and a limit to the number of links to avoid slowness while performing the script on a large number of files.
  
## Updates  
- 2020-03-20  
    - First version posted to the [forum][2]  
- 2020-06-06-23-14-32  
    - Added several properties to allow for easier customization  
        - property `UseAliases`  
        - property `AutoWiki_Links`  
        - property `theKind`  
        - property `theDelimiter`  
- 2020-06-07-20-50-57  
    - `AutoWiki_Links false` was not finding any matches. Fixed.  
- 2020-06-09-00-10-07  
    - Added yet more properties:  
        - property `limit`  
        - property `removeduplicates`  
    - Changed "step progress indicator" 
- 2020-06-12-22-27-26 
	- Added `theSeparator` to allow different characters separating the links.
	- Even with empty results `theDelimiter` was getting added. Fixed.

  
# B  

[Version B][3] will find links leading to each selected note and add them to the custom metadata field of choice (property `MDField`). Note: it has to be a RTF text field.
Other options include the use of aliases in the search and the choice of the font to be used in the rtf field.

## Updates
- 2020-05-24-13-17-38 
	- DT3 on dark mode now displays links properly, so the html before the conversion was updated to turn the whole string into a link. 
	- The sort list command now that considers numeric strings (avoiding the issue of `Text_10` coming before `Text_2`).

# C

[Version C][4] offers several possibilities. Among them: adding the links as rtf text in the custom metadata fields, adding the links in markdown to the bottom of the note using auto wiki links or `[[wiki links]]`. See [this thread][5] for a discussion.

Warning: this is an older version that combined features of versions A and B into a single script. It is now behind them and should be avoided for the time being.


---

See also [this repository][6].  
**If you want to see more stuff like this, [buy me a coffee][7] to keep me going.**

[1]:	Retrieve_Backlinks_A.md
[2]:	https://discourse.devontechnologies.com/t/return-links-back-links
[3]:	Retrieve_Backlinks_B.md
[4]:	Retrieve_Backlinks_C.md
[5]:	https://discourse.devontechnologies.com/t/return-links-back-links
[6]:	https://github.com/bcdavasconcelos/DEVONthink-3
[7]:	https://www.buymeacoffee.com/bcdavasconcelos