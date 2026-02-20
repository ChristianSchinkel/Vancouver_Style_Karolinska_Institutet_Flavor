# Zotero Field Mapping for Vancouver Style - Karolinska Institutet

## Introduction

This guide explains how Zotero fields map to citation outputs when using the Vancouver Style - Karolinska Institutet citation style. Understanding these mappings will help you enter data correctly in Zotero to produce properly formatted citations.

## General Principles

### Author Name Formatting

- **Zotero Input**: Enter names as `Last, First Middle` (e.g., `Andersson, Lars Erik`)
- **Citation Output**: Displays as `Lastname Initials` with no periods or spaces between initials (e.g., `Andersson LE`)
- Authors are separated by commas: `Andersson L, Svensson O, Nilsson H`

### Et Al. Rules

- **1-6 authors**: All authors are listed
- **7+ authors**: First 6 authors are listed, followed by "et al."
- Example: `Andersson L, Svensson O, Nilsson H, Berg K, Ek M, Lund P, et al.`

### Date Formatting

- Journal articles display only the **year**
- Books display only the **year**
- Web pages and some electronic sources show full dates in specific contexts ([cited YYYY Month DD])

### URLs and Access Dates

- DOI is preferred over URL when available
- Access dates are shown for online resources
- Format: `[cited 2024 Jan 15]`
- URLs are prefixed with: `Available from:`

---

## Item Type: Journal Articles

### Zotero Field Mapping

| Zotero Field | Maps To | Example Input | Notes |
| ------------ | ------- | ------------- | ----- |
| Item Type | - | Journal Article | Must be set correctly |
| Author | Author names | Andersson, Lars; Svensson, Olof | Enter as: Last, First. Output: Andersson L, Svensson O |
| Title | Article title | Analysis of clinical trials | Enter full article title (no quotes needed) |
| Publication | Journal name | Medical Journal | Use full name; CSL abbreviates to NLM standards |
| Volume | Volume number | 22 | Enter number only |
| Issue | Issue number | 3 | Enter number only (no parentheses) |
| Pages | Page range | 145-149 | Enter full range; CSL formats as 145-9 |
| Date | Year | 2019 | Enter full date if known; only year is displayed |
| DOI | DOI identifier | 10.1234/example | If present, creates DOI URL in "Available from:" |
| URL | Web address | <https://example.com/article> | Only used if no DOI present |
| Accessed | Access date | 2024-01-15 | Shown for online articles with URL/DOI |

### Example Output

**Input in Zotero:**

- Authors: Andersson, Lars; Svensson, Olof
- Title: Analysis of clinical trials
- Publication: Medical Journal
- Volume: 22
- Issue: 3
- Pages: 145-149
- Date: 2019

**Formatted Citation:**

```text
Andersson L, Svensson O. Analysis of clinical trials. Med J. 2019;22(3):145-9.
```

### Journal Articles - Special Notes

- Journal abbreviations follow NLM (National Library of Medicine) standards
- No space between volume and issue: `22(3)` not `22 (3)`
- Colon immediately before pages: `22(3):145-9` not `22(3): 145-9`
- Page ranges are condensed: `145-9` instead of `145-149`

---

## Item Type: Books

### Field Mapping for Books

| Zotero Field | Maps To | Example Input | Notes |
| ------------ | ------- | ------------- | ----- |
| Item Type | - | Book | Must be set correctly |
| Author | Author names | Smith, John; Brown, Robert | Enter as: Last, First. Output: Smith J, Brown R |
| Title | Book title | Introduction to microbiology | Full book title |
| Edition | Edition number | 2 | Enter number only; displayed as "2nd ed." |
| Place | Publisher location | London | City of publication |
| Publisher | Publisher name | Academic Press | Publisher name |
| Date | Year | 2020 | Enter full date; only year displayed |
| # of Pages | Total pages | 456 | Optional; shown as "456 p." if provided |
| ISBN | ISBN | 978-0-123456-78-9 | Not displayed in citation |
| URL | Web address | <https://example.com/book> | For electronic books; adds [Internet] tag |
| Accessed | Access date | 2024-01-15 | For electronic books |

### Books - Example Output

**Input in Zotero:**

- Authors: Smith, John; Brown, Robert
- Title: Introduction to microbiology
- Edition: 2
- Place: London
- Publisher: Academic Press
- Date: 2020

**Formatted Citation:**

