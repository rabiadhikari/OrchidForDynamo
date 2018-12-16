**Versioning:** Number syntax: Major.Minor.Build.Revision (x.x.x.x).  
The major number follows the Dynamo version, 132.x.x is usable in Dynamo +1.3.2.x versions. The minor number is internal major builds. The build number is internal minor builds. The revision number is an internal build number without public documentation and display in this file.  


### History of Orchid for Dynamo 1.3.x ###  

132.3.8  
- Installer split into two parallels, 132.x.x.x and 201.x.x.x version installer.  
- Revit: Family All and ByCategory / FamilyType All and ByCategory.  
- Revit: Nodes for Subcategory, create, remove, get by category and by name.  

132.3.7  
- Last Custom Nodes turned into ZeroTouch nodes --> nodes for FEM-design.  
- Revit: Nodes for Materials created and nodes for Document.contain (Category/Types)  
- Revit: Purge nodes updated, comes in a PostCommand and a Document version.  

132.3.6  
- Revit: Print --> Nodes to handle printing, several nodes created.  

132.3.5  
- Revit: SystemFamily --> CreateCompoundLayer, DeleteCompoundLayer, SetCompoundLayerWidth, and two dropdown nodes added.  

132.3.4  
- Core: Directory.Current, Directory.FromPath and File.FromPath nodes added.  

132.3.3  
- FamilyDocument: GetCategory and SetCategory node for the document added. Tooltip added AddParameter, AddsharedParameter.  

132.3.2  
- Application: All Sigma nodes is updated supporting live connection.  

132.3.1  
- FamilyDocument: Parameters.GetValue and Parameters.SetValue updated.  

132.3.0  
- Support for Dynamo version changed to 1.3.2.x  

130.3.0  
- FamilyDocument class split into subclasses. New names for all nodes in the FamilyDocument class.  

130.2.7  
- FamilyDocument.Parameters node added.   

130.2.6  
- Parameter nodes added: AddProjectParameter, AddSharedParameter, ChangeCategory, and DeleteParameter.  

130.2.5  
- Element nodes updated to take list of document.  

130.2.4  
- FamilyDocument.AddParameter node added for Category input (FamilyType).  

130.2.3  
- 6 new nodes added: Object.ToAutodeskElement, Object.ToDynamoElement, FamilyDocument.AddLookupTable, FamilyDocument.AssociateParameter, FamilyDocument.GetNestedFamily, and FamilyDocument.GetNestedFamilyType.  

130.2.2  
- Node icons updated.  

130.2.1  
- Document.ImportImage node added.  

130.2.0  
- Orchid package updated supporting Dynamo Sandbox/Studio.  
- Document.Save and Document.SaveAs nodes added.  

130.1.3  
- FamilyDocument.RenameParameter node added.  

130.1.2  
- Family.GetFamilyDocument node added.  

130.1.1  
- FamilyDocument.IsReportingParameter node is added.  

130.1.0  
- 1st version of Orchid only available at Github.  

130.0.0  
- 1st version of Orchid, primarily upgraded from the DanEDU package.  
