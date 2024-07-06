< WELCOME TO DAZH DOCUMENTARIES! >

< IMPORTANT >

>DAZH
>>ROOT
>>>DAZH.BAT
>>>DAZH-REQUIREMENT.BAT
>>>DZC.BAT

>DAZH.BAT = Dazh Interpreter .

>DAZH-REQUIREMENT.BAT = Requirement for Dazh, if without it, it will has error on the DAZH.bat or DZC.BAT .

>DZC.BAT = Dazh Compiler .

< LICENSE >

>Copyright (c) 2024 Ry2110

>Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

>The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

>THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

< SYNTAXES >

< DEPRECATED >

>usr {ex : "usr USER_NAME", info : "usr = user"}

>ext {ex : "ext", info : "ext = exit", extra_info : "Exit the current user"}

>qrt {ex : "qrt", info : "qrt = quit"}

>wit {ex : "wit 2", info : "wit = wait"}

< NON-DEPRECATED >

>dev {ex : "dev my_variable = 123", info : "dev = define"}

>prt {ex : "prt my_variable", info : "prt = print"}

>chk {ex : "chk", info : "chk = check", extra_info : "Print the current Dazh's model"}

>sav
>>Hello World! {ex : "sav", info : "sav = save", extra_info : "Save to the note data"}

>lod {ex : "lod", info : "lod = load", extra_info : "Load the note data"}

>cre {ex : "cre my_note_data_name.txt", info : "cre = create"}

>dat {ex : "dat", info : "dat = date", extra_info : "Print your current local time"}

>dow {ex : "dow https://example.com/content.html content.html", info : "dow = download"}

>crd {ex : "crd", info : "crd = "credit(s)"}

>cod
>>echo "HELLO WORLD!" {ex : "cod", info : "cod = code"}

>til {ex : "til My_Title", info : "til = title"}

>run {ex : "run example.dz"}

>? {ex : "? This_is_a_comment"}

< WORK-IN-INTERPRETER >

>dev {ex : "dev my_variable = 123", info : "dev = define"}

>prt {ex : "prt my_variable", info : "prt = print"}

>chk {ex : "chk", info : "chk = check", extra_info : "Print the current Dazh's model"}

>sav
>>Hello World! {ex : "sav", info : "sav = save", extra_info : "Save to the note data"}

>lod {ex : "lod", info : "lod = load", extra_info : "Load the note data"}

>cre {ex : "cre my_note_data_name.txt", info : "cre = create"}

>dat {ex : "dat", info : "dat = date", extra_info : "Print your current local time"}

>dow {ex : "dow https://example.com/content.html content.html", info : "dow = download"}

>crd {ex : "crd", info : "crd = "credit(s)"}

>cod
>>echo "HELLO WORLD!" {ex : "cod", info : "cod = code"}

>til {ex : "til My_Title", info : "til = title"}

>run {ex : "run example.dz"}

>? {ex : "? This_is_a_comment"}

< NOT-WORKING-IN-INTERPRETER ( WORKING-IN-COMPILER ) >

>pak {ex : "pak pro", info : "pak = package", extra_info : "Install that extra package from the server"}

>pro {ex : "pro", second_ex : "dev custom_prompt = pro" / "dev custom_prompt = pro >", info : "pro = prompt", extra_info : "the single pro command is just for normal prompt but if the command like dev custom_prompt = pro or dev custom_prompt = pro >>> , the >>> is like starting of prompt without an empty space"}

>cmp {ex : "cmp 1 < 2", info : "cmp = compare", extra_info : "Compare the two values, the rule is that if the first value is a variable the second must be a variable too, but if the first value isn't a variable the second must be a number that's not the variable too, the system will only print true or false, true for correct, false for incorrect"}

>wit {ex : "wit 2", info : "wit = wait"}
