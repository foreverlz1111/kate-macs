# Fork说明

- 使用时导入文件：
```
kate-macs.shortcuts
```
- 原旧文件重命名为：
```
old-kate-macs.shortcuts
```

# 修改内容

- [书签]项会与工具栏的 Alt+B 按键冲突,取消绑定
- [光标左移]项按键绑定没有，新增方向键左
- [撤销]项改为 Ctrl+/
- [重做]项改为 Ctrl+Shift+/
- [注释]项改为 Ctrl+x+; 再按一遍为取消注释
- [搜索框]项没有，新增 Ctrl+s
- [复制]项改为 M+w

# 按键命令
### kate_aliases = emacs-equivalent
```
beginning_of_document = M-<

beginning_of_line = C-a

close_current_view = C-x, 0

close_inactive_views = C-x, 1

delete_next_character = C-d

delete_word_right = M-d

剪切 = C-w

edit_paste = C-w

edit_select_all = C-x, C-p

end_of_document = M->

跳到行尾 = C-e

关闭文件 = C-x, C-c

打开文件 = C-x, C-f

保存文件 = C-x, C-s

go_goto_line = M-g, g

go_next_split_view = C-x, o

kate_mdi_toolview_kate_plugin_katesearch (find-and-replace) = -%;  C-s

光标右移 = C-f

光标左移 = C-b

move_line_down = C-n

move_line_up = C-p

scroll_page_down = C-v

to_matching_bracket = M-e

tools_cleanIndent = C-M-\\

view_split_horiz = C-X, 2

view_split_vert = C-X, 3

word_right = M-f

显示搜索框 = Ctrl+s

全选文本 = C-x, C-p

撤销 = C-/ 或 C-z

重做 = C+Alt+/
```

# 不可用命令
```
page up = M-v			  : ?

align view to cursor = C-l 	  : no native kate equivalent

cursor to start of block = M-a    : ?

start-end mark = C-space 	  : ? (this is the most frustrating)

kill = C-k     	 		  : technically works, but has strange side-effects

上移一个词 = Alt+B （M+b）
```
