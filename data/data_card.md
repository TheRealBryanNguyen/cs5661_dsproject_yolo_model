# Dataset Name: Detecting AI vs Human-Generated Images (Acronym)

From Kaggle, this dataset will consist a mix of AI-generated images developed by DeepMedia and human captured images from the Shutterstock platform. With this dataset, we will be dealing with a binary classification problem aimed at determining what is real vs AI-generated. Our group plans on finding the best way to efficiently and effectively determine if a given image is AI-generated or not. By doing this, we can help Internet users gain a better understanding towards distinguishing between an image or art piece that is artificially generated or was created by a human. Potential use cases include tools for detecting misinformation and raising awareness on the the dangers of AI generated content. 


#### Dataset Link
<!-- info: Provide a link to the dataset: -->
<!-- width: half -->
Dataset Link: https://www.kaggle.com/competitions/detect-ai-vs-human-generated-images/data

#### Data Card Author(s)
<!-- info: Select **one role per** Data Card Author:

(Usage Note: Select the most appropriate choice to describe the author's role
in creating the Data Card.) -->
<!-- width: half -->
- **Bryan Nguyen, Team:** (Owner / Contributor)
- **Jesus Perez Arias, Team:** (Owner / Contributor)
- **Brian Pham, Team:** (Owner / Contributor)
- **Mohamad Saleh, Team:** (Owner / Contributor)
- **Kevin Trochez, Team:** (Owner / Contributor)
- **Joseph Comeaux, Team:** (Owner / Contributor)
-  **Runyi Yang, Team:** (Owner / Contributor)
- **Vidal Zazueta, Team:** (Owner / Contributor)
- **Jesse Gonzalez, Team:** (Owner / Contributor)
- **Alan Espinosa, Team:** (Owner / Contributor)


## Authorship
### Publishers
#### Publishing Organization(s)
<!-- scope: telescope -->
<!-- info: Provide the names of the institution or organization responsible
for publishing the dataset: -->
- Kaggle
- Shutterstock
- DeepMedia


#### Industry Type(s)
<!-- scope: periscope -->
<!-- info: Select **all applicable** industry types to which the publishing
organizations belong: -->
- Corporate - Tech

#### Contact Detail(s)
<!-- scope: microscope -->
<!-- info: Provide publisher contact details: -->
- **Publishing POC**: Alessandra Sala
- **Affiliation:** Kaggle / Google LLC
- **Website:** https://www.kaggle.com/competitions/detect-ai-vs-human-generated-images

### Dataset Owners
#### Team(s)
<!-- scope: telescope -->
<!-- info: Provide the names of the groups or team(s) that own the dataset: -->
Detect AI vs. Human-Generated Images Competition Team

#### Contact Detail(s)
<!-- scope: periscope -->
<!-- info: Provide pathways to contact dataset owners: -->
- **Dataset Owner(s):** Alessandra Sala (Owner), Manuela Jeyaraj (Editor), Toma Ijatomi (Editor), Margarita Pitsiani (Editor)
- **Affiliation:** Kaggle Competition
- **Website:** https://kaggle.com/competitions/detect-ai-vs-human-generated-images


#### Author(s)
<!-- scope: microscope -->
<!-- info: Provide the details of all authors associated with the dataset:

(Usage Note: Provide the affiliation and year if different from publishing
institutions or multiple affiliations.) -->
- Alessandra Sala, Dr., Nokia Bell Labs, 2025
- Manuela Jeyaraj, Editor, 2025
- Toma Ijatomi, Editor, 2025
- Margarita Pitsiani, Editor, 2025
- Shutterstock, Inc., Corporate Author, 2025
- DeepMedia, Corporate Author, 2025

### Funding Sources
#### Institution(s)
<!-- scope: telescope -->
<!-- info: Provide the names of the funding institution(s): -->
- Shutterstock
- DeepMedia
- 
#### Funding or Grant Summary(ies)
<!-- scope: periscope -->
<!-- width: full -->
<!-- info: Provide a short summary of programs or projects that may have funded
the creation, collection, or curation of the dataset.

Use additional notes to capture any other relevant information or
considerations. -->
*For example, Institution 1 and institution 2 jointly funded this dataset as a
part of the XYZ data program, funded by XYZ grant awarded by institution 3 for
the years YYYY-YYYY.*

DeepMedia and Shutterstock jointly funded this dataset as a part of the 2025 Women in AI competition hosted for Kaggle. First place for this competition would be awarded a $2,000. 

**Additional Notes:** Add here

## Dataset Overview
#### Data Subject(s)
<!-- scope: telescope -->
<!-- info: Select ***all applicable**** subjects contained the dataset: -->
- Non-Sensitive Data about people
- Data about places and objects
- Synthetically generated data


#### Dataset Snapshot
<!-- scope: periscope -->
<!-- info: Provide a snapshot of the dataset:<br><br>(Use the additional notes
to include relevant information, considerations, and links to table(s) with
more detailed breakdowns.) -->
Category | Data
--- | ---
Size of Dataset | 4.75 MB(csv) (~12 GB in images)
Number of Instances | 85490
Number of Fields | 3 (id, image, & label)
Labeled Classes | 2 (Real, AI-generated)
Number of Labels | 2
Average Labeles Per Instance | 1
Algorithmic Labels | Yes
Human Labels | Yes
Other Characteristics | N/A

**Above:** This dataset will include both AI-generated and real images. Our group will split the data and manually classify whether is AI or human generated. The dataset will consist of three fields: the id which is the unique identifier for the image, the image itself, and the label indicating the type of image. 


#### Content Description
<!-- scope: microscope -->
<!-- info: Provide a short description of the content in a data point: -->
Our dataset will consist of a wide range of images, including individuals, groups of people, builidings, roads, and inanimate objects. The coloring in these images can be black and white or color. 


### Sensitivity of Data
#### Sensitivity Type(s)
<!-- scope: telescope -->
<!-- info: Select ***all applicable*** data types present in the dataset: -->
- None


#### Field(s) with Sensitive Data
<!-- scope: periscope -->
<!-- info: List fields in the dataset that contain S/PII, and specify if their
collection was intentional or unintentional.


Use additional notes to capture any other relevant information or
considerations. -->
- N/A
**Intentional Collected Sensitive Data**
- N/A

**Unintentionally Collected Sensitive Data**
- N/A

#### Security and Privacy Handling
<!-- scope: microscope -->
<!-- info: Summarize the measures or steps to handle sensitive data in this
dataset.

Use additional notes to capture any other relevant information or
considerations. -->


The images gathered from Shutterstock follow all security and privacy regulations. The AI-generated data was created for the Kaggle competition thus there is no sensitive data that needs to be handled. 
**Method:** description

**Method:** N/A


#### Risk Type(s)
<!-- scope: telescope -->
<!-- info: Select **all applicable** risk types presenting from the
dataset: -->
- Indirect Risk

#### Supplemental Link(s)
<!-- scope: periscope -->
<!-- info: Provide link(s) for documentation pertaining to sensitive data in
the dataset: -->
**Kaggle Competition Page:** https://www.kaggle.com/competitions/detect-ai-vs-human-generated-images
**Shutterstock Terms of Use:** https://www.shutterstock.com/terms
**DeepMedia Website:** https://www.deepmedia.ai


#### Risk(s) and Mitigation(s)
<!-- scope: microscope -->
<!-- info: Summarize the steps taken to identify and mitigate risks from PII
or sensitive information.

Use additional notes to capture any other relevant information or
considerations. -->
Some real images will include people which can pose the risk of visual data being linked through facial recognition. 

**Risk type:** Indirect Risk + Mitigations: Shutterstock's + DeepMedia licensing terms 

### Dataset Version and Maintenance
#### Maintenance Status
<!-- scope: telescope -->
<!-- info: Select **one:** -->

**Limited Maintenance** - The data will not be updated,
but any technical issues will be
addressed.

#### Version Details
<!-- scope: periscope -->
<!-- info: Provide details about **this** version of the dataset: -->
**Current Version:** 1.0

**Last Updated:** 01/2025

**Release Date:** 01/2025

