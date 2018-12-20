**Versioning:** Number syntax: Major.Minor.Build.Revision (x.x.x.x).  
The major number follows the Dynamo version, 201.x.x is usable in Dynamo +2.0.1.x versions. The minor number is internal major builds. The build number is internal minor builds. The revision number is an internal build number without public documentation and display in this file.  


### History of Orchid for Dynamo 2.0.x ###  

201.3.9  
- Revit: Nodes for SharedParameter --> SetFile, GroupByGroupName, GroupByType.  

201.3.8  
- Installer split into two parallels, 132.x.x.x and 201.x.x.x version installer.  
- Revit: Family All and ByCategory / FamilyType All and ByCategory.  
- Revit: Nodes for Subcategory, create, remove, get by category and by name.  

201.3.7  
- Last Custom Nodes turned into ZeroTouch nodes --> nodes for FEM-design.  
- Revit: Nodes for Materials created and nodes for Document.contain (Category/Types)  
- Revit: Purge nodes updated, comes in a PostCommand and a Document version.  

201.3.6  
- Revit: Print --> Nodes to handle printing, several nodes created.  

201.3.5  
- Revit: SystemFamily --> CreateCompoundLayer, DeleteCompoundLayer, SetCompoundLayerWidth, and two dropdown nodes added.  

201.3.4  
- Core: Directory.Current, Directory.FromPath and File.FromPath nodes added.  

201.3.3  
- FamilyDocument: GetCategory and SetCategory node for the document added. Tooltip added AddParameter, AddsharedParameter.  

201.3.2  
- Application: All Sigma nodes is updated supporting live connection.  

201.3.1  
- FamilyDocument: Parameters.GetValue and Parameters.SetValue updated.  

201.3.0  
- Support for Dynamo version changed to 2.0.1.x  

200.3.0  
- FamilyDocument class split into subclasses. New names for all nodes in the FamilyDocument class.  

200.2.7  
- FamilyDocument.Parameters node added.   

200.2.6  
- Parameter nodes added: AddProjectParameter, AddSharedParameter, ChangeCategory, and DeleteParameter.  

200.2.5  
- Element nodes updated to take list of document.  

200.2.4  
- FamilyDocument.AddParameter node added for Category input (FamilyType).  

200.2.3  
- 6 new nodes added: Object.ToAutodeskElement, Object.ToDynamoElement, FamilyDocument.AddLookupTable, FamilyDocument.AssociateParameter, FamilyDocument.GetNestedFamily, and FamilyDocument.GetNestedFamilyType.  

200.2.2  
- Node icons updated.  

200.2.1  
- Document.ImportImage node added.  

200.2.0  
- Orchid package updated supporting Dynamo Sandbox/Studio.  
- Document.Save and Document.SaveAs nodes added.  

200.1.3  
- FamilyDocument.RenameParameter node added.  

200.1.2  
- Family.GetFamilyDocument node added.  

200.1.1  
- FamilyDocument.IsReportingParameter node is added.  

200.1.0  
- 1st version of Orchid only available at Github.  

200.0.0  
- 1st version of Orchid, primarily upgraded from the DanEDU package.  
