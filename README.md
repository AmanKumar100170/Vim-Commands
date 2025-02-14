# Vim-Commands

- **i** : insert mode
- **esc** : back to normal mode
- **esc + :q** : quit when no changes made in file
- **esc + :q!** : quit and don't save the changes
- **esc + :wq** : quit and save changes
> l : right
> h : left
> K : up
> j : down
- **dd** : delete one line
- **gg** : move cursor to starting of file
- **G** : move cursor to end of file
- **w** : move one word ahead
- **nw** : move n words ahead
- **yy** : copy one line
- **p** : paste
- **dnw** : delete n words
- **yw** : copy one word
- **esc + :%s/word1/word2** : replace all occurences of word1 with word2
- **tail -n x file_name** : print last x lines from the file
- **head -n x file_name** : print starting x lines from the file

# Ubuntu Commands

- **echo "Some text" > file_name** : write the text of echo into the file (replacing any previous content of the file)
- **ls >> file_name** : write the content of ls into the file without replacing previous content
- **ls | grep substr** : subtring match
- **cp file1_path file2_path** : copy the contents of file 1 and paste it into file2
- **mv file1_path file2_path** : move the file (cut paste or rename), delete file from old location and move to new location