## Example of Data Points
#### Primary Data Modality
<!-- scope: telescope -->
<!-- info: Select **one**: -->
- Image Data


#### Sampling of Data Points
<!-- scope: periscope -->
<!-- info: Provide link(s) to data points or exploratory demos: -->
- Demo Link: https://www.kaggle.com/datasets/alessandrasala79/ai-vs-human-generated-dataset/data
- Typical Data Point Link: https://www.kaggle.com/datasets/alessandrasala79/ai-vs-human-generated-dataset/data


#### Data Fields
<!-- scope: microscope -->
<!-- info: List the fields in data points and their descriptions.

(Usage Note: Describe each field in a data point. Optionally use this to show
the example.) -->

Field Name | Field Value | Description
--- | --- | ---
id | 00158651c0f54532a3ed60fa49e709d9.jpg | Unique identifier for the image
image | jpg file | The actual image itself
label | real/ai | This is the field that our group is implementing to indicate whether it is real vs ai.

**Above:** Each observation from our dataset will include these three fields in our csv file. The original dataset will include id and image, where our group will manually apply the label field. 
**Additional Notes:** Add here

#### Typical Data Point
<!-- width: half -->
<!-- info: Provide an example of a typical data point and describe what makes
it typical.

**Use additional notes to capture any other relevant information or
considerations.** -->
A typical datapoint will include the image itself, its id, and the label depicting its classification. 

```
{'id': '000fe90b4fb14fca9d250167e77e3d10.jpg',
  'image': 'Image itself',
  'label': 'ai',
```

**Additional Notes:** Add here

#### Atypical Data Point
<!-- width: half -->
<!-- info: Provide an example of an outlier data point and describe what makes
it atypical.

**Use additional notes to capture any other relevant information or
considerations.** -->
The criteria for an atypical datapoint could be an image that is extremely hard to classify or an image that we're unable to depict. 

```
{'id': '0011c570133b4117b735ef0eafde3343.jpg',
  'image': 'Image itself',
  'label': '',
```

**Additional Notes:** Add here

## Motivations & Intentions
### Motivations
#### Purpose(s)
<!-- scope: telescope -->
<!-- info: Select **one**: -->
- Research

#### Domain(s) of Application
`Machine Learning`, `Computer Vision`, `Object Detection`.

#### Motivating Factor(s)

- Bringing diversity to AI imagery detection for YOLO and other ANN models
- Encouraging academics to take on the challenges of the evolving landscape of AI image creation and deepfakes.



### Intended Use
#### Dataset Use(s)

- Safe for research use
- Conditional use - some unsafe applications
- Only approved use
- Others (Kaggle Use)

#### Suitable Use Case(s)
<!-- scope: periscope -->
<!-- info: Summarize known suitable and intended use cases of this dataset.

Use additional notes to capture any specific patterns that readers should
look out for, or other relevant information or considerations. -->
**Suitable Use Case:** Summarize here. Include links where necessary.

**Suitable Use Case:** Summarize here. Include links where necessary.

**Suitable Use Case:** Summarize here. Include links where necessary.

**Additional Notes:** Add here

#### Unsuitable Use Case(s)
<!-- scope: microscope -->
<!-- info: Summarize known unsuitable and unintended use cases of this dataset.

Use additional notes to capture any specific patterns that readers should look
out for, or other relevant information or considerations. -->
**Unsuitable Use Case:** Summarize here. Include links where necessary.

**Unsuitable Use Case:** Summarize here. Include links where necessary.

**Unsuitable Use Case:** Summarize here. Include links where necessary.

**Additional Notes:** Add here

#### Research and Problem Space(s)
<!-- scope: periscope -->
<!-- info: Provide a description of the specific problem space that this
dataset intends to address. -->
Summarize here. Include any specific research questions.

#### Citation Guidelines
<!-- scope: microscope -->
<!-- info: Provide guidelines and steps for citing this dataset in research
and/or production.

Use additional notes to capture any specific patterns that readers should look
out for, or other relevant information or considerations. -->
**Guidelines & Steps:** Summarize here. Include links where necessary.

**BiBTeX:**
```
@article{kuznetsova2020open,
  title={The open images dataset v4},
  author={Kuznetsova, Alina and Rom, Hassan and Alldrin, and others},
  journal={International Journal of Computer Vision},
  volume={128},
  number={7},
  pages={1956--1981},
  year={2020},
  publisher={Springer}
}
```

**Additional Notes:** Add here

## Access, Rentention, & Wipeout
### Access
#### Access Type
<!-- scope: telescope -->
<!-- info: Select **one**: -->
- Internal - Unrestricted
- Internal - Restricted
- External - Open Access
- Others (please specify)

#### Documentation Link(s)
<!-- scope: periscope -->
<!-- info: Provide links that describe documentation to access this
dataset: -->
- Dataset Website URL
- GitHub URL

#### Prerequisite(s)

This dataset requires membership/an account on Kaggle to access the database: https://www.kaggle.com/competitions/detect-ai-vs-human-generated-images

- Read [Data Usage Policy]

#### Policy Link(s)
<!-- scope: periscope -->
<!-- info: Provide a link to the access policy: -->
- Direct download URL
- Other repository URL

Code to download data:
```
...
```

#### Access Control List(s)
<!-- scope: microscope -->
<!-- info: List and summarize any access control lists associated with this
dataset. Include links where necessary.

Use additional notes to capture any other information relevant to accessing
the dataset. -->
**Access Control List:** Write summary and notes here.

**Access Control List:** Write summary and notes here.

**Access Control List:** Write summary and notes here.

**Additional Notes:** Add here

### Retention
#### Duration
<!-- scope: periscope -->
<!-- info: Specify the duration for which this dataset can be retained: -->
Specify duration in days, months, or years.

#### Policy Summary
<!-- scope: microscope -->
<!-- info: Summarize the retention policy for this dataset. -->
**Retention Plan ID:** Write here

**Summary:** Write summary and notes here

#### Process Guide
<!-- scope: periscope -->
<!-- info: Summarize any requirements and related steps to retain the dataset.

Use additional notes to capture any other relevant information or
considerations. -->
For example:

This dataset compiles with [standard policy guidelines].

**Additional Notes:** Add here

#### Exception(s) and Exemption(s)
<!-- scope: microscope -->
<!-- info: Summarize any exceptions and related steps to retain the dataset.
Include links where necessary.

Use additional notes to capture any other relevant information or
considerations. -->
**Exemption Code:** `ANONYMOUS_DATA` /
`EMPLOYEE_DATA` / `PUBLIC_DATA` /
`INTERNAL_BUSINESS_DATA` /
`SIMULATED_TEST_DATA`

**Summary:** Write summary and notes here.

**Additional Notes:** Add here

### Wipeout and Deletion
#### Duration
<!-- scope: periscope -->
<!-- info: Specify the duration after which this dataset should be deleted or
wiped out: -->
Specify duration in days, months, or years.

#### Deletion Event Summary
<!-- scope: microscope -->
<!-- info: Summarize the sequence of events and allowable processing for data
deletion.

Use additional notes to capture any other relevant information or
considerations. -->
**Sequence of deletion and processing events:**

- Summarize first event here
- Summarize second event here
- Summarize third event here

**Additional Notes:** Add here

#### Acceptable Means of Deletion
<!-- scope: periscope -->
<!-- info: List the acceptable means of deletion: -->
- Write acceptable means of deletion
- Write acceptable means of deletion
- Write acceptable means of deletion

#### Post-Deletion Obligations
<!-- scope: microscope -->
<!-- info: Summarize the sequence of obligations after a deletion event.

**Use additional notes to capture any other relevant information or
considerations.** -->
**Sequence of post-deletion obligations:**

- Summarize first obligation here
- Summarize second obligation here
- Summarize third obligation here

**Additional Notes:** Add here

#### Operational Requirement(s)
<!-- scope: periscope -->
<!-- info: List any wipeout integration operational requirements: -->
**Wipeout Integration Operational Requirements:**

- Write first requirement here
- Write second requirement here
- Write third requirement here

#### Exceptions and Exemptions
<!-- scope: microscope -->
<!-- info: Summarize any exceptions and related steps to a deletion event.

