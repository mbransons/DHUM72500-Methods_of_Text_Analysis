# Methods of Text Analysis Portfolio

### Introduction

To explore the possibility of feminist text analysis, one might first contemplate Ahmed's call to "live a feminist life." In particular in what it is not – adopting a fixed set of ideals or norms, but about asking ethical questions and striving for equality and support in an unjust world. It involves challenging solidified histories and walls that perpetuate inequality.[^1] Engaging in 'feminist' text analysis should be a pursuit characterized by questioning and striving for equality. Moreover, when feminist scholars undertake computational text analysis, they must reflect upon several crucial questions at different stages of the process. Here are some key questions to keep in mind:

### Preparing Data for Analysis:

- Representation, Diversity, and Intersectionality: Does the dataset used include a diverse range of voices and perspectives, including those marginalized or underrepresented? Does it consider the ways in which various social identities intersect, such as gender, race, class, and sexuality?

In "Queer Data," Kevin Guyan emphasizes the impact of collection methods on participants' self-evaluation and identity exploration. He argues that data collection processes can serve as a means of consciousness-raising, offering individuals new perspectives and insights into their identities and their relationships with others. Guyan highlights that the interaction between researchers and participants is not a one-sided exchange of information, but rather a dynamic process that influences both parties.[^2]

By queering collection methods, Guyan suggests that these approaches not only provide a representation of the social world but also contribute to shaping and transforming it. He challenges the notion that identities, such as gay, trans, asexual, or heterosexual, are fixed and static categories waiting to be discovered by researchers. Instead, he asserts that these identities are partially constructed through the practices and techniques employed during data collection.[^3]

D'Ignazio and Klien highlight the value of collaboration and co-creation through the engaging of studied communities in data collection as a way to challenge power dynamics and create more equitable outcomes. They stress the need for participatory approaches that allow for community input and influence in shaping the data collection process. And underscore the values of trust-building, accountability, and power distribution when engaging studied communities – highlighting the responsibility of researchers to create inclusive and respectful research environments that value the perspectives and contributions of the communities involved.[^4]

- Gendered Language and Stereotyping: How does the dataset handle gendered language and stereotypes? Are there any steps that can be taken to mitigate the reinforcement of gender norms or biases during data preparation?

In "Gender and Cultural Analytics: Finding or Making Stereotypes?," Mandell introduces the concept of "stereotyping" in quantitative cultural analysis, drawing a parallel to the historical practice of stereo-typography. They argue that data mining can sometimes produce clichés when gender is biologized, binarized, and essentialized. Instead, they advocate for a dynamic reading of computational results, emphasizing the importance of close reading and engaging with the data interpretively.[^5]

They critically examines the methods and findings of Matthew Jockers and Jan Rybicki in their attempts to identify gender differences in writing styles using computational analysis. It raises concerns about the limitations and biases inherent in their approaches and emphasizes the importance of considering the evolving nature of gender associations and the reproducibility of results.

In particular it's suggested 'we could break the algorithm’s capacity to produce “a strong gender signal” by simply increasing the number of gender categories to be sorted. Experts in the field could create metadata to generate a completely new taxonomy to replace the tired M/F binary: “men writing as men,” “women writing as women, “women writing as men,” “men writing as women,” “unspecified (anonymous) writing as men,” “unspecified writing as women,” “men writing as men (byline) in the voice of a woman (woman narrator),” “men writing as unspecified (anonymous byline) in the voice of a woman,” “women writing as men (byline) in a voice of unspecified,” etc.—whatever categories are presented by title pages, prefaces, narrators’ discourses, and research into authorship attribution found.'[^6]

### Evaluating the Accuracy of the Model:

- Intersectional Analysis: Can the model's performance be analyzed from an intersectional lens to understand if it is consistent across different social identities? Are there any variations in accuracy based on different intersections of gender with race, class, or other factors?

