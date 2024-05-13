<a href="https://github.com/drshahizan/ai-tools/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/ai-tools" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/ai-tools/network/members"><img src="https://img.shields.io/github/forks/drshahizan/ai-tools" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/ai-tools"><img src="https://img.shields.io/github/issues-pr/drshahizan/ai-tools" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/ai-tools/issues"><img src="https://img.shields.io/github/issues/drshahizan/ai-tools" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/ai-tools/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/ai-tools?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2Fai-tools&labelColor=%23d9e3f0&countColor=%23697689&style=flat)

# [VOSviewer](https://www.vosviewer.com/)

This is a software tool for constructing and visualizing bibliometric networks such as journals, researchers, or individual publications, and they can be constructed based on citation, bibliographic coupling, co-citation, or co-authorship relations. VOSviewer also offers text mining functionality that can be used to construct and visualize co-occurrence networks of important terms extracted from a body of scientific literature. VOSviewer also offers text mining functionality that can be used to construct and visualize co-occurrence networks of important terms extracted from a body of scientific literature.

<figure><img src="https://www.vosviewer.com/media/images/content/ea30284dd349a3651f465ac581592983_large.png" alt="" width="563"></figure>

VOSviewer can be used to:

* **Visualize bibliometric networks:** VOSviewer can be used to visualize bibliometric networks in a variety of ways, such as graphs, maps, and timelines. This makes it easier to understand the relationships between different concepts.
* **Identify key players:** VOSviewer can be used to identify key players in a research field by looking at the number of papers they have published, the number of citations they have received, and the number of collaborations they have formed.
* **Identify emerging trends:** VOSviewer can be used to identify emerging trends in a research field by looking at the number of papers that have been published on a particular topic in recent years.
* **Analyze the impact of a research paper:** VOSviewer can be used to analyze the impact of a research paper by looking at the number of citations it has received and the number of times it has been used in other papers.

<figure><img src="https://www.vosviewer.com/media/images/content/a85a6c4ea4be8fe712929d0ecff44b58_large.png" alt="" width="563"></figure>

VOSviewer is a powerful tool that can be used to visualize and analyze bibliometric networks. It is free and open-source, which makes it accessible to everyone.

Here are some of the features of VOSviewer:

* **Data import:** VOSviewer can import data from a variety of sources, such as BibTeX, Endnote, and CSV files. This makes it possible to visualize bibliometric networks from a variety of sources.
* **Network visualization:** VOSviewer can visualize bibliometric networks in a variety of ways, such as graphs, maps, and timelines. This makes it easier to understand the relationships between different concepts.
* **Network analysis:** VOSviewer can be used to analyze bibliometric networks by looking at the number of papers, authors, and institutions in the network. It can also be used to identify key players and emerging trends.
* **Network export:** VOSviewer can export bibliometric networks in a variety of formats, such as PDF, PNG, and SVG files. This makes it possible to share bibliometric networks with others.

<figure><img src="https://www.vosviewer.com/media/images/content/08a8dd14196910a1715cedf5df544371_large.png" alt="" width="563"></figure>

## Obtaining Content from Databases

**Scopus – CSV** – most options for analysis (co-authorship, co-occurrence, citation, co-citation, bibliographic coupling)

- search by topic or desired publications
- select citations and click export – select CSV
- limited to 2000 articles
- include 
  - Citation information 
  - Affiliations
  - Abstract and keywords
  - Include references

**Scopus – RIS** – limited to author and co-occurrence (keyword)

- search by topic or desired publications
- select citations and click export – select RIS
- limited to 2000 articles
- include
  - citation
  - abstract

**Web of Science – plain text (txt)** – most options for analysis (co-authorship, co-occurrence, citation, co-citation, bibliographic coupling)

- search by topic or desired publications
- select citations and click export – select plain text
- limited to 500 articles
- include records from 1 to ???
- Record content – Full Record and Cited References

**Web of Science – RIS** – limited to author and co-occurrence (keyword)

- search by topic or desired publications
- select citations and click export – select RIS
- limited to 1000 articles
- include records from 1 to ???
- Record content – Author, Title, Source, Abstract

## Bibliometric Analysis using VOSViewer

### Create a map based on bibliographic data

**Export in CSV format (Scopus) or TXT (Web of Science)**

