added "bold is not bright" patch
added "blinking cursor" patch
added "copyurl" patch
added "terminfo" patch
added "undercurl" patch
      Remember : you have to run `tic -sx st.info`
      else undercurl will not work
added "workingdir" patch
added "keyboard_select" patch
      They keybindings have been heavily customized
      h, t, n, s   : move cursor left/up/down/right (also with arrow keys)
      l, c, m      : move cursor to the middle of the line/column/screen
      0, $         : move cursor to the beginning/end of the line
      g, G         : move cursor to the beginning/end of the column
      apostrophe,
      semicolon    : move cursor to the top/bottom left/right corner of the screen
      /, ?         : activate input mode and search up/down
      K, k         : repeat last search, up/down
      v            : toggle move/selection mode
      r            : toggle regular/rectangular selection type
      Return       : quit keyboard_select, keeping the highlight of the selection
      Escape       : quit keyboard_select
added "CSI 22, 23" patch
added "w3m images" patch
added "netwmicon"  patch
      Modified to hardcode icon into the st executable


Modified fg & bg color
Modified Cursor fg color
