本程序自动执行以下功能：
    1. 遍历指定目录及所有子目录，寻找指定类型的文件（.xls, .xlsx, .doc, .docx, .pdf, .jpg, .png）。
    2. '.jpg', '.jpeg', '.png'这类图片文件，仅处理50KB以下的
    3.  如果不输入路径，默认操作当前目录。
    4. 为每个找到的文件，创建一个单独的带密码的ZIP文件。并将删除源文件
    还原功能：
    1. 解压所有此程序创建的压缩文件，并删除这些压缩包。
    注意：还原操作需要使用压缩时相同的密码。
