# CNCPT Ribbon — Toolbar Documentation

This document catalogs every tool currently active on the **CNCPT** ribbon tab, grouped by panel and (where applicable) pulldown menu. Descriptions are taken from each tool's tooltip text as defined in the source code (`App.cs`).

> Icons are pulled directly from `CNCPT Ribbon/Resources/`. Tools that share an icon file are noted as such — this reflects the current state of the ribbon, not a documentation error.

---

## Panel: Resources

### Direct buttons

| Icon | Name | Description |
|---|---|---|
| ![](icons/model_metrics.png) | **Model Metrics** | Opens Model Metrics Dashboard hosted on BIMBeats. |
| ![](icons/project_creator.png) | **Project Creator** | Copies a folder tree, renames RVTs (keeps A01-style suffix), saves a new host, and relinks Revit links. |

### Pulldown: Links

| Icon | Name | Description |
|---|---|---|
| ![]() | **Cube** | Opens Cube |
| ![]() | **YouCube** | Opens Youcube |
| ![](icons/revit_cubed.png) | **Revit Cubed** | Opens playlist for Revit Cubed |
| ![](icons/pinnacle.png) | **Pinnacle** | Opens Pinnacle |
| ![](icons/autodesk_health.png) | **Autodesk Health** | Opens the Autodesk Website |

### Pulldown: Policies

| Icon | Name | Description |
|---|---|---|
| ![](icons/bim_job_captain.png) | **BIM Job Captain** | Opens BIM Job Captain responsibilities |
| ![](icons/bim_job_captain.png) | **Clash Detection** | Opens the Clash Detection procedure |
| ![](icons/bim_job_captain.png) | **Revit Project Setup** | Opens Revit project setup process |
| ![](icons/bim_job_captain.png) | **Upgrading Projects** | Opens up upgrading project policy |

### Pulldown: Requests

| Icon | Name | Description |
|---|---|---|
| ![](icons/acc_license.png) | **ACC License** | Opens link to service request center to request an ACC License. Note: BIM360 has been rebranded to ACC (Autodesk Construction Cloud). |
| ![](icons/acc_license.png) | **Clarity Setup** | Opens link to service center to request clarity setup. |
| ![](icons/family_creation.png) | **Family Creation** | Request a family to be created. Request is sent to template group. Note: Needs to have Outlook open to work properly. |
| ![](icons/acc_license.png) | **Clash Detection Setup** | Opens link to service request center to request to have a clash detection setup. |

### Pulldown: BIM Standards

| Icon | Name | Description |
|---|---|---|
| ![](icons/bim_job_captain.png) | **Clark Nexsen BIM Standards** | Opens up the Clark Nexsen BIM Standards |
| ![](icons/bim_job_captain.png) | **NCS** | Opens National CADD Standard |
| ![](icons/bim_job_captain.png) | **Navfac** | Opens Navfac Standards |
| ![](icons/bim_job_captain.png) | **AEC** | Opens AEC Standard |
| ![](icons/bim_job_captain.png) | **Veterans Affair** | Opens Veterans Affairs standard |
| ![](icons/bim_job_captain.png) | **BCOM** | Opens BCOM standard |
| ![](icons/bim_job_captain.png) | **SCO** | Opens Standard Construction Office: North Carolina |

---

## Panel: Utilities

### Direct buttons

| Icon | Name | Description |
|---|---|---|
| ![](icons/clash_resolver.png) | **Clash Resolver** | Opens the Clash Resolver — import a Navisworks XML clash report, review statuses, select clashing elements in Revit, and export the updated report. |

### Pulldown: General

| Icon | Name | Description |
|---|---|---|
| ![](icons/export_sheets_impacted_by_revisions.png) | **Export Sheets Impacted by Revisions** | Exports a list of sheets impacted by revisions to Excel (Date, Revision, Sheet number, Sheet name, Comments). |
| ![](icons/create_revision_print_sets.png) | **Create Revision Print Sets** | Creates a named Print Set (Sheet/View Set) for each revision that has sheets. Set name format: Revision Number — Revision Description. Existing print sets with matching names are deleted and recreated automatically. |
| ![](icons/center_all_rooms_spaces_areas.png) | **Center All Rooms, Spaces & Areas** | Centers all rooms, spaces, and areas to their geometric center and centers the room tag, space tag, or area tag to that point. |
| ![](icons/center_all_rooms_spaces_areas.png) | **Rotate 90° About Center** | Prompts you to select any modeled elements, then rotates each one 90° about its own bounding-box center (Z-axis). No rotation point needed — the center is computed automatically. |
| ![](icons/view_sheet_seed.png) | **View Sheet Seed** | Dynamo script used to generate views from a seed view. |
| ![](icons/view_sheet_seed.png) | **Delete Views by Phase** | Dynamo script that deletes views by a phase. |

### Pulldown: Sheet

