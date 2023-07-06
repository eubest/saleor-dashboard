# Changelog

## 3.14.0

### Minor Changes

- 7309c736b: Clean up FilterElement type
- 3093be1b7: Drop deprecated fields in transactionsAPI
- 158b22d1e: Introduce two new hook to handle datagrid, useFilterPresets to handle CRUD operation on filter presets and useRowSelection to handle datagrid row selection
- 97e440189: Implement url management for filters, clean up types
- 198341cb4: Prototype of the new filters for product listing page
- 1cb6e8b5f: Add possibility to manually edit permissions of the app. Now every user with MANAGE_APPS permission can grant any permission to the app via App -> Manage App view or remove permissions previously assigned.
- fec476b7e: Add API handlers to expermiental filters
- b4f11eff6: Introduce datagrid on category listing page
- e37c8ce44: Refactor product list datagrid to use useFilterPresets and useRowSelection hooks
- 07fa3bc0c: Properly type event handler for experimental filters
- 09c9024e0: Introduce datagrid on order draft list
- d282769fd: Refactor order list datagrid to use useFilterPresets and useRowSelection hooks
- 1cb6e8b5f: App's "about" section will be rendered as a plain text, instead of a markdown
- b0214c645: Apps: Fixed problem with Permissions Modal that was clipped on smaller screens. Now long permissions list is scrollable.

### Patch Changes

- f8c9317ed: Experimental filters: fix types and refactor initial api state
- 58a3c26f7: Applied refactors on "apps" module. Renamed some "marketplace" symbols to "appstore". Replaced some "Default" exports to named ones. Didn't introduce any visual or functional changes.
- a8babc425: Changed rendered apps' thumbnails to be bigger. They are sharper now.
- a08d034e7: Fix unability to save attribute value when the attribute value is invalid (attribute value should be only send when attribute input type is swatch)
- 52bac3b8f: Update ExpressionValue for fitlers
- 8fbf0d4a8: Set custom version within the workflow of deployments from main
- 8d16513ea: Enable method signature style ESLint rule
- a1482cc45: Refactored Manage App screen to use Macaw/next. Added missing empty-state messages, like missing permissions or app description.
- 4433a9463: Refactoring FilterContainer in filter feature
- f71e0b762: Fix customer is not present in order list view
- 1c9291932: Enable no-console ESLint rule
- 72d4df482: Fix unable to select value in simple autocomplete field
- 05ff53373: Fix null-cheks for filters
- 664029407: Dashboard is sending Saleor and Dashboard versions with Handshake event to apps, via AppBridge. To achieve that, @saleor/app-sdk was updated to 0.41.0
- 3123f04c6: Update to ESLint 8 & use standard-with-typescript ruleset
