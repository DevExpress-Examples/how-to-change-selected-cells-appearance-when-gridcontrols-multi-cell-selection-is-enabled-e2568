<!-- default file list -->
*Files to look at*:

* **[Window1.xaml](./CS/DXGrid_ChangeRowAppearance/Window1.xaml) (VB: [Window1.xaml](./VB/DXGrid_ChangeRowAppearance/Window1.xaml))**
* [Window1.xaml.cs](./CS/DXGrid_ChangeRowAppearance/Window1.xaml.cs) (VB: [Window1.xaml.vb](./VB/DXGrid_ChangeRowAppearance/Window1.xaml.vb))
<!-- default file list end -->
# How to change selected cells' appearance when GridControl's multi-cell selection is enabled


<p>You should implement your own CellStyle. In this CellStyle, implement style triggers for the SelectionState property. Four values can be 
<br />
assigned to this property: None, Focused, Selected, FocusedAndSelected.</p>

<br/>


