# Graph Report - .  (2026-04-17)

## Corpus Check
- Large corpus: 578 files · ~411,593 words. Semantic extraction will be expensive (many Claude tokens). Consider running on a subfolder, or use --no-semantic to run AST-only.

## Summary
- 4833 nodes · 15939 edges · 77 communities detected
- Extraction: 46% EXTRACTED · 54% INFERRED · 0% AMBIGUOUS · INFERRED: 8596 edges (avg confidence: 0.8)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_UI Interactions & Undo|UI Interactions & Undo]]
- [[_COMMUNITY_Dynamic Element Text|Dynamic Element Text]]
- [[_COMMUNITY_Project & View Management|Project & View Management]]
- [[_COMMUNITY_Title Block Templates|Title Block Templates]]
- [[_COMMUNITY_Graphics Styling (PenColor)|Graphics Styling (Pen/Color)]]
- [[_COMMUNITY_Terminal Strip Logic|Terminal Strip Logic]]
- [[_COMMUNITY_Element Editor Operations|Element Editor Operations]]
- [[_COMMUNITY_Conductor & Terminal Positioning|Conductor & Terminal Positioning]]
- [[_COMMUNITY_Dynamic Text Fields|Dynamic Text Fields]]
- [[_COMMUNITY_App Window Lifecycle|App Window Lifecycle]]
- [[_COMMUNITY_XML Tag & Attribute Handling|XML Tag & Attribute Handling]]
- [[_COMMUNITY_App Core & Argument Parsing|App Core & Argument Parsing]]
- [[_COMMUNITY_Elements Panel & Widgets|Elements Panel & Widgets]]
- [[_COMMUNITY_Diagram XML Serialization|Diagram XML Serialization]]
- [[_COMMUNITY_Diagram Editor & Actions|Diagram Editor & Actions]]
- [[_COMMUNITY_Project Database & UUIDs|Project Database & UUIDs]]
- [[_COMMUNITY_Element Scene & Scaling|Element Scene & Scaling]]
- [[_COMMUNITY_Print & Layout Patterns|Print & Layout Patterns]]
- [[_COMMUNITY_Primitive Decorators & Orientation|Primitive Decorators & Orientation]]
- [[_COMMUNITY_Configuration & Properties Widgets|Configuration & Properties Widgets]]
- [[_COMMUNITY_Terminal Strip Drawer & Tables|Terminal Strip Drawer & Tables]]
- [[_COMMUNITY_Template Cell Editing|Template Cell Editing]]
- [[_COMMUNITY_About Dialog & Versioning|About Dialog & Versioning]]
- [[_COMMUNITY_Filename Editing & Validation|Filename Editing & Validation]]
- [[_COMMUNITY_Text Orientation Widgets|Text Orientation Widgets]]
- [[_COMMUNITY_Mouse & Wheel Events (DV)|Mouse & Wheel Events (DV)]]
- [[_COMMUNITY_Mouse & Wheel Events (Diagram)|Mouse & Wheel Events (Diagram)]]
- [[_COMMUNITY_Demo Terminal Strip|Demo Terminal Strip]]
- [[_COMMUNITY_Formula Assistant|Formula Assistant]]
- [[_COMMUNITY_Project Documentation & Ecosystem|Project Documentation & Ecosystem]]
- [[_COMMUNITY_Terminal Strip Interfaces|Terminal Strip Interfaces]]
- [[_COMMUNITY_Simple Element Initialization|Simple Element Initialization]]
- [[_COMMUNITY_Element Properties Editors|Element Properties Editors]]
- [[_COMMUNITY_Add Link Dialog UI|Add Link Dialog UI]]
- [[_COMMUNITY_Versioning Utils|Versioning Utils]]
- [[_COMMUNITY_Icon Management|Icon Management]]
- [[_COMMUNITY_Message Box Utils|Message Box Utils]]
- [[_COMMUNITY_Elements Movement Driver|Elements Movement Driver]]
- [[_COMMUNITY_Element Properties Header|Element Properties Header]]
- [[_COMMUNITY_Config Page Base|Config Page Base]]
- [[_COMMUNITY_Terminal Data Models|Terminal Data Models]]
- [[_COMMUNITY_Demo Terminal Strip Header|Demo Terminal Strip Header]]
- [[_COMMUNITY_True Terminal Strip Header|True Terminal Strip Header]]
- [[_COMMUNITY_Bridge Point Logic|Bridge Point Logic]]
- [[_COMMUNITY_Graphics Item Utilities|Graphics Item Utilities]]
- [[_COMMUNITY_Diagram Text Items|Diagram Text Items]]
- [[_COMMUNITY_Terminal Parent Relationship|Terminal Parent Relationship]]
- [[_COMMUNITY_Project Database Model|Project Database Model]]
- [[_COMMUNITY_Table Properties Editor|Table Properties Editor]]
- [[_COMMUNITY_General Utilities|General Utilities]]
- [[_COMMUNITY_Settings Management|Settings Management]]
- [[_COMMUNITY_Pattern XML Serialization|Pattern XML Serialization]]
- [[_COMMUNITY_Item XML Serialization|Item XML Serialization]]
- [[_COMMUNITY_Properties Editor Dialog|Properties Editor Dialog]]
- [[_COMMUNITY_Template Visual Cells|Template Visual Cells]]
- [[_COMMUNITY_Template Move Handler|Template Move Handler]]
- [[_COMMUNITY_Rich Text Editor Implementation|Rich Text Editor Implementation]]
- [[_COMMUNITY_Rich Text Editor Private|Rich Text Editor Private]]
- [[_COMMUNITY_Element Factory|Element Factory]]
- [[_COMMUNITY_Auto-numbering Variables|Auto-numbering Variables]]
- [[_COMMUNITY_Diagram Content Definition|Diagram Content Definition]]
- [[_COMMUNITY_Conductor Properties Header|Conductor Properties Header]]
- [[_COMMUNITY_Conductor Profile Definition|Conductor Profile Definition]]
- [[_COMMUNITY_Terminal Strip Bridge|Terminal Strip Bridge]]
- [[_COMMUNITY_Names List Utility|Names List Utility]]
- [[_COMMUNITY_Element Scaler|Element Scaler]]
- [[_COMMUNITY_Element Data Structures|Element Data Structures]]
- [[_COMMUNITY_DXF to Element Converter|DXF to Element Converter]]
- [[_COMMUNITY_Template Location Management|Template Location Management]]
- [[_COMMUNITY_Dimensioning Logic|Dimensioning Logic]]
- [[_COMMUNITY_Helper Cell Utility|Helper Cell Utility]]
- [[_COMMUNITY_Visual Cell Base|Visual Cell Base]]
- [[_COMMUNITY_Collection Item Management|Collection Item Management]]
- [[_COMMUNITY_Elements Location Management|Elements Location Management]]
- [[_COMMUNITY_Element Scene Definition|Element Scene Definition]]
- [[_COMMUNITY_Element Content Definition|Element Content Definition]]
- [[_COMMUNITY_Rich Text XSLT Examples|Rich Text XSLT Examples]]