**Use additional notes to capture any other relevant information or
considerations.** -->
**Policy Exception bug:** [bug]

**Summary:** Write summary and notes here

**Additional Notes:** Add here

## Provenance
### Collection
#### Method(s) Used
<!-- scope: telescope -->
<!-- info: Select **all applicable** methods used to collect data: -->
- API
- Artificially Generated
- Crowdsourced - Paid
- Crowdsourced - Volunteer
- Vendor Collection Efforts
- Scraped or Crawled
- Survey, forms, or polls
- Taken from other existing datasets
- Unknown
- To be determined
- Others (please specify)

#### Methodology Detail(s)
<!-- scope: periscope -->
<!-- info: Provide a description of each collection method used.

Use additional notes to capture any other relevant information or
considerations.

(Usage Note: Duplicate and complete the following for collection method
type.) -->
**Collection Type**

**Source:** Describe here. Include links where available.

**Platform:** [Platform Name], Describe platform here. Include links where relevant.

**Is this source considered sensitive or high-risk?** [Yes/No]

**Dates of Collection:** [MMM YYYY - MMM YYYY]

**Primary modality of collection data:**

*Usage Note: Select one for this collection type.*

- Image Data
- Text Data
- Tabular Data
- Audio Data
- Video Data
- Time Series
- Graph Data
- Geospatial Data
- Unknown
- Multimodal (please specify)
- Others (please specify)

**Update Frequency for collected data:**

*Usage Note: Select one for this collection type.*

- Yearly
- Quarterly
- Monthly
- Biweekly
- Weekly
- Daily
- Hourly
- Static
- Others (please specify)

**Additional Links for this collection:**

- [Access Policy]
- [Wipeout Policy]
- [Retention Policy]

**Additional Notes:** Add here

#### Source Description(s)
<!-- scope: microscope -->
<!-- info: Provide a description of each upstream source of data.

Use additional notes to capture any other relevant information or
considerations. -->
- **Source:** Describe here. Include links, data examples, metrics, visualizations where relevant.
- **Source:** Describe here. Include links, data examples, metrics, visualizations where relevant.
- **Source:** Describe here. Include links, data examples, metrics, visualizations where relevant.

**Additional Notes:** Add here

#### Collection Cadence
<!-- scope: telescope -->
<!-- info: Select **all applicable**: -->
**Static:** Data was collected once from single or multiple sources.

**Streamed:** Data is continuously acquired from single or multiple sources.

**Dynamic:** Data is updated regularly from single or multiple sources.

**Others:** Please specify

#### Data Integration
<!-- scope: periscope -->
<!-- info: List all fields collected from different sources, and specify if
they were included or excluded from the dataset.

Use additional notes to
capture any other relevant information or considerations.

(Usage Note: Duplicate and complete the following for each upstream
source.) -->
**Source**

**Included Fields**

Data fields that were collected and are included in the dataset.

Field Name | Description
--- | ---
Field Name | Describe here. Include links, data examples, metrics, visualizations where relevant.
Field Name | Describe here. Include links, data examples, metrics, visualizations where relevant.

**Additional Notes:** Add here

**Excluded Fields**

Data fields that were collected but are excluded from the dataset.

Field Name | Description
--- | ---
Field Name | Describe here. Include links, data examples, metrics, visualizations where relevant.
Field Name | Describe here. Include links, data examples, metrics, visualizations where relevant.

**Additional Notes:** Add here

#### Data Processing
<!-- scope: microscope -->
<!-- info: Summarize how data from different sources or methods aggregated,
processed, or connected.

Use additional notes to capture any other
relevant information or considerations.

(Usage Note: Duplicate and complete the following for each source OR
collection method.) -->
**Collection Method or Source**

**Description:** Describe here. Include links where relevant.

**Methods employed:** Describe here. Include links where relevant.

**Tools or libraries:** Describe here. Include links where relevant.

**Additional Notes:** Add here

### Collection Criteria
#### Data Selection
<!-- scope: telescope -->
<!-- info: Summarize the data selection criteria.

Use additional notes to capture any other relevant information or
considerations. -->
- **Collection Method of Source:** Summarize data selection criteria here. Include links where available.
- **Collection Method of Source:** Summarize data selection criteria here. Include links where available.
- **Collection Method of Source:** Summarize data selection criteria here. Include links where available.

**Additional Notes:** Add here

#### Data Inclusion
<!-- scope: periscope -->
<!-- info: Summarize the data inclusion criteria.

Use additional notes to capture any other relevant information or
considerations. -->
- **Collection Method of Source:** Summarize data inclusion criteria here. Include links where available.
- **Collection Method of Source:** Summarize data inclusion criteria here. Include links where available.
- **Collection Method of Source:** Summarize data inclusion criteria here. Include links where available.

**Additional Notes:** Add here

#### Data Exclusion
<!-- scope: microscope -->
<!-- info: Summarize the data exclusion criteria.

Use additional notes to capture any other relevant information or
considerations. -->
- **Collection Method of Source:** Summarize data exclusion criteria here. Include links where available.
- **Collection Method of Source:** Summarize data exclusion criteria here. Include links where available.
- **Collection Method of Source:** Summarize data exclusion criteria here. Include links where available.

**Additional Notes:** Add here

### Relationship to Source
#### Use & Utility(ies)
<!-- scope: telescope -->
<!-- info: Describe how the resulting dataset is aligned with the purposes,
motivations, or intended use of the upstream source(s).

Use additional notes to capture any other relevant information or
considerations.

(Usage Note: Duplicate and complete the following for each source type.) -->
- **Source Type:** Summarize here. Include links where available.
- **Source Type:** Summarize here. Include links where available.
- **Source Type:** Summarize here. Include links where available.

**Additional Notes:** Add here

#### Benefit and Value(s)
<!-- scope: periscope -->
<!-- info: Summarize the benefits of the resulting dataset to its consumers,
compared to the upstream source(s).

Use additional notes to capture any other relevant information or
considerations.

(Usage Note: Duplicate and complete the following for each source type.) -->
- **Source Type:** Summarize here. Include links where available.
- **Source Type:** Summarize here. Include links where available.
- **Source Type:** Summarize here. Include links where available.

**Additional Notes:** Add here

#### Limitation(s) and Trade-Off(s)
<!-- scope: microscope -->
<!-- info: What are the limitations of the resulting dataset to its consumers,
compared to the upstream source(s)?

Break down by source type.<br><br>(Usage Note: Duplicate and complete the
following for each source type.) -->
- **Source Type:** Summarize here. Include links where available.
- **Source Type:** Summarize here. Include links where available.
- **Source Type:** Summarize here. Include links where available.

### Version and Maintenance
<!-- info: Fill this next row if this is not the first version of the dataset,
and there is no data card available for the first version -->
#### First Version
<!-- scope: periscope -->
<!-- info: Provide a **basic description of the first version** of this
dataset. -->
- **Release date:** MM/YYYY
- **Link to dataset:** [Dataset Name + Version]
- **Status:** [Select one: Actively Maintained/Limited Maintenance/Deprecated]
- **Size of Dataset:** 123 MB
- **Number of Instances:** 123456

#### Note(s) and Caveat(s)
<!-- scope: microscope -->
<!-- info: Summarize the caveats or nuances of the first version of this
dataset that may affect the use of the current version.

Use additional notes to capture any other relevant information or
considerations. -->
Summarize here. Include links where available.

**Additional Notes:** Add here

#### Cadence
<!-- scope: telescope -->
<!-- info: Select **one**: -->
- Yearly
- Quarterly
- Monthly
- Biweekly
- Weekly
- Daily
- Hourly
- Static
- Others (please specify)

#### Last and Next Update(s)
<!-- scope: periscope -->
<!-- info: Please describe the update schedule: -->
- **Date of last update:** DD/MM/YYYY
- **Total data points affected:** 12345
- **Data points updated:** 12345
- **Data points added:** 12345
- **Data points removed:** 12345
- **Date of next update:** DD/MM/YYYY

#### Changes on Update(s)
<!-- scope: microscope -->
<!-- info: Summarize the changes that occur when the dataset is refreshed.

Use additional notes to capture any other relevant information or
considerations.

