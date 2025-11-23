# Maternal Mortality Data Analysis Project
<!-- Edit the title above with your project title -->

## Project Overview
This project explores maternal mortality as a public health indicator, focusing on both U.S. and global trends between 2018 and 2023. Maternal mortality is not only a measure of healthcare quality but also a reflection of broader inequities in access, socioeconomic conditions, and policy effectiveness. Despite being a high-income nation, the United States has experienced rising maternal mortality rates in recent years, often exceeding those of peer countries. Globally, stark differences remain between regions, with low-income countries carrying the highest burden.

By analyzing datasets from the CDC, NCHS, and WHO, this project seeks to identify trends, regional disparities, and international comparisons. The findings can provide insight into where interventions are most urgently needed and contribute to ongoing discussions about improving maternal healthcare outcomes.

## Self Assessment and Reflection

<!-- Edit the following section with your self assessment and reflection -->

### Self Assessment
<!-- Replace the (...) with your score -->

| Category          | Score    |
| ----------------- | -------- |
| **Setup**         | 10 / 10 |
| **Execution**     | 19 / 20 |
| **Documentation** | 10 / 10 |
| **Presentation**  | 28 / 30 |
| **Total**         | 67 / 70 |

### Reflection
<!-- Edit the following section with your reflection -->

#### What went well?
Once I got comfortable with the structure of the project, the analysis actually flowed pretty smoothly. Cleaning the NCHS dataset and creating visualizations felt really good because I could see the story forming in the data. The machine learning portion also went better than expected once the preprocessing pipeline was set up correctly. Overall, the project helped me build confidence in my ability to work through a full data workflow from raw CSVs to insights to modeling.
#### What did not go well?
A few things definitely tripped me up. Some of the data formatting issues slowed me down more than I expected, especially when columns weren’t named consistently or had unexpected characters. I also spent extra time debugging model errors that ended up being caused by missing preprocessing steps. The global datasets were much larger than the U.S. dataset, so working with different scales made merging or comparing them more challenging.
#### What did you learn?
I learned how important clean, consistent data is before ever touching a model. I also learned how much easier machine learning becomes once pipelines, transformers, and feature engineering are handled properly. Beyond the technical side, I learned more about the real-world implications of maternal mortality and how different regions experience drastically different outcomes. It reminded me that data analysis isn’t just numbers, it’s connected to real people's lives.
#### What would you do differently next time?
Next time, I would start by building a stronger cleaning and validation phase up front to avoid running into issues later. I’d also like to explore more advanced models, include additional socioeconomic features, and try a clustering approach to uncover hidden patterns. Lastly, I’d document my steps earlier in the process instead of waiting until the end when things are harder to summarize.

---

## Getting Started
### Installing Dependencies

To ensure that you have all the dependencies installed, and that we can have a reproducible environment, we will be using `pipenv` to manage our dependencies. `pipenv` is a tool that allows us to create a virtual environment for our project, and install all the dependencies we need for our project. This ensures that we can have a reproducible environment, and that we can all run the same code.

```bash
pipenv install
```

This sets up a virtual environment for our project, and installs the following dependencies:

- `ipykernel`
- `jupyter`
- `notebook`
- `black`
  Throughout your analysis and development, you will need to install additional packages. You can can install any package you need using `pipenv install <package-name>`. For example, if you need to install `numpy`, you can do so by running:

```bash
pipenv install numpy
```

This will update update the `Pipfile` and `Pipfile.lock` files, and install the package in your virtual environment.

## Helpful Resources:
* [Markdown Syntax Cheatsheet](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* [Dataset options](https://it4063c.github.io/guides/datasets)