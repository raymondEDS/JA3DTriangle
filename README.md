# IHD Flash Talks: Joint Attention, Computer Vision, and Foundation Models: How state-of-the-art AI approaches can analyze instances of early childhood development
The Filming Interactions to Nurture Development (FIND) program uses video coaching to promote positive interactions between caregivers and children. One important interaction in early childhood development is joint attention where both caregiver and the child focus on a single object. In this work, we develop a pipeline that identifies instances of joint attention by using three different computer vision models, Constrative Language-Image Pre-training (CLIP), a 2D joint attention detector, and a monocular depth estimation model, to reconstruct the 3D coordinates of the caregiver, child, and object of focus. Using the 3D coordinates we are able to calculate the area of a 3D triangle that represents the space between the three entities. Our analysis shows that in instances of shared reading the area of the triangle is less than in other playing activities where joint attention is present. Our work is innovative in achieving two goals: first, we provide quantitative evidence to gain new insights into caregiver-child interactions; second, we explore the potential of a novel computational method to improve video coding programs, such as reducing the time and resources required for manual coding. Future work will include creating a labeled dataset for model evaluation and refining the model pipeline.

We had the privilege of presenting our preliminary research findings at [Early Learning and Development: Advancing Science for Positive Impact
IHD Flash Talks](https://ihd.berkeley.edu/events/seminar-series/early-learning-and-development-advancing-science-for-positive-impact).
```bash
@misc{zhao_zhang_2023,
    title = "Joint Attention, Computer Vision, and Foundation Models: How State-of-the-art AI approaches can analyze instances of early childhood development",
    author = "Zhao, Priscilla and Zhang, Raymond",
    talkseries = "Early Learning and Development: Advancing Science for Positive Impact",
    month = may,
    year = "2023",
    publisher = "IHD Flash Talks",
    url = "https://ihd.berkeley.edu/events/seminar-series/early-learning-and-development-advancing-science-for-positive-impact",
    abstract = "The Filming Interactions to Nurture Development (FIND) program uses video coaching to promote positive interactions between caregivers and children. One important interaction in early childhood development is joint attention where both caregiver and the child focus on a single object. In this work, we develop a pipeline that identifies instances of joint attention by using three different computer vision models, Constrative Language-Image Pre-training (CLIP), a 2D joint attention detector, and a monocular depth estimation model, to reconstruct the 3D coordinates of the caregiver, child, and object of focus. Using the 3D coordinates we are able to calculate the area of a 3D triangle that represents the space between the three entities. Our analysis shows that in instances of shared reading the area of the triangle is less than in other playing activities where joint attention is present. Our work is innovative in achieving two goals: first, we provide quantitative evidence to gain new insights into caregiver-child interactions; second, we explore the potential of a novel computational method to improve video coding programs, such as reducing the time and resources required for manual coding. Future work will include creating a labeled dataset for model evaluation and refining the model pipeline."
}
```
## Directories
1. `Code` contains all of the notebooks used for the project and the various models used
2. `Documents` contains posters, paper, and presentation that goes into detail about how this pipeline was developed

## Setup
All notebooks are developed in Google Colab. To replicate download notebooks into colab and run.

## Acknowledgement:
This project is done in collaboration and funded by the [Stanford Center on Early Childhood](https://earlychildhood.stanford.edu/) and [Stanford Autonomous Agents Lab](https://www.autonomousagents.stanford.edu/). Thank you to Professor Philip Fisher, Professor Nick Haber, Kyndal Yada, Sally Steinman, and many others for the contributions made during this project. 