(Usage Note: Duplicate and complete the following for each source type.) -->
- **Source Type:** Summarize here. Include links where available.
- **Source Type:** Summarize here. Include links where available.
- **Source Type:** Summarize here. Include links where available.

**Additional Notes:** Add here

## Human and Other Sensitive Attributes
#### Sensitive Human Attribute(s)
<!-- scope: telescope -->
<!-- info: Select **all attributes** that are represented (directly or
indirectly) in the dataset. -->
- Gender
- Socio-economic status
- Geography
- Language
- Age
- Culture
- Experience or Seniority
- Others (please specify)

#### Intentionality
<!-- scope: periscope -->
<!-- info: List fields in the dataset that contain human attributes, and
specify if their collection was intentional or unintentional.

Use additional notes to capture any other relevant information or
considerations. -->
**Intentionally Collected Attributes**

Human attributes were labeled or collected as a part of the dataset creation
process.

Field Name | Description
--- | ---
Field Name | Human Attributed Collected
Field Name | Human Attributed Collected

**Additional Notes:** Add here

**Unintentionally Collected Attributes**

Human attributes were not explicitly collected as a part of the dataset
creation process but can be inferred using additional methods.

Field Name | Description
--- | ---
Field Name | Human Attributed Collected
Field Name | Human Attributed Collected

**Additional Notes:** Add here

#### Rationale
<!-- scope: microscope -->
<!-- info: Describe the motivation, rationale, considerations or approaches
that caused this dataset to include the indicated human attributes.

Summarize why or how this might affect the use of the dataset. -->
Summarize here. Include links, table, and media as relevant.

#### Source(s)
<!-- scope: periscope -->
<!-- info: List the sources of the human attributes.

Use additional notes to capture any other relevant information or
considerations. -->
- **Human Attribute:** Sources
- **Human Attribute:** Sources
- **Human Attribute:** Sources

**Additional Notes:** Add here

#### Methodology Detail(s)
<!-- scope: microscope -->
<!-- info: Describe the methods used to collect human attributes in the
dataset.

Use additional notes to capture any other relevant information or
considerations.

(Usage Note: Duplicate and complete the following for each human
attribute.) -->

**Human Attribute Method:** Describe the collection method here. Include links where necessary

**Collection task:** Describe the task here. Include links where necessary

**Platforms, tools, or libraries:**

- [Platform, tools, or libraries]: Write description here
- [Platform, tools, or libraries]: Write description here
- [Platform, tools, or libraries]: Write description here

**Additional Notes:** Add here

#### Distribution(s)
<!-- width: full -->
<!-- info: Provide basic descriptive statistics for each human attribute,
noting key takeaways in the caption.

Use additional notes to capture any other relevant information or
considerations.

(Usage Note: Duplicate and complete the following for each human
attribute.) -->
Human Attribute | Label or Class | Label or Class | Label or Class | Label or Class
--- | --- | --- | --- | ---
Count | 123456 | 123456 | 123456 | 123456
[Statistic] | 123456 | 123456 | 123456 | 123456
[Statistic] | 123456 | 123456 | 123456 | 123456
[Statistic] | 123456 | 123456 | 123456 | 123456

**Above:** Provide a caption for the above table or visualization.
**Additional Notes:** Add here

#### Known Correlations
<!-- scope: periscope -->
<!-- info: Describe any known correlations with the indicated sensitive
attributes in this dataset.

Use additional notes to capture any other relevant information or
considerations.

(Usage Note: Duplicate for each known correlation.) -->
[`field_name`, `field_name`]

**Description:** Summarize here. Include visualizations, metrics, or links
where necessary.

**Impact on dataset use:** Summarize here. Include visualizations, metrics, or
links where necessary.

**Additional Notes:** add here

#### Risk(s) and Mitigation(s)
<!-- scope: microscope -->
<!-- info: Summarize systemic or residual risks, performance expectations,
trade-offs and caveats because of human attributes in this dataset.

Use additional notes to capture any other relevant information or
considerations.

Usage Note: Duplicate and complete the following for each human attribute. -->
**Human Attribute**

Summarize here. Include links and metrics where applicable.

**Risk type:** [Description + Mitigations]

**Risk type:** [Description + Mitigations]

**Risk type:** [Description + Mitigations]

**Trade-offs, caveats, & other considerations:** Summarize here. Include
visualizations, metrics, or links where necessary.

**Additional Notes:** Add here

## Extended Use
### Use with Other Data
#### Safety Level
<!-- scope: telescope -->
<!-- info: Select **one**: -->
- Safe to use with other data
- Conditionally safe to use with other data
- Should not be used with other data
- Unknown
- Others (please specify)

#### Known Safe Dataset(s) or Data Type(s)
<!-- scope: periscope -->
<!-- info: List the known datasets or data types and corresponding
transformations that **are safe to join or aggregate** this dataset with. -->
**Dataset or Data Type:** Summarize here. Include visualizations, metrics,
or links where necessary.

**Dataset or Data Type:** Summarize here. Include visualizations, metrics,
or links where necessary.

**Dataset or Data Type:** Summarize here. Include visualizations, metrics,
or links where necessary.

#### Best Practices
<!-- scope: microscope -->
<!-- info: Summarize best practices for using this dataset with other datasets
or data types.

Use additional notes to capture any other relevant information or
considerations. -->
Summarize here. Include visualizations, metrics, demonstrative examples,
or links where necessary.

**Additional Notes:** Add here

#### Known Unsafe Dataset(s) or Data Type(s)
<!-- scope: periscope -->
<!-- info: Fill this out if you selected "Conditionally safe to use with other
datasets" or "Should not be used with other datasets":

List the known datasets or data types and corresponding transformations that
are **unsafe to join or aggregate** with this dataset. -->
**Dataset or Data Type:** Summarize here. Include visualizations, metrics,
or links where necessary.

**Dataset or Data Type:** Summarize here. Include visualizations, metrics,
or links where necessary.

**Dataset or Data Type:** Summarize here. Include visualizations, metrics,
or links where necessary.

#### Limitation(s) and Recommendation(s)
<!-- scope: microscope -->
<!-- info: Fill this out if you selected "Conditionally safe to use with
other datasets" or "Should not be used with
other datasets":

Summarize limitations of the dataset that introduce foreseeable risks when the
dataset is conjoined with other datasets.

Use additional notes to capture any other relevant information or
considerations. -->
Summarize here. Include links and metrics where applicable.

**Limitation type:** Dataset or data type, description and recommendation.

**Limitation type:** Dataset or data type, description and recommendation.

**Limitation type:** Dataset or data type, description and recommendation.

**Additional Notes:** Add here

### Forking & Sampling
#### Safety Level
<!-- scope: telescope -->
<!-- info: Select **one**: -->
- Safe to form and/or sample
- Conditionally safe to fork and/or sample
- Should not be forked and/or sampled
- Unknown
- Others (please specify)

#### Acceptable Sampling Method(s)
<!-- scope: periscope -->
<!-- info: Select **all applicable** acceptable methods to sample this
dataset: -->
- Cluster Sampling
- Haphazard Sampling
- Multi-stage sampling
- Random Sampling
- Retrospective Sampling
- Stratified Sampling
- Systematic Sampling
- Weighted Sampling
- Unknown
- Unsampled
- Others (please specify)

#### Best Practice(s)
<!-- scope: microscope -->
<!-- info: Summarize the best practices for forking or sampling this dataset.

Use additional notes to capture any other relevant information or
considerations. -->
Summarize here. Include links, figures, and demonstrative examples where
available.

**Additional Notes:** Add here

#### Risk(s) and Mitigation(s)
<!-- scope: periscope -->
<!-- info: Fill this out if you selected "Conditionally safe to fork and/or
sample" or "Should not be forked and/or sampled":

Summarize known or residual risks associated with forking and sampling methods
when applied to the dataset.

Use additional notes to capture any other
relevant information or considerations. -->
Summarize here. Include links and metrics where applicable.

**Risk Type:** [Description + Mitigations]

**Risk Type:** [Description + Mitigations]

**Risk Type:** [Description + Mitigations]

**Additional Notes:** Add here

