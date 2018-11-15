<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/WindowsApplication53/Form1.cs) (VB: [Form1.vb](./VB/WindowsApplication53/Form1.vb))
* [Program.cs](./CS/WindowsApplication53/Program.cs) (VB: [Program.vb](./VB/WindowsApplication53/Program.vb))
<!-- default file list end -->
# How to handle the Customization Form (Field list) items click


<p><a href="http://documentation.devexpress.com/#WindowsForms/CustomDocument1927">Customization Form</a> consists of several child controls. To display field headers, descendants of the <a href="http://documentation.devexpress.com/#WindowsForms/clsDevExpressXtraEditorsListBoxControltopic">ListBoxControl</a> class are used. So, it is necessary to iterate through all the controls to find ListBoxControl, and then use their events to accomplish task.</p>

<br/>


