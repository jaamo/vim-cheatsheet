# VIM cheatsheet

I'm sure the world needs one more.

## Basics
`:w` Save  
`:q` Close current buffer  
`:q!` Close current buffer and ignore changes  
`:wq` Save current buffer and exit  
`:qa` Close all buffers  

## Cursor movement
<kbd>option</kbd>, <kbd>4</kbd> Move to end of line  
<kbd>0</kbd> Move to beginngin of of line  
<kbd>option</kbd>, <kbd>_</kbd> Move to the beginning of text  

## Scrolling
<kbd>ctrl</kbd>, <kbd>d</kbd> Half page down
<kbd>ctrl</kbd>, <kbd>d</kbd> Half page up
<kbd>ctrl</kbd>, <kbd>y</kbd> One line up
<kbd>ctrl</kbd>, <kbd>e</kbd> One line down

## Selecting

<kbd>v</kbd> Start selection  
<kbd>ctrl</kbd> + <kbd>v</kbd> Multi-cursor select  
<kbd>shift</kbd> + <kbd>v</kbd> Multiline select  
<kbd>g</kbd>, <kbd>v</kbd> Select previous  

## Windows
<kbd>ctrl</kbd>, <kbd>w</kbd> s <kbd>></kbd> Split window horizontally  
<kbd>ctrl</kbd>, <kbd>w</kbd> w <kbd>></kbd> Switch to another window
<kbd>ctrl</kbd>, <kbd>w</kbd> h <kbd>></kbd> Move cursor to left
<kbd>ctrl</kbd>, <kbd>w</kbd> l <kbd>></kbd> Move cursor to right
<kbd>ctrl</kbd>, <kbd>w</kbd> j <kbd>></kbd> Move cursor to down
<kbd>ctrl</kbd>, <kbd>w</kbd> k <kbd>></kbd> Move cursor to up
<kbd>ctrl</kbd>, <kbd>w</kbd> + <kbd>></kbd> Grow window right  
<kbd>ctrl</kbd>, <kbd>w</kbd> + <kbd><</kbd> Shrink window left  
  <kbd>ctrl</kbd>, <kbd>w</kbd> + <kbd>+</kbd> Grow window up  
<kbd>ctrl</kbd>, <kbd>w</kbd> + <kbd>-</kbd> Shrink window down  

## NERDTree

<kbd>shift</kbd></kbd> + <kbd>D</kbd> Remove bookmark  
`:Bookmark` Bookmark  

## Search & replace

`/` Search  
<kbd>n</kbd> Search next  
`:%s/foo/bar/g` Find each occurrence of 'foo' (in all lines), and replace it with 'bar'  
`:%s/foo//gn` Count occurences of 'foo'  

## Macros

<kbd>q</kbd>, <kbd>a</kbd> Start recording  
<kbd>q</kbd> Stop recording  
<kbd>@</kbd>, <kbd>a</kbd> Repeat recorded

