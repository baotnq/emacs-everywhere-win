# Lợi ích 

- tăng hiệu quả công việc trong suốt quãng đời còn lại 

- tăng từ 1%-5% tùy ngành nghề, công việc

- mở rộng tầm mắt 

## Đánh đổi 
- cần 1,2 tuần để làm quen với shortcut mới 

## Điều chỉnh so với chuẩn emacs 

- Ctrl + h : delete thay thế cho Backspace (rất thuận tiện)
- Select A : dung Alt + A, thay cho Ctrl + A 
- giu nguyen Ctrl + V : paste trong Visual studio , VS Code
- giu nguyen Ctrl + S: save trong Visual Studio Code

-  Muốn gõ tiếng việt, dùng keyboard layout kèm theo win, không sử dụng Unikey 
   
## Cài đặt 
AutoHotkey script to provide basic Emacs key bindings for various Windows apps

To use:

1. Clone/download all the files to a folder.
2. Download and install [AutoHotkey](https://www.autohotkey.com/)
3. Double-click EmacsEverywhere.ahk to launch.
4. Ctrl+Alt+Enter toggles whether Emacs mode is active.

## Shortcut list 
```
C-p	Previous line (move up)
C-n	Next line (move down)
C-f	Forward one character (move right) Note: conflicts with normal "find" shortcut
C-b	Back one character (move left) Note: conflicts with normal "bold" shortcut
M-f	Forward one word
M-b	Back one word
C-a	Start of line Note: conflicts with normal "Select all" shortcut
C-e	End of line
C-<	Start of page
C->	End of page
C-_	Undo
C-/ Undo
C-h Delete character befor cursor
C-d	Delete character after cursor
M-d	Delete word after cursor
C-Backspace	Delete word before cursor
C-k	Kill line
C-w	Cut region
M-w	Copy region
C-y	Paste (no kill ring, so don’t get full Emacs yank ability)
C-Space Set mark
C-g Clear mark
M-< Goto home
M-> Goto end
C-o Open line above cursor
C-w Delete selection
C-S-f Send Ctrl-f (e.g., to trigger a 'Find' dialog)
C-u Universal arg - increase numeric prefix by multiples of 4 (for repeating movement/deletion commands)
C-M-F12 Reloads the script after making edits
```

It should be fairly straightforward to add support to other programs. Feel free to contribute.
