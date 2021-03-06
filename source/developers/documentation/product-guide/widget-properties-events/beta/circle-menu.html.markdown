---
old_url: circle_menu.htm
title: "Circle Menu"
active_menu_item: developers
class_name: developers
full_width: true
---


The Circle Menu Widget should be considered to be in a Beta state until mention of it is removed from the documentation and is accessible from the Advanced section of the Toolbox

This widget allows you to have a circular menu of items to select from. Includes a selection animation and various animation options for opening and closing the menu.  Commonly would be used for Page Navigation. Thanks to [http://zikes.github.com/circle-menu/](http://zikes.github.com/circle-menu/)

<table>
<tr>
<td width="138">
<a id="general"> </a> <b>General</b>

</td>
<td width="21">
</td>
<td width="782">
</td>
</tr>
<tr>
<td width="138">
Widget Class

</td>
<td width="21">
</td>
<td width="782">
Internal class name of the widget.- CircleMenu

</td>
</tr>
<tr>
<td width="138">
Name

</td>
<td width="21">
</td>
<td width="782">
This is the Widget name that is displayed when references are made to the Widget. You can choose any name that includes alphanumeric characters.

</td>
</tr>
<tr>
<td width="138">
Items

</td>
<td width="21">
</td>
<td width="782">
  This is where you can prefill your list/dropdown widgets either manually or by importing a CSV list stored as a resource. See <a href="/developers/documentation/product-guide/widget-properties-events/prefill">Prefill</a>. The top entry is where you can enter text to show in the main item

</td>
</tr>
<tr>
<td width="138">
Start Angle

</td>
<td width="21">
</td>
<td width="782">
Specify the position of the items in relation to the center, measured in degrees where 0/360 are on the right and angle travels in a clockwise direction. An alternative to the Direction option, if you want more control

</td>
</tr>
<tr>
<td width="138">
End Angle

</td>
<td width="21">
</td>
<td width="782">
Define the offset angle for the last item to show when Direction is set to 'none'

</td>
</tr>
<tr>
<td width="138">
Circle Radius

</td>
<td width="21">
</td>
<td width="782">
Define the radius of the circle that determines the distance of the items from the center.

</td>
</tr>
<tr>
<td width="138">
Delay

</td>
<td width="21">
</td>
<td width="782">
When the menu is triggered on hover, the delay is the amount of time before the items will move back in to the center, measured in milliseconds.

</td>
</tr>
<tr>
<td width="138">
Direction

</td>
<td width="21">
</td>
<td width="782">
The direction of the items in relation to the center. top will place the items above the center, in a 90 degree semicircle centered upwards. top-half will create a full 180 degree semicircle. full will create a full 360 degree circle, with the first item appearing at the top

</td>
</tr>
<tr>
<td width="138">
Item Diameter

</td>
<td width="21">
</td>
<td width="782">
The diameter of each item, in pixels. Used to set the CSS properties of each item including width, height, and border-radius.

</td>
</tr>
<tr>
<td width="138">
Speed

</td>
<td width="21">
</td>
<td width="782">
The animation speed, in milliseconds. The number given is the total amount of time it will take for the items to move in or out from the center.

</td>
</tr>
<tr>
<td width="138">
StepIn

</td>
<td width="21">
</td>
<td width="782">
The number of milliseconds between each item moving in to the center when the menu closes. A negative value will cause the menu to close in reverse, starting with the last item.

</td>
</tr>
<tr>
<td width="138">
StepOut

</td>
<td width="21">
</td>
<td width="782">
The number of milliseconds between each item moving out from the center when the menu opens. A negative value will cause the menu to open in reverse, starting with the last item.

</td>
</tr>
<tr>
<td width="138">
Transition Function

</td>
<td width="21">
</td>
<td width="782">
Options: ease | linear | ease-in | ease-out | ease-in-out | cubic-bezier(n,n,n,n) Default: ease

The CSS timing function used to control the open/close animation.

</td>
</tr>
<tr>
<td width="138">
Trigger

</td>
<td width="21">
</td>
<td width="782">
How the menu is triggered to open and close, whether by hovering over the center item or clicking on it.

</td>
</tr>
</table>
<table>
<tr>
<td width="138">
<a id="layout"> </a> <b>Layout</b>

</td>
<td width="21">
</td>
<td width="782">
</td>
</tr>
<tr>
<td width="138">
X

</td>
<td width="21">
</td>
<td width="782">
Number of pixels from the left edge of the Page.

</td>
</tr>
<tr>
<td width="138">
Y

</td>
<td width="21">
</td>
<td width="782">
Number of pixels from the top edge of the Page.

</td>
</tr>
<tr>
<td width="138">
Sizes

</td>
<td width="21">
</td>
<td width="782">
  Where you can set the Width and Height of the widget. If a widget is within a Container in Vertical or Horizontal mode, then the widget can also be made to change size in response to the size of the display width and height See <a href="/developers/documentation/product-guide/content-and-app-layout/responsive-adaptive-fluid-design/sizes-property-dialog">'Sizes' Property Dialog</a>

</td>
</tr>
<tr>
<td width="138">
Repeat

</td>
<td width="21">
</td>
<td width="782">
  If set to True, this displays the Widget on either all pages except ones you specify in a list or only on pages you choose from a list.  Find out more about this in <a href="/developers/documentation/product-guide/content-and-app-layout/editing-and-laying-out-reference/repeating-widgets-across-multi">Repeating Widgets Across Multiple Pages</a>.

</td>
</tr>
<tr>
<td width="138">
Z-Index

</td>
<td width="21">
</td>
<td width="782">
A number that indicates the imaginary layer that the Widget is in. If you imagine several Widgets all placed over one another, the top-most Widget has the highest Z-Index and the bottom most Widget has the lowest. You can adjust the Z-Index by changing the value. You can also use the right-click menu to adjust these in a friendlier way.

</td>
</tr>
<tr>
<td width="138">
Anchors

</td>
<td width="21">
</td>
<td width="782">
  This is used in conjunction with "Docked" App Pages. You can use this to allows a Widget's X, Y, Width and Height to be automatically altered as the browser window is resized. See <a href="/developers/documentation/product-guide/content-and-app-layout/editing-and-laying-out-reference/widget-anchoring">Docking & Anchoring</a> .

</td>
</tr>
<tr>
<td width="138">
Align in Container

</td>
<td width="21">
</td>
<td width="782">
Left/Center/Right. Set as required to align the widget within its parent container

</td>
</tr>
</table>
<table>
<tr>
<td width="138">
<a id="behavior"> </a> <b>Behavior</b>

</td>
<td width="21">
</td>
<td width="782">
</td>
</tr>
<tr>
<td width="138">
Drag and Drop

</td>
<td width="21">
</td>
<td width="782">
If set to true, the user is able to drag and drop the widget with the mouse at run time

</td>
</tr>
<tr>
<td width="138">
Resizing

</td>
<td width="21">
</td>
<td width="782">
Disable/Enable. Set to True to allow the widget to be resized at Runtime. Configurable Max/Min Width and Height, Right & Bottom, Top & Left or All

</td>
</tr>
<tr>
<td width="138">
Visible

</td>
<td width="21">
</td>
<td width="782">
Set to False if you want the Widget to appear hidden by default. You would use Javascript to override this at a later stage.

</td>
</tr>
<tr>
<td width="138">
Enable

</td>
<td width="21">
</td>
<td width="782">
Set to false to leave the Widget visible but to prevent any user interaction

</td>
</tr>
</table>
<table>
<tr>
<td width="138">
<a id="data"> </a> <b>Data</b>

</td>
<td width="21">
</td>
<td width="782">
</td>
</tr>
<tr>
<td width="138">
View

</td>
<td width="21">
</td>
<td width="782">
Select the view to use

</td>
</tr>
<tr>
<td width="138">
Fields

</td>
<td width="21">
</td>
<td width="782">
  This property is used to allow you to set which data fields are taken from the View and used in the Widget. Read the <a href="/developers/documentation/product-guide/advanced-features/data-integration-reporting-dashboards/data-section-properties/fields/">Fields</a> section for more details.

</td>
</tr>
<tr>
<td width="138">
Group By

</td>
<td width="21">
</td>
<td width="782">
  This allows you to Group data within a View in the same way you would with a SQL statement. Read the <a href="/developers/documentation/product-guide/advanced-features/data-integration-reporting-dashboards/data-section-properties/fiieldsgroup-by">Group By</a> section for more details.

</td>
</tr>
<tr>
<td width="138">
Order By

</td>
<td width="21">
</td>
<td width="782">
  Specifies the order in which data is presented to the Widget.  Read the <a href="/developers/documentation/product-guide/advanced-features/data-integration-reporting-dashboards/data-section-properties/order-by">Order By</a> section for more details.

</td>
</tr>
<tr>
<td width="138">
Filter

</td>
<td width="21">
</td>
<td width="782">
This is a global, static filter that can be defined for each View in your App.

</td>
</tr>
<tr>
<td width="138">
Drill Filter

</td>
<td width="21">
</td>
<td width="782">
  This property controls the Drill Down filter that is set when a Widget is clicked on whose Broadcast property is set to True. You will be shown the Expression Editor and you can specify the precise condition that should be applied to the View that the Widget is connected to. Read the <a href="/developers/documentation/product-guide/advanced-features/data-integration-reporting-dashboards/data-section-properties/drill-filter">Drill Filter</a> section for more details.

</td>
</tr>
<tr>
<td width="138">
Broadcast

</td>
<td width="21">
</td>
<td width="782">
  Indicates whether a click action on a Widget should trigger a Drill Down on any other Widgets that a) share the same Data Source and b) whose Listen property is set. Read the <a href="/developers/documentation/product-guide/advanced-features/data-integration-reporting-dashboards/data-section-properties/broadcast">Broadcast</a> section for more details.

