# CVQA Data Collection

We reach out to our network, as well as various NLP communities to contribute to this project as annotators. Annotators must be accustomed to the cultures they participate in, as well as familiar with the languages. Contributors with significant contributions will be rewarded as co-authors in this paper.

### Data Design

We mainly follow the categorization from OKVQA, with some adaptative modifications to fit the theme of our project. The categorization of OKVQA that we use are Vehicles and Transportation, Cooking and Food, People and Everyday Life, Sports and Recreation, Plants and Animals, Geography and History, and Brands and Products. Below is the statistic of our data.

![alt text](images/image_category.png)

Our data is a multilingual, multiple-choice locally-nuanced visual question-answering. The format is similar to commonly used visual QA data such as VQA or GQA. We gather CVQA based on the cultures of various locations. Moreover, for each location, the questions are collected based on their respective local languages. We group our CVQA dataset based on this location-language pair, rather than simply based on language or location only. 

### Annotation

For each subset, annotators were instructed to select images that depict diverse cultural aspects pertinent to their cultural backgrounds. We strongly recommend annotators to use their own personal images to avoid accidental data leaks. However, we note that this request is not always possible, therefore we also allow them to use images from our pre-defined sources, which we have confirmed is permissible to use.

The questions associated with each image were to be formulated such that they are answerable solely based on the image content and are culturally relevant. Each question was accompanied by one correct answer and three distractors that were plausible yet incorrect, thus forming a multiple-choice format.

Before commencing the question creation process, annotators were provided with examples of well-formulated questions and answers to guide their efforts. These examples helped clarify the level of specificity and cultural relevance expected in the annotations. Extensive guidelines and tutorials for selecting appropriate images and formulating questions were also provided to ensure uniformity and quality across the dataset. Finally The, the CVQA data creation is the validation. Each entry is validated by a different annotator.
