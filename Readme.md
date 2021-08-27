<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128648785/13.1.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E2568)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [Window1.xaml](./CS/DXGrid_ChangeRowAppearance/Window1.xaml) (VB: [Window1.xaml.vb](./VB/DXGrid_ChangeRowAppearance/Window1.xaml.vb))
* [Window1.xaml.cs](./CS/DXGrid_ChangeRowAppearance/Window1.xaml.cs) (VB: [Window1.xaml.vb](./VB/DXGrid_ChangeRowAppearance/Window1.xaml.vb))
<!-- default file list end -->
# How to change selected cells' appearance when GridControl's multi-cell selection is enabled


<p>You should implement your own CellStyle. In this CellStyle, implement style triggers for the SelectionState property. Four values can be 
<br />
assigned to this property: None, Focused, Selected, FocusedAndSelected.</p>

<br/>


