# autohelp

When you compile with /doc the compiler will search for all XML tags in the source code and create an XML documentation file  ([see XML Documentation Comments](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/xmldoc/xml-documentation-comments)).

AutoHelp reads the DLL & XML Doc files, generates help pages and exposes them to the users.
AutoHelp uses **ASP.NET MVC 5, ASP.NET WebApi, TypeScript, JQuery and Bootstrap** to be a modern web app.

![alt tag](http://download-codeplex.sec.s-msft.com/Download?ProjectName=autohelp&DownloadId=857850)

## Usage

In order to use AutoHelp first download and extract the autohelp-master.zip file to your local projects area.
After that follow these simple instructions to stard documenting your code.

1. Open the AutoHelp.sln then build the solution. 
   Upon debugging you will be presented with your own instance of the AutoHelp website.

2. Navigate to the Manage Tab                                                               
    ![Manage Assemblies](https://www.inventor.tools/General%20Images/AutoHelp.png)
   
3. To add the .dll file that you want to document select then Find Dll file button and navigate to your file.
    ![Find Dll](https://www.inventor.tools/General%20Images/AutoHelp_Find_DLL.png)

4. Next add the XML file associated with the .dll file you selected. For more information on how to create XML documentation see [How to: Generate XML Documentation for a Project](https://msdn.microsoft.com/en-us/library/x4sa0ak0(v=vs.100).aspx)
    ![Find XML](https://www.inventor.tools/General%20Images/AutoHelp_Find_XML.png)
