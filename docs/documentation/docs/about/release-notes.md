# Releases

## 1.7.0

**Enhancements**

- `PeoplePicker`: added functionality to initialize the control with person(s) or group(s) [#98](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/98)
- `PeoplePicker`: support for searching on contains [#93](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/93)
- `PeoplePicker`: find user based on email address [#95](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/95)
- Bundle size: statically reference Office UI Fabric components in the FieldRenderer controls [#107](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/107)

**Fixes**

- `FieldNameRenderer` onClick does not suppress default link behavior [#103](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/103)

## 1.6.0

**Enhancements**

- Disabled property for PeoplePicker [#88](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/88)

**Fixes**

- New telemetry approach which allows you to use Application Insights [#81](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/81)
- PeoplePicker property selectedItems not implemented? [#90](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/90)

## 1.5.0

**New control(s)**

- New `PeoplePicker` control added [#19](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/19)

**Enhancements**

- Added properties to the `TaxonomyPicker` to specify which terms are disabled/not-selectable [#82](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/82)

**Fixes**

- Bug in `TaxonomyPicker` where values are not updated by an async change [#83](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/83)
- `FieldUserRenderer` uses email prop for `GetPropertiesFor` [#84](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/84)
- Fixed issue in single selection mode when all group items were selected in the `ListView` when user clicked on the group header [#86](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/86)

## 1.4.0

**New control(s)**

- `SecurityTrimmedControl` control got added [#74](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/74)

**Enhancements**

- Allow the `TaxonomyPicker` to also be used in Application Customizer [#77](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/77)
- Add `npm postinstall` script to automatically add the locale config [#78](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/78)

**Fixes**

- Icon not showing up in the `Placeholder` control [#76](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/76)

## 1.3.0

**Enhancements**

- `TaxonomyPicker` control got added [#22](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/22) [#63](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/63) [#64](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/64)
- `ListPicker` control got added [#34](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/34)

**Fixes**

- Issue fixed when the optional `selection` property was not provided to the `ListView` [#65](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/65)

## 1.2.5

**Fixes**

- Undo `ListView` item selection after items array updates [#55](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/55)

## 1.2.4

**Enhancements**

- Hiding placeholder title on small zones

**Fixes**

- iFrame dialog reference fix [#52](https://github.com/SharePoint/sp-dev-fx-controls-react/issues/52)

## 1.2.3

**Enhancements**

- Optimized telemetry so that it only pushes control data
- `WebPartTitle` hide control completely when empty

## 1.2.2

**Fixes**

- Fixes an issue sorting in the `ListView` control while items were selected. Indexes were not updated.

## 1.2.1

**Fixes**

- `FieldTaxonomyRenderer` got fixed to support single and multiple values

## 1.2.0

**New control(s)**

- Field controls are added to the project
- `IFrameDialog` was added to the project

**Fixes**

- Fixed theming in the `WebPartTitle` control

## 1.1.3

**Fixes**

- `FileTypeIcon` icon fixed where it did not render an icon. This control should now works in SPFx extensions.

## 1.1.2

**Enhancements**

- Improved telemetry with some object checks

**Fixes**

- Fix for `WebPartTitle` control to inherit color

## 1.1.1

**Enhancements**

- Removed operation name from telemetry

## 1.1.0

**Enhancements**

- Telemetry added

## 1.0.0

**New control(s)**

- `WebPartTitle` control got added

**Enhancements**

- ListView control got extended with the ability to specify a set of preselected items.

## Beta 1.0.0-beta.8

**Fixes**

- Fix for the `ListView` control when selection is used in combination with `setState`.

## Beta 1.0.0-beta.7

**New control(s)**

- Grouping functionality added to the `ListView` control

## Beta 1.0.0-beta.6

**New control(s)**

- Initial release
