# How to edit the document tab header via programmatically in WPF DockingManager?

[WPF DockingManager](https://www.syncfusion.com/wpf-controls/docking) does not direct option to edit the tab header programmatically. But you can edit the header via programmatically by invoke the internal method “LabelEditStartInternal” of TabLayoutPanel. You are getting and invoke the same using reflection with corresponding tab item as argument to edit.