- Choose this option to create a co-authorship, keyword co-occurrence, citation, bibliographic coupling, or co-citation map based on bibliographic data -- click next
- Choose data source - select Read data from bibliographic database files -- click next
- Select files - click on the tab of the database source and select file from computer (.csv) - click next
- Click Co-authorship and Full counting & Unit of analysis (Authors, Organization, Countries) - click next
- Choose threshold - make choice -- click next
- Choose number of authors - make choice - click next
- Verify selected authors
  - Before clicking finish, right-click on the table (if you are using a PC), and click export selected authors.
    - You can use this table to create a thesaurus to clean up names (i.e. same author but name variations) or exclude names
  - Click Finish
 
**Export in RIS format**

- Choose this option to create a co-authorship or keyword co-occurrence -- click next
- Choose data source - select Read data from reference manager files -- click next
- Under RIS tab, select file from computer - click next
- Click Co-authorship (or co-occurrence) and Full counting - change other settings you would like - click next
- Choose threshold - make choice -- click next
- Choose number of authors - make choice - click next
- Verify selected authors (or keywords)
  - Before clicking finish, right-click on the table (if you are using a PC), and click export selected authors.
    - You can use this table to create a thesaurus to clean up names (i.e. same author but name variations) or exclude names
  - Click Finish
 
### Create a map based on text data

**Export in RIS format**

- Choose this option to create a term co-occurrence map based on text data - click next
- Choose data source - select Read data from a bibliographic database (Scopus – CSV; WOS - txt) or read data from reference manager files (RIS) -- click next
- Choose fields – Title and abstract fields, Title field, or abstract field - click next (if download included abstracts - abstract & title will be an option)
- Choose counting method - choose binary or full - click next
- Choose threshold - make choice -- click next
- Choose number of terms - make choice - click next
- Verify selected terms
  - Before clicking finish, right-click on the table (if you are using a PC), and click export selected terms.
    - You can use this table to create a thesaurus to clean up terms (i.e. same author but name variations) or exclude names
  - Click Finish

## Learning Materials

