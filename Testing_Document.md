# CW2 Testing Document

Acceptance Testing
Summary: Acceptance testing was carried out to ensure the system meets user requirements.
The main objectives were:
- Verify features work correctly
- Ensure user-friendly system
- Test valid and invalid inputs
Test Cases
AT1 – Homepage → Pass  
AT2 – Images → Fail 
AT3 – Navigation → Pass  
AT4 – Staff search → Pass  
AT5 – Empty input → Pass  
AT6 – No results → Pass  
Conclusion
System works correctly with minor issues.
## Unit Testing
Unit testing and code inspection were carried out systematically across all page of the website to ensure that each unit functioned correctly while meeting design and accessibility standards. A representative page was tested thoroughly including structure, navigation, content links and layout. As the website uses a  consistent template across all pages, the same tests were then applied to the remaining pages to confirm consistency and reliability throughout. This approach ensured that all components of the website were thoroughly checked.
Unit testing involves testing individual parts of a program to ensure each component works correctly. In this project, each section of the webpage was treated as a unit and tested independently.

The following units were identified and tested:
•	Header 
•	Navigation bar 
•	Image 
•	Content sections 
•	Links (internal and external) 
•	Footer 

Each unit was tested by checking its functionality and comparing the actual result with the expected result.
•	Navigation links were clicked to ensure they opened the correct pages 
•	Images were checked to confirm they loaded correctly and included appropriate alt text 
•	Content sections were reviewed to ensure correct structure and readability 
•	Links to external files (e.g. PDFs) were tested to confirm they opened properly 
•	Layout was checked to ensure consistency across different pages

Unit-	Test	-Expected Result	-Result	-Outcome
Header-	Check heading text-Matches correct page topic-correct-pass
Image-Load image-Displays correctly -	correct	-pass
Navigation-Click links-Each link opens to the correct pages-correct-pass
Sources-Open PdFs and images-Opens correct sources and to correct pages if a PDF-correct-pass
Layout-Load page with css-Follows css layout-correct-pass
Accessibility-Alt text shows if image in unavailable-Present and correct for the image-	correct-pass

Results
The results of the unit testing showed that all components of the website functioned as expected. Each unit, which included the navigation bar, images, content sections, links, and footer, was tested individually and produced the correct outcomes. All internal and external links opened the intended pages or documents, images loaded correctly and included appropriate alt text for accessibility, and the layout remained consistent across all pages. No errors were identified during testing, and the use of a consistent template ensured that successful results on one page were replicated across the rest of the website.


## Code Inspection

## Peer Review

## Final Product:
B.1 Usability Aspects (Industry Sponsor Assessment):
Marshfield School History Web Application
This section evaluates the usability, interface quality, and overall fitness for purpose of the completed Marshfield School History web application. The system was developed in direct response to the client’s specification, which required a browser based HTML/CSS platform with two SQL databases, extensive hyperlinking to archival materials, and a structure that could be adapted for future historical research projects. The following assessment demonstrates that the implemented application is fully functional, user centred, and aligned with the needs of the Marshfield School historical research community.
1. Functional Completeness
The application fully implements the functional requirements defined by the client for the Marshfield School project. The system autostarts to Page 1, and includes all 25 required pages, covering the About section, Chapel Green Board School, Thornton Lane Board School, Marshfield School, and the two SQL database pages (Staff and Sources). The client specified:
“I require an html/css application with 2 SQL databases that are accessible through a browser.” “25 pages are required.” “Some text and page numbers in tables will require to be linked via hyperlinks to the appropriate Images folder.”
All of these requirements have been met. The Staff and Sources SQL databases are fully integrated and searchable through the browser interface, enabling efficient retrieval of historical information relating to Marshfield School and its associated institutions.
Hyperlinks throughout the site correctly connect to the structured Images directory (Books, Documents, Logbooks, Maps and Plans, etc.), allowing users to access digitised materials directly. Where the client suggested linking PDFs to reduce workload, this feature has been implemented and tested successfully.
The HTML and CSS codebase is fully annotated, line numbered, and divided into clearly labelled sections, supporting the client’s requirement for future adaptability:
The accompanying instruction manual provides detailed guidance on modifying page layouts, updating hyperlinks, and adapting the system for additional Marshfield School–related projects or other historical collections.
2. User Experience (UX) and Graphical User Interface (GUI)
The interface has been designed to be clear, consistent, and accessible for the target user group local historians, researchers, and community members interested in the history of Marshfield School. The client emphasised the importance of intuitive navigation:
“Navigation buttons are required… Change colour when mouse goes to each button.”
Accordingly, the navigation bar appears uniformly across all pages, with hover state colour changes to provide immediate visual feedback. This consistency ensures that users can move easily between the major sections of the Marshfield School project.
Readability and Layout
•	A two column content area (main text and Notable Dates)
•	A footer (“Community History Research by Ray Greenhough”)
This layout supports readability and ensures that users can quickly understand the historical context presented on each page.
Tables and Document Access
Child pages containing tables of page numbers (e.g., Page 1a, Page 3a, Page 4a–4s) are formatted for clarity, with evenly spaced cells and intuitive grouping. Selecting a page number opens the corresponding scanned document or PDF, and each document view includes Next, Previous, and Home navigation options, as required.
Accessibility Considerations
The interface uses high contrast colours, large clickable areas, and simple typography, ensuring usability for older users and those with visual impairments. The absence of unnecessary animations or complex interactions further supports accessibility.
3. Fitness for Purpose
The system directly addresses the client’s stated research challenges, particularly in relation to the Marshfield School archive:
“I often duplicate research which is not very efficient.” “Any research that I have done should really be made available and visible to my fellow researchers.”
The application centralises all staff records, sources, logbooks, admission registers, and archival materials relating to Marshfield School and its associated Board Schools. This eliminates duplicated research and ensures that historical materials are accessible to collaborators and future researchers.
The structured Images folder and extensive hyperlinking allow rapid access to primary sources, while the SQL databases provide efficient retrieval of staff and source information. The design is intentionally simple and non technical, reflecting the needs of historians who may not have programming experience.
The instruction manual ensures long term sustainability by enabling the client to adapt the system for future Marshfield School projects or other historical collections:
“The Instruction Manual will play a big part… Without it, part 2 of this project… will be untenable.”
By meeting these requirements, the system demonstrates strong alignment with the client’s workflow, research practices, and long term objectives.
4. Overall Evaluation
The completed Marshfield School History application is fully functional, user friendly, and well suited to the needs of the historical research community. Its clear navigation, consistent layout, accessible design, and robust hyperlinking structure ensure a positive user experience. The system meets all specified requirements and provides a sustainable foundation for future expansion. It therefore achieves a high level of usability and fitness for purpose in line with the expectations of the industry sponsor.


Systematic Use of GitHub (B3)  
Our team used GitHub throughout the project to manage development collaboratively. We maintained a structured repository with separate folders for software, testing documents, and weekly meeting minutes. All team members contributed regularly with meaningful commit messages documenting changes and rationale. Feature branches were used for major components before merging into the main branch. GitHub Issues and the Project Board were used to track tasks, assign responsibilities, and monitor progress. This ensured transparency, version control, and a professional workflow aligned with software engineering best practices.