#### Limitation(s) and Recommendation(s)
<!-- scope: microscope -->
<!-- info: Fill this out if you selected "Conditionally safe to fork and/or
sample" or "Should not be forked and/or sample":

Summarize the limitations that the dataset introduces when forking
or sampling the dataset and corresponding recommendations.

Use additional notes to capture any other relevant information or
considerations. -->
Summarize here. Include links and metrics where applicable.

**Limitation Type:** [Description + Recommendation]

**Limitation Type:** [Description + Recommendation]

**Limitation Type:** [Description + Recommendation]

**Additional Notes:** Add here

### Use in ML or AI Systems
#### Dataset Use(s)
<!-- scope: telescope -->
<!-- info: Select **all applicable** -->
- Training
- Testing
- Validation
- Development or Production Use
- Fine Tuning
- Others (please specify)

#### Notable Feature(s)
<!-- scope: periscope -->
<!-- info: Describe any notable feature distributions or relationships between
individual instances made explicit.

Include links to servers where readers can explore the data on their own. -->

**Exploration Demo:** [Link to server or demo.]

**Notable Field Name:** Describe here. Include links, data examples, metrics,
visualizations where relevant.

**Above:** Provide a caption for the above table or visualization.

**Additional Notes:** Add here

#### Usage Guideline(s)
<!-- scope: microscope -->
<!-- info: Summarize usage guidelines or policies that consumers should be
aware of.

Use additional notes to capture any other relevant information or
considerations. -->
**Usage Guidelines:** Summarize here. Include links where necessary.

**Approval Steps:** Summarize here. Include links where necessary.

**Reviewer:** Provide the name of a reviewer for publications referencing
this dataset.

**Additional Notes:** Add here

#### Distribution(s)
<!-- scope: periscope -->
<!-- info: Describe the recommended splits and corresponding criteria.

Use additional notes to capture any other
relevant information or considerations. -->

Set | Number of data points
--- | ---
Train | 62,563
Test | 62,563
Validation | 62,563
Dev | 62,563

**Above:** Provide a caption for the above table or visualization.

**Additional Notes:** Add here

#### Known Correlation(s)
<!-- scope: microscope -->
<!-- info: Summarize any known correlations with
the indicated features in this dataset.

Use additional notes to capture any other
relevant information or considerations.

(Usage Note: Duplicate for each known
correlation.) -->
`field_name`, `field_name`

**Description:** Summarize here. Include
visualizations, metrics, or links where
necessary.

**Impact on dataset use:** Summarize here.
Include visualizations, metrics, or links
where necessary.

**Risks from correlation:** Summarize here.
Include recommended mitigative steps if
available.

**Additional Notes:** Add here

#### Split Statistics
<!-- scope: periscope -->
<!-- width: full -->
<!-- info: Provide the sizes of each split. As appropriate, provide any
descriptive statistics for features. -->

Statistic | Train | Test | Valid | Dev
--- | --- | --- | --- | ---
Count | 123456 | 123456 | 123456 | 123456
Descriptive Statistic | 123456 | 123456 | 123456 | 123456
Descriptive Statistic | 123456 | 123456 | 123456 | 123456
Descriptive Statistic | 123456 | 123456 | 123456 | 123456

**Above:** Caption for table above.

## Transformations
<!-- info: Fill this section if any transformations were applied in the
creation of your dataset. -->
### Synopsis
#### Transformation(s) Applied
<!-- scope: telescope -->
<!-- info: Select **all applicable** transformations
that were applied to the dataset. -->
- Anomaly Detection
- Cleaning Mismatched Values
- Cleaning Missing Values
- Converting Data Types
- Data Aggregation
- Dimensionality Reduction
- Joining Input Sources
- Redaction or Anonymization
- Others (Please specify)

#### Field(s) Transformed
<!-- scope: periscope -->
<!-- info: Provide the fields in the dataset that
were transformed.

Use additional notes to capture any
other relevant information or
considerations.

(Usage Note: Duplicate and complete
the following for each transformation
type applied. Include the data types to
which fields were transformed.) -->
**Transformation Type**

Field Name | Source & Target
--- | ---
Field Name | Source Field: Target Field
Field Name | Source Field: Target Field
... | ...

**Additional Notes:** Add here

#### Library(ies) and Method(s) Used
<!-- scope: microscope -->
<!-- info: Provide a description of the methods
used to transform or process the
dataset.

Use additional notes to capture any
other relevant information or
considerations.

(Usage Note: Duplicate and complete
the following for each transformation
type applied.) -->
**Transformation Type**

**Method:** Describe the transformation
method here. Include links where
necessary.

**Platforms, tools, or libraries:**
- Platform, tool, or library: Write description here
- Platform, tool, or library: Write description here
- Platform, tool, or library: Write description here

**Transformation Results:** Provide
results, outcomes, and actions taken
because of the transformations. Include
visualizations where available.

**Additional Notes:** Add here

### Breakdown of Transformations
<!-- info: Fill out relevant rows. -->
#### Cleaning Missing Value(s)
<!-- scope: telescope -->
<!-- info: Which fields in the data were missing
values? How many? -->
Summarize here. Include links where available.

**Field Name:** Count or description

**Field Name:** Count or description

**Field Name:** Count or description

#### Method(s) Used
<!-- scope: periscope -->
<!-- info: How were missing values cleaned?
What other choices were considered? -->
Summarize here. Include links where necessary.

**Platforms, tools, or libraries**

- Platform, tool, or library: Write description here
- Platform, tool, or library: Write description here
- Platform, tool, or library: Write description here

#### Comparative Summary
<!-- scope: microscope -->
<!-- info: Why were missing values cleaned using
this method (over others)? Provide
comparative charts showing before
and after missing values were cleaned. -->
Summarize here. Include links, tables, visualizations where available.

**Field Name** | **Diff**
--- | ---
Field Name | Before: After
Field Name | Before: After
... | ...

**Above:** Provide a caption for the above table or visualization.

**Additional Notes:** Add here

#### Residual & Other Risk(s)
<!-- scope: telescope -->
<!-- info: What risks were introduced because of
this transformation? Which risks were
mitigated? -->
Summarize here. Include links and metrics where applicable.

- **Risk Type:** Description + Mitigations
- **Risk Type:** Description + Mitigations
- **Risk Type:** Description + Mitigations

#### Human Oversight Measure(s)
<!-- scope: periscope -->
<!-- info: What human oversight measures,
including additional testing,
investigations and approvals were
taken due to this transformation? -->
Summarize here. Include links where available.

#### Additional Considerations
<!-- scope: microscope -->
<!-- info: What additional considerations were
made? -->
Summarize here. Include links where available.

#### Cleaning Mismatched Value(s)
<!-- scope: telescope -->
<!-- info: Which fields in the data were corrected
for mismatched values? -->
Summarize here. Include links where available.

**Field Name:** Count or Description

**Field Name:** Count or Description

**Field Name:** Count or Description

#### Method(s) Used
<!-- scope: periscope -->
<!-- info: How were incorrect or mismatched
values cleaned? What other choices
were considered? -->
Summarize here. Include links where available.

#### Comparative Summary
<!-- scope: microscope -->
<!-- info: Why were incorrect or mismatched
values cleaned using this method (over
others)? Provide a comparative
analysis demonstrating before and
after values were cleaned. -->
Summarize here. Include links where available.

**Field Name** | **Diff**
--- | ---
Field Name | Before: After
Field Name | Before: After
... | ...

**Above:** Provide a caption for the above table or visualization.

**Additional Notes:** Add here

#### Residual & Other Risk(s)
<!-- scope: telescope -->
<!-- info: What risks were introduced because of
this transformation? Which risks were
mitigated? -->
Summarize here. Include links and metrics where applicable.

**Risk Type:** Description + Mitigations

**Risk Type:** Description + Mitigations

**Risk Type:** Description + Mitigations

#### Human Oversight Measure(s)
<!-- scope: periscope -->
<!-- info: What human oversight measures,
including additional testing,
investigations and approvals were
taken due to this transformation? -->
Summarize here. Include links where available.