## God Nodes (most connected - your core abstractions)
1. `isEmpty()` - 389 edges
2. `value()` - 241 edges
3. `setText()` - 228 edges
4. `contains()` - 200 edges
5. `toString()` - 196 edges
6. `size()` - 164 edges
7. `undoStack()` - 159 edges
8. `count()` - 151 edges
9. `clear()` - 150 edges
10. `isNull()` - 137 edges

## Surprising Connections (you probably didn't know these)
- `Coding Conventions` --rationale_for--> `QElectroTech`  [INFERRED]
  CONTRIBUTING.md → README.md
- `buildPagesList()` --calls--> `clear()`  [INFERRED]
  sources/configdialog.cpp → sources/autoNum/ui/autonumberingdockwidget.cpp
- `isValid()` --calls--> `text()`  [INFERRED]
  sources/qfilenameedit.cpp → sources/editor/graphicspart/partdynamictextfield.cpp
- `buildInterface()` --calls--> `terminalElementInfoKeys()`  [INFERRED]
  sources/ui/elementinfowidget.cpp → sources/qetinformation.cpp
- `convertPosition()` --calls--> `setPosition()`  [INFERRED]
  sources/diagram.cpp → sources/diagramposition.cpp

## Hyperedges (group relationships)
- **QElectroTech Ecosystem** — readme_qelectrotech, cmakelists_qet_project, readme_element_editor, readme_nomenclature_tool [INFERRED 0.80]