| Icon | Name | Description |
|---|---|---|
| ![](icons/create_revision_print_sets.png) | **Renumber Viewports by Grid** | Renumbers all viewports on the active sheet using the titleblock grid pattern. Columns: A (left) → Z (right). Rows: 1 (bottom) → N (top). Bottom-left cell = A1. |
| ![](icons/create_revision_print_sets.png) | **Renumber VPs by Position** | Renumbers all viewports on selected sheets using sequential integers (1, 2, 3…). Choose from four sort directions (Left↔Right, Top↔Bottom). Numbers are assigned based on each viewport's center-point position on the sheet. |
| ![](icons/view_sheet_seed.png) | **Sheet - Update Approve, Design, and Review** | Dynamo script that updates the Approve, Design and Review parameters. |
| ![](icons/view_sheet_seed.png) | **Bulk Sheet Creation** | Dynamo script that creates sheets in bulk. |
| ![](icons/create_revision_print_sets.png) | **Hide Crop Regions** | Hides the crop region boundary on all viewports for selected sheets. Select individual sheets or run on the current sheet only. |
| ![](icons/create_revision_print_sets.png) | **Show Crop Regions** | Shows the crop region boundary on all viewports for selected sheets. Select individual sheets or run on the current sheet only. |
| ![](icons/view_sheet_seed.png) | **Graphic Scales Update - Gutter** | Dynamo script that updates the graphic scales in the Gutter file. Note: this requires CN titleblock and CN gutter family. |

### Pulldown: View

| Icon | Name | Description |
|---|---|---|
| ![](icons/make_grids_2d_in_view.png) | **Make Grids 2D in View** | Makes all grid lines in the current view 2D (view-specific extents). |
| ![](icons/flip_selected_grid_ends.png) | **Flip Selected Grid Ends** | Select grids in the view, then flip the grid end (bubble) to the other side. |

### Pulldown: Space

| Icon | Name | Description |
|---|---|---|
| ![](icons/center_space_tags_in_view.png) | **Center Space Tags in View** | Selects all space tags in the current view and centers each tag in its space. |
| ![](icons/center_space_tags_in_view.png) | **Set Limit Offset to 20'** | Sets the space limit offset to 20' for all MEP spaces in the model. |
| ![](icons/center_space_tags_in_view.png) | **Delete Unoccupied and Redundant** | Deletes unoccupied (zero area) and redundant (duplicate number on same level) spaces. Shows a warning with OK and Cancel. |
| ![](icons/center_space_tags_in_view.png) | **Delete All** | Deletes all spaces in the model. Shows a warning with OK and Cancel. |

### Pulldown: Room

| Icon | Name | Description |
|---|---|---|
| ![](icons/center_room_tags_in_view.png) | **Center Room Tags in View** | Centers all room tags in the current view to their room center. |
| ![](icons/center_room_tags_in_view.png) | **Delete Rooms Not Placed** | Deletes all rooms that are not placed in the model. Shows a warning with OK and Cancel. |

---

## Panel: Disciplines

### Pulldown: Architectural

| Icon | Name | Description |
|---|---|---|
| ![](icons/arch_reference_links.png) | **Arch Reference Links** | Opens the Architectural Reference Links panel — clickable preview cards with live website thumbnails for ICC Codes, WBDG, UFGS, UL Product IQ, PCI, BIA Technical Resources, NCMA TEK Solutions, Air Barrier Association, Steel Door Institute, Building Science Corp., and the CN Planning Guide 2022. |
| ![](icons/find_off_angle_walls_grids.png) | **Find Off-Angle Walls & Grids** | Scans floor plan views for walls (straight only) and grid lines whose bearing is not an integer number of degrees. Highlights found elements purple and shows a per-view summary report. |
| ![](icons/export_sheets_impacted_by_revisions.png) | **Import Occupancy Code Schedule** | Scans the network occupancy tables folder for Excel files, lets you pick a file, then clears and repopulates the "Z-Reference (Schedule Key) - Building Code Occupancy Allowance" key schedule with the imported data. |
| ![](icons/find_off_angle_walls_grids.png) | **Renumber Doors From Room** | Renumbers door Mark parameters based on the room number they belong to. Supports multiple suffix formats for rooms with multiple doors. Doors are ordered by clockwise position from the room center. |

### Pulldown: Mechanical