#### Additional Considerations
<!-- scope: microscope -->
<!-- info: What additional considerations were made? -->
Summarize here. Include links where available.

#### Anomalies
<!-- scope: telescope -->
<!-- info: How many anomalies or outliers were
detected?
If at all, how were detected anomalies
or outliers handled?
Why or why not? -->
Summarize here. Include links where available.

**Field Name:** Count or Description

**Field Name:** Count or Description

**Field Name:** Count or Description

#### Method(s) Used
<!-- scope: periscope -->
<!-- info: What methods were used to detect
anomalies or outliers? -->
Summarize here. Include links where necessary.

**Platforms, tools, or libraries**

- Platform, tool, or library: Write description here
- Platform, tool, or library: Write description here
- Platform, tool, or library: Write description here

#### Comparative Summary
<!-- scope: microscope -->
<!-- info: Provide a comparative analysis
demonstrating before and after
anomaly handling measures. -->
Summarize here. Include links, tables, visualizations where available.

**Field Name** | **Diff**
--- | ---
Field Name | Before: After
Field Name | Before: After
... | ...

**Above:** Provide a caption for the above table or visualization.

**Additional Notes:** Add here

#### Residual & Other Risk(s)
<!-- scope: telescope -->
<!-- info: What risks were introduced because of
this transformation? Which risks were
mitigated? -->
Summarize here. Include links and metrics where applicable.

**Risk Type:** Description + Mitigations

**Risk Type:** Description + Mitigations

**Risk Type:** Description + Mitigations

#### Human Oversight Measure(s)
<!-- scope: periscope -->
<!-- info: What human oversight measures,
including additional testing,
investigations and approvals were
taken due to this transformation? -->
Summarize here. Include links where available.

#### Additional Considerations
<!-- scope: microscope -->
<!-- info: What additional considerations were made? -->
Summarize here. Include links where available.

#### Dimensionality Reduction
<!-- scope: telescope -->
<!-- info: How many original features were
collected and how many dimensions
were reduced? -->
Summarize here. Include links where available.

**Field Name:** Count or Description

**Field Name:** Count or Description

**Field Name:** Count or Description

#### Method(s) Used
<!-- scope: periscope -->
<!-- info: What methods were used to reduce the
dimensionality of the data? What other
choices were considered? -->
Summarize here. Include links where
necessary.

**Platforms, tools, or libraries**

- Platform, tool, or library: Write description here
- Platform, tool, or library: Write description here
- Platform, tool, or library: Write description here

#### Comparative Summary
<!-- scope: microscope -->
<!-- info: Why were features reduced using this
method (over others)? Provide
comparative charts showing before
and after dimensionality reduction
processes. -->
Summarize here. Include links, tables, visualizations where available.

**Field Name** | **Diff**
--- | ---
Field Name | Before: After
Field Name | Before: After
... | ...

**Above:** Provide a caption for the above table or visualization.

**Additional Notes:** Add here

#### Residual & Other Risks
<!-- scope: telescope -->
<!-- info: What risks were introduced because of
this transformation? Which risks were
mitigated? -->
Summarize here. Include links and metrics where applicable.

**Risk Type:** Description + Mitigations

**Risk Type:** Description + Mitigations

**Risk Type:** Description + Mitigations

#### Human Oversight Measure(s)
<!-- scope: periscope -->
<!-- info: What human oversight measures,
including additional testing,
investigations and approvals were
taken due to this transformation? -->
Summarize here. Include links where available.

#### Additional Considerations
<!-- scope: microscope -->
<!-- info: What additional considerations were made? -->
Summarize here. Include links where available.

#### Joining Input Sources
<!-- scope: telescope -->
<!-- info: What were the distinct input sources that were joined? -->
Summarize here. Include links where available.

**Field Name:** Count or Description

**Field Name:** Count or Description

**Field Name:** Count or Description

#### Method(s) Used
<!-- scope: periscope -->
<!-- info: What are the shared columns of fields used to join these
sources? -->
Summarize here. Include links where necessary.

**Platforms, tools, or libraries**

- Platform, tool, or library: Write description here
- Platform, tool, or library: Write description here
- Platform, tool, or library: Write description here

#### Comparative Summary
<!-- scope: microscope -->
<!-- info: Why were features joined using this
method over others?

Provide comparative charts showing
before and after dimensionality
reduction processes. -->
Summarize here. Include links, tables, visualizations where available.

**Field Name** | **Diff**
--- | ---
Field Name | Before: After
Field Name | Before: After
... | ...

**Above:** Provide a caption for the above table or visualization.

**Additional Notes:** Add here

#### Residual & Other Risk(s)
<!-- scope: telescope -->
<!-- info: What risks were introduced because of
this transformation? Which risks were
mitigated? -->
Summarize here. Include links and metrics where applicable.

**Risk Type:** Description + Mitigations

**Risk Type:** Description + Mitigations

**Risk Type:** Description + Mitigations

#### Human Oversight Measure(s)
<!-- scope: periscope -->
<!-- info: What human oversight measures,
including additional testing,
investigations and approvals were
taken due to this transformation? -->
Summarize here. Include links where
available.

#### Additional Considerations
<!-- scope: microscope -->
<!-- info: What additional considerations were
made? -->
Summarize here. Include links where
available.

#### Redaction or Anonymization
<!-- scope: telescope -->
<!-- info: Which features were redacted or
anonymized? -->
Summarize here. Include links where available.

**Field Name:** Count or Description

**Field Name:** Count or Description

**Field Name:** Count or Description

#### Method(s) Used
<!-- scope: periscope -->
<!-- info: What methods were used to redact or
anonymize data? -->
Summarize here. Include links where necessary.

**Platforms, tools, or libraries**

- Platform, tool, or library: Write description here
- Platform, tool, or library: Write description here
- Platform, tool, or library: Write description here

#### Comparative Summary
<!-- scope: microscope -->
<!-- info: Why was data redacted or anonymized
using this method over others? Provide
comparative charts showing before
and after redaction or anonymization
process. -->
Summarize here. Include links, tables, visualizations where available.

**Field Name** | **Diff**
--- | ---
Field Name | Before: After
Field Name | Before: After
... | ...

**Above:** Provide a caption for the above table or visualization.

**Additional Notes:** Add here

#### Residual & Other Risk(s)
<!-- scope: telescope -->
<!-- info: What risks were introduced because of
this transformation? Which risks were
mitigated? -->
Summarize here. Include links and metrics where applicable.

**Risk Type:** Description + Mitigations

**Risk Type:** Description + Mitigations

**Risk Type:** Description + Mitigations

#### Human Oversight Measure(s)
<!-- scope: periscope -->
<!-- info: What human oversight measures,
including additional testing,
investigations and approvals were
taken due to this transformation? -->
Summarize here. Include links where available.

#### Additional Considerations
<!-- scope: microscope -->
<!-- info: What additional considerations were
made? -->
Summarize here. Include links where available.

#### Others (Please Specify)
<!-- scope: telescope -->
<!-- info: What was done? Which features or
fields were affected? -->
Summarize here. Include links where available.

**Field Name:** Count or Description

**Field Name:** Count or Description

**Field Name:** Count or Description

#### Method(s) Used
<!-- scope: periscope -->
<!-- info: What method were used? -->
Summarize here. Include links where necessary.

**Platforms, tools, or libraries**

- Platform, tool, or library: Write description here
- Platform, tool, or library: Write description here
- Platform, tool, or library: Write description here

#### Comparative Summary
<!-- scope: microscope -->
<!-- info: Why was this method used over
others? Provide comparative charts
showing before and after this
transformation. -->
Summarize here. Include links, tables, visualizations where available.

**Field Name** | **Diff**
--- | ---
Field Name | Before: After
Field Name | Before: After
... | ...

**Above:** Provide a caption for the above table or visualization.

**Additional Notes:** Add here

#### Residual & Other Risk(s)
<!-- scope: telescope -->
<!-- info: What risks were introduced because of
this transformation? Which risks were
mitigated? -->
Summarize here. Include links and metrics where applicable.

**Risk type:** [Description + Mitigations]

**Risk type:** [Description + Mitigations]

**Risk type:** [Description + Mitigations]