</td>
</tr>
<tr>
<td width="138">
Listen

</td>
<td width="21">
</td>
<td width="782">
  This indicates whether the Widget should react to a Drill Down action on a common View. Read the <a href="/developers/documentation/product-guide/advanced-features/data-integration-reporting-dashboards/data-section-properties/listen">Listen</a> section for more details.

</td>
</tr>
<tr>
<td width="138">
Reset Filter

</td>
<td width="21">
</td>
<td width="782">
  Indicates whether a Drill Down on the Widget should reset the View's filter or whether it should add to the existing filter. Read the <a href="/developers/documentation/product-guide/advanced-features/data-integration-reporting-dashboards/data-section-properties/reset-filter">Reset Filter</a> section for more details.

</td>
</tr>
<tr>
<td width="138">
Auto Load

</td>
<td width="21">
</td>
<td width="782">
Set to true to automatically fetch data from assigned view.

</td>
</tr>
</table>
<table>
<tr>
<td width="138">
<a id="style"> </a> <b>Style</b>

</td>
<td width="21">
</td>
<td width="782">
</td>
</tr>
<tr>
<td width="138">
Opacity

</td>
<td width="21">
</td>
<td width="782">
This % value specifies the transparency of the Widget.

</td>
</tr>
<tr>
<td width="138">
Margin

