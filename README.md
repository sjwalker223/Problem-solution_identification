<h3 align="center">Problem/solution identifier</h3>

  <p align="center">
    Identifying problems and solutions from scientific texts.
  </p>
</div>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li><a href="#usage">Usage</a></li>
    <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#quick-start-guide">Quick Start Guide</a></li>
      </ul>
    <li><a href="#model-overview">Model Overview</a></li>
    <li><a href="#contributors">Contributors</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

#### The problem

I work in a fast-moving field where a large number of scientific papers are published every week. I don't have the time to read every paper that's published in my field - so how do I choose which ones to focus on? Right now, I skim their abstracts and decide which look interesting - but this takes a long time, and sometimes the abstract doesn't describe a paper well. Instead, there are two things I really want to know when deciding whether to read a paper:

1) What are the **problems** this paper is trying to address?
2) What are the **solutions** the authors propose?

#### The solution

I want to train models that can pick out just those sentences in the text of a scientific paper that describe problems and proposed/identified solutions. That way, I can screen just these sentences, and decide whether these are problems/solutions that interest me.

#### The process

I have trained two types of models to predict whether a sentence contains problems/solutions: Naive Bayes models, and BERT models.

#### The outcomes

I have a developed a model that can very accuractely pick out problems and solutions from a scientific text, which will help me to parse the scientific literature much more efficiently!

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE -->
### Prerequisites

Before using this notebook to characterise problem and solution statements, just one step is required to install the necessary packages. Install the requirements in your terminal using pip:

```sh
pip install -r requirements.txt
```

### Quick Start Guide

To train, tune, test and select the models for identifying problem and solution statements, refer to the following notebook:
* [Problem-solution notebook](Problem-solution_identifier.ipynb)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTORS -->
## Contributors
This repository was designed and developed exclusively by:
* Samuel J. Walker - [Github](https://github.com/sjwalker223) | [LinkedIn](https://www.linkedin.com/in/samueljameswalker/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