```text
Smith J, Brown R. Introduction to microbiology. 2nd ed. London: Academic Press; 2020.
```

### Electronic Book Example

**Input in Zotero:**

- Authors: Johnson, Emily
- Title: Digital health systems
- Place: New York
- Publisher: Tech Publishing
- Date: 2021
- URL: <https://example.com/digital-health>
- Accessed: 2024-01-15

**Formatted Citation:**

```text
Johnson E. Digital health systems [Internet]. New York: Tech Publishing; 2021 [cited 2024 Jan 15]. Available from: https://example.com/digital-health
```

---

## Item Type: Book Chapters

### Field Mapping for Book Chapters

| Zotero Field | Maps To | Example Input | Notes |
| ------------ | ------- | ------------- | ----- |
| Item Type | - | Book Section | Must be set correctly |
| Author | Chapter author | Anderson, Maria | Enter as: Last, First |
| Title | Chapter title | Molecular mechanisms | Chapter title (not book title) |
| Editor | Book editor | Wilson, David | Enter as: Last, First; Output: Wilson D, editor |
| Book Title | Book title | Advances in biochemistry | The book containing the chapter |
| Edition | Edition number | 3 | Enter number only |
| Place | Publisher location | Boston | City of publication |
| Publisher | Publisher name | Scientific Press | Publisher name |
| Date | Year | 2021 | Only year displayed |
| Pages | Chapter pages | 123-145 | Page range of chapter |

### Book Chapters - Example Output

**Input in Zotero:**

- Author: Anderson, Maria
- Title: Molecular mechanisms
- Editor: Wilson, David
- Book Title: Advances in biochemistry
- Edition: 3
- Place: Boston
- Publisher: Scientific Press
- Date: 2021
- Pages: 123-145

**Formatted Citation:**

```text
Anderson M. Molecular mechanisms. In: Wilson D, editor. Advances in biochemistry. 3rd ed. Boston: Scientific Press; 2021. p. 123-45.
```

---

## Item Type: Web Pages

### Field Mapping for Web Pages

| Zotero Field | Maps To | Example Input | Notes |
| ------------ | ------- | ------------- | ----- |
| Item Type | - | Web Page | Must be set correctly |
| Author | Author/Organization | World Health Organization | Can be organization name |
| Title | Page title | Microbial resistance | Title of web page |
| Website Title | Website name | WHO Website | Optional; shown if different from author |
| URL | Web address | <https://www.who.int/microbial-resistance> | Required for web pages |
| Accessed | Access date | 2024-01-15 | Required; shown as [cited 2024 Jan 15] |
| Date | Publication date | 2022 | Date content was published |

### Web Pages - Example Output

**Input in Zotero:**

- Author: World Health Organization
- Title: Microbial resistance
- URL: <https://www.who.int/microbial-resistance>
- Date: 2022
- Accessed: 2024-01-15

**Formatted Citation:**

```text
World Health Organization. Microbial resistance [Internet]. Geneva: WHO; 2022 [cited 2024 Jan 15]. Available from: https://www.who.int/microbial-resistance
```

### Web Pages - Special Notes

- `[Internet]` tag is automatically added after the title for web resources
- Access date format: `[cited YYYY Month DD]` (e.g., `[cited 2024 Jan 15]`)
- Use full month name abbreviations: Jan, Feb, Mar, Apr, May, Jun, Jul, Aug, Sep, Oct, Nov, Dec
- "Available from:" (not "Available at:") precedes the URL

---

## Item Type: Reports

### Field Mapping for Reports

| Zotero Field | Maps To | Example Input | Notes |
| ------------ | ------- | ------------- | ----- |
| Item Type | - | Report | Must be set correctly |
| Author | Author/Institution | National Institute of Health | Organization or person |
| Title | Report title | Annual health statistics | Full report title |
| Report Number | Report identifier | NIH-2023-045 | Shown as "Report No.: NIH-2023-045" |
| Place | Publisher location | Washington (DC) | City of publication |
| Institution | Publishing institution | US Department of Health | Institution name |
| Date | Publication date | 2023 | Year and month if available |
| Pages | Total pages | 125 | Optional |
| URL | Web address | <https://example.com/report> | For online reports |
| Accessed | Access date | 2024-01-15 | For online reports |

### Reports - Example Output

**Input in Zotero:**

- Author: National Institute of Health
- Title: Annual health statistics
- Report Number: NIH-2023-045
- Place: Washington (DC)
- Institution: US Department of Health
- Date: 2023