#### Human Oversight Measure(s)
<!-- scope: periscope -->
<!-- info: What human oversight measures,
including additional testing,
investigations and approvals were
taken due to this transformation? -->
Summarize here. Include links where available.

#### Additional Considerations
<!-- scope: microscope -->
<!-- info: What additional considerations were made? -->
Summarize here. Include links where available.

## Annotations & Labeling
<!-- info: Fill this section if any human or algorithmic annotation tasks were
performed in the creation of your dataset. -->
#### Annotation Workforce Type
<!-- scope: telescope -->
<!-- info: Select **all applicable** annotation
workforce types or methods used
to annotate the dataset: -->
- Annotation Target in Data
- Machine-Generated
- Annotations
- Human Annotations (Expert)
- Human Annotations (Non-Expert)
- Human Annotations (Employees)
- Human Annotations (Contractors)
- Human Annotations (Crowdsourcing)
- Human Annotations (Outsourced / Managed)
- Teams
- Unlabeled
- Others (Please specify)

#### Annotation Characteristic(s)
<!-- scope: periscope -->
<!-- info: Describe relevant characteristics of annotations
as indicated. For quality metrics, consider
including accuracy, consensus accuracy, IRR,
XRR at the appropriate granularity (e.g. across
dataset, by annotator, by annotation, etc.).

Use additional notes to capture any other
relevant information or considerations.

(Usage Note: Duplicate and complete the
following for each annotation type.) -->
**Annotation Type** | **Number**
--- | ---
Number of unique annotations | 123456789
Total number of annotations | 123456789
Average annotations per example | 123456789
Number of annotators per example | 123456789
[Quality metric per granuality] | 123456789
[Quality metric per granuality] | 123456789
[Quality metric per granuality] | 123456789

**Above:** Provide a caption for the above table or visualization.

**Additional Notes:** Add here

#### Annotation Description(s)
<!-- scope: microscope -->
<!-- info: Provide descriptions of the annotations
applied to the dataset. Include links
and indicate platforms, tools or libraries
used wherever possible.

Use additional notes to capture any
other relevant information or
considerations.

(Usage Note: Duplicate and complete
the following for each annotation
type.) -->
**(Annotation Type)**

**Description:** Description of annotations (labels, ratings) produced.
Include how this was created or authored.

**Link:** Relevant URL link.

**Platforms, tools, or libraries:**

- Platform, tool, or library: Write description here
- Platform, tool, or library: Write description here
- Platform, tool, or library: Write description here

**Additional Notes:** Add here

#### Annotation Distribution(s)
<!-- scope: periscope -->
<!-- info: Provide a distribution of annotations for each
annotation or class of annotations using the
format below.

Use additional notes to capture any other
relevant information or considerations.

(Usage Note: Duplicate and complete the
following for each annotation type.) -->
**Annotation Type** | **Number**
--- | ---
Annotations (or Class) | 12345 (20%)
Annotations (or Class) | 12345 (20%)
Annotations (or Class) | 12345 (20%)
Annotations (or Class) | 12345 (20%)
Annotations (or Class) | 12345 (20%)

**Above:** Provide a caption for the above table or visualization.

**Additional Notes:** Add here

#### Annotation Task(s)
<!-- scope: microscope -->
<!-- info: Summarize each task type associated
with annotations in the dataset.

Use additional notes to capture any
other relevant information or
considerations.

(Usage Note: Duplicate and complete
the following for each task type.) -->
**(Task Type)**

**Task description:** Summarize here. Include links if available.

**Task instructions:** Summarize here. Include links if available.

**Methods used:** Summarize here. Include links if available.

**Inter-rater adjudication policy:** Summarize here. Include links if
available.

**Golden questions:** Summarize here. Include links if available.

**Additional notes:** Add here

### Human Annotators
<!-- info: Fill this section if human annotators were used. -->
#### Annotator Description(s)
<!-- scope: periscope -->
<!-- info: Provide a brief description for each annotator
pool performing the human annotation task.

Use additional notes to capture any other
relevant information or considerations.

(Usage Note: Duplicate and complete the
following for each annotation type.) -->
**(Annotation Type)**

**Task type:** Summarize here. Include links if available.

**Number of unique annotators:** Summarize here. Include links if available.

**Expertise of annotators:** Summarize here. Include links if available.

**Description of annotators:** Summarize here. Include links if available.

**Language distribution of annotators:** Summarize here. Include links if
available.

**Geographic distribution of annotators:** Summarize here. Include links if
available.

**Summary of annotation instructions:** Summarize here. Include links if
available.

**Summary of gold questions:** Summarize here. Include links if available.

**Annotation platforms:** Summarize here. Include links if available.

**Additional Notes:** Add here

#### Annotator Task(s)
<!-- scope: microscope -->
<!-- info: Provide a brief description for each
annotator pool performing the human
annotation task.

Use additional notes to capture any
other relevant information or
considerations.

(Usage Note: Duplicate and complete
the following for each annotation
type.) -->
**(Task Type)**

**Task description:** Summarize here. Include links if available.

**Task instructions:** Summarize here. Include links if available.

**Methods used:** Summarize here. Include links if available.

**Inter-rater adjudication policy:** Summarize here. Include links if
available.

**Golden questions:** Summarize here. Include links if available.

**Additional notes:** Add here

#### Language(s)
<!-- scope: telescope -->
<!-- info: Provide annotator distributions for
each annotation type.

Use additional notes to capture any
other relevant information or
considerations.

(Usage Note: Duplicate and
complete the following for each
annotation type.) -->
**(Annotation Type)**

- Language [Percentage %]
- Language [Percentage %]
- Language [Percentage %]

**Above:** Provide a caption for the above table or visualization.

**Additional Notes:** Add here

#### Location(s)
<!-- scope: periscope -->
<!-- info: Provide annotator distributions for each
annotation type.

Use additional notes to capture any other
relevant information or considerations.

(Usage Note: Duplicate and complete the
following for each annotation type.) -->
**(Annotation Type)**

- Location [Percentage %]
- Location [Percentage %]
- Location [Percentage %]

**Above:** Provide a caption for the above table or visualization.

**Additional Notes:** Add here

#### Gender(s)
<!-- scope: microscope -->
<!-- info: Provide annotator distributions for
each annotation type.

Use additional notes to capture any
other relevant information or
considerations.

(Usage Note: Duplicate and complete
the following for each annotation
type.) -->
**(Annotation Type)**

- Gender [Percentage %]
- Gender [Percentage %]
- Gender [Percentage %]

**Above:** Provide a caption for the above table or visualization.

**Additional Notes:** Add here

## Validation Types
<!-- info: Fill this section if the data in the dataset was validated during
or after the creation of your dataset. -->
#### Method(s)
<!-- scope: telescope -->
<!-- info: Select **all applicable**: -->
- Data Type Validation
- Range and Constraint Validation
- Code/cross-reference Validation
- Structured Validation
- Consistency Validation
- Not Validated
- Others (Please Specify)

#### Breakdown(s)
<!-- scope: periscope -->
<!-- info: Provide a description of the fields and data
points that were validated.

Use additional notes to capture any other
relevant information or considerations.

(Usage Note: Duplicate and complete the
following for each validator type.) -->
**(Validation Type)**

**Number of Data Points Validated:** 12345

**Fields Validated**
Field | Count (if available)
--- | ---
Field | 123456
Field | 123456
Field | 123456

**Above:** Provide a caption for the above table or visualization.

#### Description(s)
<!-- scope: microscope -->
<!-- info: Provide a description of the methods used to
validate the dataset.

Use additional notes to capture any other
relevant information or considerations.

(Usage Note: Duplicate and complete the
following for each validator type.) -->
**(Validation Type)**

**Method:** Describe the validation method here. Include links where
necessary.

**Platforms, tools, or libraries:**

- Platform, tool, or library: Write description here
- Platform, tool, or library: Write description here
- Platform, tool, or library: Write description here

**Validation Results:** Provide results, outcomes, and actions taken because
of the validation. Include visualizations where available.

**Additional Notes:** Add here