Described in "Data Feminism" an investigation by ProPublica revealed that a widely used risk assessment algorithm created by Northpointe (now Equivant) in the United States exhibited racial disparities. White defendants were more likely to be mislabeled as low risk, while Black defendants were more frequently mislabeled as high risk. The algorithm relied on a questionnaire filled out by detainees, which indirectly included proxies for race due to the structural inequalities in US society. Factors such as single-parent households, school suspensions, and familial arrests, which are closely tied to racial realities, influenced the risk scores assigned by the algorithm.[^7]

Moreover, the algorithm also exhibited gender disparities. Women, on average, have lower rates of recidivism compared to men, yet the algorithm failed to account for this difference. Consequently, a high risk score for a woman was equivalent to a medium risk score for a man. These findings emphasize how machine learning algorithms not only predict the past but also reflect and amplify current social inequities.[^8]

The danger lies in the promotion of these biased findings as objective, which can significantly impact individuals and groups, restricting their future potential and perpetuating demographic divisions. The shortcomings of these algorithms underscore the need to critically evaluate their underlying data, assumptions, and potential biases to mitigate the perpetuation of systemic inequalities.

- Bias Detection: How can biases be detected and measured in the model's predictions? Are there any specific techniques or methodologies that can be employed to identify biases related to gender or other social factors?

In the work of SAFElab, a research lab at Columbia University led by scholar and social worker Desmond Patton, the lab utilized artificial intelligence to analyze how youth of color navigate violence both online and offline, specifically focusing on understanding and preventing gang violence in Chicago using Twitter data. They faced the challenge of not fully understanding the language and expressions used by young people, which led them to adopt a deeper approach to modeling social media data by incorporating culture, context, and nuance.[^9]

To achieve this, SAFElab engaged directly with the youth they aimed to study, hiring formerly gang-involved individuals as domain experts. These experts coded and categorized a subset of tweets, training a team of social work students to continue the coding process. Patton and doctoral student William Frey developed a "deep listening" method called the contextual analysis of social media, helping student coders overcome their own biases and grasp the intended meaning of each tweet. Subsequently, a machine learning classifier was trained to automatically label the tweets, enabling the categorization of the entire dataset.[^10]

The experiences and perspectives of Black men from Chicago were crucial in avoiding misinterpretation. By considering the context, the SAFElab model could identify that seemingly aggressive or violent tweets often contained references to song lyrics or cultural sharing rather than actual threats.

### Testing the Model:

- Dataset Generalization: How well does the model generalize to new, unseen data? Is there a need to test the model's performance on additional datasets that capture different perspectives or use cases to ensure its effectiveness across various contexts?

Brown and Mendenhall in their "Search for Zora," conceptualized "intermediate reading" as a bridge between close readings of texts in traditional research and distant readings associated with topic modeling. The researchers developed a tool that scans word-to-topic assignments in each document and generates a list of document titles with a specified percentage of words assigned to topics of interest. They described how "intermediate reading helped to provide a historical context to the key words. We argue that an intermediate reading helps us to better understand the themes and issues discussed around a Black women’s standpoint as well as the time period in which the texts were written and the author of the text."[^11]

Intermediate reading proved a satisfactory method for understanding texts within their historical and cultural contexts, particularly in relation to Black women's perspectives and experiences. It demonstrated the importance of combining computational approaches with close readings to gain nuanced insights into subjugated knowledge and marginalized voices.

- Transparency and Explainability: Can the model's decision-making process be transparent and explainable? How can the inner workings of the model be made accessible to ensure accountability and to address potential biases?

In "Authorship Attribution" Joula discusses Rudman's concerns regarding the competence of analysts and the potential impact of methodological problems on the accuracy of a study. He cites the example of the Mosteller/Wallace study on "The Federalist Papers." The study mentions a "little book of decisions" that contained critical items for the statistical analysis, but the contents of this book were not published and have been lost. The absence of this book prevents direct replication of the study and raises questions about the decisions made and their potential biases. The loss of this crucial information may hide invalidating evidence and raises doubts about the basis upon which decisions were made.[^12]

Juola postulates a set of ideals to improve models and their transparency, "For example, the ability to select the algorithms and features to use dynamically, based on the language, genre, size, of the available documents would be a nice feature to have. The ability automatically to detect areas of suspect validity (quotations, editorial insertions, phrases in foreign languages, footnotes, chapter headings and footings, etc.) would also be a nice, if almost certainly impractical, feature with current technologies."[^13]