## Communities

### Community 0 - "UI Interactions & Undo"
Cohesion: 0.01
Nodes (389): boundingRect(), handleUserTransformation(), isUseless(), rect(), sceneGeometricRect(), sceneTopLeft(), setRect(), setSpanAngle() (+381 more)

### Community 1 - "Dynamic Element Text"
Cohesion: 0.01
Nodes (308): AddElementTextCommand(), AddTextsGroupCommand(), AddTextToGroupCommand(), AlignmentTextsGroupCommand(), redo(), RemoveTextFromGroupCommand(), RemoveTextsGroupCommand(), undo() (+300 more)

### Community 2 - "Project & View Management"
Cohesion: 0.01
Nodes (279): redo(), numerotationContextToFormula(), AutoNumberingDockWidget(), clear(), conductorAutoNumChanged(), elementAutoNumChanged(), folioAutoNumChanged(), on_m_conductor_cb_activated() (+271 more)

### Community 3 - "Title Block Templates"
Cohesion: 0.01
Nodes (253): borderToXml(), exportBorder(), QGraphicsScene(), TitleBlockDimension(), toShortString(), label(), scene(), GridLayoutAnimation() (+245 more)

### Community 4 - "Graphics Styling (Pen/Color)"
Cohesion: 0.02
Nodes (246): CustomElementGraphicPart(), draw(), insideBorderRect(), titleBlockRect(), titleBlockRectForQPainter(), redo(), undo(), handlerMousePressEvent() (+238 more)

### Community 5 - "Terminal Strip Logic"
Cohesion: 0.02
Nodes (221): AddTerminalStripCommand(), redo(), RemoveTerminalStripCommand(), undo(), AddTerminalToStripCommand(), MoveTerminalCommand(), redo(), RemoveTerminalFromStripCommand() (+213 more)

### Community 6 - "Element Editor Operations"
Cohesion: 0.02
Nodes (240): elementPrefixForLocation(), toXml(), CustomElementPart(), remove(), buildElement(), Element(), copy(), copyDirectory() (+232 more)

### Community 7 - "Conductor & Terminal Positioning"
Cohesion: 0.02
Nodes (209): addHandler(), adjustHandlerPos(), bends(), boundingRect(), calculateTextItemPosition(), Conductor(), ConductorXmlRetroCompatibility, currentPathType() (+201 more)

### Community 8 - "Dynamic Text Fields"
Cohesion: 0.02
Nodes (190): on_m_licenses_comboBox_currentTextChanged(), ChangeElementDataCommand(), redo(), undo(), ChangeTerminalStripColor(), CompositeTextEditDialog(), on_m_info_cb_activated(), plainText() (+182 more)

### Community 9 - "App Window Lifecycle"
Cohesion: 0.02
Nodes (174): on_m_log_comboBox_currentTextChanged(), fillSavedQuery(), loadConfig(), BOMExportDialog(), exec(), getBom(), on_m_format_as_bom_clicked(), convertPosition() (+166 more)

### Community 10 - "XML Tag & Attribute Handling"
Cohesion: 0.02
Nodes (178): fromXml(), BorderProperties(), defaultProperties(), fromSettings(), fromXml(), toSettings(), toXml(), titleBlockFromXml() (+170 more)

### Community 11 - "App Core & Argument Parsing"
Cohesion: 0.02
Nodes (153): NewDiagramPage(), DiagramEditorHandlerSizeWidget(), on_comboBox_currentIndexChanged(), pixmap(), editElement(), findInPanel(), generalWidget(), setLocale() (+145 more)

### Community 12 - "Elements Panel & Widgets"
Cohesion: 0.02
Nodes (143): AlignmentTextDialog(), event(), eventFilter(), addGeneralWidget(), apply(), buildGui(), ElementPropertiesWidget(), setDynamicText() (+135 more)

