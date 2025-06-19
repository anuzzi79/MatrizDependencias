# MatrizDependencias

A web tool in HTML/JavaScript to visualize dependencies between entities extracted from a public Google Sheet.

---

## 📋 Description

“MatrizDependencias” lets you:
- Load a dependency matrix (rows/columns) from a Google Sheet via the Sheets API v4  
- Select an entity and discover all of its dependencies  
- Render relationships in an interactive SVG “radial” graph  
- Export the central and right panels as a PNG snapshot with a uniform background  

---

## 🚀 Features

- **Dynamic data loading** from a Google Sheet using an API key  
- **Three-column layout**:  
  1. Scrollable list of all entities  
  2. Clickable list of related entities  
  3. SVG radial graph view  
- **Case-insensitive search** via click or Enter key  
- **Field(value)** formatting when cell value isn’t “X”  
- **Multi-line support** for values containing “>”  
- **“Export to PNG”** button that hides itself before capture  
