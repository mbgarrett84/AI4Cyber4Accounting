Disclaimer: All content on this site is for educational purposes only.
## *AI4Cyber & U.S. Small and Medium-Sized Accounting Service Firms*
## Table of Contents

[A. Industry Background](#a-industry-background)
 
1. Background on Industry
2. Threat Trends

[B. Threat Modelling](#b-threat-modelling)

1. Critical Asset Identification
2. Diamond Models
3. Intelligence Buy-In

[C. Data Source Identification and Justification](#c-data-source-identification-and-justification) 
1. Data Source Identification
2. Data Source Justification

[D. Data Collection Strategies and Summary](#d-data-collection-strategies-and-summary)
1. Collection Strategies
2. Summary of Data: Phishing Dataset Example

[E. Analytical Approaches and Justification](#e-analytical-approaches-and-justification)
1. Logistic Regression: Phishing
2. Support Vector Machine: Anomaly Detection

[F. Preliminary Visualizations](#f-preliminary-visualizations)
1. Logistic Regression: Phishing
2. Support Vector Machine: Anomaly Detection

[G. About Us and Sources](#g-about-us-and-references)

1. Group
2. Sources


```
```
# A. Industry Background
##### [Return to Table of Contents](#table-of-contents)
## 1. Background on Industry
### 1.1 Background on Industry: Overview
Small and medium-sized accounting service firms are defined as all U.S. accounting firms
smaller than the “Big Four,” Deloitte, PwC, EY, and KPMG.

**Firms:** approximately 93,000

**Primary Services:** bookkeeping, payroll, financial statement preparation, tax planning and compliance, and auditing

**Employment:** approximately 250,000 

**Revenue:** approximately $55 billion

### 1.2 Background on Industry: Importance of Information Technology
**Communications:** firm staff use information technology, especially e-mail, to timely communicate with clients, vendors, and other third-parties.

**Processing and storage:** firms process and store large volumes of data.

**Data Reception and Transmission:** firms receive and transmit data to and from clients and third parties using computer applications.

## 2. Threat Trends
**Phishing Schemes:**
Accounting service firms receive, process, store, and transmit sensitive personal and business information. In many circumstances, the receipt of or request for information from clients and third parties, such as regulatory agencies, might come through varied channels and be time sensitive.  This multiplicity of channels and sense of urgency increases the risk that employees will mistake phishing attempts for legitimate client or third-party information requests.

**Malware:**
Accounting service firm employees and systems often interact with many external systems and share many files through many different channels.  File sharing under these circumstances increases the risk of malware infection.  Additionally, the sensitive information held by these firms and the high business value of continuous data availability and operations make these firms particularly attractive ransomware targets.

**Data Breaches:**
The sensitive information that accounting service firms hold makes these firms targets of data breaches.  These firms are particularly susceptible to data breaches that arise from inappropriate access to the numerous employee, client, and vendor accounts that have access to this sensitive information.

```
```
# B. Threat Modelling
##### [Return to Table of Contents](#table-of-contents)
## 1. Critical Asset Identification
Nearly all firm employees use these critical assets as part of their daily activities.
The business models of these firms depends on the reliable integrity and availability of these critical assets.
The breach of sensitive personal and business data would subject these firms to breach reporting requirements and substantial regulatory, litigation, and reputational costs.

**Hardware:** the personal computers, phones, and servers used by the firm’s employees to receive, process, store, and transmit information

**Networks:** the software and hardware allowing communication and data transmission between firm employees, clients, and third-parties

**Software:** the standard enterprise applications and specialized accounting-related software used by the firm’s employees

**Shared Resources:** the applications and interfaces connecting the firm systems with those of clients and third-parties

**Data:** sensitive personal and business information, such as SSNs, PPI, PHI, tax identifiers, and trade secrets

## 2. Diamond Models
![DM- Phishing Scheme](https://user-images.githubusercontent.com/90997678/133940239-465ebc2d-d2d7-4b61-9ad1-a3de69d4a91f.jpg)
![DM- E-mailed Malware](https://user-images.githubusercontent.com/90997678/133940244-d97d8d05-a60d-4324-a815-fc97c6e3b7bd.jpg)
![DM- Other Malware](https://user-images.githubusercontent.com/90997678/133940248-04b9a0ce-5ce9-4781-9f8c-82121ef841b6.jpg)
![DM- Insider Account Abuse](https://user-images.githubusercontent.com/90997678/133940253-2eeb5e59-f8f4-4b1d-892e-9d74f0d4347b.jpg)
![DM- Other Account Abuse](https://user-images.githubusercontent.com/90997678/133944640-9f4c5871-0e7a-4cde-bcc2-caa70c65c0db.jpg)

## 3. Intelligence Buy-In
### 3.1 Intelligence Buy-In: Risk and Value of Enhanced Security
Accounting service firms hold sensitive personal and business information that is an attractive target of data breaches.

The high business value of continuous data availability and operations make these firms particularly attractive targets of ransomware.

Data breaches and disruptions to data availability and operations have significant regulatory, litigation, and reputational costs for these firms.

Because of the above, enhanced security has high value for these firms.

### 3.2 Intelligence Buy-In: AI Capabilities and Value
Small and medium-sized accounting service firms often have high demand for limited cybersecurity resources and personnel.

The implementation of AI automation for cybersecurity tasks will help to free cybersecurity resources and personnel for higher priority tasks.

The large number of client, vendor, and other third-party accounts, communication channels, and system connections limits the ability of cybersecurity personnel to detect     anomalous patterns in related activity data.

The implementation of AI pattern recognition can help cybersecurity personnel to find actionable patterns in this voluminous activity data. 

```
```
# C. Data Source Identification and Justification
##### [Return to Table of Contents](#table-of-contents)
## 1. Data Source Identification: Mendeley Data
Mendeley Data is a cloud-based repository for data sets.

It is used by academecians, resarchers, practitioners, and others to store, access, and cite data sets.

It stores over 29 million data sets, including thousands covering the intersection of artificial intelligence, machine learning, and cybersecurity.

## 2. Data Source Justification
### 2.1 Date Source Justification: Relevancy 1: General
Mendeley Data contains recent data sets for broad cybersecurity threat trends and for specific threats facing small and medium-sized accounting service firms, including phishing and malware.

These data sets are specifically constructed and formatted for the purpose of gaining actionable cybersecurity insights.

### 2.2 Date Source Justification: Relevancy 2: Specific
The Tan (2018) dataset provides a data to gain insight into one of the most consequential threats facing small and medium-sized accounting firms: phishing and phishing-based malware.

The Palacio (2018) dataset provides data of network activity designed for the purpose of constructing an anomaly detection system. 

This form of automation is particularly helpful to small and medium-sized accounting firms, with their numerous, diverse, and dynamic network connections and limited cybersecurity personnel and resourses.

### 2.3 Data Source Justification: Accessibility
Mendeley Data is highly economically and technically accessible:

Access does not require a subscription or fee.

Data sets are readily available for download or other extraction, access does not require the development or use of APIs.

Data sets are generally formatted for ease of analysis and implementation.

```
```
# D. Data Collection Strategies and Summary
##### [Return to Table of Contents](#table-of-contents)
## 1. Collection Strategies
Applicable data sets were collected through Mendeley Data’s search function using cybersecurity related search terms, including the specific threats and vulnerabilities most applicable to small and medium-sized accounting service firms.

Data sets were downloaded and stored as .csv files.

This approach is especially accessible and flexible.

Thousands of academicians, researchers, and practitioners have viewed and downloaded applicable cybersecurity-related data sets from this source to train, test, and calibrate their cybersecurity models and applications.

## 2. Summary of Data: Phishing Dataset Example
Tan (2018) Dataset:

5000 phishing webpages and 5000 legitimate webpages are provided.

The phishing webpages were downloaded from Phishtank and OpenPhish from January to May of 2015 and from May to June of 2017.

The legitimate webpages were determined using Alexa and Common Crawl.

48 features are provided for each webpage.

Features relate to the URL name, content of the webpage, and external services, and include both categorical and quatitative data.

**Sample of Tan 2018 Dataset:**

![image](https://user-images.githubusercontent.com/90997678/136721711-0f199217-f65a-46a7-9d21-4b02e3c5c3ca.png)

```
```
# E. Analytical Approaches and Justification
##### [Return to Table of Contents](#table-of-contents)
# 1. Logistic Regression: Phishing
## 1.1 Introduction
Logistic regression is a statistical analysis method used to predict the likelihood of a particular categorical response for a given set of independent variables.

The models created through this analysis method can be used for classification.

Logistic regression will be used here for the purposes of creating a model that classifies phishing e-mails.
## 1.2 Why This Approach
The assumptions and steps of some other commonly used statistical analysis methods, such as linear regression, prevent their meaningful or productive use with a binary dependent variable.

Logistic regression models can be trained efficiently, used effectively in the presence of many features, and are easily scalable.

Logistic regression models are used for classification in several AI for cybersecurity domains, including spam and phishing detection.
## 1.3 Value Added
Phishing and phishing-delivered malware constitute one of the most common and costly threats facing small and medium-sized accounting firms.

In this threat context, even marginal improvements in protection can provide substantial value.

Logistic regression-based classification models provide additional and dynamic filtering capabilities compared to traditional dictionary-based approaches.

## 1.4 Data Sources Required
Logistic regression requires a labeled dataset to train. 

The dependent variable must be binary.
  Multinomial and ordinal logistic regression allow the dependent variable to take on additional values.

Independent variables can be categorical and quantitative.

The data set should be of at least modest size and should avoid multicollinearity and outliers.

## 1.5 Major Steps and Justification
A dataset with appropriate variables was selected for this analytic method.
  In this instance, the Tan (2018) dataset was chosen.

In a Jupyter Notebook, the appropriate libraries for this method were imported, along with the dataset.
A logistic regression model was fit to the data.

These steps were selected for their relative ease of use, accessibility, scalability, and applicability.

# 2. Support Vector Machine: Anomaly Detection
## 2.1 Introduction
Anomaly detection is used to detect outliers in data.

Support vector machines (SVM) are a class of supervised learning algorithms that are used for classification and work by maximizing the margin separating classes of data.

An SVM is used here to analyze anomalies in network traffic.

## 2.2 Why This Approach
SVMs perform well when there is a clear separation of data.

SVMs are flexible: 
  Many versions provide various options for hyperparameter tuning.
  Many varieties of kernel function are available.

SVMs can be more customizable than other anomaly detection methods that primarily rely on summary statistics, for example, analysis based on Gaussian distribution.

## 2.3 Value Added
Anomaly detection systems can greatly assist the efficiency and effectiveness of a firm’s cybersecurity program by automating the task of reviewing large volumes of network activity and presenting only suspicious events for human review.

These benefits are especially salient to small and medium-sized accounting firm, as these firms have numerous, diverse, and dynamic network connections and activity and often limited cybersecurity personnel and resources.

## 2.4 Data Sources Required
SVM for anomaly detection uses time-series data.

Standard SVM algorithms require quantitative data, as distance measures are used.

Linear SVM requires that the data be linearly separable, but adjustments to the kernel function allow for versions of the algorithm to be used with nonlinearly separable data.

## 2.5 Major Steps and Justification
A dataset with the appropriate characteristics for this analytic method were selected:
  In this instance, the Palacio (2018) dataset was chosen.

In a Jupyter Notebook, the appropriate libraries for this technique were imported, along with the dataset.

An SVM process was run on the data.

These steps were selected for their relative ease of use, accessibility, scalability, and applicability.
```
```
# F. Prelimary Visualizations
##### [Return to Table of Contents](#table-of-contents)
# 1. Logistic Regression: Phishing
## 1.1 Data
This visualization provides a display of the logistic regression coefficients for the Tan (2018) dataset.

The Tan (2018) data set contains 10,000 webpages, evenly split between phishing and legitimate, and 48 features relating to URL name, content of the webpage, and external services, with both categorical and continuous data.

## 1.2 Process
A dataset with appropriate variables was selected for this analytic method.

In this instance, the Tan (2018) dataset was chosen.

In Jupyter Notebook, the appropriate libraries for this technique were imported, along with the dataset.

A logistic regression model was fit to the data.

A bar chart visualization of the regression coefficients was created.

## 1.3 Value
The logistic regression coefficients provide the marginal effect of the feature in increasing or decreasing the likelihood that the record is associated with phishing.

Knowledge of which features are associated with phishing and the strength of these associations can help to highlight which features should receive attention in future analytic and other technical implementations and can inform personnel cybersecurity training.

## 1.4 Visualization
**Placeholder visualization due to my technical limitations:**


![logistic regression visualization-placeholder](https://user-images.githubusercontent.com/90997678/139608850-b487f801-cd86-42a6-bd1d-2b26be3dec14.png)

# 2. Support Vector Machine: Anomaly Detection
## 2.1 Data
This visualization provides a display of the SVM output when run on the Palacio (2018) data.

This dataset contains time-series data for network activity covering 56 features with both categorical and quantitative data.

## 2.2 Process
A suitable data set was acquired and prepared.

The Palacio (2018) dataset was used in this instance.

The SVM process was run.

Appropriate parameters were selected, and the events and support vector were selected for display in a scatterplot.

## 2.3 Value
This type of visualization allows one to easily review broad network activity over the time period under review and quickly target events outside of normal ranges.

In implementation scenarios with streaming data, this type of visualization could be included in cybersecurity dashboards to provide quick access and review of network activity and could be used as a tool to help further refine and tune the parameters of the underlying algorithm.

## 2.4 Visualization
**Placeholder visualization due to my technical limitations:**


![SVM visualization-placeholder](https://user-images.githubusercontent.com/90997678/139608866-c640d77e-86b0-44a9-a1e8-8e7e2bf4fa5a.png)

```
```
# G. About Us and References
##### [Return to Table of Contents](#table-of-contents)
## 1. Group
Matt Garrett (garretmb@iu.edu) researched and synthesized industry, threat trend, critical asset, diamond model, intelligence buy-in, and data source information, performed the analytics process, and created visuals, this slide deck, and the related website.

## 2. Sources
1. “Accounting Services Industry in the US – Market Research Report.” IBISWorld, 2021, Retrieved September 4, 2021 from https://www.ibisworld.com/united-states/market-research-reports/accounting-services-industry/

2. Statista Research Department. (2021, April 8). Leading accounting firms in the United States in 2020, by U.S. revenue (in billion U.S. dollars). Retrieved September 4, 2021 from https://www.statista.com/statistics/188725/25-largest-us-accounting-firms-by-net-revenue-2010/

3. Leonard, Kimberlee. (2019, February 12). How is Information Technology Used in Accounting? Retrieved September 4, 2021, from https://smallbusiness.chron.com/information-technology-used-accounting-2101.html

4. Palacio, Sebastián (2018), “Outlier Detection”, Mendeley Data, V2, doi: 10.17632/g3vxppc8k4.2, Retrieved from https://data.mendeley.com/datasets/g3vxppc8k4/2

5. Politzer, Malia. (2020, March 16). Top cyberthreats targeting accounting firms. Journal of Accountancy. Retrieved September 4, 2021, from https://www.journalofaccountancy.com/newsletters/2020/mar/top-cyberthreats-accounting-firms.html

6. Tan, Choon Lin (2018), “Phishing Dataset for Machine Learning: Feature Evaluation”, Mendeley Data, V1, doi: 10.17632/h3cgnj8hft.1. Retrieved from https://data.mendeley.com/datasets/h3cgnj8hft/1




