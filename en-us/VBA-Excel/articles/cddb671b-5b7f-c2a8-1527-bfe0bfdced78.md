
# Window.DisplayZeros Property (Excel)

 **Last modified:** March 10, 2013

 **In this article**
 [Syntax](#sectionSection0)
 [Remarks](#sectionSection1)
 [Example](#sectionSection2)


 **True** if zero values are displayed. Read/write **Boolean**.


## Syntax
<a name="sectionSection0"> </a>

 _expression_. **DisplayZeros**

 _expression_A variable that represents a  **Window** object.


## Remarks
<a name="sectionSection1"> </a>

This property applies only to worksheets and macro sheets.


## Example
<a name="sectionSection2"> </a>

This example sets the active window in Book1.xls to display zero values.


```
Workbooks("BOOK1.XLS").Worksheets("Sheet1").Activate 
ActiveWindow.DisplayZeros = True 

```


## See also
<a name="sectionSection2"> </a>


#### Concepts


 [Window Object](8591b1ad-76f8-14e2-9120-406b65093f5a.md)
#### Other resources


 [Window Object Members](f11db427-24a4-041c-2fd5-03ce73ae6c16.md)
