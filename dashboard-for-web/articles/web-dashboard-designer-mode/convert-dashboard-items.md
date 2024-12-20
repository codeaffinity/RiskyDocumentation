---
title: Convert Dashboard Items
author: Sandakelum Senevirathna
legacyId: 117951
---
# Convert Dashboard Items
The Web Dashboard provides the capability to convert data-bound dashboard items to another type.

To convert the selected dashboard item to another type, use the dashboard item's [Convert To](ui-elements/dashboard-item-menu.md) menu.

![wdd-convert-to-dialog](../../images/img125857.png)

> [!NOTE]
> You can also created a copy of the selected dashboard item using the **Duplicate current item** command.

The Web Dashboard always preserves the following settings for data-bound dashboard items.
* The set of data items used to bind the dashboard item to data.
* Data shaping settings of data items and their names.
* A custom name displayed within the dashboard item caption.

The following settings are kept if the dashboard item is being converted to an item that also supports this feature.
* [Master Filtering](interactivity/master-filtering.md) settings (e.g., the specified master filter mode).
* [Drill-Down](interactivity/drill-down.md) settings (e.g., the target dimension).
* [Conditional Formatting](appearance-customization/conditional-formatting.md) settings.
* [Coloring](appearance-customization/coloring.md) settings.
* [Calculation](data-analysis/calculations.md) settings.

For different types of dashboard items, some specific settings can be preserved. For example, the following settings are preserved.
* Legend settings for the [Chart](dashboard-item-settings/chart.md)/[Scatter Chart](dashboard-item-settings/scatter-chart.md) dashboard items.
* Series types for the [Chart](dashboard-item-settings/chart.md)/[Range Filter](dashboard-item-settings/range-filter.md) dashboard items.
* Element arrangement settings for the [Pie](dashboard-item-settings/pies.md)/[Card](dashboard-item-settings/cards.md)/[Gauge](dashboard-item-settings/gauges.md) dashboard items.
* Caption settings for the [Pie](dashboard-item-settings/pies.md)/[Gauge](dashboard-item-settings/gauges.md) dashboard items.
* Navigation settings for [Choropleth Map](dashboard-item-settings/choropleth-map.md)/[Geo Point Maps](dashboard-item-settings/geo-point-maps.md).
* The attribute whose values are displayed within shape titles for [Choropleth Map](dashboard-item-settings/choropleth-map.md)/[Geo Point Maps](dashboard-item-settings/geo-point-maps.md).
* Legend settings for the [Choropleth Map](dashboard-item-settings/choropleth-map.md)/[Geo Point Maps](dashboard-item-settings/geo-point-maps.md).
* Clustering settings for [Geo Point Maps](dashboard-item-settings/geo-point-maps.md).