### Community 13 - "Diagram XML Serialization"
Cohesion: 0.02
Nodes (111): AddGraphicsObjectCommand(), itemText(), redo(), undo(), AddPartCommand(), undo(), borderAndTitleBlockRect(), borderFromXml() (+103 more)

### Community 14 - "Diagram Editor & Actions"
Cohesion: 0.03
Nodes (137): canRotateSelection(), clipboardMayContainDiagram(), selectedConductors(), hasCopiableItems(), hasDeletableItems(), hasTextEditing(), selectedTexts(), selectedTextsGroup() (+129 more)

### Community 15 - "Project Database & UUIDs"
Cohesion: 0.03
Nodes (105): AddTerminalStripItemDialog(), fillComboBox(), openDialog(), selectedTerminalStrip(), titleblockInformation(), boundingRect(), DiagramImageItem(), editProperty() (+97 more)

### Community 16 - "Element Scene & Scaling"
Cohesion: 0.02
Nodes (99): setEventInterface(), DiagramEventAddImage(), DiagramEventInterface(), isNull(), mouseMoveEvent(), openDialog(), wheelEvent(), scale() (+91 more)

### Community 17 - "Print & Layout Patterns"
Cohesion: 0.04
Nodes (68): mergeWith(), on_m_configure_pb_clicked(), mergeWith(), changeToAutoFolioTab(), ExportConfigPage(), loadSavedTbp(), PrintConfigPage(), saveCurrentTbp() (+60 more)

### Community 18 - "Primitive Decorators & Orientation"
Cohesion: 0.04
Nodes (64): toItem(), adjustText(), applyBringForward(), applyLower(), applyRaise(), applySendBackward(), changeElementDataCommand(), ChangeInformationsCommand() (+56 more)

### Community 19 - "Configuration & Properties Widgets"
Cohesion: 0.04
Nodes (50): BorderPropertiesWidget(), setProperties(), setReadOnly(), displayedTextChanged(), defaultProperties(), fromSettings(), fromXml(), isPen() (+42 more)

### Community 20 - "Terminal Strip Drawer & Tables"
Cohesion: 0.04
Nodes (51): addNewTableToNewDiagram(), AddTableDialog(), adjustTableToFolio(), contentWidget(), headerAlignment(), headerFont(), headerMargins(), on_m_edit_header_margins_pb_clicked() (+43 more)

### Community 21 - "Template Cell Editing"
Cohesion: 0.06
Nodes (42): slot_editNames(), on_m_advanced_editor_pb_clicked(), NameListDialog(), namelistWidget(), setHelpText(), setInformationText(), on_m_edit_names_action_triggered(), alignment() (+34 more)

### Community 22 - "About Dialog & Versioning"
Cohesion: 0.27
Nodes (12): AboutQETDialog(), addAuthor(), addLibrary(), setAbout(), setAnnexProject(), setAuthors(), setContributors(), setLibraries() (+4 more)

### Community 23 - "Filename Editing & Validation"
Cohesion: 0.21
Nodes (9): QETRegExpValidator(), QRegularExpressionValidator(), validate(), displayToolTip(), init(), isEmpty(), isValid(), QFileNameEdit() (+1 more)

### Community 24 - "Text Orientation Widgets"
Cohesion: 0.24
Nodes (7): build(), emitChangeSignals(), orientation(), QTextOrientationSpinBoxWidget(), setOrientation(), setValue(), value()

### Community 25 - "Mouse & Wheel Events (DV)"
Cohesion: 0.17
Nodes (1): DVEventInterface()

### Community 26 - "Mouse & Wheel Events (Diagram)"
Cohesion: 0.17
Nodes (1): DiagramEventInterface()

### Community 27 - "Demo Terminal Strip"
Cohesion: 0.25
Nodes (5): build(), DemoBridge, DemoPhysicalTerminal, DemoRealTerminal, DemoTerminalStrip()

### Community 28 - "Formula Assistant"
Cohesion: 0.25
Nodes (5): formula(), FormulaAssistantDialog(), on_m_line_edit_textChanged(), setFormula(), setText()