**Formatted Citation:**

```text
National Institute of Health. Annual health statistics. Washington (DC): US Department of Health; 2023. Report No.: NIH-2023-045.
```

---

## Item Type: Thesis/Dissertation

### Field Mapping for Thesis/Dissertation

| Zotero Field | Maps To | Example Input | Notes |
| ------------ | ------- | ------------- | ----- |
| Item Type | - | Thesis | Must be set correctly |
| Author | Student name | Peterson, Anna | Author of thesis |
| Title | Thesis title | Genetic markers in cancer research | Full thesis title |
| Type | Degree type | Doctoral dissertation | Or "Master's thesis" |
| Place | University location | Stockholm | City in brackets [Stockholm] |
| Publisher | University name | Karolinska Institutet | Name of institution |
| Date | Year | 2023 | Year of completion |
| # of Pages | Total pages | 234 | Optional |
| URL | Web address | <http://hdl.handle.net/example> | For electronic access |
| Accessed | Access date | 2024-01-15 | If accessed online |

### Thesis/Dissertation - Example Output

**Input in Zotero:**

- Author: Peterson, Anna
- Title: Genetic markers in cancer research
- Type: Doctoral dissertation
- Place: Stockholm
- Publisher: Karolinska Institutet
- Date: 2023

**Formatted Citation:**

```text
Peterson A. Genetic markers in cancer research [Doctoral dissertation]. [Stockholm]: Karolinska Institutet; 2023.
```

### Thesis/Dissertation - Special Notes

- Thesis type appears in brackets after title: `[Doctoral dissertation]` or `[Master's thesis]`
- University location appears in brackets: `[Stockholm]`
- For Swedish theses, you may use Swedish terms if appropriate

---

## Item Type: Conference Papers

### Field Mapping for Conference Papers

| Zotero Field | Maps To | Example Input | Notes |
| ------------ | ------- | ------------- | ----- |
| Item Type | - | Conference Paper | Must be set correctly |
| Author | Presenter/Author | Nielsen, Henrik | Paper author |
| Title | Paper title | Innovations in medical imaging | Title of presentation/paper |
| Conference Name | Event name | International Medical Conference | Full conference name |
| Place | Conference location | Paris, France | City and country |
| Date | Conference date | 2023-06-15 | Full date of conference |
| Proceedings Title | Proceedings name | Proceedings of the IMC 2023 | If published in proceedings |
| Publisher | Publisher | Medical Society Press | If proceedings published |
| Pages | Page range | 45-52 | Pages in proceedings |

### Conference Papers - Example (Unpublished)

**Input in Zotero:**

- Author: Nielsen, Henrik
- Title: Innovations in medical imaging
- Conference Name: International Medical Conference
- Place: Paris, France
- Date: 2023-06-15

**Formatted Citation:**

```text
Nielsen H. Innovations in medical imaging. Paper presented at: International Medical Conference; 2023 Jun 15; Paris, France.
```

### Conference Papers - Example (Published in Proceedings)

**Input in Zotero:**

- Author: Nielsen, Henrik
- Title: Innovations in medical imaging
- Proceedings Title: Proceedings of the International Medical Conference
- Place: London
- Publisher: Medical Society Press
- Date: 2023
- Pages: 45-52

**Formatted Citation:**

```text
Nielsen H. Innovations in medical imaging. In: Proceedings of the International Medical Conference. London: Medical Society Press; 2023. p. 45-52.
```

---

## Common Mistakes

### 1. Author Name Entry

❌ **Wrong**: Entering names as "L. Andersson" or "Andersson, L."
✅ **Correct**: Enter as "Andersson, Lars" (Last, First)

### 2. Journal Abbreviations

❌ **Wrong**: Manually abbreviating journal names in Zotero
✅ **Correct**: Enter full journal name; let CSL handle abbreviation

### 3. Edition Format

❌ **Wrong**: Entering "2nd edition" or "Second edition" in the edition field
✅ **Correct**: Enter just the number "2"

### 4. Issue Numbers

❌ **Wrong**: Entering "(3)" with parentheses
✅ **Correct**: Enter just "3"

### 5. Page Ranges

❌ **Wrong**: Entering "145-9" (pre-abbreviated)
✅ **Correct**: Enter "145-149" (full range); CSL will abbreviate

### 6. Access Dates

❌ **Wrong**: Leaving access date empty for web sources
✅ **Correct**: Always enter access date for online resources

