
# Databar.BarBorder Property (Excel)

 **Last modified:** March 10, 2013

 **In this article**
 [Version Information](#sectionSection0)
 [Syntax](#sectionSection1)
 [Example](#sectionSection2)


Returns an object that specifies the border of a data bar. Read-only


## Version Information
<a name="sectionSection0"> </a>

Version Added: Excel 2010 


## Syntax
<a name="sectionSection1"> </a>

 _expression_. **BarBorder**

 _expression_A variable that represents a  ** [Databar](2684e913-c278-e6be-ba9d-053b6ad58bae.md)** object.


### Return Value

 ** [DataBarBorder](e46bb88b-ec41-a4f9-8926-34d0a22ad8e9.md)**


## Example
<a name="sectionSection2"> </a>

The following code example selects a range of cells, adds a data bar conditional formatting rule to that range, uses the  **BarBorder** property to retrieve the **DataBarBorder** object associated with that rule, and then sets the data bar's color, tint, and type.


```
Range("A1:A10").Select 
Range("A1:A10").Activate 
 
Set myDataBar = Selection.FormatConditions.AddDatabar 
With myDataBar.BarBorder 
 .Type = xlDataBarBorderSolid 
 .Color.ThemeColor = xlThemeColorAccent2 
 .Color.TintAndShade = 0 
End With 

```


## See also
<a name="sectionSection2"> </a>


#### Concepts


 [Databar Object](2684e913-c278-e6be-ba9d-053b6ad58bae.md)
#### Other resources


 [Databar Object Members](137f7e88-bb61-48a3-d2cb-76a8282cd62e.md)
