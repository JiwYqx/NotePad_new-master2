# NotePad 应用程序

## 简介

NotePad 是一个简单的笔记应用程序，允许用户创建、编辑和管理笔记。该应用程序使用 Android 的内容提供者架构来存储和检索笔记数据。用户可以通过友好的用户界面轻松地添加、删除和搜索笔记。

## 功能

- **创建和编辑笔记**：用户可以创建新笔记并编辑现有笔记的标题和内容。
- **查看笔记列表**：应用程序显示所有笔记的列表，用户可以快速浏览和选择笔记。
- **搜索功能**：用户可以通过输入关键字来搜索笔记。
- **排序功能**：用户可以根据修改时间对笔记进行排序。
- **背景颜色选择**：用户可以自定义笔记列表的背景颜色。
- **上下文菜单**：用户可以通过长按笔记项来访问上下文菜单，执行复制和删除操作。

## 文件结构

- `NoteEditor.java`：负责笔记内容的编辑界面。
- `NotePad.java`：定义了笔记数据的结构和内容提供者的契约。
- `NotePadProvider.java`：实现了内容提供者，处理对笔记数据的 CRUD 操作。
- `NotesList.java`：显示笔记列表的活动，允许用户查看和选择笔记。
- `TitleEditor.java`：用于编辑笔记标题的活动。
- `dialog_search.xml`：搜索对话框的布局文件。
- `note_editor.xml`：笔记编辑器的布局文件。
- `noteslist_item.xml`：笔记列表项的布局文件。
- `title_editor.xml`：标题编辑器的布局文件。
- `editor_options_menu.xml`：编辑器选项菜单的 XML 文件。
- `list_context_menu.xml`：列表上下文菜单的 XML 文件。
- `list_options_menu.xml`：列表选项菜单的 XML 文件。
- `NotesLiveFolder.java`：实现了创建和管理实时文件夹的功能。

## 使用说明

1. **安装应用程序**：将应用程序安装到 Android 设备上。
2. **创建笔记**：点击“添加”按钮以创建新笔记。
3. **编辑笔记**：选择现有笔记以编辑其内容或标题。
4. **搜索笔记**：使用搜索功能查找特定笔记。
5. **删除笔记**：通过上下文菜单删除不需要的笔记。
6. **更改背景颜色**：在设置中选择背景颜色以自定义笔记列表的外观。

## 代码展示

![image-20241202181051346](C:\Users\22599\AppData\Roaming\Typora\typora-user-images\image-20241202181051346.png)

![image-20241202181147600](C:\Users\22599\AppData\Roaming\Typora\typora-user-images\image-20241202181147600.png)

![image-20241202181208991](C:\Users\22599\AppData\Roaming\Typora\typora-user-images\image-20241202181208991.png)

![image-20241202181235646](C:\Users\22599\AppData\Roaming\Typora\typora-user-images\image-20241202181235646.png)

![image-20241202181246010](C:\Users\22599\AppData\Roaming\Typora\typora-user-images\image-20241202181246010.png)

![image-20241202181258733](C:\Users\22599\AppData\Roaming\Typora\typora-user-images\image-20241202181258733.png)

菜单布局文件：

![image-20241202181322340](C:\Users\22599\AppData\Roaming\Typora\typora-user-images\image-20241202181322340.png)

![image-20241202181336076](C:\Users\22599\AppData\Roaming\Typora\typora-user-images\image-20241202181336076.png)

功能实现截图：

新建日记：

![image-20241202181650024](C:\Users\22599\AppData\Roaming\Typora\typora-user-images\image-20241202181650024.png)

附加背景色改变：



![image-20241202181721517](C:\Users\22599\AppData\Roaming\Typora\typora-user-images\image-20241202181721517.png)

搜索功能：

![image-20241202181859541](C:\Users\22599\AppData\Roaming\Typora\typora-user-images\image-20241202181859541.png)

附加sort排序功能：

![image-20241202181948526](C:\Users\22599\AppData\Roaming\Typora\typora-user-images\image-20241202181948526.png)

## 许可证

本项目使用 Apache 许可证 2.0。有关详细信息，请参阅 LICENSE 文件。