### 7. URLs for Print Sources

❌ **Wrong**: Adding URLs to print books or articles
✅ **Correct**: Only add URL if you accessed the resource online

### 8. Multiple Authors

❌ **Wrong**: Entering multiple authors in one field: "Smith, John; Brown, Robert"
✅ **Correct**: Use separate author entries (click + to add another author)

---

## Journal Abbreviations

### NLM Standards

This citation style automatically abbreviates journal names according to the **National Library of Medicine (NLM)** standards.

### Where to Find Official Abbreviations

- **NLM Catalog**: <https://www.ncbi.nlm.nih.gov/nlmcatalog>
- Search for your journal and find the "ISOAbbr" (ISO Abbreviation) field
- You can also use the **LTWA (List of Title Word Abbreviations)** tool

### How Zotero Handles Abbreviations

1. Enter the **full journal name** in the "Publication" field
2. Zotero will automatically use the abbreviated form if:
   - The journal is in Zotero's journal abbreviation list
   - You have updated Zotero's abbreviation list
3. To manually add abbreviations:
   - In Zotero, go to Edit → Preferences → Advanced → Files and Folders
   - Click "Open Data Directory"
   - Create/edit the `abbreviations.json` file with your custom abbreviations

### Common Examples

| Full Journal Name | NLM Abbreviation |
| ----------------- | ---------------- |
| The New England Journal of Medicine | N Engl J Med |
| Journal of the American Medical Association | JAMA |
| The Lancet | Lancet |
| British Medical Journal | BMJ |
| Nature Medicine | Nat Med |
| Science | Science |
| Cell | Cell |
| Proceedings of the National Academy of Sciences | Proc Natl Acad Sci U S A |

### Special Cases

- Single-word titles (e.g., "Science", "Nature", "Cell") remain unchanged
- "The" is typically dropped from abbreviations
- Words like "Journal", "American", "Medical" have standard abbreviations: "J", "Am", "Med"

---

## Tips for Best Results

1. **Complete All Required Fields**: Even optional fields like access dates are important for proper formatting

2. **Use Zotero's Import Features**: When possible, import citations from databases (PubMed, Web of Science) to ensure correct data entry

3. **Double-Check Author Names**: Ensure all authors are entered correctly with proper first and last names

4. **Verify Item Types**: Selecting the correct item type is crucial for proper formatting

5. **Keep Zotero Updated**: Regular updates include improved journal abbreviations and bug fixes

6. **Review Generated Citations**: Always review the formatted output to ensure it meets requirements

7. **Use DOIs When Available**: DOIs are more permanent than URLs and are preferred

8. **Consistency**: Be consistent in how you enter data across all your references

---

## Item Type: Software, Applications, and AI Tools

### Field Mapping for Software/AI Tools

| Zotero Field | Maps To | Example Input | Notes |
| ------------ | ------- | ------------- | ----- |
| Item Type | - | Computer Program / Software | Use "Computer Program" or "Software" |
| Author | Creator/Developer | OpenAI | Organization or person |
| Title | Software/App/AI name | ChatGPT | Full name of software/application/AI tool |
| Version | Version number | 4.0 | Displayed as "ver. 4.0" |
| Medium | Type specification | Large language model | Shown in brackets; replaces [Internet] |
| Place | Publisher location | San Francisco | City of publication |
| Publisher | Company/Organization | OpenAI | Publisher name |
| Date | Release year | 2024 | Year of release |
| URL | Web address | <https://openai.com/chatgpt> | Access URL |
| Accessed | Access date | 2024-02-20 | Date accessed |

### Medium Field Options

Use the **Medium** field to specify the type of software/application/AI tool:

- `Computer program`
- `Mobile application`
- `Large language model`
- `Text-to-image model`
- Or any other descriptive term

### Software/AI Tools - Example Output

**Input in Zotero:**

- Author: OpenAI
- Title: ChatGPT
- Version: 4.0
- Medium: Large language model
- Place: San Francisco
- Publisher: OpenAI
- Date: 2024
- URL: <https://openai.com/chatgpt>
- Accessed: 2024-02-20

**Formatted Citation:**

```text
OpenAI. ChatGPT, ver. 4.0 [Large language model]. San Francisco: OpenAI; 2024 [cited 2024 Feb 20]. Available from: https://openai.com/chatgpt
```

### Software/AI Tools - Special Notes

