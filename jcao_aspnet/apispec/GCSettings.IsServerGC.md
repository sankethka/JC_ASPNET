---
uid: System.Runtime.GCSettings.IsServerGC
example:
- |
    <pre><code class="csharp" lang="lang-csharp">using System;
    using System.Runtime;

    class Sample
    {
        public static void Main()
        {
        string result;

        if (GCSettings.IsServerGC == true)
            result = "server";
        else
            result = "workstation";
        Console.WriteLine("The {0} garbage collector is running.", result);
        }
    }
    // The example displays output like the following:
    //      The workstation garbage collector is running.</code><code class="vb" lang="lang-vb">Imports System
    Imports System.Runtime

    Class Sample
    Public Shared Sub Main()
        Dim result As String

        If GCSettings.IsServerGC = True Then
            result = "server"
        Else
            result = "workstation"
        End If
        Console.WriteLine("The {0} garbage collector is running.", result)
    End Sub
    End Class
    ' The example displays output like the following:
    '      The workstation garbage collector is running.</code></pre>
---
