#### 1. When designing a custom TFX component from a Python function, which of the following steps are needed?

A : 

    Initialize your custom component object to pass with other components in a list to the pipeline orchestrator for execution.
    Decorate your Python function with the @component decorator.
    Annotate input and output artifact types and runtime parameter types

#### 2. Your ML Engineering team has existing ML pipeline code written in Java. Which TFX custom component option can you re-use this code in your TFX pipeline to speed up development? Select one.

A : Pre-built container

#### 3. Which Google Cloud developer tool powers CI/CD workflows for building, testing, and deploying TFX pipeline code? Select one.

A : Cloud Build

#### 4. How do TFX pipeline development steps relate to the levels of ML process automation? Select all that apply:

A : 

    Level 0: Manual TFX interactive component runs in Jupyter notebooks for rapid experimentation and development.
    Level 1: Continuous training TFX pipelines 
    Level 2: CICD pipelines for building, testing, and deploying continuous training TFX pipelines.