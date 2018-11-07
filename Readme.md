<h1>kd-tree from https://github.com/ubilabs/kd-tree-javascript</h1>



<h1> copy Util in windows</h1>

<pre>
<code>
  @ECHO OFF && CLS

SET /P y=Insert de number of the records: 
SET /A start=40
SET /A z=y+1
SET /A t=0

REM start the loop
:MKDIR
SET /A t=start-13*3
REM make the directory
MKDIR %start%
xcopy C:\Users\Htaung\Desktop\Images\%t%".jpg" C:\Users\Htaung\Desktop\Test/%start%\

REM increment by 1
SET /A start=start+1

REM if we're at the end, return
IF %start%==%z% (GOTO :EOF) ELSE (GOTO :MKDIR)  
</code>
</pre