### Conclusion

By considering these questions throughout the different stages of the text analysis and modeling process, feminist scholars can actively engage with the ethical implications, biases, and potential limitations of the classification analysis, leading to more informed and inclusive model development. As Guyan suggests in his work on reimagining identity characteristics as 'moving targets,'[^14] the feminist approach to computational text analysis must be ready and willing to surface unequal representations and strive for justice.

[^1]: Ahmed, S. 2017. Living a feminist life. Durham, NC: Duke University Press.
[^2]: Guyan, Kevin. Queer Data. 2022. 1st ed. Bloomsbury Publishing.
[^3]: Guyan, Kevin. Queer Data. 2022. 1st ed. Bloomsbury Publishing.
[^4]: D'Ignazio, Catherine, and Lauren Klein. "2. Collect, Analyze, Imagine, Teach." Data Feminism, 16 Mar. 2020, MIT Press, https://data-feminism.mitpress.mit.edu/pub/ei7cogfn/release/4.
[^5]: Mandell, Laura. "Gender and Cultural Analytics: Finding or Making Stereotypes?" Debates in the Digital Humanities 2019, edited by Matthew K. Gold, University of Minnesota Press, 2019, https://dhdebates.gc.cuny.edu/read/untitled-f2acf72c-a469-49d8-be35-67f9ac1e3a60/section/5d9c1b63-7b60-42dd-8cda-bde837f638f4#ch01.
[^6]: Mandell, Laura. "Gender and Cultural Analytics: Finding or Making Stereotypes?" Debates in the Digital Humanities 2019, edited by Matthew K. Gold, University of Minnesota Press, 2019, https://dhdebates.gc.cuny.edu/read/untitled-f2acf72c-a469-49d8-be35-67f9ac1e3a60/section/5d9c1b63-7b60-42dd-8cda-bde837f638f4#ch01.
[^7]: D'Ignazio, Catherine, and Lauren Klein. "2. Collect, Analyze, Imagine, Teach." Data Feminism, 16 Mar. 2020, MIT Press, https://data-feminism.mitpress.mit.edu/pub/ei7cogfn/release/4.
[^8]: D'Ignazio, Catherine, and Lauren Klein. "2. Collect, Analyze, Imagine, Teach." Data Feminism, 16 Mar. 2020, MIT Press, https://data-feminism.mitpress.mit.edu/pub/ei7cogfn/release/4.
[^9]: D’Ignazio, Catherine, and Lauren Klein. “6. the Numbers Don’t Speak for Themselves.” Data Feminism, 16 Mar. 2020, MIT Press,https://data-feminism.mitpress.mit.edu/pub/czq9dfs5/release/3.
[^10]: D’Ignazio, Catherine, and Lauren Klein. “6. the Numbers Don’t Speak for Themselves.” Data Feminism, 16 Mar. 2020, MIT Press,https://data-feminism.mitpress.mit.edu/pub/czq9dfs5/release/3.
[^11]: Nicole M. Brown, Ruby Mendenhall, Michael Black, Mark Van Moer, Karen Flynn, Malaika McKee, Assata Zerai, Ismini Lourentzou & ChengXiang Zhai (2019) In Search of Zora/When Metadata Isn’t Enough: Rescuing the Experiences of Black Women Through Statistical Modeling, Journal of Library Metadata, 19:3-4, 141-162, DOI: 10.1080/19386389.2019.1652967
[^12]: Juola, Patrick. “Authorship Attribution.” Foundations and Trends® in Information Retrieval, vol. 1, no. 3, 2007, pp. 233–334, https://doi.org/10.1561/1500000005.
[^13]: Juola, Patrick. “Authorship Attribution.” Foundations and Trends® in Information Retrieval, vol. 1, no. 3, 2007, pp. 233–334, https://doi.org/10.1561/1500000005.
[^14]: Guyan, Kevin. Queer Data. 2022. 1st ed. Bloomsbury Publishing.
