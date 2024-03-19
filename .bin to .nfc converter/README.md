# skylander_converter

 You can convert your .dump/.bin/.sky files with this script. I edited the cript from https://github.com/equipter/ClassicConverter. 
 Some of the .nfc files from the big folder may not work. You can convert your own files with this code.
 
## 1.
Make sure that all your files are renamed to .bin. You can just rename them. They will be the same file.

## 2.
Go to your terminal and go to your folder with the converter. 
CD '{place}\skylander_.nfc_flipper-zero\.bin to .nfc converter'

In {place} must be your diraction folder. For example: C:/Downloads
CD 'C:\Downloads\skylander_.nfc_flipper-zero\.bin to .nfc converter'

## 3.
Run this command:
python skylander_converter.py -i "{place}\skylander_.nfc_flipper-zero\.bin to .nfc converter\assets" -o "{place}\skylander_.nfc_flipper-zero\.bin to .nfc converter\output"