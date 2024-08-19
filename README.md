# Medical-Image-Analysis-using-Multimodal-LLM

## Project Overview
This project focuses on the development of a sophisticated medical image analysis system. The primary objective is to upload brain images and generate accurate descriptions of these images on the front end.

## Technologies Used
- **Langchain**: For managing the workflow and integration of various components.
- **Hugging Face**: Utilized for generating embeddings that aid in the analysis of medical images.
## Workflow
- **Data Collection**: Gathering a diverse dataset of brain images to train and test the models.
- **Preprocessing**: Implementing preprocessing steps to prepare the images for analysis.
- **Model Training**: Training models using advanced Multimodal large language models (MLLMs) to accurately describe the brain images.
- **Deployment**: Deploying the system to provide real-time analysis and descriptions of uploaded images.
## Current Progress
- **Model Used**: Initially used IDEFICS2, but results were not optimal.But, LLaVA and LLaVA-Med gave a optimal results.
- **Challenges Faced**: Encountered issues with training time, downloading models, and preprocessing images effectively. I faced resource problem with the available resource, had to use runpod for extra GPUs.
- **Future Phases**: Planning on creaitng front-end using gradio.
## Future Plans
- **Model Optimization**: Testing and integrating LLaVA-7B, and LLaVA-MEd-7B models.
- **Performance Improvement**: Addressing current challenges to optimize the training process and improve the overall efficiency of the system.
- **User Interface Enhancements**: Refining the front-end interface for a more user-friendly experience.
## Conclusion
This project aims to leverage cutting-edge AI and machine learning technologies to provide accurate and efficient medical image analysis. By continually improving the models and workflow, we strive to enhance diagnostic capabilities and support medical professionals in their work.
