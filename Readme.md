<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128542507/13.1.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E4334)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [Default.aspx](./CS/WebSite/Default.aspx) (VB: [Default.aspx](./VB/WebSite/Default.aspx))
<!-- default file list end -->
# How to set the text max length in the ASPxMemo control
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/e4334/)**
<!-- run online end -->


<p><strong>UPDATED:</strong><br><br>Starting with version v2013 vol 1 (13.1) the ASPxMemo.MaxLength property is available out-of-the-box.<br>Please refer to the <a href="https://www.devexpress.com/Support/Center/p/S91467">S91467: ASPxMemo - Support MaxLength</a> report for more information.<br><br>This example shows how to set the text max length in the ASPxMemo control.<br><br>If an end-user types in text or pastes it by using a corresponding shortcut, you can crop the text in the KeyDown event handler when its length exceeds the max value. If the end-user pastes text to ASPxMemo by using the context menu, you can crop the text in the "paste" event handler of the ASPxMemo "textarea" element. We disable the context menu for ASPxMemo in the Opera browser because it does not provide the "paste" event.</p>
<p><br><strong>See also:<br></strong><a href="https://www.devexpress.com/Support/Center/p/E393">OBSOLETE: ASPxMemo - How to limit the length of text that can be entered into the control using MaxLength</a><br><a href="https://www.devexpress.com/Support/Center/p/E1424">How to implement the "characters remaining" functionality for ASPxTextBox and ASPxMemo using MaxLength</a></p>

<br/>


