### Description
TabWidget is a Mendix widget that changes the caption of the default mendix TabContainer.
The new caption will be populated via a user selectable string attribute.

### Typical usage scenario
More detailed information can be shown at the tab captions of the tabcontainer.


### Features and limitations
- Population of tab captions through attributes.
- 1 widget per tab, multiple tabs = multiple widgets
- Captions will no refresh automatically, the page or tabcontainer need to be refreshed in order to get updated captions.

### Installation
- Place the Widget in a dataview which contains the Attribute to show
- Fill in the appropiate tabname (Default: Page 1) in the widget
- Assign the attribute in the widget