### Description of Human Validators
<!-- info: Fill this section if the dataset was validated using human
validators -->
#### Characteristic(s)
<!-- scope: periscope -->
<!-- info: Provide characteristics of the validator
pool(s). Use additional notes to capture any
other relevant information or considerations. -->
**(Validation Type)**
- Unique validators: 12345
- Number of examples per validator: 123456
- Average cost/task/validator: $$$
- Training provided: Y/N
- Expertise required: Y/N

#### Description(s)
<!-- scope: microscope -->
<!-- info: Provide a brief description of the validator
pool(s). Use additional notes to capture any
other relevant information or considerations.

(Usage Note: Duplicate and complete the
following for each validator type.) -->
**(Validation Type)**

**Validator description:** Summarize here. Include links if available.

**Training provided:** Summarize here. Include links if available.

**Validator selection criteria:** Summarize here. Include links if available.

**Training provided:** Summarize here. Include links if available.

**Additional Notes:** Add here

#### Language(s)
<!-- scope: telescope -->
<!-- info: Provide validator distributions.
Use additional notes to capture any other relevant information or
considerations.

(Usage Note: Duplicate and complete the following for each annotation type.)-->
**(Validation Type)**

- Language [Percentage %]
- Language [Percentage %]
- Language [Percentage %]

**Above:** Provide a caption for the above table or visualization.

**Additional Notes:** Add here

#### Location(s)
<!-- scope: periscope -->
<!-- info: Provide validator distributions.
Use additional notes to capture any other relevant information or
considerations.

(Usage Note: Duplicate and complete the following for each annotation type.)-->
**(Validation Type)**

- Location [Percentage %]
- Location [Percentage %]
- Location [Percentage %]

**Above:** Provide a caption for the above table or visualization.

**Additional Notes:** Add here

#### Gender(s)
<!-- scope: microscope -->
<!-- info: Provide validator distributions.
Use additional notes to capture any other relevant information or
considerations.

(Usage Note: Duplicate and complete the following for each annotation type.)-->
**(Validation Type)**

- Gender [Percentage %]
- Gender [Percentage %]
- Gender [Percentage %]

**Above:** Provide a caption for the above table or visualization.

**Additional Notes:** Add here

## Sampling Methods
<!-- info: Fill out the following block if your dataset employs any sampling
methods. -->
#### Method(s) Used
<!-- scope: telescope -->
<!-- info: Select **all applicable** methods used in the creation of this
dataset: -->
- Cluster Sampling
- Haphazard Sampling
- Multi-stage Sampling
- Random Sampling
- Retrospective Sampling
- Stratified Sampling
- Systematic Sampling
- Weighted Sampling
- Unknown
- Unsampled
- Others (Please specify)

#### Characteristic(s)
<!-- scope: periscope -->
<!-- info: Provide characteristics of each sampling
method used.

Use additional notes to capture any other
relevant information or considerations.

(Usage Note: Duplicate and complete the
following for each sampling method
used.) -->
**(Sampling Type)** | **Number**
--- | ---
Upstream Source | Write here
Total data sampled | 123m
Sample size | 123
Threshold applied | 123k units at property
Sampling rate | 123
Sample mean | 123
Sample std. dev | 123
Sampling distribution | 123
Sampling variation | 123
Sample statistic | 123

**Above:** Provide a caption for the above table or visualization.

**Additional Notes:** Add here

#### Sampling Criteria
<!-- scope: microscope -->
<!-- info: Describe the criteria used to sample data from
upstream sources.

Use additional notes to capture any other
relevant information or considerations. -->
- **Sampling method:** Summarize here. Include links where applicable.
- **Sampling method:** Summarize here. Include links where applicable.
- **Sampling method:** Summarize here. Include links where applicable.

## Known Applications & Benchmarks
<!-- info: Fill out the following section if your dataset was primarily
created for use in AI or ML system(s) -->
#### ML Application(s)
<!-- scope: telescope -->
<!-- info: Provide a list of key ML tasks
that the dataset has been
used for.

Usage Note: Use comma-separated keywords. -->
*For example: Classification, Regression, Object Detection*

#### Evaluation Result(s)
<!-- scope: periscope -->
<!-- info: Provide the evaluation results from
models that this dataset has been used
in.

Use additional notes to capture any
other relevant information or
considerations.

(Usage Note: Duplicate and complete the
following for each model.) -->
**(Model Name)**

**Model Card:** [Link to full model card]

Evaluation Results

- Accuracy: 123 (params)
- Precision: 123 (params)
- Recall: 123 (params)
- Performance metric: 123 (params)

**Above:** Provide a caption for the above table or visualization.

**Additional Notes:** Add here

#### Evaluation Process(es)
<!-- scope: microscope -->
<!-- info: Provide a description of the evaluation process for
the model's overall performance or the
determination of how the dataset contributes to
the model's performance.

Use additional notes to capture any other relevant
information or considerations.

(Usage Note: Duplicate and complete the following
for each model and method used.) -->
**(Model Name)**

**[Method used]:** Summarize here. Include links where available.

- **Process:** Summarize here. Include links, diagrams, visualizations, tables as relevant.
- **Factors:** Summarize here. Include links, diagrams, visualizations, tables as relevant.
- **Considerations:** Summarize here. Include links, diagrams, visualizations, tables as relevant.
- **Results:** Summarize here. Include links, diagrams, visualizations, tables as relevant.

**Additional Notes:** Add here

#### Description(s) and Statistic(s)
<!-- scope: periscope -->
<!-- info: Provide a description of the model(s) and
task(s) that this dataset has been used
in.

Use additional notes to capture any
other relevant information or
considerations.

(Usage Note: Duplicate and complete the
following for each model.) -->
**(Model Name)**

**Model Card:** Link to full model card

**Model Description:** Summarize here. Include links where applicable.

- Model Size: 123 (params)
- Model Weights: 123 (params)
- Model Layers 123 (params)
- Latency: 123 (params)

**Additional Notes:** Add here

#### Expected Performance and Known Caveats
<!-- scope: microscope -->
<!-- info: Provide a description of the expected performance
and known caveats of the models for this dataset.

Use additional notes to capture any other relevant
information or considerations.

(Usage Note: Duplicate and complete the following
for each model.) -->
**(Model Name)**

**Expected Performance:** Summarize here. Include links where available.

**Known Caveats:** Summarize here. Include links, diagrams, visualizations, and
tables as relevant.

**Additioanl Notes:** Add here

## Terms of Art
### Concepts and Definitions referenced in this Data Card
<!-- info: Use this space to include the expansions and definitions of any
acronyms, concepts, or terms of art used across the Data Card.
Use standard definitions where possible. Include the source of the definition
where indicated. If you are using an interpretation,
adaptation, or modification of the standard definition for the purposes of your
Data Card or dataset, include your interpretation as well. -->
#### Term of Art
Definition: Write here

Source: Write here and share link

Interpretation: Write here

#### Term of Art
Definition: Write here

Source: Write here and share link

Interpretation: Write here

#### Term of Art
Definition: Write here

Source: Write here and share link

Interpretation: Write here

#### Term of Art
Definition: Write here

Source: Write here and share link

Interpretation: Write here

#### Term of Art
Definition: Write here

Source: Write here and share link

Interpretation: Write here

#### Term of Art
Definition: Write here

Source: Write here and share link

Interpretation: Write here

#### Term of Art
Definition: Write here

Source: Write here and share link

Interpretation: Write here

#### Term of Art
Definition: Write here

Source: Write here and share link

Interpretation: Write here

#### Term of Art
Definition: Write here

Source: Write here and share link

Interpretation: Write here

#### Term of Art
Definition: Write here

Source: Write here and share link

Interpretation: Write here

#### Term of Art
Definition: Write here

Source: Write here and share link

Interpretation: Write here

#### Term of Art
Definition: Write here

Source: Write here and share link

Interpretation: Write here

## Reflections on Data
<!-- info: Use this space to include any additional information about the
dataset that has not been captured by the Data Card. For example,
does the dataset contain data that might be offensive, insulting, threatening,
or might otherwise cause anxiety? If so, please contact the appropriate parties
to mitigate any risks. -->
### Title
Write notes here.

### Title
Write notes here.

### Title
Write notes here.
