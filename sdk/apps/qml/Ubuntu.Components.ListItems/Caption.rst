.. _sdk_ubuntu_components_listitems_caption:

Ubuntu.Components.ListItems Caption
===================================

List item that shows a piece of text.

+--------------------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------+
| Import Statement:                                                                                                                                      | import Ubuntu.Components.ListItems 1.3                                                                                                                    |
+--------------------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------+
| Inherits:                                                                                                                                              | :ref:`Item <sdk_qtquick_item>`                                                                                                                            |
+--------------------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------+

Properties
----------

-  `text </sdk/apps/qml/Ubuntu.Components/ListItems.Caption/#text-prop>`_  : string

Detailed Description
--------------------

**Note:** **The component is deprecated. Use :ref:`ListItem <sdk_ubuntu_components_listitem>` and Captiopns components instead.**

Examples:

.. code:: qml

    import Ubuntu.Components.ListItems 1.3 as ListItem
    Column {
        ListItem.Standard {
            text: "Default list item."
        }
        ListItem.Caption {
            text: "This is a caption text, which can span multiple lines."
        }
    }

Property Documentation
----------------------

.. _sdk_ubuntu_components_listitems_caption_text:

+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| text : string                                                                                                                                                                                                                                                                                                |
+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

The text that is shown in the list item as a label.

