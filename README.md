# SelfcontainingC-
Selfcontainng dlls in C#

<p>copy this line to powershell</p>

<pre><code>dotnet publish -r win-x64 /p:PublishSingleFile=true /p:IncludeNativeLibrariesForSelfExtract=true --self-contained true  
</code></pre>

![](Selfcontaining.png)


Found @
https://learn.microsoft.com/en-us/answers/questions/296816/self-contained-single-file-does-not-produce-a-sing
