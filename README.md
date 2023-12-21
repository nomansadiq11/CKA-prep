# CKA-prep

VIM Learning

- Modes
    - Normal mode cannot write text but run commands
    - edit mode by pressing the i = insert

- save andd quit
    - q! = force quit and q = quit and ! means force

- Moving around
    - H J K L keys move aroundd the text in the file
    - H = left, J = down , K = up , L = right
    - press 4 + H means shift left 4 character
    - move words by words by uinsg w comman, you can move by count of words like 4 + w means move 4 words and b for backwors
    - move between sentance like ) to move forward sentance by sentacne and ( backwards
    - } move paragraph { move back
    - find type slash like this "/find"
    - move end of the file press capital g like shift + g
    - move back top of the file type gg
    - want to go specfic line type :linenumber
    - search the current word undderthe cursor by typeing the * now you can enter * again or n you can search again same word and if you like to search backword than enter # mark

- how to delete
    - d for delete
    - d + w means delete the word
    - dd deleline the line
    - u = undu
- how to copy
    - y for copy
    - y + w coy the word
    - yy for copy the whole line
- change command
    - c for change
    - c + w change that current wor
    - c /h change mode start with h
- visual mode
    - press shift + v you can selection and you can use motion keys to move the section
    - control v will be select the bolos and like remove the line s
- Registers
    - when you press the dd for delete the line but its also copy to the clipboard when you next time paste it will bring the deleted line
    - so we have registers we can store the values by press double quots a it will store the value in a register as we have 52 register all alphabets capital or small
- Replace
    - you can repalce the string wth following :s/old/new/g here g for global
- Mark
    - you can bookmark line and comeback again to this line by jump like this press ma m = mark and a = mark name you so moved to another line now you need to move back to this mark location you can press double quotes and mark name like a

