# 1092 Asia University Advanced Computer Programming Sample
Code sample for Asia University 1092 Advanced Computer Programming.
<br/>
一些基本的問題先看下面的<a href="#%E6%B3%A8%E6%84%8F--notice">注意</a>條目
<br/>
Some simple problem try to find solution in <a href="#%E6%B3%A8%E6%84%8F--notice">Notice</a> subject, at bottom of this page

# 3/26 第五週 | Week 5
## 檔案 | Files
<a href="Week5">資料夾</a> (File Directory)
<il>
  <p>課堂練習 | Exercise</p>
  <li>Week5/<a href="Week5/Exercise.py">Exercise.py</a></li>
  <li>Week5/<a href="Week5/ExerciseEn.py">ExerciseEn.py</a> (Eng. Ver)</li>
  <p></p>
  <p>作業 | Homework</p>
  <li>Week5/<a href="Week5/Homework.py">Homework.py</a></li>
  <li>Week5/<a href="Week5/HomeworkEn.py">HomeworkEn.py</a> (Eng. Ver)</li>
</il>

## 注意 | Notice
### 針對 Python | For Python
各程式需要用到的模組我會寫在程式碼開頭，檢查模組是否已安裝的方法如下
<br/>
The required modules in program, I wrote it on the top of the source code, to check the module are installed, follow the stpes below:
<br/>
<br/>
執行程式後看有報此錯誤碼
<br/>
Run .py file and if you see Terminal return this error message
<pre><code>Traceback (most recent call last):
  File "&#60;stdin&#62;", line 1, in <module>
ModuleNotFoundError: No module named 'requests'</code></pre>
則代表模組 requests 尚未安裝
<br/>
In this case, that means module "requests" doesn't installed
<br/>
<br/>
也可以在終端機中輸入
<br/>
You also can type the command below into Terminal
<pre><code>pip show <模組名稱 (Module Name)></code></pre>
以下回傳訊息也是模組未安裝的意思
<br/>
If Terminal return the message below, it also means module doesn't installed
<pre><code>WARNING: Package(s) not found: <模組名稱 (Module Name)></code></pre>

<br/>
若要安裝模組，在終端機中輸入
<br/>
To install the module, type the command below into Terminal
<pre><code>pip install <模組名稱 (Module Name)></code></pre>
若以上指令沒用，嘗試：
If the command above not working, try this
<pre><code>python -m pip install <模組名稱 Module Name></code></pre>
還是沒用的話，就要把 Python 重新安裝，且在安裝過程中勾選「Add Python to PATH」詳細可參考<a href="https://medium.com/codingbar/%E8%87%AA%E5%AD%B8python%E7%9A%84%E7%AC%AC%E9%9B%B6%E8%AA%B2-%E5%A6%82%E4%BD%95%E5%AE%89%E8%A3%9Dpython%E7%92%B0%E5%A2%83-7eeeb1642889">此連結</a>
<br/>
If still not working, then you should reinstall Python, and while you installing, be sure you checked the box called something like "Add python to PATH". To know more detail you can found it in this <a href="https://datatofish.com/add-python-to-windows-path/">link</a>
<img src="imgs/0001_add_Python_to_Path.png">
<br/>
安裝完後再將電腦重新啓動
<br/>
Then reboot your computer when you finished install

---

Author: 109021331 CYou Liao