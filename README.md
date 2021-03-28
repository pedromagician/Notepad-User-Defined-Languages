# User Defined Languages for Notepad++

<a href="https://notepad-plus-plus.org/">Notepad++</a> is a free source code editor and Notepad replacement that supports several languages.

UDL (User Defined Languages) interface allows the user to define rules for formatting text, keywords, comments, numbers...

- - -
How To Install:
- Copy userDefinedLang-TXT.DAT.xml into %AppData%\Notepad++\userDefineLangs\\
- Copy TXT-DAT.xml into %AppData%\Notepad++\functionList\\
- In the %AppData%\Notepad++\functionList\overrideMap.xml you have to add the following lines:
    - &lt;association id="TXT-DAT.xml" userDefinedLangName="TXT-DAT"/&gt;
- Copy TXT-DAT.xml %ProgramFiles%\Notepad++\autoCompletion\\