### Community 29 - "Project Documentation & Ecosystem"
Cohesion: 0.22
Nodes (9): Project Contributors, qelectrotech project, Coding Conventions, Undo Commands, Element Editor, Gentoo Ebuild, Nomenclature Tool, QElectroTech (+1 more)

### Community 30 - "Terminal Strip Interfaces"
Cohesion: 0.33
Nodes (0): 

### Community 31 - "Simple Element Initialization"
Cohesion: 0.5
Nodes (1): SimpleElement()

### Community 32 - "Element Properties Editors"
Cohesion: 0.67
Nodes (1): AbstractElementPropertiesEditorWidget()

### Community 33 - "Add Link Dialog UI"
Cohesion: 0.67
Nodes (0): 

### Community 34 - "Versioning Utils"
Cohesion: 1.0
Nodes (0): 

### Community 35 - "Icon Management"
Cohesion: 1.0
Nodes (0): 

### Community 36 - "Message Box Utils"
Cohesion: 1.0
Nodes (0): 

### Community 37 - "Elements Movement Driver"
Cohesion: 1.0
Nodes (0): 

### Community 38 - "Element Properties Header"
Cohesion: 1.0
Nodes (0): 

### Community 39 - "Config Page Base"
Cohesion: 1.0
Nodes (0): 

### Community 40 - "Terminal Data Models"
Cohesion: 1.0
Nodes (0): 

### Community 41 - "Demo Terminal Strip Header"
Cohesion: 1.0
Nodes (0): 

### Community 42 - "True Terminal Strip Header"
Cohesion: 1.0
Nodes (0): 

### Community 43 - "Bridge Point Logic"
Cohesion: 1.0
Nodes (0): 

### Community 44 - "Graphics Item Utilities"
Cohesion: 1.0
Nodes (0): 

### Community 45 - "Diagram Text Items"
Cohesion: 1.0
Nodes (0): 

### Community 46 - "Terminal Parent Relationship"
Cohesion: 1.0
Nodes (0): 

### Community 47 - "Project Database Model"
Cohesion: 1.0
Nodes (0): 

### Community 48 - "Table Properties Editor"
Cohesion: 1.0
Nodes (0): 

### Community 49 - "General Utilities"
Cohesion: 1.0
Nodes (0): 

### Community 50 - "Settings Management"
Cohesion: 1.0
Nodes (0): 

### Community 51 - "Pattern XML Serialization"
Cohesion: 1.0
Nodes (0): 

### Community 52 - "Item XML Serialization"
Cohesion: 1.0
Nodes (0): 

### Community 53 - "Properties Editor Dialog"
Cohesion: 1.0
Nodes (0): 

### Community 54 - "Template Visual Cells"
Cohesion: 1.0
Nodes (0): 

### Community 55 - "Template Move Handler"
Cohesion: 1.0
Nodes (0): 

### Community 56 - "Rich Text Editor Implementation"
Cohesion: 1.0
Nodes (0): 

### Community 57 - "Rich Text Editor Private"
Cohesion: 1.0
Nodes (0): 

### Community 58 - "Element Factory"
Cohesion: 1.0
Nodes (0): 

### Community 59 - "Auto-numbering Variables"
Cohesion: 1.0
Nodes (0): 

### Community 60 - "Diagram Content Definition"
Cohesion: 1.0
Nodes (0): 

### Community 61 - "Conductor Properties Header"
Cohesion: 1.0
Nodes (0): 

### Community 62 - "Conductor Profile Definition"
Cohesion: 1.0
Nodes (0): 

### Community 63 - "Terminal Strip Bridge"
Cohesion: 1.0
Nodes (0): 

### Community 64 - "Names List Utility"
Cohesion: 1.0
Nodes (0): 

### Community 65 - "Element Scaler"
Cohesion: 1.0
Nodes (0): 

### Community 66 - "Element Data Structures"
Cohesion: 1.0
Nodes (0): 

### Community 67 - "DXF to Element Converter"
Cohesion: 1.0
Nodes (0): 

### Community 68 - "Template Location Management"
Cohesion: 1.0
Nodes (0): 

