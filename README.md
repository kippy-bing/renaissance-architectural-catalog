# Renaissance Architectural Catalog

A digital catalog analyzing architectural motifs in Renaissance paintings by Domenico Veneziano and Carlo Crivelli.

## Purpose
This project aims to create a structured, peer-reviewed digital catalog that analyzes and compares the use of specific architectural elements within a selection of paintings by Domenico Veneziano and Carlo Crivelli. The focus is on how architectural elements—whether realistic, symbolic, or stylized—create space, convey meaning, and guide the viewer's eye within the pictorial frame.

## Scope
The catalog currently includes analyses of:
- Domenico Veneziano, *Saint Lucy Altarpiece* (c. 1445–1447)
- Carlo Crivelli, *The Annunciation, with Saint Emidius* (1486)

Additional paintings may be added in the future.

## Methodology
1. **Selection**: Choose one painting from each artist.
2. **Analysis**: For each painting, identify distinct architectural elements and create a dedicated GitHub Issue for each, providing detailed analysis.
3. **Data Entry**: Populate a CSV file (`catalog.csv`) with structured data linking to the analysis Issues.
4. **Review**: Use GitHub Pull Requests to review and merge entries, ensuring quality and accuracy.

## File Structure
- `catalog.csv`: Main catalog database with columns:
  - `Painting_Title`
  - `Artist`
  - `Year`
  - `Architectural_Element`
  - `Description_of_Element`
  - `Function_in_Composition`
  - `Related_Issue_Number`
- `README.md`: This file.
- Issues: Detailed analyses of individual architectural elements.

## How to Contribute
1. Fork the repository.
2. Create a new branch for your analysis.
3. Add rows to `catalog.csv` and create corresponding Issues.
4. Open a Pull Request linking to the Issues.

## License
This project is licensed under the MIT License.