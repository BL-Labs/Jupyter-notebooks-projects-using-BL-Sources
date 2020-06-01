# Jupyter Notebooks using BL's Collections data and Sources
A list of Jupyter Notebooks' projects using BL's Collections data and Sources.

Jupyter Notebooks is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text.

- [Applied Data Analysis](https://github.com/mromanello/ADA-DHOxSS2019) as taught at DHOxSS 2019: covers tidying data, visualization, modeling, and advanced applications of data analysis. By Giovanni Colavizza and Matteo Romanello (run them on [Binder](https://mybinder.org/v2/gh/mromanello/ADA-DHOxSS2019/master));

- [LibCrowds Jupyter Notebooks](https://github.com/LibCrowds/notebooks) - explore the data created via the British Library's [LibCrowds](http://libcrowds.com/) platform, which includes crowdsourced transcriptions of historic playbills and catalogue data from card catalogues (run them on [Binder](https://mybinder.org/v2/gh/libcrowds/notebooks/master?urlpath=lab));

- [topic-modeling-billing Jupyter Notebook](https://github.com/hibernator11/notebook-texts-metadata/blob/master/topic-modeling-billing.ipynb) - Topic Models are a type of statistical language models used for discovering hidden structure in a collection of texts; this example is based on a dataset that comprises 264 volumes of digitised theatrical playbills published between 1660 – 1902 (mostly 19th century) from England, Scotland, Wales and Ireland. Digitised from the British Library's physical collection of over 500 volumes of playbills, the dataset contains text files in Optical Character Recognition (OCR) format. More information about the dataset at https://data.bl.uk/playbills/ (run it on [Binder](https://mybinder.org/v2/gh/hibernator11/notebook-texts-example/master?urlpath=notebooks/topic-modeling-billing.ipynb);

- [Using the openVirus EThOS API](https://github.com/anjackson/contentminer/blob/master/openVirus_EThOS_API.ipynb) - British Library's EThOS indexed Theses can be queried using Solr's API; this Notebook looks for all the theses that mention 'coronavirus' or 'coronaviruses', and counts their hits. Please access BL's [Digital scholarship blog](https://blogs.bl.uk/digital-scholarship) and the blog post ["Searching eTheses for the openVirus project"](https://blogs.bl.uk/digital-scholarship/2020/05/searching-etheses-for-the-openvirus-project.html) for more information about [The openVirus Project](https://github.com/petermr/openVirus) and other research done within this project. By [Andy Jackson](https://anjackson.net/), Technical Lead for the UK Web Archive;

- [GLAM Workbench: Web Archives](https://github.com/GLAM-Workbench/web-archives/): collection of Jupyter notebooks that document web archive data sources and standards, and walk through methods of harvesting, analysing, and visualising that data. To see which Notebooks work with UKWA (UK Web Archive), please consult the *Web Archives* entry at the [GLAM Workbench](https://glam-workbench.github.io/web-archives/) site. By [Tim Sherratt](https://www.timsherratt.org/), "historian and hacker", Associate Professor of Digital Heritage at the University of Canberra, Australia.

#### Other projects using BL Collections data and Sources

- [r-for-newspapers-data](https://github.com/yannryan-irl/r-for-newspapers-data) - The repository for the in-progress open book, 'R for Newspaper Data'. By Yann Ryan.
<br/>

## In this Repository (Work In Progress)
- [Microsoft 19th Century Books](Microsoft19thCenturyBooks/):

    - [base.ipynb](Microsoft19thCenturyBooks/base.ipynb): examples of different types of access and ways to load source data from The British Library Collections; includes some basic processing and visualisation (see it on [JN Viewer](https://nbviewer.jupyter.org/github/BL-Labs/Jupyter-notebooks-projects-using-BL-Sources/blob/master/Microsoft19thCenturyBooks/base.ipynb));

    - [load_JSON_files.ipynb](Microsoft19thCenturyBooks/load_JSON_files.ipynb): example on how to load JSON files from a directory and its sub-directories, loading all their data into a single DataFrame, removing blocks of text that are empty (see it on [JN Viewer](https://nbviewer.jupyter.org/github/BL-Labs/Jupyter-notebooks-projects-using-BL-Sources/blob/master/Microsoft19thCenturyBooks/load_JSON_files.ipynb); run it on [Binder](https://mybinder.org/v2/gh/BL-Labs/Jupyter-notebooks-projects-using-BL-Sources/master?filepath=Microsoft19thCenturyBooks/load_JSON_files.ipynb) or on [Google Colab](https://colab.research.google.com/github/BL-Labs/Jupyter-notebooks-projects-using-BL-Sources/blob/master/Microsoft19thCenturyBooks/load_JSON_files.ipynb) -- note: on Colab, it will require to download the 295MB zip file used to sample this process -- already included on Binder).

- LOD_SPARQL / British National Bibliography:

    - [Books by Subject](LOD_SPARQL/00_BNB_SPARQL_books_by_LCSH_subject.ipynb): retrieve books' records (that have a ISBN) indexed under a given LCSH Subject / Topic (see it on [JN Viewer](https://nbviewer.jupyter.org/github/BL-Labs/Jupyter-notebooks-projects-using-BL-Sources/blob/master/LOD_SPARQL/00_BNB_SPARQL_books_by_LCSH_subject.ipynb));

    - [Resources for Two Subjects](LOD_SPARQL/01_BNB_SPARQL_Compare_Publication_Year_for_two_Subjects.ipynb): compare the evolution of published resources by year, indexed under a given LCSH Subject / Topic (see it on [JN Viewer](https://nbviewer.jupyter.org/github/BL-Labs/Jupyter-notebooks-projects-using-BL-Sources/blob/master/LOD_SPARQL/01_BNB_SPARQL_Compare_Publication_Year_for_two_Subjects.ipynb));

    - [Linked Data / Interactive Map](LOD_SPARQL/02_BNB_SPARQL_LOD_Extraction_Interactive_Map.ipynb): queries the BNB SPARQL EndPoint, and enriches the results with Linked Open Data from Geonames and WikiData to display the places of publication in an interactive map. Forked / Copied from Author: Gustavo Candela (https://github.com/hibernator11), Research and Development department at The Biblioteca Virtual Miguel de Cervantes, University of Alicante, Spain (see it on [JN Viewer](https://nbviewer.jupyter.org/github/BL-Labs/Jupyter-notebooks-projects-using-BL-Sources/blob/master/LOD_SPARQL/02_BNB_SPARQL_LOD_Extraction_Interactive_Map.ipynb)).
<br/>

##
#### Explore and experiment with the British Library’s [digital collections](https://data.bl.uk/)

The British Library community is able to flourish online thanks to freely available resources such as this.

You can help support our mission to continue making our collection accessible to everyone, for research, inspiration and enjoyment, by donating on the British Library supporter [webpage here](http://tiny.cc/BL-Donate).

Thank you for supporting the [British Library](https://www.bl.uk/).

[![The British Library](https://github.com/BL-Labs/Jupyter-notebooks-projects-using-BL-Sources/raw/master/wstatic/BL_EWK.png)
![The British Library Buildings Closed But Always Open Online to Everyone](https://github.com/BL-Labs/Jupyter-notebooks-projects-using-BL-Sources/raw/master/wstatic/BL_CoronaV19_OpenOnline.jpg)](https://www.bl.uk/)