| No  | Title                                                    | File                                | 
|---------:|----------------------------------------------------------|-------------------------------------|
| 1. | Systematic Literature Review Template| <a href="https://liveutm-my.sharepoint.com/:b:/g/personal/shahizan_live_utm_my/Ecqg1PGM56hPuJ3WYS5GSxIBAk-sdXXQekXDE9REqlBPqw?e=TCYh4Z" ><img src="../images/rfp.png" width="24px" height="24px" ></a>|
| 2. |**Li, J., Othman, M. S., Chen, H., & Yusuf, L. M.** (2024). *A critical review of feature selection methods for machine learning in IoT security*. *International Journal of Communication Networks and Distributed Systems*, **30**(3), 264-312.| <a href="https://liveutm-my.sharepoint.com/:u:/g/personal/shahizan_live_utm_my/EbuhF-z_hHFHrH6Unw1jkW8Bf03YTvZEGtFta8EgbPE0_w?e=Ak2UdL" ><img src="../images/rfp.png" width="24px" height="24px" ></a>|
| 3. | **Bauer, A., Coppola, R., Alégroth, E., & Gorschek, T.** (2023). *Code review guidelines for GUI-based testing artifacts*. *Information and Software Technology*, 163, 107299.  | <a href="https://liveutm-my.sharepoint.com/:u:/g/personal/shahizan_live_utm_my/EUdvio6IFq1EpK8D4-jMybYBp_Yv0kSdpSObrD_feDsNaA?e=jtA82T" ><img src="../images/rfp.png" width="24px" height="24px" ></a> | 
| 4. | **De la Torre-López, J., Ramírez, A., & Romero, J. R.** (2023). *Artificial intelligence to automate the systematic review of scientific literature*. *Computing*, 105(10), 2171–2194.| <a href="https://liveutm-my.sharepoint.com/:u:/g/personal/shahizan_live_utm_my/ETfVmEqkVV5HpQpBcfzVzUcBCWBnRHMZh88Ns7QRkYq_Sg?e=PANSiC" ><img src="../images/rfp.png" width="24px" height="24px" ></a>|
| 5. | **Carbonell-Alcocer, A., Romero-Luis, J., Gertrudix, M., & Wuebben, D.** (2023). *Datasets on the assessment of the scientific publication’s corpora in circular economy and bioenergy approached from education and communication*. *Data in Brief*, 47, 108958.| <a href="https://liveutm-my.sharepoint.com/:u:/g/personal/shahizan_live_utm_my/EcLELbVGVxxJvr1BwXi4HkQBvMVMjEljCIiJSik0JkrbpA?e=qMrzKn" ><img src="../images/rfp.png" width="24px" height="24px" ></a> |
| 6.| **Marcos Dib, Carlos Alberto Alvares Rocha, Li Weigang, & Allan V. A. Faria.** (2022). Systematic Literature Review about Text Classification (Version 1) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.7017720|<a href="https://liveutm-my.sharepoint.com/:u:/g/personal/shahizan_live_utm_my/Ef-nkCWqbSVEhzZ8orbZdo0BzMbrrd9-tywjQfVLWcg_5w?e=AeagmP" ><img src="../images/rfp.png" width="24px" height="24px" ></a>|
| 7. | Juan Cruz-Benito (2016). Systematic Literature Review & Mapping | <a href="https://liveutm-my.sharepoint.com/:b:/g/personal/shahizan_live_utm_my/Ec8dnIh50vBJtkDLbrRBRNUBjNzSpEGXFqi4n4l5A4I2dg?e=rD6kH5" ><img src="../images/rfp.png" width="24px" height="24px" ></a>|
|8.| **Busse, C., August, E.** (2021). How to Write and Publish a Research Paper for a Peer-Reviewed Journal. J Canc Educ 36, 909–913 (2021). https://doi.org/10.1007/s13187-020-01751-z | <a href="https://doi.org/10.1007/s13187-020-01751-z" ><img src="../images/rfp.png" width="24px" height="24px" ></a>|
|9.| Google Scholar Metrics | <a href="https://scholar.google.com.ec/citations?view_op=metrics_intro&hl=en" ><img src="../images/rfp.png" width="24px" height="24px" ></a>|
|10.| **LaPlaca, P. J., Lindgreen, A., & Vanhamme, J.** (2018). *How to Write Really Good Articles for Premier Academic Journals*. *Industrial Marketing Management*, **68**, 202-209. | <a href="https://www.sciencedirect.com/science/article/abs/pii/S001985011730874X?via%3Dihub" ><img src="../images/rfp.png" width="24px" height="24px" ></a>|
|11.| **Kofod-Petersen, A.** (2018). How to Do a Structured Literature Review in Computer Science. NTNU | <a href="https://research.idi.ntnu.no/aimasters/files/SLR_HowTo2018.pdf" ><img src="../images/rfp.png" width="24px" height="24px" ></a>|
|12.| **Mengist, W., Soromessa, T., & Legese, G.** (2020). *Method for conducting systematic literature review and meta-analysis for environmental science research*. MethodsX, 7. | <a href="https://www.sciencedirect.com/science/article/pii/S221501611930353X" ><img src="../images/rfp.png" width="24px" height="24px" ></a>|
|13.| **Silva, R. L. S., & Weidt Neiva, F.** (2016). Systematic Literature Review in Computer Science - A Practical Guide. Report number: 002/2016. Federal University of Juiz de Fora| <a href="https://www.researchgate.net/publication/320704338_Systematic_Literature_Review_in_Computer_Science_-_A_Practical_Guide" ><img src="../images/rfp.png" width="24px" height="24px" ></a>|
|14.| **Carrera-Rivera, A., Ochoa, W., Larrinaga, F., & Lasa, G.** (2022). How to conduct a systematic literature review: A quick guide for computer science research. *MethodsX*, *9*, 101895. https://doi.org/10.1016/j.mex.2022.101895| <a href="https://doi.org/10.1016/j.mex.2022.101895" ><img src="../images/rfp.png" width="24px" height="24px" ></a>|



## Youtube

1. [MENEMUKAN NOVELTY PENELITIAN DENGAN VOS VIEWER | ANALISA BIBILIOMETRIK](https://www.youtube.com/watch?v=VW9Z6pqfqjY)
2. [Bibliometric Analysis of DIMENSIONS Data Using VosViewer](https://youtu.be/or6LA0anOBQ?si=9JLBjVstDcof2VP)
3. [How to run a bibliometric analysis in VOSviewer with searches from multiple databases](https://youtu.be/beNo3yeJ6YM?si=AcmIhvM5dHXQFSJW)



[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan\&labelColor=%23697689\&countColor=%23555555\&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
