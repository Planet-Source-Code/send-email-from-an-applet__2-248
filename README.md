<div align="center">

## Send email from an applet


</div>

### Description

Can I send an Email from an applet? Of Course you can just use the following! OR you could look at www.javasoft.com for Java mailAPI.

(Found on the web--Java FAQ at http://www.irt.org)
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[N/A](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/empty.md)
**Level**          |Unknown
**User Rating**    |2.5 (5 globes from 2 users)
**Compatibility**  |Java \(JDK 1\.1\)
**Category**       |[Applet](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/applet__2-81.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/send-email-from-an-applet__2-248/archive/master.zip)





### Source Code

```
try {
  URL mail = new URL("MAILTO:YOU@HOME.ORG");
} catch (MalformedURLException e) {
  System.err.println("Invalid URL");
}
getAppletContext().showDocument(mail);
```

