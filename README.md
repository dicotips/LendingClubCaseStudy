# Lending Club Case Study

## Introduction 

Exploratory and Data Analysis for a Consumer Finance company. We want to help the company to identify risky customers when offering loans. Risks are identified based on the applicant's profile.

## Group members:
* Pavan Narra (@pavan440)
* Jheser Guzman (@dicotips)
### Methods Used
* Exploratory Data Analysis
* Data Visualization

### Technologies
* Python
* Pandas
* Jupyter Notebooks

## Download and Setup
### Prerequisites

This project needs Anaconda installed in the computer.

For more details about the instalation, go to:  https://docs.anaconda.com/anaconda/install/index.html
### How to Run

You can download the source code cloning this repository using Git:

1. Open your favorite Terminal app (Unix, Linux or Macos), such as Terminal, Command, Console, iTerm2, so on.

2. Clone the repository

```
git clone https://github.com/dicotips/LendingClubCaseStudy.git
```

3. Open the ** *.ipynb** notebooy file in Anaconda.

```
jupyter notebook Group_PavanNarra.ipynb
```

## Business Understanding

**Source:** UpGrad Assignment description

*You work for a **consumer finance** company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two **types of risks** are associated with the bank’s decision:*

* *If the applicant is **likely to repay the loan**, then not approving the loan results in a **loss of business** to the company*

* *If the applicant is **not likely to repay the loan**, i.e. he/she is likely to default, then approving the loan may lead to a **financial loss** for the company*

## Data Used

*The data given below contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.*

When a person applies for a loan, there are two types of decisions that could be taken by the company:

1. **Loan accepted:** If the company approves the loan, there are 3 possible scenarios described below:

  * **Fully paid:** Applicant has fully paid the loan (the principal and the interest rate)

  * **Current:** Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

  * **Charged-off:** Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

2. **Loan rejected:** The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