| Icon | Name | Description |
|---|---|---|
| ![](icons/arch_reference_links.png) | **Sizing Guidelines** | Opens Mechanical Guidelines. |
| ![](icons/export_spaces_to_excel.png) | **Export Spaces to Excel** | Exports all available space data to an Excel file in a folder you choose. |
| ![](icons/airflows_from_excel_to_spaces.png) | **Airflows from Excel to Spaces** | Dynamo script that takes airflows from an Excel file and sends them to the spaces. |
| ![](icons/airflows_from_excel_to_spaces.png) | **Air Flows to Space** | Dynamo tool that takes specified airflows from spaces and applies them to diffusers. |
| ![](icons/export_spaces_to_excel.png) | **Place Air Terminals** | Places air terminals in the current model based on positions read from a linked model. Select the linked model, choose a diffuser family type, and pick spaces by selection, all in view, or all in model. Terminals are placed on the linked ceiling face (face-hosted) or level-based as a fallback. Detects existing terminals within 6" and lets you skip or replace them. |
| ![](icons/export_spaces_to_excel.png) | **Align Air Terminals** | Re-snaps existing air terminals to the linked ceiling tile grid. Select the MEP Spaces to process and run from a Ceiling Plan view. Terminals already on the grid, or more than 1.5 ft from any intersection, are left alone. Reports the count adjusted per space. |
| ![](icons/export_spaces_to_excel.png) | **Tag Air Terminals in View** | Tags all air terminals in the current view using the default air terminal tag. Tags are placed offset to the right for readability. |
| ![](icons/export_spaces_to_excel.png) | **Tag Duct/Pipe in View** | Tags all ductwork and pipe in the current view with the default tag. Skips elements shorter than 5 feet. Tags are placed 1 foot above. |
| ![](icons/export_spaces_to_excel.png) | **HVAC TakeOffs** | Building-envelope takeoffs on the active floor plan view: dimensions every exterior wall with two stacked strings on the exterior side, tags all doors and windows hosted in exterior walls, and tags all visible Spaces at the boundary centroid (Number + Name + Area). Per-element errors are collected and reported at the end. |
| ![](icons/export_spaces_to_excel.png) | **Draw Duct and Pipe from Equipment** | Selects all mechanical equipment visible in view and models out duct and pipe connections at 5 feet length. |
| ![](icons/export_spaces_to_excel.png) | **Calculate Duct Length** | Select ductwork elements to calculate and display the total linear length in feet and inches. |
| ![](icons/export_spaces_to_excel.png) | **Apply Insulation** | Applies insulation to ductwork and piping by system type. Select insulation types and thickness from what is loaded in the model, and choose which duct and pipe systems to apply insulation to. Covers straight runs, fittings, and accessories. Optionally overwrites existing insulation. |

### Pulldown: Electrical

| Icon | Name | Description |
|---|---|---|
| ![](icons/voltage_drop_feeder_lengths.png) | **Voltage Drop & Feeder Lengths** | Calculates voltage drop and feeder lengths for electrical equipment. Reads circuit lengths from electrical systems and writes them to CN ElecEQ_Conductor Length. Calculates feeder VD% and cumulative VD% up the supply-from chain for all equipment where "Include in Voltage Drop Calcs" is enabled. |
| ![](icons/voltage_drop_feeder_lengths.png) | **Set Space Limit Offset** | Sets the Limit Offset parameter on every placed MEP Space by ray-casting upward from a grid of sample points to detect the ceiling or structure above each space. Falls back to 15 ft above the space Z for open/outdoor spaces with no ceiling hit. |
| ![](icons/voltage_drop_feeder_lengths.png) | **Align Lighting Devices** | Re-snaps existing lighting fixtures and devices to the linked ceiling tile grid. Uses the same ceiling grid as Align Air Terminals. Fixtures already on the grid, or more than 1.5 ft from any intersection, are left alone. Reports the count adjusted per space. |

### Pulldown: Plumbing

| Icon | Name | Description |
|---|---|---|
| ![](icons/airflows_from_excel_to_spaces.png) | **Future Tool** | Placeholder — not yet implemented. |
| ![](icons/airflows_from_excel_to_spaces.png) | **Model Piping from Equipment** | Selects all mechanical equipment visible in view and models out piping connections at 5 feet length. |

### Pulldown: Fire Protection

| Icon | Name | Description |
|---|---|---|
| ![](icons/airflows_from_excel_to_spaces.png) | **Future Tool** | Placeholder — not yet implemented. |

### Pulldown: Structural

| Icon | Name | Description |
|---|---|---|
| ![](icons/airflows_from_excel_to_spaces.png) | **Future Tool** | Placeholder — not yet implemented. |

---

## Panel: BIM Management

> Conditional panel — only appears if the current user is listed in `bim-management-users.txt` (whitelist check in `Utils.IsUserInWhitelist`).

### Direct buttons

| Icon | Name | Description |
|---|---|---|
| ![](icons/export_sheets_impacted_by_revisions.png) | **Revit File Report** | Select one or more Revit (.rvt) files and generate a detailed XML report for each, covering worksets, line styles, line patterns, families & types, levels, grids, phases, scope boxes, materials, and fill patterns. |
| ![](icons/arch_reference_links.png) | **Report Dashboard** | Opens the Revit Report Dashboard in your default browser. Load the XML files generated by the Revit File Report tool to visualize and compare worksets, families, line styles, sheets, materials, and more. Supports loading up to 8 files simultaneously with side-by-side comparison mode. |
| ![](icons/gemini.png) | **Gemini** | Opens the AI Toolbox with Gemini login/access instructions. |

---

## Notes

- All tools live under the single **CNCPT** ribbon tab.
- A number of buttons and entire panels (Links/Standards individual tabs, several legacy Dynamo tools, discipline "Template Request" buttons, and unused discipline tabs) exist in source but are currently commented out and not shown on the live ribbon — they were excluded from this document since they aren't part of the active toolbar.
- "Future Tool" placeholders (Plumbing, Fire Protection, Structural) are reserved slots with no functionality yet.