- The **Version** field is displayed with "ver." prefix
- The **Medium** field appears in brackets after the version
- If no Medium field is provided, `[Internet]` is shown by default for items with URLs
- For AI tools like ChatGPT, Claude, Midjourney, etc., use appropriate medium descriptions

---

## Using the Medium Field

### Medium Field - Overview

The **Medium** field allows you to specify the format or type of a resource, which appears in brackets in the citation. This field **replaces** the default `[Internet]` tag when filled in.

### When to Use the Medium Field

- **Software and Applications**: Specify the type (e.g., "Computer program", "Mobile application")
- **AI Tools**: Specify the AI type (e.g., "Large language model", "Text-to-image model")
- **Special Formats**: DVDs, Blu-rays, streaming services, etc.
- **Electronic Resources**: When you want to specify something more specific than "Internet"

### How It Works

- **With Medium field**: The value you enter appears in brackets (e.g., `[Computer program]`)
- **Without Medium field**: If a URL is present, `[Internet]` is shown automatically
- **No URL, no Medium**: No bracket notation appears

### Medium Field - Examples

| Medium Field Value | Output |
| ------------------ | ------- |
| Computer program | `[Computer program]` |
| Mobile application | `[Mobile application]` |
| Large language model | `[Large language model]` |
| Text-to-image model | `[Text-to-image model]` |
| DVD | `[DVD]` |
| *empty* (with URL) | `[Internet]` |

---

## Using the Extra Field for Figures, Tables, and Images

### Extra Field - Overview

The **Extra** field (mapped to the `note` variable in CSL) can be used to add information about figures, tables, or images referenced in a source. This information appears at the **end of the citation** after the identifier (DOI, ISBN, ISSN, PMID, or URL).

### Format in Extra Field

Enter the information in this format:

```text
Figure [Number]. [Title]; p. [Page]
```

Or:

```text
Table [Number]. [Title]; p. [Page]
```

Or:

```text
Image [Number]. [Title]; p. [Page]
```

### Extra Field - Examples

**Input in Zotero Extra field:**

```text
Figure 3. Distribution of responses; p. 42
```

**Output in citation:**

```text
... Available from: https://example.com. Figure 3. Distribution of responses; p. 42
```

**Another example:**

```text
Table 1. Summary statistics; p. 15
```

**Output:**

```text
... doi: 10.1234/example. Table 1. Summary statistics; p. 15
```

### Extra Field - Special Notes

- The Extra field content appears after a period separator
- You can use any text that starts with "Figure", "Table", or "Image"
- This is useful for referencing specific visual elements from a source
- The CSL does not filter by prefix—enter only relevant content in the Extra field

---

## Identifier Priority and Display

### For Journal Articles

The citation style displays identifiers in the following **priority order**:

1. **DOI** (Digital Object Identifier) - Highest priority
   - Format: `doi: 10.1234/example`

2. **PMID** (PubMed ID) - If no DOI
   - Format: `PMID: 12345678`

3. **ISSN** (International Standard Serial Number) - If no DOI or PMID
   - Format: `ISSN: 1234-5678`

4. **URL** - If none of the above
   - Format: `Available from: https://example.com`

### For Books

The citation style displays identifiers in the following **priority order**:

1. **ISBN** (International Standard Book Number) - Highest priority
   - Format: `ISBN: 978-0-123456-78-9`

2. **URL** - If no ISBN
   - Format: `Available from: https://example.com`

### For Other Items

- **URL** is displayed if present
  - Format: `Available from: https://example.com`

### Important Notes

- Only **one identifier** is displayed per citation (the highest priority available)
- DOI is preferred over all other identifiers for journal articles
- ISBN is preferred for books
- Always enter the most specific identifier available in Zotero

---

## Additional Resources

- **Karolinska Institutet Library**: <https://kib.ki.se/en/write-cite/writing-references-apa-vancouver/reference-guides/reference-guide-vancouver>
- **Citing Medicine (NLM)**: <https://www.ncbi.nlm.nih.gov/books/NBK7256/>
- **Zotero Documentation**: <https://www.zotero.org/support/>
- **CSL Documentation**: <https://citationstyles.org/>

---

## Questions or Issues?

If you encounter formatting issues:

1. Verify you're using the latest version of the style file
2. Check that all fields are entered correctly in Zotero
3. Ensure your Zotero software is up to date
4. Consult the Karolinska Institutet Library for style-specific questions

---

Last Updated: 2026-02-20
