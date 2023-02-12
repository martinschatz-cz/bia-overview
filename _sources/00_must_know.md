# Must Know Sources

## NEUBIAS
NEUBIAS is a unique network of bioimage analysts in Europe, aiming at strengthening the bridge between life science,  computer science and digital image processing by:

 * Establishing the role and identity of bioimage analysts in the life science community
 * Sharing bioimage analysis knowledge and techniques
 * Improving image analysis technology, foster innovations and collaborations
 * Securing image data integrity
 * Complementing rapidly evolving microscopy techniques
 
### NEUBIAS web pages
[eubias.org/NEUBIAS](https://eubias.org/NEUBIAS/)


### NEUBIAS Academy
NUBIAS Academy is anouncing webinars presenting new BiA tools, ideas or workflows. While the youtube channel is where all the records are. This is a great start when you want to start using or get to know a new tool.
 * [Web](https://eubias.org/NEUBIAS/training-schools/neubias-academy-home/)
 * [Youtube Channel](https://www.youtube.com/playlist?list=PLbQR9xT-T5W9qcTWdljmaBJcvF_4lhUdH)




### NEUBIAS F1000Research Gateway
The gateway for all papers connected to BioImage Analysis tools, reviews and so on. The F1000Research is curently the best choice for Open Science publishing - everything is availabel from start, opn peer reviewd and with data and codes (wher relevant).
[f1000research.com/NEUBIAS](https://f1000research.com/NEUBIAS)


## Books (open access)
 * [Bioimage Data Analysis Workflows (Kota Miura, Nataša Sladoje)](https://link.springer.com/book/10.1007/978-3-030-22386-1)
 * [Introduction to Bioimage Analysis (Pete Bankhead)](https://bioimagebook.github.io/)
 * [Analyzing fluorescence microscopy images with ImageJ (Pete Bankhead)](https://petebankhead.gitbooks.io/imagej-intro/content/)

## Communities

### Image.sc Forum
[forum.image.sc](https://forum.image.sc/)

If you have any kind of question, this is place to start. You can get here answers even sniplets of codes in matter of hour - all thanks to very active community.

This forum’s focus is software-oriented aspects of scientific imaging, particularly (but not limited to) image analysis, processing, acquisition, storage, and management of digital scientific images. Everyone is welcome to ask questions. It’s for beginners and experts; life scientists and computer scientists; for practical questions and theoretical approaches to solving scientific problems with images. The primary objective is to foster independent learning 170 for everyone in the community.


### Microforum
[forum.microlist.org](https://forum.microlist.org/)

Microforum’s focus is hardware, acquisition, and specimen-related aspects of scientific imaging, particularly (but not limited to) theory and practical use of optical microscopes and detectors, fluorescent proteins and probes, and specimen preparation.

### ITK
[discourse.itk.org](https://discourse.itk.org/)

A place to discuss image analysis with the Insight Toolkit (ITK). This includes the pragmatics of programming with the library, image processing theory, how to address specific problems, and how to contribute to the community.

### Official forum of KNIME Analytics Platform
[forum.knime.com](https://forum.knime.com/)

Official forum of KNIME Analytics Platform, an open-source data analytics, reporting and integration platform. KNIME integrates various components for machine learning and data mining through its modular data pipelining concept.

## Reproducible Data Science

### [The Turing Way](https://the-turing-way.netlify.app/welcome) 
 Making reproducible Data Science "too easy not to do", handbook to reproducible, ethical and collaborative data science.
### [Zero-to-Binder](https://the-turing-way.netlify.app/communication/binder/zero-to-binder.html) 
How to create a Binder project from scratch for Python, Julia or R GitHub repository.
### [chatGPT](https://chat.openai.com)
ChatGPT can help with reproducible data science by providing assistance with documentation, code execution, and data analysis. For example, it can provide explanations on best practices for documentation, generate code snippets to perform specific data science tasks, and assist with statistical analysis. Additionally, ChatGPT can also help with generating reports and visualizations to communicate the results of data science projects in a clear and concise manner. However, it's important to note that reproducibility in data science also relies heavily on proper data management, version control, and collaboration. 

**Never completely rely on ChatGPT. ChatGPT is not perfect and may sometimes provide incorrect or unreliable information. Double-check and verify information that you receive.**

## Papers

### [Avoiding Twisted Pixels: Ethical Guidelines for the Appropriate Use and Manipulation of Scientific Digital Images](https://doi.org/10.1007/s11948-010-9201-y)
Digital imaging has provided scientists with new opportunities to acquire and manipulate data using techniques that were difficult or impossible to employ in the past. Because digital images are easier to manipulate than film images, new problems have emerged. One growing concern in the scientific community is that digital images are not being handled with sufficient care. The problem is twofold: (1) the very small, yet troubling, number of intentional falsifications that have been identified, and (2) the more common unintentional, inappropriate manipulation of images for publication. Journals and professional societies have begun to address the issue with specific digital imaging guidelines. Unfortunately, the guidelines provided often do not come with instructions to explain their importance. Thus they deal with what should or should not be done, but not the associated ‘why’ that is required for understanding the rules. This article proposes 12 guidelines for scientific digital image manipulation and discusses the technical reasons behind these guidelines. These guidelines can be incorporated into lab meetings and graduate student training in order to provoke discussion and begin to bring an end to the culture of “data beautification”.


```
@article{Cromey2010,
  doi = {10.1007/s11948-010-9201-y},
  url = {https://doi.org/10.1007/s11948-010-9201-y},
  year = {2010},
  month = jun,
  publisher = {Springer Science and Business Media {LLC}},
  volume = {16},
  number = {4},
  pages = {639--667},
  author = {Douglas W. Cromey},
  title = {Avoiding Twisted Pixels: Ethical Guidelines for the Appropriate Use and Manipulation of Scientific Digital Images},
  journal = {Science and Engineering Ethics}
}
```

### [Reproducible image handling and analysis](https://doi.org/10.15252/embj.2020105889)
Image data are universal in life sciences research. Their proper handling is not. A significant proportion of image data in research papers show signs of mishandling that undermine their interpretation. We propose that a precise description of the image processing and analysis applied is required to address this problem. A new norm for reporting reproducible image analyses will diminish mishandling, as it will alert co-authors, referees, and journals to aberrant image data processing or, if published nonetheless, it will document it to the reader. To promote this norm, we discuss the effectiveness of this approach and give some step-by-step instructions for publishing reproducible image data processing and analysis workflows.

```
@article{Miura2021,
  doi = {10.15252/embj.2020105889},
  url = {https://doi.org/10.15252/embj.2020105889},
  year = {2021},
  month = jan,
  publisher = {{EMBO}},
  volume = {40},
  number = {3},
  author = {Kota Miura and Simon F N{\o}rrelykke},
  title = {Reproducible image handling and analysis},
  journal = {The {EMBO} Journal}
}
```

### [Accuracy and precision in quantitative fluorescence microscopy](https://doi.org/10.1083/jcb.200903097)
The light microscope has long been used to document the localization of fluorescent molecules in cell biology research. With advances in digital cameras and the discovery and development of genetically encoded fluorophores, there has been a huge increase in the use of fluorescence microscopy to quantify spatial and temporal measurements of fluorescent molecules in biological specimens. Whether simply comparing the relative intensities of two fluorescent specimens, or using advanced techniques like Förster resonance energy transfer (FRET) or fluorescence recovery after photobleaching (FRAP), quantitation of fluorescence requires a thorough understanding of the limitations of and proper use of the different components of the imaging system. Here, I focus on the parameters of digital image acquisition that affect the accuracy and precision of quantitative fluorescence microscopy measurements.

```
@article{10.1083/jcb.200903097,
    author = {Waters, Jennifer C.},
    title = "{Accuracy and precision in quantitative fluorescence microscopy}",
    journal = {Journal of Cell Biology},
    volume = {185},
    number = {7},
    pages = {1135-1148},
    year = {2009},
    month = {06},
    abstract = "{The light microscope has long been used to document the localization of fluorescent molecules in cell biology research. With advances in digital cameras and the discovery and development of genetically encoded fluorophores, there has been a huge increase in the use of fluorescence microscopy to quantify spatial and temporal measurements of fluorescent molecules in biological specimens. Whether simply comparing the relative intensities of two fluorescent specimens, or using advanced techniques like Förster resonance energy transfer (FRET) or fluorescence recovery after photobleaching (FRAP), quantitation of fluorescence requires a thorough understanding of the limitations of and proper use of the different components of the imaging system. Here, I focus on the parameters of digital image acquisition that affect the accuracy and precision of quantitative fluorescence microscopy measurements.}",
    issn = {0021-9525},
    doi = {10.1083/jcb.200903097},
    url = {https://doi.org/10.1083/jcb.200903097},
    eprint = {https://rupress.org/jcb/article-pdf/185/7/1135/1342498/jcb\_200903097.pdf},
}
```

### [A Hitchhiker's guide through the bio-image analysis software universe](https://doi.org/10.1002/1873-3468.14451)
Modern research in the life sciences is unthinkable without computational methods for extracting, quantifying and visualising information derived from microscopy imaging data of biological samples. In the past decade, we observed a dramatic increase in available software packages for these purposes. As it is increasingly difficult to keep track of the number of available image analysis platforms, tool collections, components and emerging technologies, we provide a conservative overview of software that we use in daily routine and give insights into emerging new tools. We give guidance on which aspects to consider when choosing the platform that best suits the user's needs, including aspects such as image data type, skills of the team, infrastructure and community at the institute and availability of time and budget.

```
@article{Haase2022,
  doi = {10.1002/1873-3468.14451},
  url = {https://doi.org/10.1002/1873-3468.14451},
  year = {2022},
  month = jul,
  publisher = {Wiley},
  volume = {596},
  number = {19},
  pages = {2472--2485},
  author = {Robert Haase and Elnaz Fazeli and David Legland and Michael Doube and Si{\^{a}}n Culley and Ilya Belevich and Eija Jokitalo and Martin Schorb and Anna Klemm and Christian Tischer},
  title = {A Hitchhiker{\textquotesingle}s guide through the bio-image analysis software universe},
  journal = {{FEBS} Letters}
}
```

### [Metrics reloaded: Pitfalls and recommendations for image analysis validation](https://doi.org/10.48550/arXiv.2206.01653)
Increasing evidence shows that flaws in machine learning (ML) algorithm validation are an underestimated global problem. Particularly in automatic biomedical image analysis, chosen performance metrics often do not reflect the domain interest, thus failing to adequately measure scientific progress and hindering translation of ML techniques into practice. To overcome this, a large international expert consortium created Metrics Reloaded, a comprehensive framework guiding researchers towards choosing metrics in a problem-aware manner. Following the convergence of ML methodology across application domains, Metrics Reloaded fosters the convergence of validation methodology. The framework was developed in a multi-stage Delphi process and is based on the novel concept of a problem fingerprint - a structured representation of the given problem that captures all aspects that are relevant for metric selection from the domain interest to the properties of the target structure(s), data set and algorithm output. Metrics Reloaded targets image analysis problems that can be interpreted as a classification task at image, object or pixel level, namely image-level classification, object detection, semantic segmentation, and instance segmentation tasks. Users are guided through the process of selecting and applying appropriate validation metrics while being made aware of potential pitfalls. To improve the user experience, we implemented the framework in the Metrics Reloaded online tool, which also provides a common point of access to explore weaknesses and strengths of the most common validation metrics. An instantiation of the framework for various biological and medical image analysis use cases demonstrates its broad applicability across domains.

```
@misc{https://doi.org/10.48550/arxiv.2206.01653,
  doi = {10.48550/ARXIV.2206.01653},
  url = {https://arxiv.org/abs/2206.01653},
  author = {Maier-Hein, Lena and Reinke, Annika and Godau, Patrick and Tizabi, Minu D. and Christodoulou, Evangelia and Glocker, Ben and Isensee, Fabian and Kleesiek, Jens and Kozubek, Michal and Reyes, Mauricio and Riegler, Michael A. and Wiesenfarth, Manuel and Baumgartner, Michael and Eisenmann, Matthias and Heckmann-Nötzel, Doreen and Kavur, A. Emre and Rädsch, Tim and Acion, Laura and Antonelli, Michela and Arbel, Tal and Bakas, Spyridon and Bankhead, Peter and Benis, Arriel and Cardoso, M. Jorge and Cheplygina, Veronika and Cimini, Beth and Collins, Gary S. and Farahani, Keyvan and Ferrer, Luciana and Galdran, Adrian and van Ginneken, Bram and Haase, Robert and Hashimoto, Daniel A. and Hoffman, Michael M. and Huisman, Merel and Jannin, Pierre and Kahn, Charles E. and Kainmueller, Dagmar and Kainz, Bernhard and Karargyris, Alexandros and Karthikesalingam, Alan and Kenngott, Hannes and Kofler, Florian and Kopp-Schneider, Annette and Kreshuk, Anna and Kurc, Tahsin and Landman, Bennett A. and Litjens, Geert and Madani, Amin and Maier-Hein, Klaus and Martel, Anne L. and Mattson, Peter and Meijering, Erik and Menze, Bjoern and Moher, David and Moons, Karel G. M. and Müller, Henning and Nichyporuk, Brennan and Nickel, Felix and Petersen, Jens and Rajpoot, Nasir and Rieke, Nicola and Saez-Rodriguez, Julio and Gutiérrez, Clarisa Sánchez and Shetty, Shravya and van Smeden, Maarten and Sudre, Carole H. and Summers, Ronald M. and Taha, Abdel A. and Tsaftaris, Sotirios A. and Van Calster, Ben and Varoquaux, Gaël and Jäger, Paul F.},
  keywords = {Computer Vision and Pattern Recognition (cs.CV), FOS: Computer and information sciences, FOS: Computer and information sciences},
  title = {Metrics reloaded: Pitfalls and recommendations for image analysis validation},
  publisher = {arXiv},
  year = {2022},
  copyright = {Creative Commons Attribution Non Commercial No Derivatives 4.0 International}
}

```