### Community 69 - "Dimensioning Logic"
Cohesion: 1.0
Nodes (0): 

### Community 70 - "Helper Cell Utility"
Cohesion: 1.0
Nodes (0): 

### Community 71 - "Visual Cell Base"
Cohesion: 1.0
Nodes (0): 

### Community 72 - "Collection Item Management"
Cohesion: 1.0
Nodes (0): 

### Community 73 - "Elements Location Management"
Cohesion: 1.0
Nodes (0): 

### Community 74 - "Element Scene Definition"
Cohesion: 1.0
Nodes (0): 

### Community 75 - "Element Content Definition"
Cohesion: 1.0
Nodes (0): 

### Community 76 - "Rich Text XSLT Examples"
Cohesion: 1.0
Nodes (1): RichText XSLT Example

## Knowledge Gaps
- **11 isolated node(s):** `ConductorXmlRetroCompatibility`, `ElementXmlRetroCompatibility`, `qelectrotech project`, `Project Contributors`, `Element Editor` (+6 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **Thin community `Versioning Utils`** (2 nodes): `QetVersion()`, `qetversion.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Icon Management`** (2 nodes): `QET()`, `qeticons.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Message Box Utils`** (2 nodes): `QET()`, `qetmessagebox.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Elements Movement Driver`** (2 nodes): `m_movement_driver()`, `elementsmover.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Element Properties Header`** (2 nodes): `AbstractElementPropertiesEditorWidget()`, `elementpropertieswidget.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Config Page Base`** (2 nodes): `ConfigPage()`, `configpage.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Terminal Data Models`** (2 nodes): `operator()`, `modelTerminalData.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Demo Terminal Strip Header`** (2 nodes): `TerminalStripDrawer()`, `demoterminalstrip.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `True Terminal Strip Header`** (2 nodes): `trueterminalstrip.h`, `TerminalStripDrawer()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Bridge Point Logic`** (2 nodes): `terminalstriplayoutpattern.h`, `m_bridge_point_d()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Graphics Item Utilities`** (2 nodes): `QGIUtility()`, `qgraphicsitemutility.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Diagram Text Items`** (2 nodes): `QGraphicsTextItem()`, `diagramtextitem.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Terminal Parent Relationship`** (2 nodes): `terminal.h`, `parent_element_()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Project Database Model`** (2 nodes): `QAbstractTableModel()`, `projectdbmodel.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Table Properties Editor`** (2 nodes): `Ui()`, `graphicstablepropertieseditor.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `General Utilities`** (2 nodes): `QETUtils()`, `qetutils.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Settings Management`** (2 nodes): `QetSettings()`, `qetsettings.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Pattern XML Serialization`** (2 nodes): `terminalstriplayoutpatternxml.h`, `TerminalStripLayoutPatternXml()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Item XML Serialization`** (2 nodes): `terminalstripitemxml.h`, `TerminalStripItemXml()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Properties Editor Dialog`** (2 nodes): `PropertiesEditorDialog()`, `propertieseditordialog.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Template Visual Cells`** (2 nodes): `templatecellsset.h`, `TitleBlockTemplateVisualCell()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Template Move Handler`** (2 nodes): `MoveTitleBlockTemplatesHandler()`, `movetemplateshandler.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Rich Text Editor Implementation`** (2 nodes): `qdesigner_internal()`, `richtexteditor.cpp`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Rich Text Editor Private`** (2 nodes): `qdesigner_internal()`, `richtexteditor_p.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Element Factory`** (2 nodes): `ElementFactory()`, `elementfactory.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Auto-numbering Variables`** (2 nodes): `autonum()`, `assignvariables.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Diagram Content Definition`** (1 nodes): `diagramcontent.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Conductor Properties Header`** (1 nodes): `conductorproperties.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Conductor Profile Definition`** (1 nodes): `conductorprofile.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Terminal Strip Bridge`** (1 nodes): `terminalstripbridge.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Names List Utility`** (1 nodes): `nameslist.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Element Scaler`** (1 nodes): `qet_elementscaler.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Element Data Structures`** (1 nodes): `elementdata.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `DXF to Element Converter`** (1 nodes): `dxftoelmt.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Template Location Management`** (1 nodes): `templatelocation.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Dimensioning Logic`** (1 nodes): `dimension.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Helper Cell Utility`** (1 nodes): `helpercell.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Visual Cell Base`** (1 nodes): `templatevisualcell.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Collection Item Management`** (1 nodes): `elementcollectionitem.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Elements Location Management`** (1 nodes): `elementslocation.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Element Scene Definition`** (1 nodes): `elementscene.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Element Content Definition`** (1 nodes): `elementcontent.h`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Rich Text XSLT Examples`** (1 nodes): `RichText XSLT Example`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `isEmpty()` connect `App Window Lifecycle` to `UI Interactions & Undo`, `Dynamic Element Text`, `Project & View Management`, `Title Block Templates`, `Graphics Styling (Pen/Color)`, `Terminal Strip Logic`, `Element Editor Operations`, `Conductor & Terminal Positioning`, `Dynamic Text Fields`, `XML Tag & Attribute Handling`, `App Core & Argument Parsing`, `Elements Panel & Widgets`, `Diagram XML Serialization`, `Diagram Editor & Actions`, `Project Database & UUIDs`, `Element Scene & Scaling`, `Print & Layout Patterns`, `Primitive Decorators & Orientation`, `Configuration & Properties Widgets`, `Terminal Strip Drawer & Tables`, `Template Cell Editing`?**
  _High betweenness centrality (0.176) - this node is a cross-community bridge._
- **Why does `setText()` connect `UI Interactions & Undo` to `Dynamic Element Text`, `Project & View Management`, `Title Block Templates`, `Graphics Styling (Pen/Color)`, `Terminal Strip Logic`, `Element Editor Operations`, `Conductor & Terminal Positioning`, `Dynamic Text Fields`, `App Window Lifecycle`, `XML Tag & Attribute Handling`, `App Core & Argument Parsing`, `Elements Panel & Widgets`, `Diagram XML Serialization`, `Diagram Editor & Actions`, `Project Database & UUIDs`, `Element Scene & Scaling`, `Print & Layout Patterns`, `Primitive Decorators & Orientation`, `Configuration & Properties Widgets`, `Terminal Strip Drawer & Tables`, `Template Cell Editing`, `About Dialog & Versioning`, `Filename Editing & Validation`?**
  _High betweenness centrality (0.069) - this node is a cross-community bridge._
- **Why does `count()` connect `Title Block Templates` to `UI Interactions & Undo`, `Dynamic Element Text`, `Project & View Management`, `Graphics Styling (Pen/Color)`, `Terminal Strip Logic`, `Element Editor Operations`, `Conductor & Terminal Positioning`, `Dynamic Text Fields`, `App Window Lifecycle`, `XML Tag & Attribute Handling`, `App Core & Argument Parsing`, `Elements Panel & Widgets`, `Diagram XML Serialization`, `Diagram Editor & Actions`, `Project Database & UUIDs`, `Element Scene & Scaling`, `Primitive Decorators & Orientation`, `Configuration & Properties Widgets`, `Terminal Strip Drawer & Tables`, `Template Cell Editing`, `About Dialog & Versioning`?**
  _High betweenness centrality (0.055) - this node is a cross-community bridge._
- **Are the 387 inferred relationships involving `isEmpty()` (e.g. with `incrementLetters()` and `toXml()`) actually correct?**
  _`isEmpty()` has 387 INFERRED edges - model-reasoned connections that need verification._
- **Are the 240 inferred relationships involving `value()` (e.g. with `draw()` and `drawDxf()`) actually correct?**
  _`value()` has 240 INFERRED edges - model-reasoned connections that need verification._
- **Are the 223 inferred relationships involving `setText()` (e.g. with `addPageToList()` and `QFileNameEdit()`) actually correct?**
  _`setText()` has 223 INFERRED edges - model-reasoned connections that need verification._
- **Are the 198 inferred relationships involving `contains()` (e.g. with `addPage()` and `convertPosition()`) actually correct?**
  _`contains()` has 198 INFERRED edges - model-reasoned connections that need verification._