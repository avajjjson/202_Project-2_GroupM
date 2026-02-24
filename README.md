# CIVE 202 Project 2 Group M

**Summary**

This project automates the Nebraska Department of Transportation (NDOT) concrete mix design process. These calculations were originally done in Excel, but have been transposed into a Jupyter notebook. The program accepts user inputs for material weights, specific gravities, aggregate percentages, and mix design parameters, then computes and prints a formatted weight summary for one cubic yard of concrete.

**User Guide**

Requirements
- Python 3.x
- Jupyter Notebook or JupyterLab

1. Open `Project2_GroupM_Code_Document.ipynb` in Jupyter Notebook.
2. Run the cell by pressing **Ctrl+Enter**, clicking the **Run** button, or selecting **Run Selected Cell**.
3. Follow the prompts and enter the requested values when asked.
4. Once all inputs are provided, the program will print a formatted **NDOT Concrete Mix Design – Weight Summary**.

### Inputs Required
The program will prompt you for the following:

**Project Info**
- Project number
- Class of concrete

**Cementitious Material Weights** *(lb per cubic yard)*
- Cement (A)
- Fly Ash (B)
- Silica Fume (C)
- Other SCM (D)

**Mix Design Parameters**
- Water-to-cement ratio
- Target air content (%)
- Target percent fine aggregate (%)
- Target percent coarse aggregate (%)
- Target percent other aggregate (%)

**Specific Gravities**
- Cement, Fly Ash, Silica Fume, Other SCM
- Fine Aggregate, Coarse Aggregate, Other Aggregate