</td>
<td width="21">
</td>
<td width="782">
  Used to specify the margin around a widget when the parent container is in Relative Mode. See <a href="/developers/documentation/product-guide/content-and-app-layout/introduction/setting-a-margin">Setting a Margin</a>

</td>
</tr>
<tr>
<td width="138">
Box Sizing

</td>
<td width="21">
</td>
<td width="782">
content-box/border-box. Content-box - The padding or border of the element are laid out and drawn outside the specified width and height. Border-box -The padding or border element is laid out and drawn inside the specified width and height.

</td>
</tr>
<tr>
<td width="138">
Border

</td>
<td width="21">
</td>
<td width="782">
Specified the line width/style and colour of the border surrounding the Widget.

</td>
</tr>
<tr>
<td width="138">
BG Color

</td>
<td width="21">
</td>
<td width="782">
This specifies a default background color of the App. .

</td>
</tr>
<tr>
<td width="138">
Font

</td>
<td width="21">
</td>
<td width="782">
Define the Font for items in the menu

</td>
</tr>
<tr>
<td width="138">
Color

</td>
<td width="21">
</td>
<td width="782">
Define the Font Color of items in the menu

</td>
</tr>
<tr>
<td width="138">
Item Bg Color

</td>
<td width="21">
</td>
<td width="782">
Define the Background Color of the Menu Items

</td>
</tr>
<tr>
<td width="138">
Custom CSS Classes

</td>
<td width="21">
</td>
<td width="782">
  Where you define your CSS Style to customise your widgets  See also <a href="/developers/documentation/product-guide/advanced-features/custom-css-classes/">Custom CSS Classes</a>

</td>
</tr>
<tr>
<td width="138">
Widget Style

</td>
<td width="21">
</td>
<td width="782">
  This refers to the <a href="/developers/documentation/product-guide/content-and-app-layout/introduction/themes-styles/themesmanage">Theme entry</a> that should be used to set the Widget's default appearance. Once a Theme Style has been selected, individual components such as Font and Colors can be Set to False if you want the Widget to appear hidden by default.

</td>
</tr>
</table>

<table>
<tr>
<td width="148">
  <strong>Supported Events:</strong>

</td>
<td width="15">
</td>
<td width="108">
</td>
<td width="11">
</td>
<td width="140">
</td>
</tr>
<tr>
<td width="148">
  <a href="/developers/documentation/product-guide/widget-properties-events/events/event-reference-list/mouse-events">Mouse Events</a>

</td>
<td width="15">
</td>
<td width="108">
  <a href="/developers/documentation/product-guide/widget-properties-events/events/event-reference-list/general-events">General Events</a>

</td>
<td width="11">
</td>
<td width="140">
  <a href="/developers/documentation/product-guide/widget-properties-events/events/event-reference-list/data-events">Data Events</a>

</td>
</tr>
<tr>
<td width="148">
On Click

</td>
<td width="15">
</td>
<td width="108">
OnInit

</td>
<td width="11">
</td>
<td width="140">
OnSelect

</td>
</tr>
<tr>
<td width="148">
On Double Click

</td>
<td width="15">
</td>
<td width="108">
OnOpen

</td>
<td width="11">
</td>
<td width="140">
</td>
</tr>
<tr>
<td width="148">
On Mouse Down

</td>
<td width="15">
</td>
<td width="108">
OnClose

</td>
<td width="11">
</td>
<td width="140">
</td>
</tr>
<tr>
<td width="148">
On Mouse Up

</td>
<td width="15">
</td>
<td width="108">
</td>
<td width="11">
</td>
<td width="140">
</td>
</tr>
<tr>
<td width="148">
On Mouse Enter

</td>
<td width="15">
</td>
<td width="108">
</td>
<td width="11">
</td>
<td width="140">
</td>
</tr>
<tr>
<td width="148">
On Mouse Leave

</td>
<td width="15">
</td>
<td width="108">
</td>
<td width="11">
</td>
<td width="140">
</td>
</tr>
<tr>
<td width="148">
On Drag Start

</td>
<td width="15">
</td>
<td width="108">
</td>
<td width="11">
</td>
<td width="140">
</td>
</tr>
<tr>
<td width="148">
On Drag Stop

</td>
<td width="15">
</td>
<td width="108">
</td>
<td width="11">
</td>
<td width="140">
</td>
</tr>
<tr>
<td width="148">
On Resize Start

</td>
<td width="15">
</td>
<td width="108">
</td>
<td width="11">
</td>
<td width="140">
</td>
</tr>
<tr>
<td width="148">
On Resize Stop

</td>
<td width="15">
</td>
<td width="108">
</td>
<td width="11">
</td>
<td width="140">
</td>
</tr>
</table>

## See Also

 - [Circular Menu Widget](/developers/documentation/product-guide/advanced-important-widgets/circle-menu-widget/)
 - [Mouse Events](/developers/documentation/product-guide/widget-properties-events/events/event-reference-list/mouse-events)
 - [General Events](/developers/documentation/product-guide/widget-properties-events/events/event-reference-list/general-events)
 - [Data Events](/developers/documentation/product-guide/widget-properties-events/events/event-reference-list/data-events)
